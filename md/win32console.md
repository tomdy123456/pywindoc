# win32console


## Module win32console

Interface to the Windows Console functions for dealing with character-mode applications

#### Methods

  - [CreateConsoleScreenBuffer](win32console.md#win32consolecreateconsolescreenbuffer)

    Creates a new console handle&nbsp;

  - [GetConsoleDisplayMode](win32console.md#win32consolegetconsoledisplaymode)

    Returns the current console's display mode&nbsp;

  - [AttachConsole](win32console.md#win32consoleattachconsole)

    Attaches calling process to console of another process&nbsp;

  - [AllocConsole](win32console.md#win32consoleallocconsole)

    Creates a new console for the calling process&nbsp;

  - [FreeConsole](win32console.md#win32consolefreeconsole)

    Detaches process from its console&nbsp;

  - [GetConsoleProcessList](win32console.md#win32consolegetconsoleprocesslist)

    Returns pids of all processes attached to current console&nbsp;

  - [GetConsoleCP](win32console.md#win32consolegetconsolecp)

    Returns the input code page for calling process's console&nbsp;

  - [GetConsoleOutputCP](win32console.md#win32consolegetconsoleoutputcp)

    Returns the output code page for calling process's console&nbsp;

  - [SetConsoleCP](win32console.md#win32consolesetconsolecp)

    Sets the input code page for calling process's console&nbsp;

  - [SetConsoleOutputCP](win32console.md#win32consolesetconsoleoutputcp)

    Sets the output code page for calling process's console&nbsp;

  - [GetConsoleSelectionInfo](win32console.md#win32consolegetconsoleselectioninfo)

    Returns info on text selection within the current console&nbsp;

  - [AddConsoleAlias](win32console.md#win32consoleaddconsolealias)

    Creates a new console alias&nbsp;

  - [GetConsoleAliases](win32console.md#win32consolegetconsolealiases)

    Retrieves aliases defined under specified executable&nbsp;

  - [GetConsoleAliasExes](win32console.md#win32consolegetconsolealiasexes)

    Lists all executables that have console aliases defined&nbsp;

  - [GetConsoleWindow](win32console.md#win32consolegetconsolewindow)

    Returns a handle to the console's window, or 0 if none exists&nbsp;

  - [GetNumberOfConsoleFonts](win32console.md#win32consolegetnumberofconsolefonts)

    Returns the number of fonts available to the console&nbsp;

  - [SetConsoleTitle](win32console.md#win32consolesetconsoletitle)

    Sets the title of calling process's console&nbsp;

  - [GetConsoleTitle](win32console.md#win32consolegetconsoletitle)

    Returns the title of console to which calling process is attached&nbsp;

  - [GenerateConsoleCtrlEvent](win32console.md#win32consolegenerateconsolectrlevent)

    Sends a control signal to a group of processes attached to a common console&nbsp;

  - [GetStdHandle](win32console.md#win32consolegetstdhandle)

    Returns one of calling process's standard handles&nbsp;


## [win32console](win32console.md#win32console)\.AddConsoleAlias

AddConsoleAlias\(Source, Target, ExeName\)
Creates a new console alias

#### Parameters

  - Source : [PyUNICODE](PyUNICODE.md)

    The string to be mapped to the target string

  - Target : [PyUNICODE](PyUNICODE.md)

    String to be substituted for Source\.  If None, alias is removed

  - ExeName : [PyUNICODE](PyUNICODE.md)

    Name of executable that will use alias


## [win32console](win32console.md#win32console)\.AllocConsole

AllocConsole\(\)
Creates a new console for the calling process

#### Comments

Calling process must not already be attached to another console


## [win32console](win32console.md#win32console)\.AttachConsole

AttachConsole\(ProcessId\)
Attaches to console of another process

#### Parameters

  - ProcessId : int

    Pid of another process, or ATTACH\_PARENT\_PROCESS

#### Comments

Calling process must not already be attached to another console


## [win32console](win32console.md#win32console)\.CreateConsoleScreenBuffer

[PyConsoleScreenBuffer](PyConsoleScreenBuffer.md) = CreateConsoleScreenBuffer\(DesiredAccess, ShareMode

, SecurityAttributes

, Flags

\)
Creates a new console screen buffer

#### Parameters

  - DesiredAccess=GENERIC\_READ and GENERIC\_WRITE : int

    GENERIC\_READ and/or GENERIC\_WRITE

  - ShareMode=FILE\_SHARE\_READ and FILE\_SHARE\_WRITE : int

    FILE\_SHARE\_READ and/or FILE\_SHARE\_WRITE

  - SecurityAttributes=None : [PySECURITY\_ATTRIBUTES](PySECURITY.md#pysecurityattributes)

    Specifies security descriptor and inheritance for handle

  - Flags=CONSOLE\_TEXTMODE\_BUFFER : int

    CONSOLE\_TEXTMODE\_BUFFER is currently only valid flag


## [win32console](win32console.md#win32console)\.FreeConsole

FreeConsole\(\)
Detaches process from its current console


## [win32console](win32console.md#win32console)\.GenerateConsoleCtrlEvent

GenerateConsoleCtrlEvent\(CtrlEvent, ProcessGroupId\)
Sends a control signal to a group of processes attached to a common console

#### Parameters

  - CtrlEvent : int

    Signal to be sent to specified process group - CTRL\_C\_EVENT or CTRL\_BREAK\_EVENT

  - ProcessGroupId=0 : int

    Pid of a process group, use 0 for calling process


## [win32console](win32console.md#win32console)\.GetConsoleAliasExes

[PyUNICODE](PyUNICODE.md) = GetConsoleAliasExes\(\)
Lists all executables that have console aliases defined

#### Return Value
Returns a unicode string containing executable names separated by NULLS


## [win32console](win32console.md#win32console)\.GetConsoleAliases

[PyUNICODE](PyUNICODE.md) = GetConsoleAliases\(ExeName\)
Retrieves aliases defined under specified executable

#### Parameters

  - ExeName : [PyUNICODE](PyUNICODE.md)

    Name of executable for which to return aliases

#### Return Value
Returns a unicode string containing null-terminated pairs of aliases and their target text 

of the form "alias1=replacementtext1\\\\0alias2=replacementtext2\\\\0"


## [win32console](win32console.md#win32console)\.GetConsoleCP

int = GetConsoleCP\(\)
Returns the input code page for calling process's console


## [win32console](win32console.md#win32console)\.GetConsoleDisplayMode

int = GetConsoleDisplayMode\(\)
Returns the current console's display mode

#### Comments

Only exists on Wix XP and later

#### Return Value
CONSOLE\_FULLSCREEN,CONSOLE\_FULLSCREEN\_HARDWARE


## [win32console](win32console.md#win32console)\.GetConsoleOutputCP

int = GetConsoleOutputCP\(\)
Returns the output code page for calling process's console


## [win32console](win32console.md#win32console)\.GetConsoleProcessList

\(int,\.\.\.\) = GetConsoleProcessList\(\)
Returns pids of all processes attached to current console


## [win32console](win32console.md#win32console)\.GetConsoleSelectionInfo

dict = GetConsoleSelectionInfo\(\)
Returns info on text selection within the current console

#### Return Value
Returns a dictionary containing \{Flags:int, SelectionAnchor: [PyCOORD](PyCOORD.md), Selection:[PySMALL\_RECT](PySMALL.md#pysmallrect)\} 

Flags will contain a combination of 

CONSOLE\_NO\_SELECTION,CONSOLE\_SELECTION\_IN\_PROGRESS,CONSOLE\_SELECTION\_NOT\_EMPTY,CONSOLE\_MOUSE\_SELECTION,CONSOLE\_MOUSE\_DOWN


## [win32console](win32console.md#win32console)\.GetConsoleTitle

[PyUNICODE](PyUNICODE.md) = GetConsoleTitle\(\)
Returns the title of the console window


## [win32console](win32console.md#win32console)\.GetConsoleWindow

int = GetConsoleWindow\(\)
Returns a handle to the console's window, or 0 if none exists

#### Return Value
This function may raise NotImplementedError if it does not exist on 

the platform, or a [PyHANDLE](PyHANDLE.md) object with a value of 0\.  It will never 

raise a win32 exception\.


## [win32console](win32console.md#win32console)\.GetNumberOfConsoleFonts

int = GetNumberOfConsoleFonts\(\)
Returns the number of fonts available to the console

#### Comments

Function is not documented in MSDN


## [win32console](win32console.md#win32console)\.GetStdHandle

[PyConsoleScreenBuffer](PyConsoleScreenBuffer.md) = GetStdHandle\(StdHandle\)
Returns one of calling process's standard handles

#### Parameters

  - StdHandle : int

    Specifies the handle to return - STD\_INPUT\_HANDLE, STD\_OUTPUT\_HANDLE, or STD\_ERROR\_HANDLE

#### Return Value
Returns a [PyConsoleScreenBuffer](PyConsoleScreenBuffer.md) wrapping the handle, or None if specified handle does not exist


## [win32console](win32console.md#win32console)\.SetConsoleCP

SetConsoleCP\(CodePageId\)
Sets the input code page for calling process's console

#### Parameters

  - CodePageId : int

    The code page to set


## [win32console](win32console.md#win32console)\.SetConsoleOutputCP

SetConsoleOutputCP\(CodePageID\)
Sets the output code page for calling process's console

#### Parameters

  - CodePageID : int

    The code page to set


## [win32console](win32console.md#win32console)\.SetConsoleTitle

SetConsoleTitle\(ConsoleTitle\)
Sets the title of the console window

#### Parameters

  - ConsoleTitle : [PyUNICODE](PyUNICODE.md)

    New title for the console