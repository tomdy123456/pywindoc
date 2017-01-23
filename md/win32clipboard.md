# win32clipboard


## Module win32clipboard

A module which supports the Windows Clipboard API\.

#### Methods

  - [ChangeClipboardChain](win32clipboard.md#win32clipboardchangeclipboardchain)

    Removes a specified window from the chain 

of clipboard viewers\.&nbsp;

  - [CloseClipboard](win32clipboard.md#win32clipboardcloseclipboard)

    Closes the clipboard\.&nbsp;

  - [CountClipboardFormats](win32clipboard.md#win32clipboardcountclipboardformats)

    Retrieves the number of different data 

formats currently on the clipboard\.&nbsp;

  - [EmptyClipboard](win32clipboard.md#win32clipboardemptyclipboard)

    Empties the clipboard and frees handles to data 

in the clipboard\.&nbsp;

  - [EnumClipboardFormats](win32clipboard.md#win32clipboardenumclipboardformats)

    Lets you enumerate the data formats that 

are currently available on the clipboard\.&nbsp;

  - [GetClipboardData](win32clipboard.md#win32clipboardgetclipboarddata)

    Retrieves data from the clipboard in a 

specified format\.&nbsp;

  - [GetClipboardDataHandle](win32clipboard.md#win32clipboardgetclipboarddatahandle)

    Retrieves data from the clipboard in a 

specified format, returning the underlying integer handle\.&nbsp;

  - [GetClipboardFormatName](win32clipboard.md#win32clipboardgetclipboardformatname)

    Retrieves from the clipboard the name 

of the specified registered format\.&nbsp;

  - [GetClipboardOwner](win32clipboard.md#win32clipboardgetclipboardowner)

    Retrieves the window handle of the current 

owner of the clipboard\.&nbsp;

  - [GetClipboardSequenceNumber](win32clipboard.md#win32clipboardgetclipboardsequencenumber)

    Returns the clipboard sequence number 

for the current window station\.&nbsp;

  - [GetClipboardViewer](win32clipboard.md#win32clipboardgetclipboardviewer)

    Retrieves the handle of the first window in 

the clipboard viewer chain\.&nbsp;

  - [GetGlobalMemory](win32clipboard.md#win32clipboardgetglobalmemory)

    Returns the contents of the specified global 

memory object\.&nbsp;

  - [GetOpenClipboardWindow](win32clipboard.md#win32clipboardgetopenclipboardwindow)

    Retrieves the handle of the window that 

currently has the clipboard open\.&nbsp;

  - [GetPriorityClipboardFormat](win32clipboard.md#win32clipboardgetpriorityclipboardformat)

    Returns the first available clipboard 

format in the specified list\.&nbsp;

  - [IsClipboardFormatAvailable](win32clipboard.md#win32clipboardisclipboardformatavailable)

    Determines whether the clipboard 

contains data in the specified format\.&nbsp;

  - [OpenClipboard](win32clipboard.md#win32clipboardopenclipboard)

    Opens the clipboard for examination\.&nbsp;

  - [RegisterClipboardFormat](win32clipboard.md#win32clipboardregisterclipboardformat)

    Registers a new clipboard format\.&nbsp;

  - [SetClipboardData](win32clipboard.md#win32clipboardsetclipboarddata)

    Places data on the clipboard in a specified 

clipboard format\.&nbsp;

  - [SetClipboardText](win32clipboard.md#win32clipboardsetclipboardtext)

    Places text on the clipboard \.&nbsp;

  - [SetClipboardViewer](win32clipboard.md#win32clipboardsetclipboardviewer)

    Adds the specified window to the chain of 

clipboard viewers&nbsp;


## [win32clipboard](win32clipboard.md#win32clipboard)\.ChangeClipboardChain

int = ChangeClipboardChain\(hWndRemove, hWndNewNext

\)
The ChangeClipboardChain 

function removes a specified window from the chain of clipboard viewers\.

#### Parameters

  - hWndRemove : int

    Integer handle to the window to be removed from 

the chain\. The handle must have been passed to the SetClipboardViewer 

function\.

  - hWndNewNext : int

    Integer handle to the window that follows the 

hWndRemove window in the clipboard viewer chain\. \(This is the handle 

returned by SetClipboardViewer, unless the sequence was changed in 

response to a WM\_CHANGECBCHAIN message\.\)

#### Comments

The window identified by hWndNewNext replaces the hWndRemove window 

in the chain\. The SetClipboardViewer function sends a WM\_CHANGECBCHAIN 

message to the first window in the clipboard viewer chain\.

#### Win32 API References

  - Search for ChangeClipboardChain at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=ChangeClipboardChain.md), [google](http://www.google.com/search?q=ChangeClipboardChain.md) or [google groups](http://groups.google.com/groups?q=ChangeClipboardChain.md)\.

#### Return Value
The return value indicates the result of passing the 

WM\_CHANGECBCHAIN message to the windows in the clipboard viewer chain\. 

Because a window in the chain typically returns FALSE when it processes 

WM\_CHANGECBCHAIN, the return value from ChangeClipboardChain is typically 

FALSE\. If there is only one window in the chain, the return value is 

typically TRUE\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.CloseClipboard

None = CloseClipboard\(\)
The CloseClipboard function closes 

the clipboard\.

#### Comments

When the window has finished examining or changing the clipboard, 

close the clipboard by calling CloseClipboard\. This enables other windows 

to access the clipboard\.
 

Do not place an object on the clipboard after calling CloseClipboard\.

#### Win32 API References

  - Search for CloseClipboard at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=CloseClipboard.md), [google](http://www.google.com/search?q=CloseClipboard.md) or [google groups](http://groups.google.com/groups?q=CloseClipboard.md)\.

#### Return Value
If the function succeeds, the return value is None\.
 

If the function fails, win32api\.error is raised with the GetLastError 

info\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.CountClipboardFormats

int = CountClipboardFormats\(\)
The CountClipboardFormats 

function retrieves the number of different data formats currently on the 

clipboard\.

#### Win32 API References

  - Search for CountClipboardFormats at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=CountClipboardFormats.md), [google](http://www.google.com/search?q=CountClipboardFormats.md) or [google groups](http://groups.google.com/groups?q=CountClipboardFormats.md)\.

#### Return Value
If the function succeeds, the return value is the number of 

different data formats currently on the clipboard\. 

If the function fails, win32api\.error is raised with the GetLastError 

info\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.EmptyClipboard

None = EmptyClipboard\(\)
The EmptyClipboard function empties 

the clipboard and frees handles to data in the clipboard\. The function then 

assigns ownership of the clipboard to the window that currently has the 

clipboard open\.

#### Comments

Before calling EmptyClipboard, an application must open the 

clipboard by using the OpenClipboard function\. If the application 

specifies a NULL window handle when opening the clipboard, EmptyClipboard 

succeeds but sets the clipboard owner to NULL\.

#### Win32 API References

  - Search for EmptyClipboard at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=EmptyClipboard.md), [google](http://www.google.com/search?q=EmptyClipboard.md) or [google groups](http://groups.google.com/groups?q=EmptyClipboard.md)\.

#### Return Value
If the function succeeds, the return value is None\.
 

If the function fails, win32api\.error is raised with the GetLastError 

info\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.EnumClipboardFormats

int = EnumClipboardFormats\(format\)
The EnumClipboardFormats 

function lets you enumerate the data formats that are currently available 

on the clipboard\.

#### Parameters

  - format=0 : int

    Specifies a clipboard format that is known to be 

available\.
 

To start an enumeration of clipboard formats, set format to zero\. When 

format is zero, the function retrieves the first available clipboard 

format\. For subsequent calls during an enumeration, set format to the 

result of the previous EnumClipboardFormat call\.

#### Comments

Clipboard data formats are stored in an ordered list\. To perform an 

enumeration of clipboard data formats, you make a series of calls to the 

EnumClipboardFormats function\. For each call, the format parameter 

specifies an available clipboard format, and the function returns the next 

available clipboard format\.
 

You must open the clipboard before enumerating its formats\. Use the 

OpenClipboard function to open the clipboard\. The EnumClipboardFormats 

function fails if the clipboard is not open\.
 

The EnumClipboardFormats function enumerates formats in the order that 

they were placed on the clipboard\. If you are copying information to the 

clipboard, add clipboard objects in order from the most descriptive 

clipboard format to the least descriptive clipboard format\. If you are 

pasting information from the clipboard, retrieve the first clipboard 

format that you can handle\. That will be the most descriptive clipboard 

format that you can handle\.
 

The system provides automatic type conversions for certain clipboard 

formats\. In the case of such a format, this function enumerates the 

specified format, then enumerates the formats to which it can be 

converted\.  For more information, see Standard Clipboard Formats and 

Synthesized Clipboard Formats\.

#### Win32 API References

  - Search for EnumClipboardFormats at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=EnumClipboardFormats.md), [google](http://www.google.com/search?q=EnumClipboardFormats.md) or [google groups](http://groups.google.com/groups?q=EnumClipboardFormats.md)\.

#### Return Value
If the function succeeds, the return value is the clipboard 

format that follows the specified format\. In other words, the next 

available clipboard format\.
 

If there are no more clipboard formats to enumerate, the return value is 

zero\.
 

If the function fails, win32api\.error is raised with the GetLastError 

info\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.GetClipboardData

string/unicode = GetClipboardData\(format\)
The GetClipboardData function 

retrieves data from the clipboard in a specified format\. The clipboard 

must have been opened previously\.  Note that not all data formats are supported, 

and that the underlying handle can be retrieved with 

[win32clipboard::GetClipboardDataHandle](win32clipboard.md#win32clipboardgetclipboarddatahandle)

#### Parameters

  - format=CF\_TEXT : int

    Specifies a clipboard format\. For a description of 

the standard clipboard formats, see Standard Clipboard Formats\. 

In Unicode builds \(ie, python 3k\), the default is CF\_UNICODETEXT\.

#### Comments

An application can enumerate the available formats in advance by 

using the EnumClipboardFormats function\.
 

The clipboard controls the handle that the GetClipboardData function 

returns, not the application\. The application should copy the data 

immediately\. The application cannot rely on being able to make long-term 

use of the handle\. The application must not free the handle nor leave it 

locked\.
 

The system performs implicit data format conversions between certain 

clipboard formats when an application calls the GetClipboardData function\. 

For example, if the CF\_OEMTEXT format is on the clipboard, a window can 

retrieve data in the CF\_TEXT format\. The format on the clipboard is 

converted to the requested format on demand\. For more information, see 

Synthesized Clipboard Formats\.

#### Win32 API References

  - Search for GetClipboardData at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetClipboardData.md), [google](http://www.google.com/search?q=GetClipboardData.md) or [google groups](http://groups.google.com/groups?q=GetClipboardData.md)\.

  - Search for Standard Clipboard Formats at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=Standard Clipboard Formats.md), [google](http://www.google.com/search?q=Standard Clipboard Formats.md) or [google groups](http://groups.google.com/groups?q=Standard Clipboard Formats.md)\.

####  To Do
 CF\_METAFILEPICT format returns a pointer to a METAFILEPICT struct which contains the metafile handle, 

rather than returning the handle directly\.  This code currently fails with 

error: \(6, 'GetClipboardData:GetMetafileBitsEx\(NULL\)', 'The handle is invalid\.'\)

#### Return Value
If the function fails, the standard win32api\.error exception 

is raised\.  If the function succeeds, the return value is as 

described in the following table:




## [win32clipboard](win32clipboard.md#win32clipboard)\.GetClipboardDataHandle

int = GetClipboardDataHandle\(format\)
Retrieves data from the 

clipboard in a specified format, and returns an integer handle to the data\. 

To get the data bytes, use the  [win32clipboard::GetClipboardData](win32clipboard.md#win32clipboardgetclipboarddata) function\.

#### Parameters

  - format=CF\_TEXT : int

    Specifies a clipboard format\. For a description of 

the standard clipboard formats, see Standard Clipboard Formats\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.GetClipboardFormatName

string = GetClipboardFormatName\(format\)
The GetClipboardFormatName 

function retrieves from the clipboard the name of the specified registered 

format\.

#### Parameters

  - format : int

    Specifies the type of format to be retrieved\. This 

parameter must not specify any of the predefined clipboard formats\.

#### Win32 API References

  - Search for GetClipboardFormatName at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetClipboardFormatName.md), [google](http://www.google.com/search?q=GetClipboardFormatName.md) or [google groups](http://groups.google.com/groups?q=GetClipboardFormatName.md)\.

#### Return Value
If the function succeeds, the return value is the string containing 

the format\.
 

If the function fails, win32api\.error is raised with the GetLastError 

info\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.GetClipboardOwner

int = GetClipboardOwner\(\)
The GetClipboardOwner function 

retrieves the window handle of the current owner of the clipboard\.

#### Comments

The clipboard can still contain data even if the clipboard is not 

currently owned\.
 

In general, the clipboard owner is the window that last placed data in 

clipboard\. The EmptyClipboard function assigns clipboard ownership\.

#### Win32 API References

  - Search for GetClipboardOwner at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetClipboardOwner.md), [google](http://www.google.com/search?q=GetClipboardOwner.md) or [google groups](http://groups.google.com/groups?q=GetClipboardOwner.md)\.

#### Return Value
If the function succeeds, the return value is the handle of the 

window that owns the clipboard\. 

If the function fails, win32api\.error is raised with the GetLastError 

info\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.GetClipboardSequenceNumber

int = GetClipboardSequenceNumber\(\)
The 

GetClipboardSequenceNumber function returns the clipboard sequence number 

for the current window station\.

#### Comments

This method is not available on some early Windows \(eg 95\) machines\.

\[This is preliminary documentation and subject to change\.\]
 

The system keeps a 32-bit serial number for the clipboard for each window 

station\. This number is incremented whenever the contents of the 

clipboard change or the clipboard is emptied\. You can track this value to 

determine whether the clipboard contents have changed and optimize 

creating DataObjects\. If clipboard rendering is delayed, the sequence 

number is not incremented until the changes are rendered\.

#### Win32 API References

  - Search for GetClipboardSequenceNumber at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetClipboardSequenceNumber.md), [google](http://www.google.com/search?q=GetClipboardSequenceNumber.md) or [google groups](http://groups.google.com/groups?q=GetClipboardSequenceNumber.md)\.

#### Return Value
The return value is the clipboard sequence number\. If you do not 

have WINSTA\_ACCESSCLIPBOARD access to the window station, the function 

returns zero\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.GetClipboardViewer

int = GetClipboardViewer\(\)
The GetClipboardViewer function 

retrieves the handle of the first window in the clipboard viewer chain\.

#### Win32 API References

  - Search for GetClipboardViewer at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetClipboardViewer.md), [google](http://www.google.com/search?q=GetClipboardViewer.md) or [google groups](http://groups.google.com/groups?q=GetClipboardViewer.md)\.

#### Return Value
If the function succeeds, the return value is the handle of the 

first window in the clipboard viewer chain\. 

If the function fails, win32api\.error is raised with the GetLastError 

info\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.GetGlobalMemory

string = GetGlobalMemory\(hglobal\)
Returns the contents of the specified 

global memory object\.

#### Parameters

  - hglobal : [PyHANDLE](PyHANDLE.md)

    The handle to the global memory object


## [win32clipboard](win32clipboard.md#win32clipboard)\.GetOpenClipboardWindow

int = GetOpenClipboardWindow\(\)
The GetOpenClipboardWindow 

function retrieves the handle of the window that currently has the 

clipboard open\.

#### Comments

If an application or dynamic-link library \(DLL\) specifies a NULL 

window handle when calling the OpenClipboard function, the clipboard is 

opened but is not associated with a window\. In such a case, 

GetOpenClipboardWindow returns NULL\.

#### Win32 API References

  - Search for GetOpenClipboardWindow at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetOpenClipboardWindow.md), [google](http://www.google.com/search?q=GetOpenClipboardWindow.md) or [google groups](http://groups.google.com/groups?q=GetOpenClipboardWindow.md)\.

#### Return Value
If the function succeeds, the return value is the handle of the 

window that has the clipboard open\. 

If the function fails, win32api\.error is raised with the GetLastError 

info\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.GetPriorityClipboardFormat

int = GetPriorityClipboardFormat\(formats\)
Returns the first available clipboard format in the specified list\.

#### Parameters

  - formats : sequence

    Sequence of integers identifying clipboard formats, 

in priority order\. For a description of the standard clipboard formats, 

see Standard Clipboard Formats\.

#### Win32 API References

  - Search for GetPriorityClipboardFormat at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetPriorityClipboardFormat.md), [google](http://www.google.com/search?q=GetPriorityClipboardFormat.md) or [google groups](http://groups.google.com/groups?q=GetPriorityClipboardFormat.md)\.

  - Search for Standard Clipboard Formats at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=Standard Clipboard Formats.md), [google](http://www.google.com/search?q=Standard Clipboard Formats.md) or [google groups](http://groups.google.com/groups?q=Standard Clipboard Formats.md)\.

#### Return Value
If the function succeeds, the return value is the first clipboard 

format in the list for which data is available\. If the clipboard is 

empty, the return value is NULL\. If the clipboard contains data, but not 

in any of the specified formats, the return value is -1\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.IsClipboardFormatAvailable

int = IsClipboardFormatAvailable\(format\)
The 

IsClipboardFormatAvailable function determines whether the clipboard 

contains data in the specified format\.

#### Parameters

  - format : int

    Specifies a clipboard format\. For a description of 

the standard clipboard formats, see Standard Clipboard Formats\.

#### Comments

Typically, an application that recognizes only one clipboard format 

would call this function when processing the WM\_INITMENU or 

WM\_INITMENUPOPUP message\. The application would then enable or disable 

the Paste menu item, depending on the return value\. Applications that 

recognize more than one clipboard format should use the 

GetPriorityClipboardFormat function for this purpose\.

#### Win32 API References

  - Search for IsClipboardFormatAvailable at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=IsClipboardFormatAvailable.md), [google](http://www.google.com/search?q=IsClipboardFormatAvailable.md) or [google groups](http://groups.google.com/groups?q=IsClipboardFormatAvailable.md)\.

  - Search for Standard Clipboard Formats at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=Standard Clipboard Formats.md), [google](http://www.google.com/search?q=Standard Clipboard Formats.md) or [google groups](http://groups.google.com/groups?q=Standard Clipboard Formats.md)\.

#### Return Value
If the clipboard format is available, the return value is nonzero\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.OpenClipboard

None = OpenClipboard\(hWnd\)
The OpenClipboard function opens the 

clipboard for examination and prevents other applications from modifying 

the clipboard content\.

#### Parameters

  - hWnd=None : [PyHANDLE](PyHANDLE.md)

    Integer handle to the window to be associated with the 

open clipboard\. If this parameter is None, the open clipboard is associated 

with the current task\.

#### Comments

OpenClipboard fails if another window has the clipboard open\.
 

An application should call the CloseClipboard function after every 

successful call to OpenClipboard\.
 

The window identified by the hWnd parameter does not become the 

clipboard owner unless the EmptyClipboard function is called\.

#### Win32 API References

  - Search for OpenClipboard at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=OpenClipboard.md), [google](http://www.google.com/search?q=OpenClipboard.md) or [google groups](http://groups.google.com/groups?q=OpenClipboard.md)\.

#### Return Value
If the function succeeds, the return value is None\.
 

If the function fails, win32api\.error is raised with the GetLastError 

info\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.RegisterClipboardFormat

None = RegisterClipboardFormat\(name\)
The 

RegisterClipboardFormat function registers a new clipboard format\. 

This format can then be used as a valid clipboard format\.

#### Parameters

  - name : string

    String that names the new format\.

#### Comments

If a registered format with the specified name already exists, a 

new format is not registered and the return value identifies the existing 

format\. This enables more than one application to copy and paste data 

using the same registered clipboard format\. Note that the format name 

comparison is case-insensitive\.
 

Registered clipboard formats are identified by values in the range 0xC000 

through 0xFFFF\.

#### Win32 API References

  - Search for RegisterClipboardFormat at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegisterClipboardFormat.md), [google](http://www.google.com/search?q=RegisterClipboardFormat.md) or [google groups](http://groups.google.com/groups?q=RegisterClipboardFormat.md)\.

#### Return Value
If the function succeeds, the return value identifies the 

registered clipboard format\. 

If the function fails, win32api\.error is raised with the GetLastError 

info\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.SetClipboardData

int = SetClipboardData\(format, hMem

\)
The SetClipboardData function 

places data on the clipboard in a specified clipboard format\. The window 

must be the current clipboard owner, and the application must have called 

the OpenClipboard function\. \(When responding to the WM\_RENDERFORMAT and 

WM\_RENDERALLFORMATS messages, the clipboard owner must not call 

OpenClipboard before calling SetClipboardData\.\)

#### Parameters

  - format : int

    Specifies a clipboard format\. For a description of 

the standard clipboard formats, see Standard Clipboard Formats\.

  - hMem : int/buffer

    Integer handle to the data in the specified 

format, or string, unicode, or any object that supports the buffer interface\. 

A global memory object is allocated, and the object's buffer is copied to the new memory\. 

This parameter can be 0, indicating that the window provides data in 

the specified clipboard format \(renders the format\) upon request\. If a 

window delays rendering, it must process the WM\_RENDERFORMAT and 

WM\_RENDERALLFORMATS messages\.
 

After SetClipboardData is called, the system owns the object identified 

by the hMem parameter\. The application can read the data, but must not 

free the handle or leave it locked\. If the hMem parameter identifies a 

memory object, the object must have been allocated using the GlobalAlloc 

function with the GMEM\_MOVEABLE and GMEM\_DDESHARE flags\.

#### Comments

The uFormat parameter can identify a registered clipboard format, 

or it can be one of the standard clipboard formats\. For more information, 

see Registered Clipboard Formats and Standard Clipboard Formats\.
 

The system performs implicit data format conversions between certain 

clipboard formats when an application calls the GetClipboardData function\. 

For example, if the CF\_OEMTEXT format is on the clipboard, a window can 

retrieve data in the CF\_TEXT format\. The format on the clipboard is 

converted to the requested format on demand\. For more information, see 

Synthesized Clipboard Formats\.

#### Win32 API References

  - Search for SetClipboardData at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SetClipboardData.md), [google](http://www.google.com/search?q=SetClipboardData.md) or [google groups](http://groups.google.com/groups?q=SetClipboardData.md)\.

#### Return Value
If the function succeeds, the return value is integer handle 

of the data\.
 

If the function fails, win32api\.error is raised with the GetLastError 

info\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.SetClipboardText

int = SetClipboardText\(text, format

\)
Convienience function to 

call SetClipboardData with text\.

#### Parameters

  - text : str/unicode

    The text to place on the clipboard\.

  - format=CF\_TEXT : int

    The clipboard format to use - must be CF\_TEXT or CF\_UNICODETEXT

#### Comments

You may pass a Unicode or string/bytes object to this function, 

but depending on the value of the 'format' param, it may be converted 

to the appropriate type for that param\.

Many applications will want to call this function twice, with the 

same string specified but CF\_UNICODETEXT specified the second\.

#### Win32 API References

  - Search for SetClipboardData at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SetClipboardData.md), [google](http://www.google.com/search?q=SetClipboardData.md) or [google groups](http://groups.google.com/groups?q=SetClipboardData.md)\.

#### Return Value
If the function succeeds, the return value is integer handle 

of the data\.
 

If the function fails, win32api\.error is raised with the GetLastError 

info\.


## [win32clipboard](win32clipboard.md#win32clipboard)\.SetClipboardViewer

[PyHANDLE](PyHANDLE.md) = SetClipboardViewer\(hWndNewViewer\)
The SetClipboardViewer function 

adds the specified window to the chain of clipboard viewers\. Clipboard 

viewer windows receive a WM\_DRAWCLIPBOARD message whenever the content of 

the clipboard changes\.

#### Parameters

  - hWndNewViewer : [PyHANDLE](PyHANDLE.md)

    Integer handle to the window to be added to 

the clipboard chain\.

#### Comments

The windows that are part of the clipboard viewer chain, called 

clipboard viewer windows, must process the clipboard messages 

WM\_CHANGECBCHAIN and WM\_DRAWCLIPBOARD\. Each clipboard viewer window calls 

the SendMessage function to pass these messages to the next window in the 

clipboard viewer chain\.
 

A clipboard viewer window must eventually remove itself from the clipboard 

viewer chain by calling the ChangeClipboardChain function -- for example, 

in response to theWM\_DESTROY message\.

#### Win32 API References

  - Search for SetClipboardViewer at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SetClipboardViewer.md), [google](http://www.google.com/search?q=SetClipboardViewer.md) or [google groups](http://groups.google.com/groups?q=SetClipboardViewer.md)\.

#### Return Value
Returns a handle to the next window in chain, or None if no other viewer exists\.

If the function succeeds, the return value identifies the next 

window in the clipboard viewer chain\.
 

If an error occurs or there are no other windows in the clipboard viewer 

chain, win32api\.error is raised with the GetLastError info\.