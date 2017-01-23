# Python.2c


## Python, C\+\+, and COM

Python a helpful cousin to C\+\+ COM development

Ever want to write your pseudo-code for C\+\+ win32 or COM 

programming and be able to have it run? In many cases python offers 

just that\.Python offers easy, fast development, yet is still close 

enough to C\+\+ to be recognizable\. For example, compare python's class 

mechanism and exception handling\. With the perspective of being a 

light overview, we'll look at some details of development of a raw C\+\+ 

COM component and compare that to python development\. What is 

interesting to focus on, is not how their different, but how they are 

similar, which is useful to leverage\. For example, here's what 

abstract base classes \(an idea used for COM interfaces\) look like in 

python and C\+\+\.

#### Example
Abstract Base classes:

class IFlintstone

\{

public:

  virtual TellWilma\(long when\)=0;

\};

class IRubble

\{

public:

  virtual AskBetty\(long when\)=0;

\};

\#Abtract Base classes for python

\#not as formal as C\+\+'s

class IFlintstone:

  def TellWilma\(self,when=0\):

    raise RuntimeError, 'virtual function'

class IRubble:

  def AskBetty\(self,when=0\):

    raise RuntimeError, 'virtual function'

Also, in the Win32 world, python and C\+\+ are very similar\. You'll 

notice that if you look at some of the other win32 examples in 

overviews\. Python is capable of some sophisticated win32 programming 

allowing you to get the problem worked out before you have to write 

out the C\+\+\. For COM, like C\+\+, python is multi-threaded and can live 

in any apartment\.  You even have at your disposal 

PyIUnknown\.QueryInterface, pythoncom\.CoInitializeEx, etc\. much like in 

C\+\+\.\. But don't have to worry about casting, reference counts, and 

such\. Python has a translucent rather than black-box approach to COM\.

Thus, in COM programming, you can quickly prototype a program, and 

then if necessary, work on a C\+\+ solution\. As already mentioned, a 

typical means in C\+\+ to develop COM objects is with multiple 

inheritance\. You create class that inherits whatever interfaces 

\(abstract base classes\), you want to expose\.  The only disadvantage to 

this is that it means that the interfaces can't have the same function 

names\. These interfaces need to be defined using IDL to allow for 

proxies, resove any ambiguities C\+\+ may have, and generate type 

libraries\.  A very simple IDL interface wouuld look like:

IDL interface:

import "unknwn\.idl"

\[object, uuid\(11111111-2222-3333-4444-555555555555\)\]

interface IFlintstone : IUnknown

\{

  HRESULT TellWilma\(\[in\] int when\);

\}

interface IRubble : IUnknown

\{

  HRESULT AskBetty\(\[in\] int when\);

\}

After running it through the MIDL compiler, you include the header 

file created by MIDL and then inherit this just as with the class 

examples above\. Then you define every method for each interface which 

includes IUnknown, as well as IFlintstone and IRubble\. At this point, 

I'm ommitting some details like the metaclass which implements 

IClassFactory that creates Bedrock and errorhandeling , but from this 

class you can see the basic functions you'll have to write\.

C\+\+ definition:

\#include "file\_from\_midl\.h"

class BedRock : public IFlintstone, public IRubble \{

    LONG m\_references;

public:

   BedRock\(\) : m\_references\(0\)\{ \} // constructor

   ~BedRock\(void\) \{ \} //destructor

   // IUnknown Methods not shown in their entirety

   STDMETHODIMP QueryInterface\(REFIID riid, void \*\*ppv\)

   STDMETHODIMP\_\(ULONG\) AddRef\(void\)

   STDMETHODIMP\_\(ULONG\) Release\(void\)

   // IBedRock Methods

   STDMETHODIMP TellWilma\(long when\)

   \{

      write\_to\_cartoon\(when,"Wilma\!"\);

      return S\_OK;

   \}

   STDMETHODIMP AskBetty\(long when\)

   \{

      write\_to\_cartoon\(when,"Hey uh Betty\!"\);

      return S\_OK;

   \}

\};

How does python manage this? First of all, You do not bother to 

write IUnknown and IClassFactory \(python, being a dynamic language, 

uses IDispatch to expose the methods you're interested in\)\. Which also 

means there is no MIDL step you have to go through, if you change what 

interfaces are going to be used\. Python's approach is for you to add 

attributes to your python class, defining the necessary COM specifics\. 

For example, instead of defining the GUIDs in MIDL, you simply use the 

\_reg\_clsid\_ attribute to define the class's GUID\.

For the other methods, the basic idea is to create a python class 

and write class attributes that will expose what methods you want for 

COM\. For interfaces which have native support you can include the list 

of interfaces in a \_com\_interfaces\_ attribute for your class\.  And, 

for all interfaces, you simply add the interface's method calls to the 

list of in the \_public\_methods\_ class attribute\. In this case, neither 

IFlintstone nor IRubble have native support, so we don't bother with 

\_com\_interfaces\_\.

You'll notice the python COM class object is reasonably simple, but 

similar in spirit to the above\.

Basic python COM code

\#\#Abtract Base classes for python

class IFlintstone:

  def TellWilma\(self,when=0\):

    raise RuntimeError, 'virtual function'

class IRubble:

  def AskBetty\(self,when=0\):

    raise RuntimeError, 'virtual function'

class BedRock\(IFlintstone, IRubble\): \#no need to use MIDL for these

    \_public\_methods\_ = \['TellWilma', 'AskBetty'\]

    \_reg\_progid\_ = "Python\.Bedrock"

    \_reg\_clsid\_ = "\{12345678-1234-5678-1234-567812345678\}"

    def \_\_init\_\_\(self\): \#constructur

&\#09pass \#not doing anthing w/it

&\#09     \#no need to keep track of reference counts

    def \_\_del\_\_\(self\): \#destructor

&\#09pass \#not much going on here either

    def TellWilma\(self,when=0\):

&\#09write\_to\_cartoon\(when,"Wilma\!"\)

    def AskBetty\(self,when=0\):

&\#09write\_to\_cartoon\(when,"Hey uh Betty"\)

if \_\_name\_\_=='\_\_main\_\_':

    UseCommandLine\(BedRock\)

Have a great time with programming with python\! 

