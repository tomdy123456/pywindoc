# win32api


## Module win32api

A module, encapsulating the Windows Win32 API\.

#### Methods

  - [AbortSystemShutdown](win32api.md#win32apiabortsystemshutdown)

    Aborts a system shutdown&nbsp;

  - [InitiateSystemShutdown](win32api.md#win32apiinitiatesystemshutdown)

    Initiates a shutdown and optional restart of the specified computer\.&nbsp;

  - [Apply](win32api.md#win32apiapply)

    Calls a Python function, but traps Win32 exceptions\.&nbsp;

  - [Beep](win32api.md#win32apibeep)

    Generates a simple tone on the speaker\.&nbsp;

  - [BeginUpdateResource](win32api.md#win32apibeginupdateresource)

    Begins an update cycle for a PE file\.&nbsp;

  - [ChangeDisplaySettings](win32api.md#win32apichangedisplaysettings)

    Changes video mode for default display&nbsp;

  - [ChangeDisplaySettingsEx](win32api.md#win32apichangedisplaysettingsex)

    Changes video mode for specified display&nbsp;

  - [ClipCursor](win32api.md#win32apiclipcursor)

    Confines the cursor to a rectangular area on the screen\.&nbsp;

  - [CloseHandle](win32api.md#win32apiclosehandle)

    Closes an open handle\.&nbsp;

  - [CopyFile](win32api.md#win32apicopyfile)

    Copy a file\.&nbsp;

  - [DebugBreak](win32api.md#win32apidebugbreak)

    Breaks into the C debugger\.&nbsp;

  - [DeleteFile](win32api.md#win32apideletefile)

    Deletes the specified file\.&nbsp;

  - [DragQueryFile](win32api.md#win32apidragqueryfile)

    Retrieve the file names for dropped files\.&nbsp;

  - [DragFinish](win32api.md#win32apidragfinish)

    Free memory associated with dropped files\.&nbsp;

  - [DuplicateHandle](win32api.md#win32apiduplicatehandle)

    Duplicates a handle\.&nbsp;

  - [EndUpdateResource](win32api.md#win32apiendupdateresource)

    Ends a resource update cycle of a PE file\.&nbsp;

  - [EnumDisplayDevices](win32api.md#win32apienumdisplaydevices)

    Obtain information about the display devices in a system&nbsp;

  - [EnumDisplayMonitors](win32api.md#win32apienumdisplaymonitors)

    Lists monitors for a device context&nbsp;

  - [EnumDisplaySettings](win32api.md#win32apienumdisplaysettings)

    Lists available modes for specified device&nbsp;

  - [EnumDisplaySettingsEx](win32api.md#win32apienumdisplaysettingsex)

    Lists available modes for a display device, with optional flags&nbsp;

  - [EnumResourceLanguages](win32api.md#win32apienumresourcelanguages)

    List languages for specified resource&nbsp;

  - [EnumResourceNames](win32api.md#win32apienumresourcenames)

    Enumerates all the resources of the specified type from the nominated file\.&nbsp;

  - [EnumResourceTypes](win32api.md#win32apienumresourcetypes)

    Return list of all resource types contained in module&nbsp;

  - [ExpandEnvironmentStrings](win32api.md#win32apiexpandenvironmentstrings)

    Expands environment-variable strings and replaces them with their defined values\.&nbsp;

  - [ExitWindows](win32api.md#win32apiexitwindows)

    Logs off the current user&nbsp;

  - [ExitWindowsEx](win32api.md#win32apiexitwindowsex)

    either logs off the current user, shuts down the system, or shuts down and restarts the system\.&nbsp;

  - [FindFiles](win32api.md#win32apifindfiles)

    Find files matching a file spec\.&nbsp;

  - [FindFirstChangeNotification](win32api.md#win32apifindfirstchangenotification)

    Creates a change notification handle and sets up initial change notification filter conditions\.&nbsp;

  - [FindNextChangeNotification](win32api.md#win32apifindnextchangenotification)

    Requests that the operating system signal a change notification handle the next time it detects an appropriate change\.&nbsp;

  - [FindCloseChangeNotification](win32api.md#win32apifindclosechangenotification)

    Closes the change notification handle\.&nbsp;

  - [FindExecutable](win32api.md#win32apifindexecutable)

    Find an executable associated with a document\.&nbsp;

  - [FormatMessage](win32api.md#win32apiformatmessage)

    Return an error message string\.&nbsp;

  - [FormatMessageW](win32api.md#win32apiformatmessagew)

    Return an error message string \(as a Unicode object\)\.&nbsp;

  - [FreeLibrary](win32api.md#win32apifreelibrary)

    Decrements the reference count of the loaded dynamic-link library \(DLL\) module\.&nbsp;

  - [GenerateConsoleCtrlEvent](win32api.md#win32apigenerateconsolectrlevent)

    Send a specified signal to a console process group that shares the console associated with the calling process\.&nbsp;

  - [GetAsyncKeyState](win32api.md#win32apigetasynckeystate)

    Retrieves the asynch state of a virtual key code\.&nbsp;

  - [GetCommandLine](win32api.md#win32apigetcommandline)

    Return the application's command line\.&nbsp;

  - [GetComputerName](win32api.md#win32apigetcomputername)

    Returns the local computer name&nbsp;

  - [GetComputerNameEx](win32api.md#win32apigetcomputernameex)

    Retrieves a NetBIOS or DNS name associated with the local computer&nbsp;

  - [GetComputerObjectName](win32api.md#win32apigetcomputerobjectname)

    Retrieves the local computer's name in a specified format&nbsp;

  - [GetMonitorInfo](win32api.md#win32apigetmonitorinfo)

    Retrieves information for a monitor by handle&nbsp;

  - [GetUserName](win32api.md#win32apigetusername)

    Returns the current user name\.&nbsp;

  - [GetUserNameEx](win32api.md#win32apigetusernameex)

    Returns the current user name in format specified by Name\* constants&nbsp;

  - [GetCursorPos](win32api.md#win32apigetcursorpos)

    Returns the position of the cursor, in screen co-ordinates\.&nbsp;

  - [GetCurrentThread](win32api.md#win32apigetcurrentthread)

    Returns a pseudohandle for the current thread\.&nbsp;

  - [GetCurrentThreadId](win32api.md#win32apigetcurrentthreadid)

    Returns the thread ID for the current thread\.&nbsp;

  - [GetCurrentProcessId](win32api.md#win32apigetcurrentprocessid)

    Returns the thread ID for the current thread\.&nbsp;

  - [GetCurrentProcess](win32api.md#win32apigetcurrentprocess)

    Returns a pseudohandle for the current process\.&nbsp;

  - [GetConsoleTitle](win32api.md#win32apigetconsoletitle)

    Return the application's console title\.&nbsp;

  - [GetDateFormat](win32api.md#win32apigetdateformat)

    Formats a date as a date string for a specified locale\.&nbsp;

  - [GetDiskFreeSpace](win32api.md#win32apigetdiskfreespace)

    Retrieves information about a disk\.&nbsp;

  - [GetDiskFreeSpaceEx](win32api.md#win32apigetdiskfreespaceex)

    Retrieves information about a disk\.&nbsp;

  - [GetDllDirectory](win32api.md#win32apigetdlldirectory)

    Retrieves the DLL search path&nbsp;

  - [GetDomainName](win32api.md#win32apigetdomainname)

    Returns the current domain name&nbsp;

  - [GetEnvironmentVariable](win32api.md#win32apigetenvironmentvariable)

    Retrieves the value of an environment variable\.&nbsp;

  - [GetEnvironmentVariableW](win32api.md#win32apigetenvironmentvariablew)

    Retrieves the value of an environment variable\.&nbsp;

  - [GetFileAttributes](win32api.md#win32apigetfileattributes)

    Retrieves the attributes for the named file\.&nbsp;

  - [GetFileVersionInfo](win32api.md#win32apigetfileversioninfo)

    Retrieves string version info&nbsp;

  - [GetFocus](win32api.md#win32apigetfocus)

    Retrieves the handle of the keyboard focus window associated with the thread that called the method\.&nbsp;

  - [GetFullPathName](win32api.md#win32apigetfullpathname)

    Returns the full path of a \(possibly relative\) path&nbsp;

  - [GetHandleInformation](win32api.md#win32apigethandleinformation)

    Retrieves a handle's flags\.&nbsp;

  - [GetKeyboardLayout](win32api.md#win32apigetkeyboardlayout)

    Retrieves the active input locale identifier&nbsp;

  - [GetKeyboardLayoutList](win32api.md#win32apigetkeyboardlayoutlist)

    Returns a sequence of all locale ids in the system&nbsp;

  - [GetKeyboardLayoutName](win32api.md#win32apigetkeyboardlayoutname)

    Retrieves the name of the active input locale identifier \(formerly called the keyboard layout\)\.&nbsp;

  - [GetKeyboardState](win32api.md#win32apigetkeyboardstate)

    Retrieves the status of the 256 virtual keys on the keyboard\.&nbsp;

  - [GetKeyState](win32api.md#win32apigetkeystate)

    Retrives the last known key state for a key\.&nbsp;

  - [GetLastError](win32api.md#win32apigetlasterror)

    Retrieves the last error code known by the system\.&nbsp;

  - [GetLastInputInfo](win32api.md#win32apigetlastinputinfo)

    Returns time of last input event in tick count&nbsp;

  - [GetLocalTime](win32api.md#win32apigetlocaltime)

    Returns the current local time\.&nbsp;

  - [GetLongPathName](win32api.md#win32apigetlongpathname)

    Converts the specified path to its long form\.&nbsp;

  - [GetLongPathNameW](win32api.md#win32apigetlongpathnamew)

    Converts the specified path to its long form\.&nbsp;

  - [GetLogicalDrives](win32api.md#win32apigetlogicaldrives)

    Returns a bitmask representing the currently available disk drives\.&nbsp;

  - [GetLogicalDriveStrings](win32api.md#win32apigetlogicaldrivestrings)

    Returns a list of strings for all the drives\.&nbsp;

  - [GetModuleFileName](win32api.md#win32apigetmodulefilename)

    Retrieves the filename of the specified module\.&nbsp;

  - [GetModuleFileNameW](win32api.md#win32apigetmodulefilenamew)

    Retrieves the unicode filename of the specified module\.&nbsp;

  - [GetModuleHandle](win32api.md#win32apigetmodulehandle)

    Returns the handle of an already loaded DLL\.&nbsp;

  - [GetPwrCapabilities](win32api.md#win32apigetpwrcapabilities)

    Retrieves system's power capabilities&nbsp;

  - [GetProfileSection](win32api.md#win32apigetprofilesection)

    Returns a list of entries in an INI file\.&nbsp;

  - [GetProcAddress](win32api.md#win32apigetprocaddress)

    Returns the address of the specified exported dynamic-link library \(DLL\) function\.&nbsp;

  - [GetProfileVal](win32api.md#win32apigetprofileval)

    Returns a value from an INI file\.&nbsp;

  - [GetShortPathName](win32api.md#win32apigetshortpathname)

    Returns the 8\.3 version of a pathname\.&nbsp;

  - [GetStdHandle](win32api.md#win32apigetstdhandle)

    Returns a handle for the standard input, standard output, or standard error device&nbsp;

  - [GetSysColor](win32api.md#win32apigetsyscolor)

    Returns the system colors\.&nbsp;

  - [GetSystemDefaultLangID](win32api.md#win32apigetsystemdefaultlangid)

    Retrieves the system default language identifier\.&nbsp;

  - [GetSystemDefaultLCID](win32api.md#win32apigetsystemdefaultlcid)

    Retrieves the system default locale identifier\.&nbsp;

  - [GetSystemDirectory](win32api.md#win32apigetsystemdirectory)

    Returns the Windows system directory\.&nbsp;

  - [GetSystemFileCacheSize](win32api.md#win32apigetsystemfilecachesize)

    Returns the amount of memory reserved for file cache&nbsp;

  - [SetSystemFileCacheSize](win32api.md#win32apisetsystemfilecachesize)

    Sets the amount of memory reserved for file cache&nbsp;

  - [GetSystemInfo](win32api.md#win32apigetsysteminfo)

    Retrieves information about the current system\.&nbsp;

  - [GetNativeSystemInfo](win32api.md#win32apigetnativesysteminfo)

    Retrieves information about the current system for a Wow64 process\.&nbsp;

  - [GetSystemMetrics](win32api.md#win32apigetsystemmetrics)

    Returns the specified system metrics\.&nbsp;

  - [GetSystemTime](win32api.md#win32apigetsystemtime)

    Returns the current system time\.&nbsp;

  - [GetTempFileName](win32api.md#win32apigettempfilename)

    Creates a temporary file\.&nbsp;

  - [GetTempPath](win32api.md#win32apigettemppath)

    Returns the path designated as holding temporary files\.&nbsp;

  - [GetThreadLocale](win32api.md#win32apigetthreadlocale)

    Returns the current thread's locale\.&nbsp;

  - [GetTickCount](win32api.md#win32apigettickcount)

    Returns the milliseconds since windows started\.&nbsp;

  - [GetTimeFormat](win32api.md#win32apigettimeformat)

    Formats a time as a time string for a specified locale\.&nbsp;

  - [GetTimeZoneInformation](win32api.md#win32apigettimezoneinformation)

    Returns the system time-zone information\.&nbsp;

  - [GetVersion](win32api.md#win32apigetversion)

    Returns Windows version information\.&nbsp;

  - [GetVersionEx](win32api.md#win32apigetversionex)

    Returns Windows version information as a tuple\.&nbsp;

  - [GetVolumeInformation](win32api.md#win32apigetvolumeinformation)

    Returns information about a volume and file system attached to the system\.&nbsp;

  - [GetWindowsDirectory](win32api.md#win32apigetwindowsdirectory)

    Returns the windows directory\.&nbsp;

  - [GetWindowLong](win32api.md#win32apigetwindowlong)

    Retrieves a long value at the specified offset into the extra window memory of the given window\.&nbsp;

  - [GetUserDefaultLangID](win32api.md#win32apigetuserdefaultlangid)

    Retrieves the user default language identifier\.&nbsp;

  - [GetUserDefaultLCID](win32api.md#win32apigetuserdefaultlcid)

    Retrieves the user default locale identifier\.&nbsp;

  - [GlobalMemoryStatus](win32api.md#win32apiglobalmemorystatus)

    Returns systemwide memory usage&nbsp;

  - [GlobalMemoryStatusEx](win32api.md#win32apiglobalmemorystatusex)

    Returns physical and virtual memory usage&nbsp;

  - [keybd\_event](win32api.md#win32apikeybd_event)

    Simulate a keyboard event&nbsp;

  - [mouse\_event](win32api.md#win32apimouse_event)

    Simulate a mouse event&nbsp;

  - [LoadCursor](win32api.md#win32apiloadcursor)

    Loads a cursor\.&nbsp;

  - [LoadKeyboardLayout](win32api.md#win32apiloadkeyboardlayout)

    Loads a new locale id&nbsp;

  - [LoadLibrary](win32api.md#win32apiloadlibrary)

    Loads the specified DLL, and returns the handle\.&nbsp;

  - [LoadLibraryEx](win32api.md#win32apiloadlibraryex)

    Loads the specified DLL, and returns the handle\.&nbsp;

  - [LoadResource](win32api.md#win32apiloadresource)

    Finds and loads a resource from a PE file\.&nbsp;

  - [LoadString](win32api.md#win32apiloadstring)

    Loads a string from a resource file\.&nbsp;

  - [MapVirtualKeyEx](win32api.md#win32apimapvirtualkeyex)

    Translates \(maps\) a virtual-key code into a scan code or character value, or translates a scan code into a virtual-key code\.&nbsp;

  - [MessageBeep](win32api.md#win32apimessagebeep)

    Plays a predefined waveform sound\.&nbsp;

  - [MessageBox](win32api.md#win32apimessagebox)

    Display a message box\.&nbsp;

  - [MonitorFromPoint](win32api.md#win32apimonitorfrompoint)

    Finds monitor that contains a point&nbsp;

  - [MonitorFromRect](win32api.md#win32apimonitorfromrect)

    Finds monitor that has largest intersection with a rectangle&nbsp;

  - [MonitorFromWindow](win32api.md#win32apimonitorfromwindow)

    Finds monitor that contains a window&nbsp;

  - [MoveFile](win32api.md#win32apimovefile)

    Moves or renames a file\.&nbsp;

  - [MoveFileEx](win32api.md#win32apimovefileex)

    Moves or renames a file\.&nbsp;

  - [OpenProcess](win32api.md#win32apiopenprocess)

    Retrieves a handle to an existing process\.&nbsp;

  - [OutputDebugString](win32api.md#win32apioutputdebugstring)

    Writes output to the Windows debugger\.&nbsp;

  - [PostMessage](win32api.md#win32apipostmessage)

    Post a message to a window\.&nbsp;

  - [PostQuitMessage](win32api.md#win32apipostquitmessage)

    Posts a quit message\.&nbsp;

  - [PostThreadMessage](win32api.md#win32apipostthreadmessage)

    Post a message to a thread\.&nbsp;

  - [RegCloseKey](win32api.md#win32apiregclosekey)

    Closes a registry key\.&nbsp;

  - [RegConnectRegistry](win32api.md#win32apiregconnectregistry)

    Establishes a connection to a predefined registry handle on another computer\.&nbsp;

  - [RegCopyTree](win32api.md#win32apiregcopytree)

    Copies an entire registry key to another location&nbsp;

  - [RegCreateKey](win32api.md#win32apiregcreatekey)

    Creates the specified key, or opens the key if it already exists\.&nbsp;

  - [RegCreateKeyEx](win32api.md#win32apiregcreatekeyex)

    Extended version of RegCreateKey&nbsp;

  - [RegDeleteKey](win32api.md#win32apiregdeletekey)

    Deletes the specified key\.&nbsp;

  - [RegDeleteKeyEx](win32api.md#win32apiregdeletekeyex)

    Deletes a registry key from 32 or 64 bit registry view&nbsp;

  - [RegDeleteTree](win32api.md#win32apiregdeletetree)

    Recursively deletes a key's subkeys and values&nbsp;

  - [RegDeleteValue](win32api.md#win32apiregdeletevalue)

    Removes a named value from the specified registry key\.&nbsp;

  - [RegEnumKey](win32api.md#win32apiregenumkey)

    Enumerates subkeys of the specified open registry key\.&nbsp;

  - [RegEnumKeyEx](win32api.md#win32apiregenumkeyex)

    Enumerates subkeys of the specified open registry key\.&nbsp;

  - [RegEnumKeyExW](win32api.md#win32apiregenumkeyexw)

    Unicode version of RegEnumKeyEx&nbsp;

  - [RegEnumValue](win32api.md#win32apiregenumvalue)

    Enumerates values of the specified open registry key\.&nbsp;

  - [RegFlushKey](win32api.md#win32apiregflushkey)

    Writes all the attributes of the specified key to the registry\.&nbsp;

  - [RegGetKeySecurity](win32api.md#win32apireggetkeysecurity)

    Retrieves the security on the specified registry key\.&nbsp;

  - [RegLoadKey](win32api.md#win32apiregloadkey)

    Creates a subkey under HKEY\_USER or HKEY\_LOCAL\_MACHINE and stores registration information from a specified file into that subkey\.&nbsp;

  - [RegOpenCurrentUser](win32api.md#win32apiregopencurrentuser)

    Opens HKEY\_CURRENT\_USER for impersonated user&nbsp;

  - [RegOpenKey](win32api.md#win32apiregopenkey)

    Alias for [win32api::RegOpenKeyEx](win32api.md#win32apiregopenkeyex)&nbsp;

  - [RegOpenKeyEx](win32api.md#win32apiregopenkeyex)

    Opens the specified key\.&nbsp;

  - [RegOpenKeyTransacted](win32api.md#win32apiregopenkeytransacted)

    Opens a registry key as part of a transaction\.&nbsp;

  - [RegOverridePredefKey](win32api.md#win32apiregoverridepredefkey)

    Redirects one of the predefined keys to different key\.&nbsp;

  - [RegQueryValue](win32api.md#win32apiregqueryvalue)

    Retrieves the value associated with the unnamed value for a specified key in the registry\.&nbsp;

  - [RegQueryValueEx](win32api.md#win32apiregqueryvalueex)

    Retrieves the type and data for a specified value name associated with an open registry key\.&nbsp;

  - [RegQueryInfoKey](win32api.md#win32apiregqueryinfokey)

    Returns information about the specified key\.&nbsp;

  - [RegQueryInfoKeyW](win32api.md#win32apiregqueryinfokeyw)

    Returns information about an open registry key&nbsp;

  - [RegRestoreKey](win32api.md#win32apiregrestorekey)

    Restores a key and subkeys from a saved registry file&nbsp;

  - [RegSaveKey](win32api.md#win32apiregsavekey)

    Saves the specified key, and all its subkeys to the specified file\.&nbsp;

  - [RegSaveKeyEx](win32api.md#win32apiregsavekeyex)

    Extended version of RegSaveKey&nbsp;

  - [RegSetKeySecurity](win32api.md#win32apiregsetkeysecurity)

    Sets the security on the specified registry key\.&nbsp;

  - [RegSetValue](win32api.md#win32apiregsetvalue)

    Associates a value with a specified key\.  Currently, only strings are supported\.&nbsp;

  - [RegSetValueEx](win32api.md#win32apiregsetvalueex)

    Stores data in the value field of an open registry key\.&nbsp;

  - [RegUnLoadKey](win32api.md#win32apiregunloadkey)

    Unloads the specified registry key and its subkeys from the registry\.  The keys must have been loaded previously by a call to RegLoadKey\.&nbsp;

  - [RegisterWindowMessage](win32api.md#win32apiregisterwindowmessage)

    Given a string, return a system wide unique message ID\.&nbsp;

  - [RegNotifyChangeKeyValue](win32api.md#win32apiregnotifychangekeyvalue)

    Watch for registry changes&nbsp;

  - [SearchPath](win32api.md#win32apisearchpath)

    Searches a path for a file\.&nbsp;

  - [SendMessage](win32api.md#win32apisendmessage)

    Send a message to a window\.&nbsp;

  - [SetConsoleCtrlHandler](win32api.md#win32apisetconsolectrlhandler)

    Adds or removes an application-defined HandlerRoutine function from the list of handler functions for the calling process\.&nbsp;

  - [SetConsoleTitle](win32api.md#win32apisetconsoletitle)

    Sets the title for the current console\.&nbsp;

  - [SetCursorPos](win32api.md#win32apisetcursorpos)

    The SetCursorPos function moves the cursor to the specified screen coordinates\.&nbsp;

  - [SetDllDirectory](win32api.md#win32apisetdlldirectory)

    Modifies the application-specific DLL search path&nbsp;

  - [SetErrorMode](win32api.md#win32apiseterrormode)

    Controls whether the system will handle the specified types of serious errors, or whether the process will handle them\.&nbsp;

  - [SetFileAttributes](win32api.md#win32apisetfileattributes)

    Sets the named file's attributes\.&nbsp;

  - [SetLastError](win32api.md#win32apisetlasterror)

    Sets the last error code known for the current thread\.&nbsp;

  - [SetSysColors](win32api.md#win32apisetsyscolors)

    Changes color of various window elements&nbsp;

  - [SetLocalTime](win32api.md#win32apisetlocaltime)

    Changes the system's local time\.&nbsp;

  - [SetSystemTime](win32api.md#win32apisetsystemtime)

    Sets the system time\.&nbsp;

  - [SetClassLong](win32api.md#win32apisetclasslong)

    Replaces the specified 32-bit \(long\) value at the specified offset into the extra class memory for the window\.&nbsp;

  - [SetClassWord](win32api.md#win32apisetclassword)

    Replaces the specified 32-bit \(long\) value at the specified offset into the extra class memory for the window\.&nbsp;

  - [SetWindowWord](win32api.md#win32apisetwindowword)

    &nbsp;

  - [SetCursor](win32api.md#win32apisetcursor)

    Set the cursor to the HCURSOR object\.&nbsp;

  - [SetEnvironmentVariable](win32api.md#win32apisetenvironmentvariable)

    Creates, deletes, or changes the value of an environment variable\.&nbsp;

  - [SetEnvironmentVariable](win32api.md#win32apisetenvironmentvariable)

    Creates, deletes, or changes the value of an environment variable\.&nbsp;

  - [SetEnvironmentVariableW](win32api.md#win32apisetenvironmentvariablew)

    Creates, deletes, or changes the value of an environment variable\.&nbsp;

  - [SetHandleInformation](win32api.md#win32apisethandleinformation)

    Sets a handles's flags&nbsp;

  - [SetStdHandle](win32api.md#win32apisetstdhandle)

    Sets a handle for the standard input, standard output, or standard error device&nbsp;

  - [SetSystemPowerState](win32api.md#win32apisetsystempowerstate)

    Powers machine down to a suspended state&nbsp;

  - [SetThreadLocale](win32api.md#win32apisetthreadlocale)

    Sets the current thread's locale\.&nbsp;

  - [SetTimeZoneInformation](win32api.md#win32apisettimezoneinformation)

    Sets the system time-zone information\.&nbsp;

  - [SetWindowLong](win32api.md#win32apisetwindowlong)

    Places a long value at the specified offset into the extra window memory of the given window\.&nbsp;

  - [ShellExecute](win32api.md#win32apishellexecute)

    Executes an application\.&nbsp;

  - [ShowCursor](win32api.md#win32apishowcursor)

    The ShowCursor method displays or hides the cursor\.&nbsp;

  - [Sleep](win32api.md#win32apisleep)

    Suspends current application execution&nbsp;

  - [TerminateProcess](win32api.md#win32apiterminateprocess)

    Terminates a process\.&nbsp;

  - [ToAsciiEx](win32api.md#win32apitoasciiex)

    Translates the specified virtual-key code and keyboard state to the corresponding character or characters\.&nbsp;

  - [Unicode](win32api.md#win32apiunicode)

    Creates a new [PyUnicode](PyUnicode.md) object&nbsp;

  - [UpdateResource](win32api.md#win32apiupdateresource)

    Updates a resource in a PE file\.&nbsp;

  - [VkKeyScan](win32api.md#win32apivkkeyscan)

    Translates a character to the corresponding virtual-key code and shift state\.&nbsp;

  - [VkKeyScan](win32api.md#win32apivkkeyscan)

    Translates a character to the corresponding virtual-key code and shift state\.&nbsp;

  - [WinExec](win32api.md#win32apiwinexec)

    Execute a program\.&nbsp;

  - [WinHelp](win32api.md#win32apiwinhelp)

    Invokes the Windows Help engine\.&nbsp;

  - [WriteProfileSection](win32api.md#win32apiwriteprofilesection)

    Writes a complete section to an INI file or registry\.&nbsp;

  - [WriteProfileVal](win32api.md#win32apiwriteprofileval)

    Write a value to a Windows INI file\.&nbsp;

  - [HIBYTE](win32api.md#win32apihibyte)

    An interface to the win32api HIBYTE macro\.&nbsp;

  - [LOBYTE](win32api.md#win32apilobyte)

    An interface to the win32api LOBYTE macro\.&nbsp;

  - [HIWORD](win32api.md#win32apihiword)

    An interface to the win32api HIWORD macro\.&nbsp;

  - [LOWORD](win32api.md#win32apiloword)

    An interface to the win32api LOWORD macro\.&nbsp;

  - [RGB](win32api.md#win32apirgb)

    An interface to the win32api RGB macro\.&nbsp;

  - [MAKELANGID](win32api.md#win32apimakelangid)

    Creates a language identifier from a primary language identifier and a sublanguage identifier\.&nbsp;

  - [MAKEWORD](win32api.md#win32apimakeword)

    creates a WORD value by concatenating the specified values\.&nbsp;

  - [MAKELONG](win32api.md#win32apimakelong)

    creates a LONG value by concatenating the specified values\.&nbsp;


## [win32api](win32api.md#win32api)\.AbortSystemShutdown

AbortSystemShutdown\(computerName\)
Aborts a system shutdown

#### Parameters

  - computerName : string/[PyUnicode](PyUnicode.md)

    Specifies the name of the computer where the shutdown is to be stopped\.

#### Win32 API References

  - Search for AbortSystemShutdown at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=AbortSystemShutdown.md), [google](http://www.google.com/search?q=AbortSystemShutdown.md) or [google groups](http://groups.google.com/groups?q=AbortSystemShutdown.md)\.


## [win32api](win32api.md#win32api)\.Apply

object = Apply\(exceptionHandler, func

, args

\)
Calls a Python function, but traps Win32 exceptions\.

#### Parameters

  - exceptionHandler : object

    An object which will be called when a win32 exception occurs\.

  - func : object

    The function call call under the protection of the Win32 exception handler\.

  - args : tuple

    Args for the function\.

#### Comments

Calls the specified function in a manner similar to 

the built-in function apply\(\), but allows Win32 exceptions 

to be handled by Python\.  If a Win32 exception occurs calling 

the function, the specified exceptionHandler is called, and its 

return value determines the action taken\.




## [win32api](win32api.md#win32api)\.Beep

Beep\(freq, dur\)
Generates simple tones on the speaker\.

#### Parameters

  - freq : int

    Specifies the frequency, in hertz, of the sound\. This parameter must be in the range 37 through 32,767 \(0x25 through 0x7FFF\)\.

  - dur : int

    Specifies the duration, in milliseconds, of the sound\.~ 

One value has a special meaning: If dwDuration is  - 1, the function 

operates asynchronously and produces sound until called again\.

#### Win32 API References

  - Search for Beep at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=Beep.md), [google](http://www.google.com/search?q=Beep.md) or [google groups](http://groups.google.com/groups?q=Beep.md)\.


## [win32api](win32api.md#win32api)\.BeginUpdateResource

[PyHANDLE](PyHANDLE.md) = BeginUpdateResource\(filename, delete

\)
Begins an update cycle for a PE file\.

#### Parameters

  - filename : string

    File in which to update resources\.

  - delete : int

    Flag to indicate that all existing resources should be deleted\.


## [win32api](win32api.md#win32api)\.ChangeDisplaySettings

int = ChangeDisplaySettings\(DevMode, Flags

\)
Changes video mode for default display

#### Parameters

  - DevMode : [PyDEVMODE](PyDEVMODE.md)

    A PyDEVMODE object as returned from EnumDisplaySettings, or None to reset to default settings from registry

  - Flags : int

    One of the win32con\.CDS\_\* constants, or 0

#### Return Value
Returns DISP\_CHANGE\_SUCCESSFUL on success, or one of the DISP\_CHANGE\_\* error constants on failure


## [win32api](win32api.md#win32api)\.ChangeDisplaySettingsEx

int = ChangeDisplaySettingsEx\(DeviceName, DevMode

, Flags

\)
Changes video mode for specified display

#### Parameters

  - DeviceName=None : str

    Name of device as returned by [win32api::EnumDisplayDevices](win32api.md#win32apienumdisplaydevices), use None for default display device

  - DevMode=None : [PyDEVMODE](PyDEVMODE.md)

    A PyDEVMODE object as returned from [win32api::EnumDisplaySettings](win32api.md#win32apienumdisplaysettings), or None to reset to default settings from registry

  - Flags=0 : int

    One of the win32con\.CDS\_\* constants, or 0

#### Comments

Accepts keyword arguments

#### Return Value
Returns DISP\_CHANGE\_SUCCESSFUL on success, or one of the DISP\_CHANGE\_\* error constants on failure


## [win32api](win32api.md#win32api)\.ClipCursor

ClipCursor\(left, top, right, bottom\)
Confines the cursor to a rectangular area on the screen\.

#### Parameters

  - left, top, right, bottom : \(int, int, int, int\)

    contains the screen coordinates of the upper-left and lower-right corners of the confining rectangle\. If this parameter is omitted or \(0,0,0,0\), the cursor is free to move anywhere on the screen\.

#### Win32 API References

  - Search for ClipCursor at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=ClipCursor.md), [google](http://www.google.com/search?q=ClipCursor.md) or [google groups](http://groups.google.com/groups?q=ClipCursor.md)\.


## [win32api](win32api.md#win32api)\.CloseHandle

CloseHandle\(handle\)
Closes an open handle\.

#### Parameters

  - handle : [PyHANDLE](PyHANDLE.md)/int

    A previously opened handle\.


## [win32api](win32api.md#win32api)\.CopyFile

CopyFile\(src, dest, bFailOnExist\)
Copies an existing file to a new file

#### Parameters

  - src : string[PyUnicode](PyUnicode.md)

    Name of an existing file\.

  - dest : string/[PyUnicode](PyUnicode.md)

    Name of file to copy to\.

  - bFailOnExist=0 : int

    Indicates if the operation should fail if the file exists\.

#### Win32 API References

  - Search for CopyFile at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=CopyFile.md), [google](http://www.google.com/search?q=CopyFile.md) or [google groups](http://groups.google.com/groups?q=CopyFile.md)\.


## [win32api](win32api.md#win32api)\.DebugBreak

DebugBreak\(\)
Breaks into the C debugger

#### Win32 API References

  - Search for DebugBreak at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=DebugBreak.md), [google](http://www.google.com/search?q=DebugBreak.md) or [google groups](http://groups.google.com/groups?q=DebugBreak.md)\.


## [win32api](win32api.md#win32api)\.DeleteFile

DeleteFile\(fileName\)
Deletes the specified file\.

#### Parameters

  - fileName : string/[PyUnicode](PyUnicode.md)

    File to delete\.

#### Win32 API References

  - Search for DeleteFile at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=DeleteFile.md), [google](http://www.google.com/search?q=DeleteFile.md) or [google groups](http://groups.google.com/groups?q=DeleteFile.md)\.


## [win32api](win32api.md#win32api)\.DragFinish

DragFinish\(hDrop\)
Releases the memory stored by Windows for the filenames\.

#### Parameters

  - hDrop : int

    Handle identifying the structure containing the file names\.

#### Win32 API References

  - Search for DragFinish at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=DragFinish.md), [google](http://www.google.com/search?q=DragFinish.md) or [google groups](http://groups.google.com/groups?q=DragFinish.md)\.


## [win32api](win32api.md#win32api)\.DragQueryFile

string/int = DragQueryFile\(hDrop, fileNum

\)
Retrieves the file names of dropped files\.

#### Parameters

  - hDrop : int

    Handle identifying the structure containing the file names\.

  - fileNum=0xFFFFFFFF : int

    Specifies the index of the file to query\.

#### Win32 API References

  - Search for DragQueryFile at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=DragQueryFile.md), [google](http://www.google.com/search?q=DragQueryFile.md) or [google groups](http://groups.google.com/groups?q=DragQueryFile.md)\.

#### Return Value
If the fileNum parameter is 0xFFFFFFFF \(the default\) then the return value 

is an integer with the count of files dropped\.  If fileNum is between 0 and Count, 

the return value is a string containing the filename\.
 

If an error occurs, and exception is raised\.


## [win32api](win32api.md#win32api)\.DuplicateHandle

[PyHANDLE](PyHANDLE.md) = DuplicateHandle\(hSourceProcess, hSource

, hTargetProcessHandle

, desiredAccess

, bInheritHandle

, options

\)
Duplicates a handle\.

#### Parameters

  - hSourceProcess : [PyHANDLE](PyHANDLE.md)

    Identifies the process containing the handle to duplicate\.

  - hSource : [PyHANDLE](PyHANDLE.md)

    Identifies the handle to duplicate\. This is an open object handle that is valid in the context of the source process\.

  - hTargetProcessHandle : [PyHANDLE](PyHANDLE.md)

    Identifies the process that is to receive the duplicated handle\. The handle must have PROCESS\_DUP\_HANDLE access\.

  - desiredAccess : int

    Specifies the access requested for the new handle\. This parameter is ignored if the dwOptions parameter specifies the DUPLICATE\_SAME\_ACCESS flag\. Otherwise, the flags that can be specified depend on the type of object whose handle is being duplicated\. For the flags that can be specified for each object type, see the following Remarks section\. Note that the new handle can have more access than the original handle\.

  - bInheritHandle : int

    Indicates whether the handle is inheritable\. If TRUE, the duplicate handle can be inherited by new processes created by the target process\. If FALSE, the new handle cannot be inherited\.

  - options : int

    Specifies optional actions\. This parameter can be zero, or any combination of the following flags
DUPLICATE\_CLOSE\_SOURCEloses the source handle\. This occurs regardless of any error status returned\.

DUPLICATE\_SAME\_ACCESSIgnores the dwDesiredAccess parameter\. The duplicate handle has the same access as the source handle\.

#### Comments

When duplicating a handle for a different process, you should either keep a 

reference to the returned PyHANDLE, or call \.Detach\(\) on it to prevent it 

from being closed prematurely\.


## [win32api](win32api.md#win32api)\.EndUpdateResource

EndUpdateResource\(handle, discard\)
Ends a resource update cycle of a PE file\.

#### Parameters

  - handle : [PyHANDLE](PyHANDLE.md)

    The update-file handle\.

  - discard : int

    Flag to discard all writes\.


## [win32api](win32api.md#win32api)\.EnumDisplayDevices

[PyDISPLAY\_DEVICE](PyDISPLAY.md#pydisplaydevice) = EnumDisplayDevices\(Device, DevNum

, Flags

\)
Obtain information about the display devices in a system

#### Parameters

  - Device=None : string

    Name of device, use None to obtain information for the display adapter\(s\) on the machine, based on DevNum

  - DevNum=0 : int

    Index of device of interest, starting with zero

  - Flags=0 : int

    Reserved, use 0 if passed in

#### Comments

Accepts keyword arguments


## [win32api](win32api.md#win32api)\.EnumDisplayMonitors

list = EnumDisplayMonitors\(hdc, rcClip

\)
Lists display monitors for a given device context and area

#### Parameters

  - hdc=None : [PyHANDLE](PyHANDLE.md)

    Handle to device context, use None for virtual desktop

  - rcClip=None : [PyRECT](PyRECT.md)

    Clipping rectangle, can be None

#### Comments

Accepts keyword arguments

#### Return Value
Returns a sequence of tuples\.  For each monitor found, returns a handle to the monitor, 

device context handle, and intersection rectangle: \(hMonitor, hdcMonitor, [PyRECT](PyRECT.md)\)


## [win32api](win32api.md#win32api)\.EnumDisplaySettings

[PyDEVMODE](PyDEVMODE.md) = EnumDisplaySettings\(DeviceName, ModeNum

\)
List available modes for specified display device

#### Parameters

  - DeviceName=None : string

    Name of device as returned by [win32api::EnumDisplayDevices](win32api.md#win32apienumdisplaydevices), use None for default display device

  - ModeNum=0 : int

    Index of setting to return, or one of ENUM\_CURRENT\_SETTINGS, ENUM\_REGISTRY\_SETTINGS

#### Comments

Accepts keyword arguments


## [win32api](win32api.md#win32api)\.EnumDisplaySettingsEx

[PyDEVMODE](PyDEVMODE.md) = EnumDisplaySettingsEx\(DeviceName, ModeNum

, Flags

\)
Lists available modes for a display device, with optional flags

#### Parameters

  - DeviceName=None : string

    Name of device as returned by [win32api::EnumDisplayDevices](win32api.md#win32apienumdisplaydevices)\. Can be None for default display

  - ModeNum : int

    Index of setting to return, or one of ENUM\_CURRENT\_SETTINGS, ENUM\_REGISTRY\_SETTINGS

  - Flags=0 : int

    EDS\_RAWMODE \(2\) is only defined flag

#### Comments

Accepts keyword arguments


## [win32api](win32api.md#win32api)\.EnumResourceLanguages

\[int,\.\.\.\] = EnumResourceLanguages\(hmodule, lpType

, lpName

\)
List languages for a resource

#### Parameters

  - hmodule : [PyHANDLE](PyHANDLE.md)

    Handle to the module that contains resource

  - lpType : [PyResourceId](PyResourceId.md)

    Resource type, can be string or integer

  - lpName : [PyResourceId](PyResourceId.md)

    Resource name, can be string or integer


## [win32api](win32api.md#win32api)\.EnumResourceNames

\[string, \.\.\.\] = EnumResourceNames\(hmodule, resType

\)
Enumerates all the resources of the specified type from the nominated file\.

#### Parameters

  - hmodule : [PyHANDLE](PyHANDLE.md)

    The handle to the module to enumerate\.

  - resType : [PyResourceId](PyResourceId.md)

    The type of resource to enumerate\. \(win32con\.RT\_\*\)\. 

If passed as a string, form is '\#' sign followed by decimal number\. eg RT\_ANICURSOR would be '\#21'

#### Return Value
The result is a list of string or integers, one for each resource enumerated\.


## [win32api](win32api.md#win32api)\.EnumResourceTypes

\[[PyUnicode](PyUnicode.md),\.\.\.\] = EnumResourceTypes\(hmodule\)
Return name or integer id of all resource types contained in module

#### Parameters

  - hmodule : [PyHANDLE](PyHANDLE.md)

    The handle to the module to enumerate\.


## [win32api](win32api.md#win32api)\.ExitWindows

ExitWindows\(reserved1, reserved2\)
Logs off the current user

#### Parameters

  - reserved1=0 : int

    

  - reserved2=0 : int

    

#### Win32 API References

  - Search for AbortSystemShutdown at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=AbortSystemShutdown.md), [google](http://www.google.com/search?q=AbortSystemShutdown.md) or [google groups](http://groups.google.com/groups?q=AbortSystemShutdown.md)\.


## [win32api](win32api.md#win32api)\.ExitWindowsEx

ExitWindowsEx\(flags, reserved\)
either logs off the current user, shuts down the system, or shuts down and restarts the system\.

#### Parameters

  - flags : int

    The shutdown operation

  - reserved=0 : int

    

#### Comments

It sends the WM\_QUERYENDSESSION message to all applications to determine if they can be terminated\.

#### Win32 API References

  - Search for AbortSystemShutdown at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=AbortSystemShutdown.md), [google](http://www.google.com/search?q=AbortSystemShutdown.md) or [google groups](http://groups.google.com/groups?q=AbortSystemShutdown.md)\.


## [win32api](win32api.md#win32api)\.ExpandEnvironmentStrings

string = ExpandEnvironmentStrings\(in\)
Expands environment-variable strings and replaces them with their defined values\.

#### Parameters

  - in : string

    String to expand

#### Win32 API References

  - Search for ExpandEnvironmentStrings at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=ExpandEnvironmentStrings.md), [google](http://www.google.com/search?q=ExpandEnvironmentStrings.md) or [google groups](http://groups.google.com/groups?q=ExpandEnvironmentStrings.md)\.


## [win32api](win32api.md#win32api)\.FindCloseChangeNotification

FindCloseChangeNotification\(handle\)
Closes the change notification handle\.

#### Parameters

  - handle : int

    The handle returned from [win32api::FindFirstChangeNotification](win32api.md#win32apifindfirstchangenotification)


## [win32api](win32api.md#win32api)\.FindExecutable

\(int, string\) = FindExecutable\(filename, dir

\)
Retrieves the name and handle of the executable \(\.EXE\) file associated with the specified filename\.

#### Parameters

  - filename : string

    A file name\.  This can be either a document or executable file\.

  - dir : string

    The default directory\.

#### Comments

The function will raise an exception if it fails\.

#### Win32 API References

  - Search for FindExecutable at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=FindExecutable.md), [google](http://www.google.com/search?q=FindExecutable.md) or [google groups](http://groups.google.com/groups?q=FindExecutable.md)\.

#### Return Value
The return value is a tuple of \(integer, string\)
 

The integer is the instance handle of the executable file associated 

with the specified filename\. \(This handle could also be the handle of 

a dynamic data exchange \[DDE\] server application\.\)
 

The may contain the path to the DDE server started if no server responds to a request to initiate a DDE conversation\.


## [win32api](win32api.md#win32api)\.FindFiles

list = FindFiles\(fileSpec\)
Retrieves a list of matching filenames\.  An interface to the API FindFirstFile/FindNextFile/Find close functions\.

#### Parameters

  - fileSpec : string

    A string that specifies a valid directory or path and filename, which can contain wildcard characters \(\* and ?\)\.

#### Win32 API References

  - Search for FindFirstFile at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=FindFirstFile.md), [google](http://www.google.com/search?q=FindFirstFile.md) or [google groups](http://groups.google.com/groups?q=FindFirstFile.md)\.

  - Search for FindNextFile at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=FindNextFile.md), [google](http://www.google.com/search?q=FindNextFile.md) or [google groups](http://groups.google.com/groups?q=FindNextFile.md)\.

  - Search for FindClose at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=FindClose.md), [google](http://www.google.com/search?q=FindClose.md) or [google groups](http://groups.google.com/groups?q=FindClose.md)\.

#### Return Value
Returns a sequence of [WIN32\_FIND\_DATA](WIN32.md#win32find_data) tuples


## [win32api](win32api.md#win32api)\.FindFirstChangeNotification

int = FindFirstChangeNotification\(pathName, bSubDirs

, filter

\)
Creates a change notification handle and sets up initial change notification filter conditions\.

#### Parameters

  - pathName : string

    Specifies the path of the directory to watch\.

  - bSubDirs : int

    Specifies whether the function will monitor the directory or the directory tree\. If this parameter is TRUE, the function monitors the directory tree rooted at the specified directory; if it is FALSE, it monitors only the specified directory

  - filter : int

    Specifies the filter conditions that satisfy a change notification wait\. This parameter can be one or more of the following values:

   

       Value

   

   

       Meaning

   

FILE\_NOTIFY\_CHANGE\_FILE\_NAMEAny file name change in the watched directory or subtree causes a change notification wait operation to return\. Changes include renaming, creating, or deleting a file name\.

FILE\_NOTIFY\_CHANGE\_DIR\_NAMEAny directory-name change in the watched directory or subtree causes a change notification wait operation to return\. Changes include creating or deleting a directory\.

FILE\_NOTIFY\_CHANGE\_ATTRIBUTESAny attribute change in the watched directory or subtree causes a change notification wait operation to return\.

FILE\_NOTIFY\_CHANGE\_SIZEAny file-size change in the watched directory or subtree causes a change notification wait operation to return\. The operating system detects a change in file size only when the file is written to the disk\. For operating systems that use extensive caching, detection occurs only when the cache is sufficiently flushed\.

FILE\_NOTIFY\_CHANGE\_LAST\_WRITEAny change to the last write-time of files in the watched directory or subtree causes a change notification wait operation to return\. The operating system detects a change to the last write-time only when the file is written to the disk\. For operating systems that use extensive caching, detection occurs only when the cache is sufficiently flushed\.

FILE\_NOTIFY\_CHANGE\_SECURITYAny security-descriptor change in the watched directory or subtree causes a change notification wait operation to return

#### Return Value
Although the result is a handle, the handle can not be closed via CloseHandle\(\) - therefore a PyHandle object is not used\.


## [win32api](win32api.md#win32api)\.FindNextChangeNotification

FindNextChangeNotification\(handle\)
Requests that the operating system signal a change notification handle the next time it detects an appropriate change\.

#### Parameters

  - handle : [PyHANDLE](PyHANDLE.md)

    The handle returned from [win32api::FindFirstChangeNotification](win32api.md#win32apifindfirstchangenotification)


## [win32api](win32api.md#win32api)\.FormatMessage

string = FormatMessage\(errCode\)
Returns an error message from the system error file\.

#### Parameters

  - errCode=0 : int

    The error code to return the message for,  If this value is 0, then GetLastError\(\) is called to determine the error code\.

#### Alternative Parameters

  - flags

    Flags for the call\.  Note that FORMAT\_MESSAGE\_ALLOCATE\_BUFFER and FORMAT\_MESSAGE\_ARGUMENT\_ARRAY will always be added\.

  - source

    The source object\.  If flags contain FORMAT\_MESSAGE\_FROM\_HMODULE it should be an int; 

if flags contain FORMAT\_MESSAGE\_FROM\_STRING it should be a string containing the error msg; 

otherwise it is ignored\.

  - messageId

    The message ID\.

  - languageID

    The language ID\.

  - inserts

    The string inserts to insert\.

#### Win32 API References

  - Search for GetLastError at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetLastError.md), [google](http://www.google.com/search?q=GetLastError.md) or [google groups](http://groups.google.com/groups?q=GetLastError.md)\.

  - Search for FormatMessage at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=FormatMessage.md), [google](http://www.google.com/search?q=FormatMessage.md) or [google groups](http://groups.google.com/groups?q=FormatMessage.md)\.


## [win32api](win32api.md#win32api)\.FormatMessageW

[PyUnicode](PyUnicode.md) = FormatMessageW\(errCode\)
Returns an error message from the system error file\.

#### Parameters

  - errCode=0 : int

    The error code to return the message for,  If this value is 0, 

then GetLastError\(\) is called to determine the error code\.

#### Alternative Parameters

  - flags

    Flags for the call\.  Note that FORMAT\_MESSAGE\_ALLOCATE\_BUFFER and FORMAT\_MESSAGE\_ARGUMENT\_ARRAY will always be added\.

  - source

    The source object\.  If flags contain FORMAT\_MESSAGE\_FROM\_HMODULE it should be an int or [PyHANDLE](PyHANDLE.md); 

if flags contain FORMAT\_MESSAGE\_FROM\_STRING it should be a unicode string; 

otherwise it is ignored\.

  - messageId

    The message ID\.

  - languageID

    The language ID\.

  - inserts

    The string inserts to insert\.

#### Win32 API References

  - Search for GetLastError at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetLastError.md), [google](http://www.google.com/search?q=GetLastError.md) or [google groups](http://groups.google.com/groups?q=GetLastError.md)\.

  - Search for FormatMessage at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=FormatMessage.md), [google](http://www.google.com/search?q=FormatMessage.md) or [google groups](http://groups.google.com/groups?q=FormatMessage.md)\.


## [win32api](win32api.md#win32api)\.FreeLibrary

FreeLibrary\(hModule\)
Decrements the reference count of the loaded dynamic-link library \(DLL\) module\.

#### Parameters

  - hModule : [PyHANDLE](PyHANDLE.md)

    Specifies the handle to the module\.

#### Win32 API References

  - Search for FreeLibrary at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=FreeLibrary.md), [google](http://www.google.com/search?q=FreeLibrary.md) or [google groups](http://groups.google.com/groups?q=FreeLibrary.md)\.


## [win32api](win32api.md#win32api)\.GenerateConsoleCtrlEvent

int = GenerateConsoleCtrlEvent\(controlEvent, processGroupId

\)
Send a specified signal to a console process group that shares the console associated with the calling process\.

#### Parameters

  - controlEvent : int

    Signal to generate\.

  - processGroupId : int

    Process group to get signal\.

#### Win32 API References

  - Search for GenerateConsoleCtrlEvent at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GenerateConsoleCtrlEvent.md), [google](http://www.google.com/search?q=GenerateConsoleCtrlEvent.md) or [google groups](http://groups.google.com/groups?q=GenerateConsoleCtrlEvent.md)\.


## [win32api](win32api.md#win32api)\.GetAsyncKeyState

int = GetAsyncKeyState\(key\)
Retrieves the status of the specified key\.

#### Parameters

  - key : int

    Specifies one of 256 possible virtual-key codes\.

#### Comments

An application can use the virtual-key code constants win32con\.VK\_SHIFT, 

win32con\.VK\_CONTROL, and win32con\.VK\_MENU as values for the key parameter\. 

This gives the state of the SHIFT, CTRL, or ALT keys without distinguishing 

between left and right\. An application can also use the following virtual-key 

code constants as values for key to distinguish between the left and 

right instances of those keys: 

win32con\.VK\_LSHIFT 

win32con\.VK\_RSHIFT 

win32con\.VK\_LCONTROL 

win32con\.VK\_RCONTROL 

win32con\.VK\_LMENU 

win32con\.VK\_RMENU 

The GetAsyncKeyState method works with mouse buttons\. However, it checks on 

the state of the physical mouse buttons, not on the logical mouse buttons that 

the physical buttons are mapped to\.

#### Win32 API References

  - Search for GetAsyncKeyState at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetAsyncKeyState.md), [google](http://www.google.com/search?q=GetAsyncKeyState.md) or [google groups](http://groups.google.com/groups?q=GetAsyncKeyState.md)\.

#### Return Value
The return value specifies whether the key was pressed since the last 

call to GetAsyncKeyState, and whether the key is currently up or down\. If 

the most significant bit is set, the key is down, and if the least significant 

bit is set, the key was pressed after the previous call to GetAsyncKeyState\. 

The return value is zero if a window in another thread or process currently has the 

keyboard focus\.


## [win32api](win32api.md#win32api)\.GetCommandLine

string = GetCommandLine\(\)
Retrieves the current application's command line\.

#### Win32 API References

  - Search for GetCommandLine at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetCommandLine.md), [google](http://www.google.com/search?q=GetCommandLine.md) or [google groups](http://groups.google.com/groups?q=GetCommandLine.md)\.


## [win32api](win32api.md#win32api)\.GetComputerName

string = GetComputerName\(\)
Returns the local computer name

#### Win32 API References

  - Search for GetComputerName at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetComputerName.md), [google](http://www.google.com/search?q=GetComputerName.md) or [google groups](http://groups.google.com/groups?q=GetComputerName.md)\.


## [win32api](win32api.md#win32api)\.GetComputerNameEx

string = GetComputerNameEx\(NameType\)
Retrieves a NetBIOS or DNS name associated with the local computer

#### Parameters

  - NameType : int

    Value from COMPUTER\_NAME\_FORMAT enum, win32con\.ComputerName\*

#### Win32 API References

  - Search for GetComputerNameEx at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetComputerNameEx.md), [google](http://www.google.com/search?q=GetComputerNameEx.md) or [google groups](http://groups.google.com/groups?q=GetComputerNameEx.md)\.


## [win32api](win32api.md#win32api)\.GetComputerObjectName

string = GetComputerObjectName\(NameFormat\)
Retrieves the local computer's name in a specified format\.

#### Parameters

  - NameFormat : int

    EXTENDED\_NAME\_FORMAT value, win32con\.Name\*

#### Win32 API References

  - Search for GetComputerObjectName at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetComputerObjectName.md), [google](http://www.google.com/search?q=GetComputerObjectName.md) or [google groups](http://groups.google.com/groups?q=GetComputerObjectName.md)\.


## [win32api](win32api.md#win32api)\.GetConsoleTitle

string = GetConsoleTitle\(\)
Returns the title for the current console\.


## [win32api](win32api.md#win32api)\.GetCurrentProcess

int = GetCurrentProcess\(\)
Returns a pseudohandle for the current process\.

#### Comments

A pseudohandle is a special constant that is interpreted as the current thread handle\. The calling thread can use this handle to specify itself whenever a thread handle is required\. Pseudohandles are not inherited by child processes\. 

The method [win32api::DuplicateHandle](win32api.md#win32apiduplicatehandle) can be used to create a handle that other threads and processes can use\. 

As this handle can not be closed, and integer is returned rather than 

a [PyHANDLE](PyHANDLE.md) object, which would attempt to automatically close the handle\.

#### Win32 API References

  - Search for GetCurrentProcess at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetCurrentProcess.md), [google](http://www.google.com/search?q=GetCurrentProcess.md) or [google groups](http://groups.google.com/groups?q=GetCurrentProcess.md)\.


## [win32api](win32api.md#win32api)\.GetCurrentProcessId

int = GetCurrentProcessId\(\)
Returns the thread ID for the current process\.

#### Win32 API References

  - Search for GetCurrentProcessId at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetCurrentProcessId.md), [google](http://www.google.com/search?q=GetCurrentProcessId.md) or [google groups](http://groups.google.com/groups?q=GetCurrentProcessId.md)\.


## [win32api](win32api.md#win32api)\.GetCurrentThread

int = GetCurrentThread\(\)
Returns a pseudohandle for the current thread\.

#### Comments

A pseudohandle is a special constant that is interpreted as the current thread handle\. The calling thread can use this handle to specify itself whenever a thread handle is required\. Pseudohandles are not inherited by child processes\. 

The method [win32api::DuplicateHandle](win32api.md#win32apiduplicatehandle) can be used to create a handle that other threads and processes can use\. 

As this handle can not be closed, and integer is returned rather than 

a [PyHANDLE](PyHANDLE.md) object, which would attempt to automatically close the handle\.

#### Win32 API References

  - Search for GetCurrentThread at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetCurrentThread.md), [google](http://www.google.com/search?q=GetCurrentThread.md) or [google groups](http://groups.google.com/groups?q=GetCurrentThread.md)\.


## [win32api](win32api.md#win32api)\.GetCurrentThreadId

int = GetCurrentThreadId\(\)
Returns the thread ID for the current thread\.

#### Win32 API References

  - Search for GetCurrentThreadId at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetCurrentThreadId.md), [google](http://www.google.com/search?q=GetCurrentThreadId.md) or [google groups](http://groups.google.com/groups?q=GetCurrentThreadId.md)\.


## [win32api](win32api.md#win32api)\.GetCursorPos

int, int = GetCursorPos\(\)
Returns the position of the cursor, in screen co-ordinates\.

#### Win32 API References

  - Search for GetCursorPos at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetCursorPos.md), [google](http://www.google.com/search?q=GetCursorPos.md) or [google groups](http://groups.google.com/groups?q=GetCursorPos.md)\.


## [win32api](win32api.md#win32api)\.GetDateFormat

string = GetDateFormat\(locale, flags

, time

, format

\)
Formats a date as a date string for a specified locale\. The function formats either a specified date or the local system date\.

#### Parameters

  - locale : int

    

  - flags : int

    

  - time : [PyTime](PyTime.md)

    The time to use, or None to use the current time\.

  - format : string

    May be None


## [win32api](win32api.md#win32api)\.GetDiskFreeSpace

tuple = GetDiskFreeSpace\(rootPath\)
Retrieves information about the specified disk, including the amount of free space available\.

#### Parameters

  - rootPath : string

    Specifies the root directory of the disk to return information about\. If rootPath is None, the method uses the root of the current directory\.

#### Win32 API References

  - Search for GetDiskFreeSpace at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetDiskFreeSpace.md), [google](http://www.google.com/search?q=GetDiskFreeSpace.md) or [google groups](http://groups.google.com/groups?q=GetDiskFreeSpace.md)\.

#### Return Value
The return value is a tuple of 4 integers, containing 

the number of sectors per cluster, the number of bytes per sector, 

the total number of free clusters on the disk and the total number of clusters on the disk\. 

If the function fails, an error is returned\.


## [win32api](win32api.md#win32api)\.GetDiskFreeSpaceEx

tuple = GetDiskFreeSpaceEx\(rootPath\)
Retrieves information about the specified disk, including the amount of free space available\.

#### Parameters

  - rootPath : string

    Specifies the root directory of the disk to return information about\. If rootPath is None, the method uses the root of the current directory\.

#### Win32 API References

  - Search for GetDiskFreeSpaceEx at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetDiskFreeSpaceEx.md), [google](http://www.google.com/search?q=GetDiskFreeSpaceEx.md) or [google groups](http://groups.google.com/groups?q=GetDiskFreeSpaceEx.md)\.

#### Return Value
The return value is a tuple of 3 integers, containing 

the number of free bytes available 

the total number of bytes available on disk 

the total number of free bytes on disk 

the above values may be less, if user-quotas are in effect 

If the function fails, an error is returned\.


## [win32api](win32api.md#win32api)\.GetDllDirectory

[PyUnicode](PyUnicode.md) = GetDllDirectory\(\)
Returns the DLL search path

#### Win32 API References

  - Search for GetDllDirectory at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetDllDirectory.md), [google](http://www.google.com/search?q=GetDllDirectory.md) or [google groups](http://groups.google.com/groups?q=GetDllDirectory.md)\.


## [win32api](win32api.md#win32api)\.GetDomainName

string = GetDomainName\(\)
Returns the current domain name

#### Comments

This is a convenience wrapper of the Win32 function LookupAccountSid\(\)


## [win32api](win32api.md#win32api)\.GetEnvironmentVariable

str = GetEnvironmentVariable\(variable\)
Retrieves the value of an environment variable\.

#### Parameters

  - variable : str

    The variable to get

#### Win32 API References

  - Search for GetEnvironmentVariable at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetEnvironmentVariable.md), [google](http://www.google.com/search?q=GetEnvironmentVariable.md) or [google groups](http://groups.google.com/groups?q=GetEnvironmentVariable.md)\.

#### Return Value
Returns None if environment variable is not found


## [win32api](win32api.md#win32api)\.GetEnvironmentVariableW

[PyUnicode](PyUnicode.md) = GetEnvironmentVariableW\(Name\)
Retrieves the unicode value of an environment variable\.

#### Parameters

  - Name : str

    The variable to retrieve

#### Win32 API References

  - Search for GetEnvironmentVariableW at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetEnvironmentVariableW.md), [google](http://www.google.com/search?q=GetEnvironmentVariableW.md) or [google groups](http://groups.google.com/groups?q=GetEnvironmentVariableW.md)\.

#### Return Value
Returns None if environment variable is not found


## [win32api](win32api.md#win32api)\.GetFileAttributes

int = GetFileAttributes\(pathName\)
Retrieves the attributes for the named file\.

#### Parameters

  - pathName : string

    The name of the file whose attributes are to be returned\. 

If this param is a unicode object, GetFileAttributesW is called\.

#### Win32 API References

  - Search for GetFileAttributes at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetFileAttributes.md), [google](http://www.google.com/search?q=GetFileAttributes.md) or [google groups](http://groups.google.com/groups?q=GetFileAttributes.md)\.

  - Search for GetFileAttributesW at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetFileAttributesW.md), [google](http://www.google.com/search?q=GetFileAttributesW.md) or [google groups](http://groups.google.com/groups?q=GetFileAttributesW.md)\.

#### Return Value
The return value is a combination of the win32con\.FILE\_ATTRIBUTE\_\* constants\. 

An exception is raised on failure\.


## [win32api](win32api.md#win32api)\.GetFileVersionInfo

GetFileVersionInfo\(Filename, SubBlock\)
Retrieve version info for specified file

#### Parameters

  - Filename : string/unicode

    File to query for version info

  - SubBlock : string/unicode

    Information to return: \\\\ for VS\_FIXEDFILEINFO, \\\\VarFileInfo\\\\Translation for languages/codepages available


## [win32api](win32api.md#win32api)\.GetFocus

int = GetFocus\(\)
Retrieves the handle of the keyboard focus window associated with the thread that called the method\.

#### Win32 API References

  - Search for GetFocus at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetFocus.md), [google](http://www.google.com/search?q=GetFocus.md) or [google groups](http://groups.google.com/groups?q=GetFocus.md)\.

#### Return Value
The method raises an exception if no window with the focus exists\.


## [win32api](win32api.md#win32api)\.GetFullPathName

string = GetFullPathName\(fileName\)
Returns the full path of a \(possibly relative\) path

#### Parameters

  - fileName : string

    The file name\.

#### Comments

Please use [win32file::GetFullPathName](win32file.md#win32filegetfullpathname) instead - it has better Unicode semantics\.


## [win32api](win32api.md#win32api)\.GetHandleInformation

int = GetHandleInformation\(Object\)
Retrieves a handle's flags\.

#### Parameters

  - Object : [PyHANDLE](PyHANDLE.md)

    Handle to an object

#### Comments

Not available on Win98/Me

#### Return Value
Returns a combination of HANDLE\_FLAG\_INHERIT, HANDLE\_FLAG\_PROTECT\_FROM\_CLOSE


## [win32api](win32api.md#win32api)\.GetKeyState

int = GetKeyState\(key\)
Retrieves the status of the specified key\.

#### Parameters

  - key : int

    Specifies a virtual key\. If the desired virtual key is a letter or digit \(A through Z, a through z, or 0 through 9\), key must be set to the ASCII value of that character\. For other keys, it must be a virtual-key code\.

#### Comments

The key status returned from this function changes as a given thread 

reads key messages from its message queue\. The status does not reflect the 

interrupt-level state associated with the hardware\. Use the [win32api::GetAsyncKeyState](win32api.md#win32apigetasynckeystate) method to retrieve that information\.

#### Win32 API References

  - Search for GetKeyState at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetKeyState.md), [google](http://www.google.com/search?q=GetKeyState.md) or [google groups](http://groups.google.com/groups?q=GetKeyState.md)\.

#### Return Value
The return value specifies the status of 

the given virtual key\. If the high-order bit is 1, the key is down; 

otherwise, it is up\. If the low-order bit is 1, the key is toggled\. 

A key, such as the CAPS LOCK key, is toggled if it is turned on\. 

The key is off and untoggled if the low-order bit is 0\. A toggle key's 

indicator light \(if any\) on the keyboard will be on when the key is 

toggled, and off when the key is untoggled\.


## [win32api](win32api.md#win32api)\.GetKeyboardLayout

int = GetKeyboardLayout\(threadId\)
retrieves the active input locale identifier \(formerly called the keyboard layout\) for the specified thread\.

#### Parameters

  - threadId=0 : int

    

#### Comments

If the idThread parameter is zero, the input locale identifier for the active thread is returned\.


## [win32api](win32api.md#win32api)\.GetKeyboardLayoutList

\(int,\.\.\) = GetKeyboardLayoutList\(\)
Returns a sequence of all locale ids currently loaded


## [win32api](win32api.md#win32api)\.GetKeyboardLayoutName

int = GetKeyboardLayoutName\(\)
Retrieves the name of the active input locale identifier \(formerly called the keyboard layout\)\.


## [win32api](win32api.md#win32api)\.GetKeyboardState

string = GetKeyboardState\(\)
Retrieves the status of the 256 virtual keys on the keyboard\.

#### Win32 API References

  - Search for GetKeyboardState at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetKeyboardState.md), [google](http://www.google.com/search?q=GetKeyboardState.md) or [google groups](http://groups.google.com/groups?q=GetKeyboardState.md)\.

#### Return Value
The return value is a string of exactly 256 characters\. 

Each character represents the bitmask for a key - see the Win32 

documentation for more details\.


## [win32api](win32api.md#win32api)\.GetLastError

int = GetLastError\(\)
Retrieves the calling thread's last error code value\.

#### Win32 API References

  - Search for GetLastError at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetLastError.md), [google](http://www.google.com/search?q=GetLastError.md) or [google groups](http://groups.google.com/groups?q=GetLastError.md)\.


## [win32api](win32api.md#win32api)\.GetLastInputInfo

int = GetLastInputInfo\(\)
Returns time of last input event in tick count

#### Win32 API References

  - Search for GetLastInputInfo at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetLastInputInfo.md), [google](http://www.google.com/search?q=GetLastInputInfo.md) or [google groups](http://groups.google.com/groups?q=GetLastInputInfo.md)\.


## [win32api](win32api.md#win32api)\.GetLocalTime

tuple = GetLocalTime\(\)
Returns the current local time


## [win32api](win32api.md#win32api)\.GetLogicalDriveStrings

string = GetLogicalDriveStrings\(\)
Returns a string with all logical drives currently mapped\.

#### Win32 API References

  - Search for GetLogicalDriveStrings at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetLogicalDriveStrings.md), [google](http://www.google.com/search?q=GetLogicalDriveStrings.md) or [google groups](http://groups.google.com/groups?q=GetLogicalDriveStrings.md)\.

#### Return Value
The return value is a single string, with each drive 

letter NULL terminated\. 

Use "s\.split\('\\\\0'\)" to split into components\.


## [win32api](win32api.md#win32api)\.GetLogicalDrives

int = GetLogicalDrives\(\)
Returns a bitmask representing the currently available disk drives\.

#### Win32 API References

  - Search for GetLogicalDrives at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetLogicalDrives.md), [google](http://www.google.com/search?q=GetLogicalDrives.md) or [google groups](http://groups.google.com/groups?q=GetLogicalDrives.md)\.


## [win32api](win32api.md#win32api)\.GetLongPathName

string = GetLongPathName\(fileName\)
Converts the specified path to its long form\.

#### Parameters

  - fileName : string

    The file name\.

#### Comments

This function may raise a NotImplementedError exception if the version 

of Windows does not support this function\.


## [win32api](win32api.md#win32api)\.GetLongPathNameW

[PyUnicode](PyUnicode.md) = GetLongPathNameW\(fileName\)
Converts the specified path to its long form\.

#### Parameters

  - fileName : [PyUnicode](PyUnicode.md)

    The file name\.

#### Comments

This function may raise a NotImplementedError exception if the version 

of Windows does not support this function\.


## [win32api](win32api.md#win32api)\.GetModuleFileName

string = GetModuleFileName\(hModule\)
Retrieves the filename of the specified module\.

#### Parameters

  - hModule : [PyHANDLE](PyHANDLE.md)

    Specifies the handle to the module\.

#### Win32 API References

  - Search for GetModuleFileName at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetModuleFileName.md), [google](http://www.google.com/search?q=GetModuleFileName.md) or [google groups](http://groups.google.com/groups?q=GetModuleFileName.md)\.


## [win32api](win32api.md#win32api)\.GetModuleFileNameW

[PyUnicode](PyUnicode.md) = GetModuleFileNameW\(hModule\)
Retrieves the unicode filename of the specified module\.

#### Parameters

  - hModule : [PyHANDLE](PyHANDLE.md)

    Specifies the handle to the module\.

#### Win32 API References

  - Search for GetModuleFileName at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetModuleFileName.md), [google](http://www.google.com/search?q=GetModuleFileName.md) or [google groups](http://groups.google.com/groups?q=GetModuleFileName.md)\.


## [win32api](win32api.md#win32api)\.GetModuleHandle

int = GetModuleHandle\(fileName\)
Returns the handle of an already loaded DLL\.

#### Parameters

  - fileName=None : string

    Specifies the file name of the module to load\.

#### Win32 API References

  - Search for GetModuleHandle at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetModuleHandle.md), [google](http://www.google.com/search?q=GetModuleHandle.md) or [google groups](http://groups.google.com/groups?q=GetModuleHandle.md)\.


## [win32api](win32api.md#win32api)\.GetMonitorInfo

dict = GetMonitorInfo\(hMonitor\)
Retrieves information for a monitor by handle

#### Parameters

  - hMonitor : [PyHANDLE](PyHANDLE.md)

    Handle to a monitor

#### Comments

Accepts keyword args

#### Return Value
Returns a dictionary representing a MONITORINFOEX structure


## [win32api](win32api.md#win32api)\.GetNativeSystemInfo

tuple = GetNativeSystemInfo\(\)
Retrieves information about the current system for a Wow64 process\.

#### Win32 API References

  - Search for GetNativeSystemInfo at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetNativeSystemInfo.md), [google](http://www.google.com/search?q=GetNativeSystemInfo.md) or [google groups](http://groups.google.com/groups?q=GetNativeSystemInfo.md)\.

#### Return Value
The return value is a tuple of 9 values, which corresponds 

to the Win32 SYSTEM\_INFO structure\.  The element names are: 

wProcessorArchitecture
dwPageSize
lpMinimumApplicationAddress
lpMaximumApplicationAddress
 

dwActiveProcessorMask
dwNumberOfProcessors
 

dwProcessorType
dwAllocationGranularity
\(wProcessorLevel,wProcessorRevision\)


## [win32api](win32api.md#win32api)\.GetProcAddress

int = GetProcAddress\(hModule, functionName

\)
Returns the address of the specified exported dynamic-link library \(DLL\) function\.

#### Parameters

  - hModule : [PyHANDLE](PyHANDLE.md)

    Specifies the handle to the module\.

  - functionName : [PyResourceId](PyResourceId.md)

    Specifies the name of the procedure, or its ordinal value

#### Win32 API References

  - Search for GetProcAddress at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetProcAddress.md), [google](http://www.google.com/search?q=GetProcAddress.md) or [google groups](http://groups.google.com/groups?q=GetProcAddress.md)\.


## [win32api](win32api.md#win32api)\.GetProfileSection

list = GetProfileSection\(section, iniName

\)
Retrieves all entries from a section in an INI file\.

#### Parameters

  - section : string

    The section in the INI file to retrieve a entries for\.

  - iniName=None : string

    The name of the INI file\.  If None, the system INI file is used\.

#### Comments

This function is obsolete, applications should use the registry instead\.

#### Win32 API References

  - Search for GetProfileSection at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetProfileSection.md), [google](http://www.google.com/search?q=GetProfileSection.md) or [google groups](http://groups.google.com/groups?q=GetProfileSection.md)\.

#### Return Value
The return value is a list of strings\.


## [win32api](win32api.md#win32api)\.GetProfileVal

int/string = GetProfileVal\(section, entry

, defValue

, iniName

\)
Retrieves entries from a windows INI file\.  This method encapsulates GetProfileString, GetProfileInt, GetPrivateProfileString and GetPrivateProfileInt\.

#### Parameters

  - section : string

    The section in the INI file to retrieve a value for\.

  - entry : string

    The entry within the section in the INI file to retrieve a value for\.

  - defValue : int/string

    The default value\.  The type of this parameter determines the methods return type\.

  - iniName=None : string

    The name of the INI file\.  If None, the system INI file is used\.

#### Comments

This function is obsolete, applications should use the registry instead\.

#### Win32 API References

  - Search for GetProfileString at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetProfileString.md), [google](http://www.google.com/search?q=GetProfileString.md) or [google groups](http://groups.google.com/groups?q=GetProfileString.md)\.

  - Search for GetProfileInt at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetProfileInt.md), [google](http://www.google.com/search?q=GetProfileInt.md) or [google groups](http://groups.google.com/groups?q=GetProfileInt.md)\.

  - Search for GetPrivateProfileString at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetPrivateProfileString.md), [google](http://www.google.com/search?q=GetPrivateProfileString.md) or [google groups](http://groups.google.com/groups?q=GetPrivateProfileString.md)\.

  - Search for GetPrivateProfileInt at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetPrivateProfileInt.md), [google](http://www.google.com/search?q=GetPrivateProfileInt.md) or [google groups](http://groups.google.com/groups?q=GetPrivateProfileInt.md)\.

#### Return Value
The return value is the same type as the default parameter\.


## [win32api](win32api.md#win32api)\.GetPwrCapabilities

dict = GetPwrCapabilities\(\)
Retrieves system's power capabilities

#### Comments

Requires Win2k or later\.

#### Win32 API References

  - Search for GetPwrCapabilities at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetPwrCapabilities.md), [google](http://www.google.com/search?q=GetPwrCapabilities.md) or [google groups](http://groups.google.com/groups?q=GetPwrCapabilities.md)\.

#### Return Value
Returns a dict representing a SYSTEM\_POWER\_CAPABILITIES struct


## [win32api](win32api.md#win32api)\.GetShortPathName

string = GetShortPathName\(path\)
Obtains the short path form of the specified path\.

#### Parameters

  - path : string/unicode

    If a unicode object is passed, 

GetShortPathNameW will be called and a unicode object returned\.

#### Comments

The short path name is an 8\.3 compatible file name\.  As the input path does 

not need to be absolute, the returned name may be longer than the input path\.

#### Win32 API References

  - Search for GetShortPathName at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetShortPathName.md), [google](http://www.google.com/search?q=GetShortPathName.md) or [google groups](http://groups.google.com/groups?q=GetShortPathName.md)\.


## [win32api](win32api.md#win32api)\.GetStdHandle

GetStdHandle\(handle\)
Returns a handle for the standard input, standard output, or standard error device

#### Parameters

  - handle : int

    input, output, or error device


## [win32api](win32api.md#win32api)\.GetSysColor

int = GetSysColor\(index\)
Returns the current system color for the specified element\.

#### Parameters

  - index : int

    The Id of the element to return\.  See the API for full details\.

#### Win32 API References

  - Search for GetSysColor at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetSysColor.md), [google](http://www.google.com/search?q=GetSysColor.md) or [google groups](http://groups.google.com/groups?q=GetSysColor.md)\.

#### Return Value
The return value is a windows RGB color representation\.


## [win32api](win32api.md#win32api)\.GetSystemDefaultLCID

int = GetSystemDefaultLCID\(\)
Retrieves the system default locale identifier\.

#### Win32 API References

  - Search for GetSystemDefaultLCID at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetSystemDefaultLCID.md), [google](http://www.google.com/search?q=GetSystemDefaultLCID.md) or [google groups](http://groups.google.com/groups?q=GetSystemDefaultLCID.md)\.


## [win32api](win32api.md#win32api)\.GetSystemDefaultLangID

int = GetSystemDefaultLangID\(\)
Retrieves the system default language identifier\.

#### Win32 API References

  - Search for GetSystemDefaultLangID at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetSystemDefaultLangID.md), [google](http://www.google.com/search?q=GetSystemDefaultLangID.md) or [google groups](http://groups.google.com/groups?q=GetSystemDefaultLangID.md)\.


## [win32api](win32api.md#win32api)\.GetSystemDirectory

string = GetSystemDirectory\(\)
Returns the path of the Windows system directory\.

#### Win32 API References

  - Search for GetSystemDirectory at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetSystemDirectory.md), [google](http://www.google.com/search?q=GetSystemDirectory.md) or [google groups](http://groups.google.com/groups?q=GetSystemDirectory.md)\.


## [win32api](win32api.md#win32api)\.GetSystemFileCacheSize

tuple = GetSystemFileCacheSize\(\)
Returns the amount of memory reserved for file cache

#### Return Value
Returns a tuple containing the minimum and maximum cache sizes, and flags \(combination of win32con\.MM\_WORKING\_SET\_\* flags\)


## [win32api](win32api.md#win32api)\.GetSystemInfo

tuple = GetSystemInfo\(\)
Retrieves information about the current system\.

#### Win32 API References

  - Search for GetSystemInfo at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetSystemInfo.md), [google](http://www.google.com/search?q=GetSystemInfo.md) or [google groups](http://groups.google.com/groups?q=GetSystemInfo.md)\.

#### Return Value
The return value is a tuple of 9 values, which corresponds 

to the Win32 SYSTEM\_INFO structure\.  The element names are: 

wProcessorArchitecture
dwPageSize
lpMinimumApplicationAddress
lpMaximumApplicationAddress
 

dwActiveProcessorMask
dwNumberOfProcessors
 

dwProcessorType
dwAllocationGranularity
\(wProcessorLevel,wProcessorRevision\)


## [win32api](win32api.md#win32api)\.GetSystemMetrics

int = GetSystemMetrics\(index\)
Retrieves various system metrics and system configuration settings\.

#### Parameters

  - index : int

    Which metric is being requested\.  See the API documentation for a full list\.

#### Win32 API References

  - Search for GetSystemMetrics at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetSystemMetrics.md), [google](http://www.google.com/search?q=GetSystemMetrics.md) or [google groups](http://groups.google.com/groups?q=GetSystemMetrics.md)\.


## [win32api](win32api.md#win32api)\.GetSystemTime

tuple = GetSystemTime\(\)
Returns the current system time


## [win32api](win32api.md#win32api)\.GetTempFileName

tuple = GetTempFileName\(path, prefix

, nUnique

\)
Returns creates a temporary filename of the following form: path\\\\preuuuu\.tmp\.

#### Parameters

  - path : string

    Specifies the path where the method creates the temporary filename\. 

Applications typically specify a period \(\.\) or the result of the GetTempPath function for this parameter\.

  - prefix : string

    Specifies the temporary filename prefix\.

  - nUnique : int

    Specifies an nteger used in creating the temporary filename\. 

If this parameter is nonzero, it is appended to the temporary filename\. 

If this parameter is zero, Windows uses the current system time to create a number to append to the filename\.

#### Win32 API References

  - Search for GetTempFileName at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetTempFileName.md), [google](http://www.google.com/search?q=GetTempFileName.md) or [google groups](http://groups.google.com/groups?q=GetTempFileName.md)\.

#### Return Value
The return value is a tuple of \(string, int\), where string is the 

filename, and rc is the unique number used to generate the filename\.


## [win32api](win32api.md#win32api)\.GetTempPath

string = GetTempPath\(\)
Retrieves the path of the directory designated for temporary files\.


## [win32api](win32api.md#win32api)\.GetThreadLocale

int = GetThreadLocale\(\)
Returns the current thread's locale\.


## [win32api](win32api.md#win32api)\.GetTickCount

int = GetTickCount\(\)
Returns the number of milliseconds since windows started\.


## [win32api](win32api.md#win32api)\.GetTimeFormat

string = GetTimeFormat\(locale, flags

, time

, format

\)
Formats a time as a time string for a specified locale\. The function formats either a specified time or the local system time\.

#### Parameters

  - locale : int

    

  - flags : int

    

  - time : [PyTime](PyTime.md)

    The time to use, or None to use the current time\.

  - format : string

    May be None


## [win32api](win32api.md#win32api)\.GetTimeZoneInformation

tuple = GetTimeZoneInformation\(times\_as\_tuples\)
Retrieves the system time-zone information\.

#### Parameters

  - times\_as\_tuples=False : bool

    If true, the SYSTEMTIME elements are returned as tuples instead of a time object\.

#### Return Value
The return value is a tuple of \(rc, tzinfo\), where rc is 

the integer return code from ::GetTimezoneInformation\(\), which may be

   

       value

   

   

       description

   

TIME\_ZONE\_ID\_STANDARDif in standard time

TIME\_ZONE\_ID\_DAYLIGHTif in daylight savings time

TIME\_ZONE\_ID\_UNKNOWNif the timezone in question doesn't use daylight savings time, \(eg\. indiana time\)\.

tzinfo is a tuple of:

#### Items

  - \[0\] int : bias

    Specifies the current bias, in minutes, for local time translation on this computer\. The bias is the difference, in minutes, between Coordinated Universal Time \(UTC\) and local time\. All translations between UTC and local time are based on the following formula:

UTC = local time \+ bias 

  - \[1\] unicode : standardName

    Specifies a string associated with standard time on this operating system\. For example, this member could contain "EST" to indicate Eastern Standard Time\. This string is not used by the operating system, so anything stored there using the SetTimeZoneInformation function is returned unchanged by the GetTimeZoneInformation function\. This string can be empty\.

  - \[2\] [PyTime](PyTime.md)/tuple : standardTime

    Specifies a SYSTEMTIME object that contains a date and local time when the transition from daylight saving time to standard time occurs on this operating system\. If this date is not specified, the wMonth member in the SYSTEMTIME structure must be zero\. If this date is specified, the DaylightDate value in the TIME\_ZONE\_INFORMATION structure must also be specified\. 

To select the correct day in the month, set the wYear member to zero, the wDayOfWeek member to an appropriate weekday, and the wDay member to a value in the range 1 through 5\. Using this notation, the first Sunday in April can be specified, as can the last Thursday in October \(5 is equal to "the last"\)\.

  - \[3\] int : standardBias

    Specifies a bias value to be used during local time translations that occur during standard time\. This member is ignored if a value for the StandardDate member is not supplied\. 
This value is added to the value of the Bias member to form the bias used during standard time\. In most time zones, the value of this member is zero\.

  - \[4\] unicode : daylightName

    

  - \[5\] [PyTime](PyTime.md)/tuple : daylightTime

    

  - \[6\] int : daylightBias

    Specifies a bias value to be used during local time translations that occur during daylight saving time\. This member is ignored if a value for the DaylightDate member is not supplied\. 

This value is added to the value of the Bias member to form the bias used during daylight saving time\. In most time zones, the value of this member is &\#150 60\.


## [win32api](win32api.md#win32api)\.GetUserDefaultLCID

int = GetUserDefaultLCID\(\)
Retrieves the user default locale identifier\.

#### Win32 API References

  - Search for GetUserDefaultLCID at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetUserDefaultLCID.md), [google](http://www.google.com/search?q=GetUserDefaultLCID.md) or [google groups](http://groups.google.com/groups?q=GetUserDefaultLCID.md)\.


## [win32api](win32api.md#win32api)\.GetUserDefaultLangID

int = GetUserDefaultLangID\(\)
Retrieves the user default language identifier\.

#### Win32 API References

  - Search for GetUserDefaultLangID at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetUserDefaultLangID.md), [google](http://www.google.com/search?q=GetUserDefaultLangID.md) or [google groups](http://groups.google.com/groups?q=GetUserDefaultLangID.md)\.


## [win32api](win32api.md#win32api)\.GetUserName

string = GetUserName\(\)
Returns the current user name

#### Win32 API References

  - Search for GetUserName at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetUserName.md), [google](http://www.google.com/search?q=GetUserName.md) or [google groups](http://groups.google.com/groups?q=GetUserName.md)\.


## [win32api](win32api.md#win32api)\.GetUserNameEx

string = GetUserNameEx\(NameFormat\)
Returns the current user name in format from EXTENDED\_NAME\_FORMAT enum

#### Parameters

  - NameFormat : int

    EXTENDED\_NAME\_FORMAT value, win32con\.Name\*

#### Win32 API References

  - Search for GetUserNameEx at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=GetUserNameEx.md), [google](http://www.google.com/search?q=GetUserNameEx.md) or [google groups](http://groups.google.com/groups?q=GetUserNameEx.md)\.


## [win32api](win32api.md#win32api)\.GetVersion

int = GetVersion\(\)
Returns the current version of Windows, and information about the environment\.

#### Return Value
The return value's low word is the major/minor version of Windows\.  The high 

word is 0 if the platform is Windows NT, or 1 if Win32s on Windows 3\.1


## [win32api](win32api.md#win32api)\.GetVersionEx

tuple = GetVersionEx\(format\)
Returns the current version of Windows, and information about the environment\.

#### Parameters

  - format=0 : int

    The format of the version info to return\. 

May be 0 \(for OSVERSIONINFO\) or 1 \(for OSVERSIONINFOEX\)

#### Return Value
The return value is a tuple with the following information\.

#### Items

  - \[0\] int : majorVersion

    Identifies the major version number of the operating system\.

  - \[1\] int : minorVersion

    Identifies the minor version number of the operating system\.

  - \[2\] int : buildNumber

    Identifies the build number of the operating system in the low-order word\. \(The high-order word contains the major and minor version numbers\.\)

  - \[3\] int : platformId

    Identifies the platform supported by the operating system\.  May be one of VER\_PLATFORM\_WIN32s, VER\_PLATFORM\_WIN32\_WINDOWS or VER\_PLATFORM\_WIN32\_NT

  - \[4\] string : version

    Contains arbitrary additional information about the operating system\.

#### Return Value
or if the format param is 1, the return value is a tuple with:

#### Items

  - \[0\] int : majorVersion

    Identifies the major version number of the operating system\.

  - \[1\] int : minorVersion

    Identifies the minor version number of the operating system\.

  - \[2\] int : buildNumber

    Identifies the build number of the operating system in the low-order word\. \(The high-order word contains the major and minor version numbers\.\)

  - \[3\] int : platformId

    Identifies the platform supported by the operating system\.  May be one of VER\_PLATFORM\_WIN32s, VER\_PLATFORM\_WIN32\_WINDOWS or VER\_PLATFORM\_WIN32\_NT

  - \[4\] string : version

    Contains arbitrary additional information about the operating system\.

  - \[5\] int : wServicePackMajor

    Major version number of the latest Service Pack installed on the system\. For example, for Service Pack 3, the major version number is 3\. If no Service Pack has been installed, the value is zero\.

  - \[6\] int : wServicePackMinor

    Minor version number of the latest Service Pack installed on the system\. For example, for Service Pack 3, the minor version number is 0\.

  - \[7\] int : wSuiteMask

    Bit flags that identify the product suites available on the system\. This member can be a combination of the VER\_SUITE\_\* values\.

  - \[8\] int : wProductType

    Additional information about the system\. This member can be one of the VER\_NT\_\* values\.

  - \[9\] int : wReserved

    


## [win32api](win32api.md#win32api)\.GetVolumeInformation

tuple = GetVolumeInformation\(path\)
Returns information about a file system and colume whose root directory is specified\.

#### Parameters

  - path : string

    The root path of the volume on which information is being requested\.

#### Return Value
The return is a tuple of: 

string - Volume Name 

long - Volume serial number\. 

long - Maximum Component Length of a file name\. 

long - Sys Flags - other flags specific to the file system\.  See the api for details\. 

string - File System Name


## [win32api](win32api.md#win32api)\.GetWindowLong

int = GetWindowLong\(hwnd, offset

\)
Retrieves a long value at the specified offset into the extra window memory of the given window\.

#### Parameters

  - hwnd : [PyHANDLE](PyHANDLE.md)

    The handle to the window\.

  - offset : int

    Specifies the zero-based byte offset of the value to change\. Valid values are in the range zero through the number of bytes of extra window memory, minus four \(for example, if 12 or more bytes of extra memory were specified, a value of 8 would be an index to the third long integer\), or one of the GWL\_ constants\.

#### Comments

This function calls the GetWindowLongPtr Api function


## [win32api](win32api.md#win32api)\.GetWindowsDirectory

string = GetWindowsDirectory\(\)
Returns the path of the Windows directory\.


## [win32api](win32api.md#win32api)\.GlobalMemoryStatus

dict = GlobalMemoryStatus\(\)
Returns systemwide memory usage

#### Return Value
Returns a dictionary representing a MEMORYSTATUS structure


## [win32api](win32api.md#win32api)\.GlobalMemoryStatusEx

dict = GlobalMemoryStatusEx\(\)
Returns physical and virtual memory usage

#### Comments

Only available on Win2k and later\.

#### Return Value
Returns a dictionary representing a MEMORYSTATUSEX structure


## [win32api](win32api.md#win32api)\.HIBYTE

int = HIBYTE\(val\)
An interface to the win32api HIBYTE macro\.

#### Parameters

  - val : int

    The value to retrieve the HIBYTE from\.

#### Comments

This is simply a wrapper to a C\+\+ macro\.


## [win32api](win32api.md#win32api)\.HIWORD

int = HIWORD\(val\)
An interface to the win32api HIWORD macro\.

#### Parameters

  - val : int

    The value to retrieve the HIWORD from\.

#### Comments

This is simply a wrapper to a C\+\+ macro\.


## [win32api](win32api.md#win32api)\.InitiateSystemShutdown

InitiateSystemShutdown\(computerName, message, timeOut, bForceClose, bRebootAfterShutdown\)
Initiates a shutdown and optional restart of the specified computer\.

#### Parameters

  - computerName : string/[PyUnicode](PyUnicode.md)

    Specifies the name of the computer to shut-down, or None

  - message : string/[PyUnicode](PyUnicode.md)

    Message to display in a dialog box

  - timeOut : int

    Specifies the time \(in seconds\) that the dialog box should be displayed\. While this dialog box is displayed, the shutdown can be stopped by the AbortSystemShutdown function\. 

If dwTimeout is zero, the computer shuts down without displaying the dialog box, and the shutdown cannot be stopped by AbortSystemShutdown\.

  - bForceClose : int

    Specifies whether applications with unsaved changes are to be forcibly closed\. If this parameter is TRUE, such applications are closed\. If this parameter is FALSE, a dialog box is displayed prompting the user to close the applications\.

  - bRebootAfterShutdown : int

    Specifies whether the computer is to restart immediately after shutting down\. If this parameter is TRUE, the computer is to restart\. If this parameter is FALSE, the system flushes all caches to disk, clears the screen, and displays a message indicating that it is safe to power down\.

#### Win32 API References

  - Search for InitiateSystemShutdown at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=InitiateSystemShutdown.md), [google](http://www.google.com/search?q=InitiateSystemShutdown.md) or [google groups](http://groups.google.com/groups?q=InitiateSystemShutdown.md)\.


## [win32api](win32api.md#win32api)\.LOBYTE

int = LOBYTE\(val\)
An interface to the win32api LOBYTE macro\.

#### Parameters

  - val : int

    The value to retrieve the LOBYTE from\.

#### Comments

This is simply a wrapper to a C\+\+ macro\.


## [win32api](win32api.md#win32api)\.LOWORD

int = LOWORD\(val\)
An interface to the win32api LOWORD macro\.

#### Parameters

  - val : int

    The value to retrieve the LOWORD from\.

#### Comments

This is simply a wrapper to a C\+\+ macro\.


## [win32api](win32api.md#win32api)\.LoadCursor

[PyHANDLE](PyHANDLE.md) = LoadCursor\(hInstance, cursorid

\)
Loads a cursor\.

#### Parameters

  - hInstance : [PyHANDLE](PyHANDLE.md)

    Handle to the instance to load the resource from, or None to load a standard system cursor

  - cursorid : [PyResourceId](PyResourceId.md)

    The ID of the cursor\.  Can be a resource id or for system cursors, one of win32con\.IDC\_\*

#### Win32 API References

  - Search for LoadCursor at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=LoadCursor.md), [google](http://www.google.com/search?q=LoadCursor.md) or [google groups](http://groups.google.com/groups?q=LoadCursor.md)\.


## [win32api](win32api.md#win32api)\.LoadKeyboardLayout

int = LoadKeyboardLayout\(KLID, Flags

\)
Loads a new locale id

#### Parameters

  - KLID : string

    Hex string containing a locale id, eg "00000409"

  - Flags=0 : int

    Combination of win32con\.KLF\_\* constants

#### Return Value
Returns the numeric locale id that was loaded


## [win32api](win32api.md#win32api)\.LoadLibrary

int = LoadLibrary\(fileName\)
Loads the specified DLL, and returns the handle\.

#### Parameters

  - fileName : string

    Specifies the file name of the module to load\.

#### Win32 API References

  - Search for LoadLibrary at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=LoadLibrary.md), [google](http://www.google.com/search?q=LoadLibrary.md) or [google groups](http://groups.google.com/groups?q=LoadLibrary.md)\.


## [win32api](win32api.md#win32api)\.LoadLibraryEx

[PyHANDLE](PyHANDLE.md) = LoadLibraryEx\(fileName, handle

, handle

\)
Loads the specified DLL, and returns the handle\.

#### Parameters

  - fileName : string

    Specifies the file name of the module to load\.

  - handle : [PyHANDLE](PyHANDLE.md)

    Reserved - must be zero

  - handle : flags

    Specifies the action to take when loading the module\.

#### Win32 API References

  - Search for LoadLibraryEx at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=LoadLibraryEx.md), [google](http://www.google.com/search?q=LoadLibraryEx.md) or [google groups](http://groups.google.com/groups?q=LoadLibraryEx.md)\.


## [win32api](win32api.md#win32api)\.LoadResource

string = LoadResource\(handle, type

, name

, language

\)
Finds and loads a resource from a PE file\.

#### Parameters

  - handle : [PyHANDLE](PyHANDLE.md)

    The handle of the module containing the resource\.  Use None for currrent process executable\.

  - type : [PyResourceId](PyResourceId.md)

    The type of resource to load\.

  - name : [PyResourceId](PyResourceId.md)

    The name or Id of the resource to load\.

  - language=NEUTRAL : int

    Language to use, defaults to LANG\_NEUTRAL\.


## [win32api](win32api.md#win32api)\.LoadString

[PyUnicode](PyUnicode.md) = LoadString\(handle, stringId

, numChars

\)
Loads a string from a resource file\.

#### Parameters

  - handle : [PyHANDLE](PyHANDLE.md)

    The handle of the module containing the resource\.

  - stringId : int

    The ID of the string to load\.

  - numChars=1024 : int

    Number of characters to allocate for the return buffer\.


## [win32api](win32api.md#win32api)\.MAKELANGID

int = MAKELANGID\(PrimaryLanguage, SubLanguage

\)
Creates a language identifier from a primary language identifier and a sublanguage identifier\.

#### Parameters

  - PrimaryLanguage : int

    Primary language identifier

  - SubLanguage : int

    The sublanguage identifier

#### Comments

This is simply a wrapper to a C\+\+ macro\.


## [win32api](win32api.md#win32api)\.MAKELONG

int = MAKELONG\(low, high

\)
creates a LONG value by concatenating the specified values\.

#### Parameters

  - low : int

    Specifies the low-order byte of the new value\.

  - high : int

    Specifies the high-order byte of the new value\.

#### Comments

This is simply a wrapper to a C\+\+ macro\.


## [win32api](win32api.md#win32api)\.MAKEWORD

int = MAKEWORD\(low, high

\)
creates a WORD value by concatenating the specified values\.

#### Parameters

  - low : int

    Specifies the low-order byte of the new value\.

  - high : int

    Specifies the high-order byte of the new value\.

#### Comments

This is simply a wrapper to a C\+\+ macro\.


## [win32api](win32api.md#win32api)\.MapVirtualKey

int = MapVirtualKey\(vk, type

, hlayout

\)
Translates \(maps\) a virtual-key code into a scan code or character value, or translates a scan code into a virtual-key code\.

#### Parameters

  - vk : int

    The virtual key code\.

  - type : int

    The type of conversion to make - see the API

  - hlayout=None : handle

    The keyboard layout to use\.  If not 

specified, the API function MapVirtualKey will be called\.  If it 

is specified MapVirtualKeyEx will be called\.

#### Comments

implemented by calling the unicode versions of the API \(MapVirtualKeyW/MapVirtualKeyExW\)


## [win32api](win32api.md#win32api)\.MessageBeep

int = MessageBeep\(type\)
Plays a predefined waveform sound\.

#### Parameters

  - type=win32con\.MB\_OK : int

    Specifies the sound type, as 

identified by an entry in the \[sounds\] section of the 

registry\. This parameter can be one of MB\_ICONASTERISK, 

MB\_ICONEXCLAMATION, MB\_ICONHAND, MB\_ICONQUESTION or MB\_OK\.

#### Comments

The waveform sound for each sound type is identified by an entry in the \[sounds\] section of the registry\.


## [win32api](win32api.md#win32api)\.MessageBox

int = MessageBox\(hwnd, message

, title

, style

, language

\)
Display a message box\.

#### Parameters

  - hwnd : [PyHANDLE](PyHANDLE.md)

    The handle of the parent window\.  See the comments section\.

  - message : string

    The message to be displayed in the message box\.

  - title : string/None

    The title for the message box\.  If None, the applications title will be used\.

  - style=win32con\.MB\_OK : int

    The style of the message box\.

  - language=win32api\.MAKELANGID\(LANG\_NEUTRAL,SUBLANG\_DEFAULT\) : int

    The language ID to use\.

#### Comments

Normally, a program in a GUI environment will use one of the MessageBox 

methods supplied by the GUI \(eg, [win32ui::MessageBox](win32ui.md#win32uimessagebox) or [PyCWnd::MessageBox](PyCWnd.md#pycwndmessagebox)\)

#### Return Value
An integer identifying the button pressed to dismiss the dialog\.


## [win32api](win32api.md#win32api)\.MonitorFromPoint

[PyHANDLE](PyHANDLE.md) = MonitorFromPoint\(pt, Flags

\)
Finds monitor that contains a point

#### Parameters

  - pt : \(int, int\)

    Tuple of 2 ints \(x,y\) specifying screen coordinates

  - Flags=0 : int

    Flags that determine default behaviour, one of MONITOR\_DEFAULTTONEAREST,MONITOR\_DEFAULTTONULL,MONITOR\_DEFAULTTOPRIMARY

#### Comments

Accepts keyword arguments

#### Return Value
Returns None if no monitor was found


## [win32api](win32api.md#win32api)\.MonitorFromRect

[PyHANDLE](PyHANDLE.md) = MonitorFromRect\(rc, Flags

\)
Finds monitor that has largest intersection with a rectangle

#### Parameters

  - rc : [PyRECT](PyRECT.md)

    Rectangle to be examined

  - Flags=0 : int

    Flags that determine default behaviour, one of MONITOR\_DEFAULTTONEAREST,MONITOR\_DEFAULTTONULL,MONITOR\_DEFAULTTOPRIMARY

#### Comments

Accepts keyword arguments

#### Return Value
Returns None if no monitor was found


## [win32api](win32api.md#win32api)\.MonitorFromWindow

[PyHANDLE](PyHANDLE.md) = MonitorFromWindow\(hwnd, Flags

\)
Finds monitor that contains a window

#### Parameters

  - hwnd : [PyHANDLE](PyHANDLE.md)

    Handle to a window

  - Flags=0 : int

    Flags that determine default behaviour, one of MONITOR\_DEFAULTTONEAREST,MONITOR\_DEFAULTTONULL,MONITOR\_DEFAULTTOPRIMARY

#### Comments

Accepts keyword arguments

#### Return Value
Returns None if no monitor was found


## [win32api](win32api.md#win32api)\.MoveFile

MoveFile\(srcName, destName\)
Renames a file, or a directory \(including its children\)\.

#### Parameters

  - srcName : string

    The name of the source file\.

  - destName : string

    The name of the destination file\.

#### Comments

This method can not move files across volumes\.

#### Win32 API References

  - Search for MoveFile\. at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=MoveFile..md), [google](http://www.google.com/search?q=MoveFile..md) or [google groups](http://groups.google.com/groups?q=MoveFile..md)\.


## [win32api](win32api.md#win32api)\.MoveFileEx

MoveFileEx\(srcName, destName, flag\)
Renames a file\.

#### Parameters

  - srcName : string

    The name of the source file\.

  - destName : string

    The name of the destination file\.  May be None\.

  - flag : int

    Flags indicating how the move is to be performed\.  See the API for full details\.

#### Comments

This method can move files across volumes\.
 

If destName is None, and flags contains win32con\.MOVEFILE\_DELAY\_UNTIL\_REBOOT, the 

file will be deleted next reboot\.

#### Win32 API References

  - Search for MoveFileEx at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=MoveFileEx.md), [google](http://www.google.com/search?q=MoveFileEx.md) or [google groups](http://groups.google.com/groups?q=MoveFileEx.md)\.


## [win32api](win32api.md#win32api)\.OpenProcess

[PyHANDLE](PyHANDLE.md) = OpenProcess\(reqdAccess, bInherit

, pid

\)
Retrieves a handle to an existing process

#### Parameters

  - reqdAccess : int

    The required access\.

  - bInherit : int

    Specifies whether the returned handle can be inherited by a new process created by the current process\. If TRUE, the handle is inheritable\.

  - pid : int

    The process ID


## [win32api](win32api.md#win32api)\.OutputDebugString

OutputDebugString\(msg\)
Sends a string to the Windows debugging device\.

#### Parameters

  - msg : string

    The string to write\.


## [win32api](win32api.md#win32api)\.PostMessage

PostMessage\(hwnd, idMessage, wParam, lParam\)
Post a message to a window\.

#### Parameters

  - hwnd : [PyHANDLE](PyHANDLE.md)

    The hWnd of the window to receive the message\.

  - idMessage : int

    The ID of the message to post\.

  - wParam=None : int

    The wParam for the message

  - lParam=None : int

    The lParam for the message

#### Win32 API References

  - Search for PostMessage at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=PostMessage.md), [google](http://www.google.com/search?q=PostMessage.md) or [google groups](http://groups.google.com/groups?q=PostMessage.md)\.


## [win32api](win32api.md#win32api)\.PostQuitMessage

PostQuitMessage\(exitCode\)
Post a quit message to an app\.

#### Parameters

  - exitCode=0 : int

    The exit code

#### Win32 API References

  - Search for PostQuitMessage at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=PostQuitMessage.md), [google](http://www.google.com/search?q=PostQuitMessage.md) or [google groups](http://groups.google.com/groups?q=PostQuitMessage.md)\.


## [win32api](win32api.md#win32api)\.PostThreadMessage

PostThreadMessage\(tid, idMessage, wParam, lParam\)
Post a message to the specified thread\.

#### Parameters

  - tid : int

    Identifier of the thread to which the message will be posted\.

  - idMessage : int

    The ID of the message to post\.

  - wParam=None : int/str

    The wParam for the message

  - lParam=None : int/str

    The lParam for the message

#### Win32 API References

  - Search for PostThreadMessage at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=PostThreadMessage.md), [google](http://www.google.com/search?q=PostThreadMessage.md) or [google groups](http://groups.google.com/groups?q=PostThreadMessage.md)\.


## [win32api](win32api.md#win32api)\.RGB

int = RGB\(red, green

, blue

\)
An interface to the win32api RGB macro\.

#### Parameters

  - red : int

    The red value

  - green : int

    The green value

  - blue : int

    The blue value

#### Comments

This is simply a wrapper to a C\+\+ macro\.


## [win32api](win32api.md#win32api)\.RegCloseKey

RegCloseKey\(key\)
Closes a previously opened registry key\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    The key to be closed\.

#### Win32 API References

  - Search for RegCloseKey at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegCloseKey.md), [google](http://www.google.com/search?q=RegCloseKey.md) or [google groups](http://groups.google.com/groups?q=RegCloseKey.md)\.


## [win32api](win32api.md#win32api)\.RegConnectRegistry

int = RegConnectRegistry\(computerName, key

\)
Establishes a connection to a predefined registry handle on another computer\.

#### Parameters

  - computerName : string

    The name of the remote computer, of the form \\\\\\\\computername\.  If None, the local computer is used\.

  - key : int

    The predefined handle\.  May be win32con\.HKEY\_LOCAL\_MACHINE or win32con\.HKEY\_USERS\.

#### Win32 API References

  - Search for RegConnectRegistry at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegConnectRegistry.md), [google](http://www.google.com/search?q=RegConnectRegistry.md) or [google groups](http://groups.google.com/groups?q=RegConnectRegistry.md)\.

#### Return Value
The return value is the handle of the opened key\. 

If the function fails, an exception is raised\.


## [win32api](win32api.md#win32api)\.RegCopyTree

RegCopyTree\(KeySrc, SubKey, KeyDest\)
Copies an entire registry key to another location

#### Parameters

  - KeySrc : [PyHKEY](PyHKEY.md)

    Registry key to be copied

  - SubKey : [PyUnicode](PyUnicode.md)

    Subkey to be copied, can be None

  - KeyDest : [PyHKEY](PyHKEY.md)

    The destination key

#### Comments

Accepts keyword args\.

Requires Vista or later\.


## [win32api](win32api.md#win32api)\.RegCreateKey

[PyHKEY](PyHKEY.md) = RegCreateKey\(key, subKey

\)
Creates the specified key, or opens the key if it already exists\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS

  - subKey : string

    The name of a key that this method opens or creates\. 

This key must be a subkey of the key identified by the key parameter\. 

If key is one of the predefined keys, subKey may be None\. In that case, 

the handle returned is the same hkey handle passed in to the function\.

#### Win32 API References

  - Search for RegCreateKey at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegCreateKey.md), [google](http://www.google.com/search?q=RegCreateKey.md) or [google groups](http://groups.google.com/groups?q=RegCreateKey.md)\.

#### Return Value
The return value is the handle of the opened key\. 

If the function fails, an exception is raised\.


## [win32api](win32api.md#win32api)\.RegCreateKeyEx

[PyHKEY](PyHKEY.md), int = RegCreateKeyEx\(Key, SubKey

, samDesired

, Class

, Options

, SecurityAttributes

, Transaction

\)
Extended version of RegCreateKey

#### Parameters

  - Key : [PyHKEY](PyHKEY.md)/int

    Registry key or one of win32con\.HKEY\_\* values

  - SubKey : [PyUnicode](PyUnicode.md)

    Name of subkey to open or create\.

  - samDesired : int

    Access allowed to handle, combination of win32con\.KEY\_\* constants\.  Can also contain 

standard access rights such as DELETE, WRITE\_OWNER, etc\.

  - Class=None : [PyUnicode](PyUnicode.md)

    Name of registry key class

  - Options=REG\_OPTION\_NON\_VOLATILE : int

    One of the winnt\.REG\_OPTION\_\* values

  - SecurityAttributes=None : [PySECURITY\_ATTRIBUTES](PySECURITY.md#pysecurityattributes)

    Specifies security for key and handle inheritance

  - Transaction=None : [PyHANDLE](PyHANDLE.md)

    Handle to a transaction as returned by [win32transaction::CreateTransaction](win32transaction.md#win32transactioncreatetransaction)

#### Comments

Implemented only as Unicode \(RegCreateKeyExW\)\.  Accepts keyword arguments\.

If a transaction handle is passed in, RegCreateKeyTransacted will be called \(requires Vista or later\)

#### Win32 API References

  - Search for RegCreateKeyEx at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegCreateKeyEx.md), [google](http://www.google.com/search?q=RegCreateKeyEx.md) or [google groups](http://groups.google.com/groups?q=RegCreateKeyEx.md)\.

  - Search for RegCreateKeyTransacted at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegCreateKeyTransacted.md), [google](http://www.google.com/search?q=RegCreateKeyTransacted.md) or [google groups](http://groups.google.com/groups?q=RegCreateKeyTransacted.md)\.

#### Return Value
Returns registry handle and flag indicating if key was opened or created \(REG\_CREATED\_NEW\_KEY or REG\_OPENED\_EXISTING\_KEY\)


## [win32api](win32api.md#win32api)\.RegDeleteKey

RegDeleteKey\(key, subKey\)
Deletes the specified key\.  This method can not delete keys with subkeys\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS

  - subKey : string

    The name of the key to delete\. 

This key must be a subkey of the key identified by the key parameter\. 

This value must not be None, and the key may not have subkeys\.

#### Comments

If the method succeeds, the entire key, including all of its values, is removed\. 

If the method fails, and exception is raised\.

#### Win32 API References

  - Search for RegDeleteKey at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegDeleteKey.md), [google](http://www.google.com/search?q=RegDeleteKey.md) or [google groups](http://groups.google.com/groups?q=RegDeleteKey.md)\.


## [win32api](win32api.md#win32api)\.RegDeleteKeyEx

RegDeleteKeyEx\(Key, SubKey, samDesired, Transaction\)
Deletes a registry key from 32 or 64 bit registry view

#### Parameters

  - Key : [PyHKEY](PyHKEY.md)/int

    Registry key or one of win32con\.HKEY\_\* values

  - SubKey : [PyUnicode](PyUnicode.md)

    Name of subkey to be deleted\.

  - samDesired=0 : int

    Can be KEY\_WOW64\_32KEY or KEY\_WOW64\_64KEY to specify alternate registry view

  - Transaction=None : [PyHANDLE](PyHANDLE.md)

    Handle to a transaction as returned by [win32transaction::CreateTransaction](win32transaction.md#win32transactioncreatetransaction)

#### Comments

Accepts keyword args\.

Requires 64-bit XP, Vista, or later\.

Key to be deleted cannot contain subkeys

If a transaction handle is specified, RegDeleteKeyTransacted is called

#### Win32 API References

  - Search for RegDeleteKeyEx at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegDeleteKeyEx.md), [google](http://www.google.com/search?q=RegDeleteKeyEx.md) or [google groups](http://groups.google.com/groups?q=RegDeleteKeyEx.md)\.

  - Search for RegDeleteKeyTransacted at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegDeleteKeyTransacted.md), [google](http://www.google.com/search?q=RegDeleteKeyTransacted.md) or [google groups](http://groups.google.com/groups?q=RegDeleteKeyTransacted.md)\.


## [win32api](win32api.md#win32api)\.RegDeleteTree

RegDeleteTree\(Key, SubKey\)
Recursively deletes a key's subkeys and values

#### Parameters

  - Key : [PyHKEY](PyHKEY.md)

    Handle to a registry key

  - SubKey : [PyUnicode](PyUnicode.md)

    Name of subkey to be deleted, or None for all subkeys and values

#### Comments

Accepts keyword args\.

Requires Vista or later\.


## [win32api](win32api.md#win32api)\.RegDeleteValue

RegDeleteValue\(key, value\)
Removes a named value from the specified registry key\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS

  - value : string

    The name of the value to remove\.

#### Win32 API References

  - Search for RegDeleteValue at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegDeleteValue.md), [google](http://www.google.com/search?q=RegDeleteValue.md) or [google groups](http://groups.google.com/groups?q=RegDeleteValue.md)\.


## [win32api](win32api.md#win32api)\.RegEnumKey

string = RegEnumKey\(key, index

\)
Enumerates subkeys of the specified open registry key\. The function retrieves the name of one subkey each time it is called\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS

  - index : int

    The index of the key to retrieve\.

#### Win32 API References

  - Search for RegEnumKey at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegEnumKey.md), [google](http://www.google.com/search?q=RegEnumKey.md) or [google groups](http://groups.google.com/groups?q=RegEnumKey.md)\.


## [win32api](win32api.md#win32api)\.RegEnumKeyEx

tuple = RegEnumKeyEx\(Key\)
Lists subkeys of a registry key

#### Parameters

  - Key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS\.

#### Return Value
Returns subkeys as tuples of  \(name, reserved, class, last write time\)\. Reserved will always be 0\.


## [win32api](win32api.md#win32api)\.RegEnumKeyExW

tuple = RegEnumKeyExW\(Key\)
Unicode version of RegEnumKeyEx

#### Parameters

  - Key : [PyHKEY](PyHKEY.md)

    Registry handle opened with KEY\_ENUMERATE\_SUB\_KEYS, or one of win32con\.HKEY\_\* constants

#### Return Value
Returns subkeys as tuples of  \(name, reserved, class, last write time\)\. Reserved will always be 0\.


## [win32api](win32api.md#win32api)\.RegEnumValue

\(string,object,type\) = RegEnumValue\(key, index

\)
Enumerates values of the specified open registry key\. The function retrieves the name of one subkey each time it is called\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS

  - index : int

    The index of the key to retrieve\.

#### Comments

This function is typically called repeatedly, until an exception is raised, indicating no more values\.

#### Win32 API References

  - Search for PyRegEnumValue at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=PyRegEnumValue.md), [google](http://www.google.com/search?q=PyRegEnumValue.md) or [google groups](http://groups.google.com/groups?q=PyRegEnumValue.md)\.


## [win32api](win32api.md#win32api)\.RegFlushKey

RegFlushKey\(key\)
Writes all the attributes of the specified key to the registry\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS

#### Comments

It is not necessary to call RegFlushKey to change a key\. 

Registry changes are flushed to disk by the registry using its lazy flusher\. 

Registry changes are also flushed to disk at system shutdown\. 

Unlike [win32api::RegCloseKey](win32api.md#win32apiregclosekey), the RegFlushKey method returns only when all the data has been written to the registry\. 

An application should only call RegFlushKey if it requires absolute certainty that registry changes are on disk\. If you don't know whether a RegFlushKey call is required, it probably isn't\.

#### Win32 API References

  - Search for RegFlushKey at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegFlushKey.md), [google](http://www.google.com/search?q=RegFlushKey.md) or [google groups](http://groups.google.com/groups?q=RegFlushKey.md)\.


## [win32api](win32api.md#win32api)\.RegGetKeySecurity

[PySECURITY\_DESCRIPTOR](PySECURITY.md#pysecuritydescriptor) = RegGetKeySecurity\(key, security\_info

\)
Retrieves the security on the specified registry key\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    Handle to an open key for which the security descriptor is set\.

  - security\_info : int

    Specifies the components of the security descriptor to retrieve\. The value can be a combination of the \*\_SECURITY\_INFORMATION constants\.

#### Win32 API References

  - Search for RegGetKeySecurity at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegGetKeySecurity.md), [google](http://www.google.com/search?q=RegGetKeySecurity.md) or [google groups](http://groups.google.com/groups?q=RegGetKeySecurity.md)\.


## [win32api](win32api.md#win32api)\.RegLoadKey

RegLoadKey\(key, subKey, filename\)
The RegLoadKey method creates a subkey under HKEY\_USER or HKEY\_LOCAL\_MACHINE 

and stores registration information from a specified file into that subkey\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS

  - subKey : string

    The name of the key to delete\. 

This key must be a subkey of the key identified by the key parameter\. 

This value must not be None, and the key may not have subkeys\.

  - filename : string

    The name of the file to load registry data from\. 

This file must have been created with the [win32api::RegSaveKey](win32api.md#win32apiregsavekey) function\. 

Under the file allocation table \(FAT\) file system, the filename may not have an extension\.

#### Comments

A call to RegLoadKey fails if the calling process does not have the SE\_RESTORE\_PRIVILEGE privilege\. 

If hkey is a handle returned by [win32api::RegConnectRegistry](win32api.md#win32apiregconnectregistry), then the path specified in fileName is relative to the remote computer\.

#### Win32 API References

  - Search for RegLoadKey at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegLoadKey.md), [google](http://www.google.com/search?q=RegLoadKey.md) or [google groups](http://groups.google.com/groups?q=RegLoadKey.md)\.


## [win32api](win32api.md#win32api)\.RegNotifyChangeKeyValue

RegNotifyChangeKeyValue\(key, bWatchSubTree, dwNotifyFilter, hKey, fAsynchronous\)
Receive notification of registry changes

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    Handle to an open registry key

  - bWatchSubTree : int

    Boolean, notify of changes to subkeys if True

  - dwNotifyFilter : int

    Combination of REG\_NOTIFY\_CHANGE\_\* constants

  - hKey : [PyHANDLE](PyHANDLE.md)

    Event handle to be signalled, use None if fAsynchronous is False

  - fAsynchronous : int

    Boolean, function returns immediately if True, waits for change if False


## [win32api](win32api.md#win32api)\.RegOpenCurrentUser

[PyHKEY](PyHKEY.md) = RegOpenCurrentUser\(samDesired\)
Opens HKEY\_CURRENT\_USER for impersonated user

#### Parameters

  - samDesired=MAXIMUM\_ALLOWED : int

    Desired access, combination of win32con\.KEY\_\*

#### Win32 API References

  - Search for RegOpenCurrentUser at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegOpenCurrentUser.md), [google](http://www.google.com/search?q=RegOpenCurrentUser.md) or [google groups](http://groups.google.com/groups?q=RegOpenCurrentUser.md)\.


## [win32api](win32api.md#win32api)\.RegOpenKey

[PyHKEY](PyHKEY.md) = RegOpenKey\(\)
Opens the specified key\.

#### Comments

This funcion is implemented using [win32api::RegOpenKeyEx](win32api.md#win32apiregopenkeyex), by taking advantage 

of default parameters\.  See [win32api::RegOpenKeyEx](win32api.md#win32apiregopenkeyex) for more details\.


## [win32api](win32api.md#win32api)\.RegOpenKeyEx

[PyHKEY](PyHKEY.md) = RegOpenKeyEx\(key, subKey

, reserved

, sam

\)
Opens the specified key\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS

  - subKey : string

    The name of a key that this method opens\. 

This key must be a subkey of the key identified by the key parameter\. 

If key is one of the predefined keys, subKey may be None\. In that case, 

the handle returned is the same key handle passed in to the function\.

  - reserved=0 : int

    Reserved\.  Must be zero\.

  - sam=KEY\_READ : int

    Specifies an access mask that describes the desired security access for the new key\. This parameter can be a combination of the following win32con constants: 

KEY\_ALL\_ACCESS
KEY\_CREATE\_LINK
KEY\_CREATE\_SUB\_KEY
KEY\_ENUMERATE\_SUB\_KEYS
KEY\_EXECUTE
KEY\_NOTIFY
KEY\_QUERY\_VALUE
KEY\_READ
KEY\_SET\_VALUE
KEY\_WRITE

#### Win32 API References

  - Search for RegOpenKeyEx at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegOpenKeyEx.md), [google](http://www.google.com/search?q=RegOpenKeyEx.md) or [google groups](http://groups.google.com/groups?q=RegOpenKeyEx.md)\.

#### Return Value
The return value is the handle of the opened key\. 

If the function fails, an exception is raised\.


## [win32api](win32api.md#win32api)\.RegOpenKeyTransacted

[PyHKEY](PyHKEY.md) = RegOpenKeyTransacted\(Key, SubKey

, samDesired

, Transaction

, Options

\)
Opens a registry key as part of a transaction

#### Parameters

  - Key : [PyHKEY](PyHKEY.md)/int

    Registry key or one of win32con\.HKEY\_\* values

  - SubKey : [PyUnicode](PyUnicode.md)

    Name of subkey to open\.  Can be None to reopen an existing key\.

  - samDesired : int

    Access allowed to handle, combination of win32con\.KEY\_\* constants\.  Can also contain 

standard access rights such as DELETE, WRITE\_OWNER, etc\.

  - Transaction : [PyHANDLE](PyHANDLE.md)

    Handle to a transaction as returned by [win32transaction::CreateTransaction](win32transaction.md#win32transactioncreatetransaction)

  - Options=0 : int

    Reserved, use only 0

#### Comments

Accepts keyword arguments\.

Requires Vista or later\.

#### Win32 API References

  - Search for RegOpenKeyTransacted at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegOpenKeyTransacted.md), [google](http://www.google.com/search?q=RegOpenKeyTransacted.md) or [google groups](http://groups.google.com/groups?q=RegOpenKeyTransacted.md)\.

#### Return Value
Returns a transacted registry handle\.  Note that operations on subkeys are not automatically transacted\.


## [win32api](win32api.md#win32api)\.RegOverridePredefKey

RegOverridePredefKey\(Key, NewKey\)
Redirects one of the predefined keys to different key

#### Parameters

  - Key : [PyHKEY](PyHKEY.md)

    One of the predefined registry keys \(win32con\.HKEY\_\*\)

  - NewKey : [PyHKEY](PyHKEY.md)

    Registry key to which it will be redirected\.  Pass None to restore original key\.

#### Comments

Requires Windows 2000 or later\.

#### Win32 API References

  - Search for RegOverridePredefKey at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegOverridePredefKey.md), [google](http://www.google.com/search?q=RegOverridePredefKey.md) or [google groups](http://groups.google.com/groups?q=RegOverridePredefKey.md)\.


## [win32api](win32api.md#win32api)\.RegQueryInfoKey

\(int, int, long\) = RegQueryInfoKey\(key\)
Returns the number of 

subkeys, the number of values a key has, 

and if available the last time the key was modified as 

100's of nanoseconds since Jan 1, 1600\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or or any one of the following win32con 

constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS

#### Win32 API References

  - Search for RegQueryInfoKey at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegQueryInfoKey.md), [google](http://www.google.com/search?q=RegQueryInfoKey.md) or [google groups](http://groups.google.com/groups?q=RegQueryInfoKey.md)\.


## [win32api](win32api.md#win32api)\.RegQueryInfoKeyW

dict = RegQueryInfoKeyW\(Key\)
Returns information about an open registry key

#### Parameters

  - Key : [PyHKEY](PyHKEY.md)

    Handle to a registry key, or one of win32con\.HKEY\_\* constants

#### Win32 API References

  - Search for RegQueryInfoKeyW at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegQueryInfoKeyW.md), [google](http://www.google.com/search?q=RegQueryInfoKeyW.md) or [google groups](http://groups.google.com/groups?q=RegQueryInfoKeyW.md)\.


## [win32api](win32api.md#win32api)\.RegQueryValue

string = RegQueryValue\(key, subKey

\)
The RegQueryValue method retrieves the value associated with 

the unnamed value for a specified key in the registry\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS

  - subKey : string

    The name of the subkey with which the value is associated\. 

If this parameter is None or empty, the function retrieves the value set by the [win32api::RegSetValue](win32api.md#win32apiregsetvalue) method for the key identified by key\.

#### Comments

Values in the registry have name, type, and data components\. This method 

retrieves the data for a key's first value that has a NULL name\. 

But the underlying API call doesn't return the type, Lame Lame Lame, DONT USE THIS\!\!\!

#### Win32 API References

  - Search for RegQueryValue at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegQueryValue.md), [google](http://www.google.com/search?q=RegQueryValue.md) or [google groups](http://groups.google.com/groups?q=RegQueryValue.md)\.


## [win32api](win32api.md#win32api)\.RegQueryValueEx

\(object,type\) = RegQueryValueEx\(key, valueName

\)
Retrieves the type and data for a specified value name associated with an open registry key\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS

  - valueName : string

    The name of the value to query\.

#### Comments

Values in the registry have name, type, and data components\. This method 

retrieves the data for the given value\.

#### Win32 API References

  - Search for RegQueryValueEx at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegQueryValueEx.md), [google](http://www.google.com/search?q=RegQueryValueEx.md) or [google groups](http://groups.google.com/groups?q=RegQueryValueEx.md)\.


## [win32api](win32api.md#win32api)\.RegRestoreKey

RegRestoreKey\(Key, File, Flags\)
Restores a key and subkeys from a saved registry file

#### Parameters

  - Key : [PyHKEY](PyHKEY.md)

    Handle to registry key to be restored\.  Can also be one of win32con\.HKEY\_\* values\.

  - File : [PyUnicode](PyUnicode.md)

    File from which to restore registry data

  - Flags=0 : int

    One of REG\_FORCE\_RESTORE,REG\_NO\_LAZY\_FLUSH,REG\_REFRESH\_HIVE,REG\_WHOLE\_HIVE\_VOLATILE \(from winnt\)

#### Comments

Implemented only as Unicode \(RegRestoreKeyW\)\.  Accepts keyword arguments\.

Requires SeBackupPrivilege and SeRestorePrivilege

#### Win32 API References

  - Search for RegRestoreKey at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegRestoreKey.md), [google](http://www.google.com/search?q=RegRestoreKey.md) or [google groups](http://groups.google.com/groups?q=RegRestoreKey.md)\.


## [win32api](win32api.md#win32api)\.RegSaveKey

RegSaveKey\(key, filename, sa\)
The RegSaveKey method saves the specified key, and all its subkeys to the specified file\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS

  - filename : string

    The name of the file to save registry data to\. 

This file cannot already exist\. If this filename includes an extension, it cannot be used on file allocation table \(FAT\) file systems by the [win32api::RegLoadKey](win32api.md#win32apiregloadkey), win32api::RegReplaceKey

, or [win32api::RegRestoreKey](win32api.md#win32apiregrestorekey) methods\.

  - sa=None : [PySECURITY\_ATTRIBUTES](PySECURITY.md#pysecurityattributes)

    The security attributes of the created file\.

#### Comments

If key represents a key on a remote computer, the path described by fileName is relative to the remote computer\. 

The caller of this method must possess the SeBackupPrivilege security privilege\.

#### Win32 API References

  - Search for RegSaveKey at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegSaveKey.md), [google](http://www.google.com/search?q=RegSaveKey.md) or [google groups](http://groups.google.com/groups?q=RegSaveKey.md)\.


## [win32api](win32api.md#win32api)\.RegSaveKeyEx

RegSaveKeyEx\(Key, File, SecurityAttributes, Flags\)
Extended version of RegSaveKey

#### Parameters

  - Key : [PyHKEY](PyHKEY.md)

    Handle to a registry key or one of HKEY\_CURRENT\_CONFIG, HKEY\_CURRENT\_USER

  - File : [PyUnicode](PyUnicode.md)

    Name of file in which to save data\.  File must not already exist\.

  - SecurityAttributes=None : [PySECURITY\_ATTRIBUTES](PySECURITY.md#pysecurityattributes)

    Specifies security for the file to be created

  - Flags=REG\_LATEST\_FORMAT : int

    One of REG\_STANDARD\_FORMAT,REG\_LATEST\_FORMAT,REG\_NO\_COMPRESSION \(from winnt\.py\)

#### Comments

Implemented only as Unicode \(RegSaveKeyExW\)\.  Accepts keyword arguments\.

SE\_BACKUP\_NAME privilege must be enabled\.

#### Win32 API References

  - Search for RegSaveKeyEx at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegSaveKeyEx.md), [google](http://www.google.com/search?q=RegSaveKeyEx.md) or [google groups](http://groups.google.com/groups?q=RegSaveKeyEx.md)\.


## [win32api](win32api.md#win32api)\.RegSetKeySecurity

RegSetKeySecurity\(key, security\_info, sd\)
Sets the security on the specified registry key\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    Handle to an open key for which the security descriptor is set\.

  - security\_info : int

    Specifies the components of the security descriptor to set\. The value can be a combination of the \*\_SECURITY\_INFORMATION constants\.

  - sd : [PySECURITY\_DESCRIPTOR](PySECURITY.md#pysecuritydescriptor)

    The new security descriptor for the key

#### Comments

If key is one of the predefined keys, the predefined key should be closed with [win32api::RegCloseKey](win32api.md#win32apiregclosekey)\. That ensures that the new security information is in effect the next time the predefined key is referenced\.

#### Win32 API References

  - Search for PyRegSetKeySecurity at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=PyRegSetKeySecurity.md), [google](http://www.google.com/search?q=PyRegSetKeySecurity.md) or [google groups](http://groups.google.com/groups?q=PyRegSetKeySecurity.md)\.


## [win32api](win32api.md#win32api)\.RegSetValue

RegSetValue\(key, subKey, type, value\)
Associates a value with a specified key\.  Currently, only strings are supported\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS

  - subKey : string

    The name of the subkey with which the value is associated\. 

This parameter can be None or empty, in which case the value will be added to the key identified by the key parameter\.

  - type : int

    Type of data\. Must be win32con\.REG\_SZ

  - value : string

    The value to associate with the key\.

#### Comments

If the key specified by the lpszSubKey parameter does not exist, the RegSetValue function creates it\. 

Value lengths are limited by available memory\. Long values \(more than 2048 bytes\) should be stored as files with the filenames stored in the configuration registry\. This helps the registry perform efficiently\. 

The key identified by the key parameter must have been opened with KEY\_SET\_VALUE access\.

#### Win32 API References

  - Search for RegSetValue at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegSetValue.md), [google](http://www.google.com/search?q=RegSetValue.md) or [google groups](http://groups.google.com/groups?q=RegSetValue.md)\.


## [win32api](win32api.md#win32api)\.RegSetValueEx

RegSetValueEx\(key, valueName, reserved, type, value\)
Stores data in the value field of an open registry key\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_CLASSES\_ROOT
HKEY\_CURRENT\_USER
HKEY\_LOCAL\_MACHINE
HKEY\_USERS

  - valueName : string

    The name of the value to set\. 

If a value with this name is not already present in the key, the method adds it to the key\. 

If this parameter is None or an empty string and the type parameter is the win32api\.REG\_SZ type, this function sets the same value the [win32api::RegSetValue](win32api.md#win32apiregsetvalue) method would set\.

  - reserved : any

    Place holder for reserved argument\.  Zero will always be passed to the API function\.

  - type : int

    Type of data\.

   

       Value

   

   

       Meaning

   

REG\_BINARYBinary data in any form\.

REG\_DWORDA 32-bit number\.

REG\_DWORD\_LITTLE\_ENDIANA 32-bit number in little-endian format\. This is equivalent to REG\_DWORD\.
In little-endian format, a multi-byte value is stored in memory from the lowest byte \(the little end\) to the highest byte\. For example, the value 0x12345678 is stored as \(0x78 0x56 0x34 0x12\) in little-endian format\.

REG\_QWORDA 64-bit number\.

REG\_QWORD\_LITTLE\_ENDIANA 64-bit number in little-endian format\. This is equivalent to REG\_QWORD\.
In little-endian format, a multi-byte value is stored in memory from the lowest byte \(the little end\) to the highest byte\. For example, the value 0x12345678 is stored as \(0x78 0x56 0x34 0x12\) in little-endian format\. 

Windows NT and Windows 95 are designed to run on little-endian computer architectures\. A user may connect to computers that have big-endian architectures, such as some UNIX systems\.

REG\_DWORD\_BIG\_ENDIANA 32-bit number in big-endian format\. 

In big-endian format, a multi-byte value is stored in memory from the highest byte \(the big end\) to the lowest byte\. For example, the value 0x12345678 is stored as \(0x12 0x34 0x56 0x78\) in big-endian format\.

REG\_EXPAND\_SZA null-terminated string that contains unexpanded references to environment variables \(for example, %PATH%\)\. It will be a Unicode or ANSI string depending on whether you use the Unicode or ANSI functions\.

REG\_LINKA Unicode symbolic link\.

REG\_MULTI\_SZAn array of null-terminated strings, terminated by two null characters\.

REG\_NONENo defined value type\.

REG\_RESOURCE\_LISTA device-driver resource list\.

REG\_SZA null-terminated string\. It will be a Unicode or ANSI string depending on whether you use the Unicode or ANSI functions

  - value : registry data

    The value to be stored with the specified value name\.

#### Comments

This method can also set additional value and type information for the specified key\. 

The key identified by the key parameter must have been opened with KEY\_SET\_VALUE access\. 

To open the key, use the [win32api::RegCreateKeyEx](win32api.md#win32apiregcreatekeyex) or [win32api::RegOpenKeyEx](win32api.md#win32apiregopenkeyex) methods\. 

Value lengths are limited by available memory\. 

Long values \(more than 2048 bytes\) should be stored as files with the filenames stored in the configuration registry\. 

This helps the registry perform efficiently\. 

The key identified by the key parameter must have been opened with KEY\_SET\_VALUE access\.

#### Win32 API References

  - Search for RegSetValueEx at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegSetValueEx.md), [google](http://www.google.com/search?q=RegSetValueEx.md) or [google groups](http://groups.google.com/groups?q=RegSetValueEx.md)\.


## [win32api](win32api.md#win32api)\.RegUnLoadKey

RegUnLoadKey\(key, subKey\)
The RegUnLoadKey function unloads the specified registry key and its subkeys from the registry\. 

The key should have been created by a previous call to [win32api::RegLoadKey](win32api.md#win32apiregloadkey)\.

#### Parameters

  - key : [PyHKEY](PyHKEY.md)/int

    An already open key, or any one of the following win32con constants:
HKEY\_USERS
HKEY\_LOCAL\_MACHINE

  - subKey : string

    The name of the key to unload\. 

This key must be a subkey of the key identified by the key parameter\. 

This value must not be None\.

#### Comments

A call to RegUnLoadKey fails if the calling process does not have the SE\_RESTORE\_PRIVILEGE privilege\. 

If hkey is a handle returned by [win32api::RegConnectRegistry](win32api.md#win32apiregconnectregistry), then the path specified in fileName is relative to the remote computer\.

#### Win32 API References

  - Search for RegUnLoadKey at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegUnLoadKey.md), [google](http://www.google.com/search?q=RegUnLoadKey.md) or [google groups](http://groups.google.com/groups?q=RegUnLoadKey.md)\.


## [win32api](win32api.md#win32api)\.RegisterWindowMessage

RegisterWindowMessage\(msgString\)
The RegisterWindowMessage method, given a string, returns a system wide unique 

message ID, suitable for sending messages between applications who both register the same string\.

#### Parameters

  - msgString : string

    The name of the message to register\. 

All applications that register this message string will get the same message\. 

ID back\.  It will be unique in the system and suitable for applications to 

use to exchange messages\.

#### Comments

Only use RegisterWindowMessage when more than one application must process the 

 same message\. For sending private messages within a window class, an application 

 can use any integer in the range WM\_USER through 0x7FFF\. \(Messages in this range 

 are private to a window class, not to an application\. For example, predefined 

 control classes such as BUTTON, EDIT, LISTBOX, and COMBOBOX may use values in 

 this range\.\)

#### Win32 API References

  - Search for RegisterWindowMessage at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=RegisterWindowMessage.md), [google](http://www.google.com/search?q=RegisterWindowMessage.md) or [google groups](http://groups.google.com/groups?q=RegisterWindowMessage.md)\.


## [win32api](win32api.md#win32api)\.SearchPath

int = SearchPath\(path, fileName

, fileExt

\)
Searches a path for the specified file\.

#### Parameters

  - path : string

    The path to search\.  If None, searches the standard paths\.

  - fileName : string

    The name of the file to search for\.

  - fileExt=None : string

    specifies an extension to be added to the filename when searching for the file\. 

The first character of the filename extension must be a period \(\.\)\. 

The extension is added only if the specified filename does not end with an extension\. 

If a filename extension is not required or if the filename contains an extension, this parameter can be None\.

#### Win32 API References

  - Search for SearchPath at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SearchPath.md), [google](http://www.google.com/search?q=SearchPath.md) or [google groups](http://groups.google.com/groups?q=SearchPath.md)\.

#### Return Value
The return value is a tuple of \(string, int\)\.  string is the full 

path name located\.  int is the offset in the string of the base name 

of the file\.


## [win32api](win32api.md#win32api)\.SendMessage

SendMessage\(hwnd, idMessage, wParam, lParam\)
Send a message to a window\.

#### Parameters

  - hwnd : [PyHANDLE](PyHANDLE.md)

    The hWnd of the window to receive the message\.

  - idMessage : int

    The ID of the message to send\.

  - wParam=None : int/string

    The wParam for the message

  - lParam=None : int/string

    The lParam for the message

#### Win32 API References

  - Search for SendMessage at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SendMessage.md), [google](http://www.google.com/search?q=SendMessage.md) or [google groups](http://groups.google.com/groups?q=SendMessage.md)\.


## [win32api](win32api.md#win32api)\.SetClassLong

int = SetClassLong\(hwnd, offset

, val

\)
Replaces the specified 32 or 64 bit value at the specified offset into the extra class memory for the window\.

#### Parameters

  - hwnd : [PyHANDLE](PyHANDLE.md)

    The handle to the window\.

  - offset : int

    Specifies the zero-based byte offset of the value to change\. Valid values are in the range zero through the number of bytes of extra window memory, minus four \(for example, if 12 or more bytes of extra memory were specified, a value of 8 would be an index to the third long integer\), or one of the GWL\_ constants\.

  - val : int

    Specifies the long value to place in the window's reserved memory\.

#### Comments

This function calls the SetClassLongPtr Api function


## [win32api](win32api.md#win32api)\.SetClassWord

int = SetClassWord\(hwnd, offset

, val

\)

#### Parameters

  - hwnd : int

    The handle to the window\.

  - offset : int

    Specifies the zero-based byte offset of the value to change\. Valid values are in the range zero through the number of bytes of extra window memory, minus four \(for example, if 12 or more bytes of extra memory were specified, a value of 8 would be an index to the third long integer\), or one of the GWL\_ constants\.

  - val : int

    Specifies the long value to place in the window's reserved memory\.

#### Comments

This function is obsolete, use [win32api::SetClassLong](win32api.md#win32apisetclasslong) instead


## [win32api](win32api.md#win32api)\.SetConsoleCtrlHandler

SetConsoleCtrlHandler\(ctrlHandler, bAdd\)
Adds or removes an application-defined HandlerRoutine function from the list of handler functions for the calling process\.

#### Parameters

  - ctrlHandler : callable

    The function to call\.  This function 

should accept one param - the type of signal\.

  - bAdd : int

    True if the handler is being added, false if removed\.

#### Comments

Note that the implementation is a single CtrlHandler in C, which 

keeps a list of the handlers added by this function\.  So although this 

function uses the same semantics as the Win32 function \(ie, last 

registered first called, and first to return True stops the calls\) the 

true order of all Python and C implemented CtrlHandlers may not match 

what would happen if all were implemented in C\. 

This handler must acquire the Python lock before it can call any 

of the registered handlers\.  This means the handler may not be called 

until the current Python thread yields the lock\. 

 

A console process can use the [win32api::GenerateConsoleCtrlEvent](win32api.md#win32apigenerateconsolectrlevent) 

function to send a CTRL\+C or CTRL\+BREAK signal to a console process 

group\. 

The system generates CTRL\_CLOSE\_EVENT, CTRL\_LOGOFF\_EVENT, and 

CTRL\_SHUTDOWN\_EVENT signals when the user closes the console, logs off, 

or shuts down the system so that the process has an opportunity to 

clean up before termination\.

#### Win32 API References

  - Search for SetConsoleCtrlHandler at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SetConsoleCtrlHandler.md), [google](http://www.google.com/search?q=SetConsoleCtrlHandler.md) or [google groups](http://groups.google.com/groups?q=SetConsoleCtrlHandler.md)\.


## [win32api](win32api.md#win32api)\.SetConsoleTitle

SetConsoleTitle\(title\)
Sets the title for the current console\.

#### Parameters

  - title : string

    The new title

#### Win32 API References

  - Search for SetConsoleTitle at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SetConsoleTitle.md), [google](http://www.google.com/search?q=SetConsoleTitle.md) or [google groups](http://groups.google.com/groups?q=SetConsoleTitle.md)\.


## [win32api](win32api.md#win32api)\.SetCursor

[PyHANDLE](PyHANDLE.md) = SetCursor\(hCursor\)
Set the cursor to the HCURSOR object\.

#### Parameters

  - hCursor : [PyHANDLE](PyHANDLE.md)

    The new cursor\. Can be None to remove cursor\.

#### Win32 API References

  - Search for SetCursor at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SetCursor.md), [google](http://www.google.com/search?q=SetCursor.md) or [google groups](http://groups.google.com/groups?q=SetCursor.md)\.

#### Return Value
The result is the previous cursor if there was one\.


## [win32api](win32api.md#win32api)\.SetCursorPos

SetCursorPos\(x,y\)
The SetCursorPos function moves the cursor to the specified screen coordinates\.

#### Parameters

  - x,y : \(int, int\)

    The new position\.

#### Win32 API References

  - Search for SetCursorPos at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SetCursorPos.md), [google](http://www.google.com/search?q=SetCursorPos.md) or [google groups](http://groups.google.com/groups?q=SetCursorPos.md)\.


## [win32api](win32api.md#win32api)\.SetDllDirectory

SetDllDirectory\(PathName\)
Modifies the application-specific DLL search path

#### Parameters

  - PathName : [PyUnicode](PyUnicode.md)

    Directory to be added to search path, can be None to restore defaults

#### Win32 API References

  - Search for SetDllDirectory at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SetDllDirectory.md), [google](http://www.google.com/search?q=SetDllDirectory.md) or [google groups](http://groups.google.com/groups?q=SetDllDirectory.md)\.


## [win32api](win32api.md#win32api)\.SetEnvironmentVariable

SetEnvironmentVariable\(Name, Value\)
Creates, deletes, or changes the value of an environment variable\.

#### Parameters

  - Name : str/unicode

    Name of the environment variable

  - Value : str/unicode

    Value to be set, use None to remove variable

#### Win32 API References

  - Search for SetEnvironmentVariable at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SetEnvironmentVariable.md), [google](http://www.google.com/search?q=SetEnvironmentVariable.md) or [google groups](http://groups.google.com/groups?q=SetEnvironmentVariable.md)\.


## [win32api](win32api.md#win32api)\.SetEnvironmentVariableW

SetEnvironmentVariableW\(Name, Value\)
Creates, deletes, or changes the value of an environment variable\.

#### Parameters

  - Name : str

    Name of the environment variable

  - Value : str

    Value to be set, or None to remove variable

#### Win32 API References

  - Search for SetEnvironmentVariable at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SetEnvironmentVariable.md), [google](http://www.google.com/search?q=SetEnvironmentVariable.md) or [google groups](http://groups.google.com/groups?q=SetEnvironmentVariable.md)\.


## [win32api](win32api.md#win32api)\.SetErrorMode

int = SetErrorMode\(errorMode\)
Controls whether the system will handle the specified types of serious errors, or whether the process will handle them\.

#### Parameters

  - errorMode : int

    A set of bit flags that specify the process error mode

#### Win32 API References

  - Search for SetErrorMode at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SetErrorMode.md), [google](http://www.google.com/search?q=SetErrorMode.md) or [google groups](http://groups.google.com/groups?q=SetErrorMode.md)\.

#### Return Value
The result is an integer containing the old error flags\.


## [win32api](win32api.md#win32api)\.SetFileAttributes

int = SetFileAttributes\(pathName, attrs

\)
Sets the named file's attributes\.

#### Parameters

  - pathName : string

    The name of the file\.

  - attrs : int

    The attributes to set\.  Must be a combination of the win32con\.FILE\_ATTRIBUTE\_\* constants\.


## [win32api](win32api.md#win32api)\.SetHandleInformation

SetHandleInformation\(Object, Mask, Flags\)
Sets a handles's flags

#### Parameters

  - Object : [PyHANDLE](PyHANDLE.md)

    Handle to an object

  - Mask : int

    Bitmask specifying which flags should be set

  - Flags : int

    Bitmask of flag values to be set\. Valid Flags are HANDLE\_FLAG\_INHERIT, HANDLE\_FLAG\_PROTECT\_FROM\_CLOSE

#### Comments

Not available on Win98/Me


## [win32api](win32api.md#win32api)\.SetLastError

int = SetLastError\(\)
Sets the calling thread's last error code value\.

#### Win32 API References

  - Search for SetLastError at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SetLastError.md), [google](http://www.google.com/search?q=SetLastError.md) or [google groups](http://groups.google.com/groups?q=SetLastError.md)\.


## [win32api](win32api.md#win32api)\.SetLocalTime

SetLocalTime\(SystemTime\)
Changes the system's local time

#### Parameters

  - SystemTime : [PyTime](PyTime.md)

    The local time to be set\.  Can also be a time tuple\.


## [win32api](win32api.md#win32api)\.SetStdHandle

SetStdHandle\(handle, handle\)
Set the handle for the standard input, standard output, or standard error device

#### Parameters

  - handle : int

    input, output, or error device

  - handle : [PyHANDLE](PyHANDLE.md)/int

    A previously opened handle to be a standard handle


## [win32api](win32api.md#win32api)\.SetSysColors

SetSysColors\(Elements, RgbValues\)
Changes color of various window elements

#### Parameters

  - Elements : tuple

    A tuple of ints, COLOR\_\* constants indicating which window element to change

  - RgbValues : tuple

    An equal length tuple of ints representing RGB values \(see [win32api::RGB](win32api.md#win32apirgb)\)


## [win32api](win32api.md#win32api)\.SetSystemFileCacheSize

SetSystemFileCacheSize\(MinimumFileCacheSize, MaximumFileCacheSize, Flags\)
Sets the amount of memory reserved for file cache

#### Parameters

  - MinimumFileCacheSize : long

    Minimum size in bytes\.

  - MaximumFileCacheSize : long

    Maximum size in bytes\.

  - Flags=0 : int

    Combination of win32con\.MM\_WORKING\_SET\_\* flags

#### Comments

Requires SE\_INCREASE\_QUOTA\_NAME priv

Pass -1 for both min and max to flush file cache\.

Accepts keyword args\.


## [win32api](win32api.md#win32api)\.SetSystemPowerState

SetSystemPowerState\(Suspend, Force\)
Initiates low power mode to make system sleep or hibernate

#### Parameters

  - Suspend : boolean

    True - system is suspended\. False - initiates hibernation\.

  - Force : boolean

    True - power state occurs unconditionally\. False - applications are queried for permission\.

#### Comments

Requires Win2k or later\.

SE\_SHUTDOWN\_NAME privilege must be enabled\.

#### Win32 API References

  - Search for SetSystemPowerState at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SetSystemPowerState.md), [google](http://www.google.com/search?q=SetSystemPowerState.md) or [google groups](http://groups.google.com/groups?q=SetSystemPowerState.md)\.


## [win32api](win32api.md#win32api)\.SetSystemTime

int = SetSystemTime\(year, month

, dayOfWeek

, day

, hour

, minute

, second

, millseconds

\)
Returns the current system time

#### Parameters

  - year : int

    

  - month : int

    

  - dayOfWeek : int

    

  - day : int

    

  - hour : int

    

  - minute : int

    

  - second : int

    

  - millseconds : int

    


## [win32api](win32api.md#win32api)\.SetThreadLocale

SetThreadLocale\(lcid\)
Sets the current thread's locale\.

#### Parameters

  - lcid : int

    The new LCID


## [win32api](win32api.md#win32api)\.SetTimeZoneInformation

tuple = SetTimeZoneInformation\(tzi\)
Sets the system time-zone information\.

#### Parameters

  - tzi : tuple

    A tuple with the timezone info

#### Comments

The tuple is of form:

#### Items

  - \[0\] int : Bias

    

  - \[1\] string : StandardName

    

  - \[2\] SYSTEMTIME tuple : StandardDate

    

  - \[3\] int : StandardBias

    

  - \[4\] string : DaylightName

    

  - \[5\] SYSTEMTIME tuple : DaylightDate

    

  - \[6\] int : DaylightBias

    


## [win32api](win32api.md#win32api)\.SetWindowLong

int = SetWindowLong\(hwnd, offset

, val

\)
Places a long value at the specified offset into the extra window memory of the given window\.

#### Parameters

  - hwnd : int

    The handle to the window\.

  - offset : int

    Specifies the zero-based byte offset of the value to change\. Valid values are in the range zero through the number of bytes of extra window memory, minus four \(for example, if 12 or more bytes of extra memory were specified, a value of 8 would be an index to the third long integer\), or one of the GWL\_ constants\.

  - val : int

    Specifies the long value to place in the window's reserved memory\.

#### Comments

This function calls the SetWindowLongPtr Api function


## [win32api](win32api.md#win32api)\.SetWindowWord

int = SetWindowWord\(hwnd, offset

, val

\)

#### Parameters

  - hwnd : [PyHANDLE](PyHANDLE.md)

    The handle to the window\.

  - offset : int

    Specifies the zero-based byte offset of the value to change\. Valid values are in the range zero through the number of bytes of extra window memory, minus four \(for example, if 12 or more bytes of extra memory were specified, a value of 8 would be an index to the third long integer\), or one of the GWL\_ constants\.

  - val : int

    Specifies the long value to place in the window's reserved memory\.

#### Comments

This function is obsolete, use [win32api::SetWindowLong](win32api.md#win32apisetwindowlong) instead


## [win32api](win32api.md#win32api)\.ShellExecute

int = ShellExecute\(hwnd, op

, file

, params

, dir

, bShow

\)
Opens or prints a file\.

#### Parameters

  - hwnd : [PyHANDLE](PyHANDLE.md)

    The handle of the parent window, or 0 for no parent\.  This window receives any message boxes an application produces \(for example, for error reporting\)\.

  - op : string

    The operation to perform\.  May be "open", "print", or None, which defaults to "open"\.

  - file : string

    The name of the file to open\.

  - params : string

    The parameters to pass, if the file name contains an executable\.  Should be None for a document file\.

  - dir : string

    The initial directory for the application\.

  - bShow : int

    Specifies whether the application is shown when it is opened\. If the lpszFile parameter specifies a document file, this parameter is zero\.

#### Win32 API References

  - Search for ShellExecute at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=ShellExecute.md), [google](http://www.google.com/search?q=ShellExecute.md) or [google groups](http://groups.google.com/groups?q=ShellExecute.md)\.

#### Return Value
The instance handle of the application that was run\. \(This handle could also be the handle of a dynamic data exchange \[DDE\] server application\.\) 

If there is an error, the method raises an exception\.


## [win32api](win32api.md#win32api)\.ShowCursor

int = ShowCursor\(show\)
The ShowCursor method displays or hides the cursor\.

#### Parameters

  - show : int

    Visiblilty flag

#### Comments

This function sets an internal display counter that 

determines whether the cursor should be displayed\. The 

cursor is displayed only if the display count is greater 

than or equal to 0\. If a mouse is installed, the initial display 

count is 0\. If no mouse is installed, the display count is -1\.

#### Win32 API References

  - Search for ShowCursor at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=ShowCursor.md), [google](http://www.google.com/search?q=ShowCursor.md) or [google groups](http://groups.google.com/groups?q=ShowCursor.md)\.

#### Return Value
The return value specifies the new display counter


## [win32api](win32api.md#win32api)\.Sleep

int = Sleep\(time, bAlterable

\)
Suspends execution of the current thread for the specified time\.

#### Parameters

  - time : int

    The number of milli-seconds to sleep for,

  - bAlterable=0 : int

    Specifies whether the function may terminate early due to an I/O completion callback function\.

#### Win32 API References

  - Search for Sleep at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=Sleep.md), [google](http://www.google.com/search?q=Sleep.md) or [google groups](http://groups.google.com/groups?q=Sleep.md)\.

  - Search for SleepEx at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=SleepEx.md), [google](http://www.google.com/search?q=SleepEx.md) or [google groups](http://groups.google.com/groups?q=SleepEx.md)\.

#### Return Value
The return value is zero if the specified time interval expired\.


## [win32api](win32api.md#win32api)\.TerminateProcess

TerminateProcess\(handle, exitCode\)
Kills a process

#### Parameters

  - handle : [PyHANDLE](PyHANDLE.md)

    The handle of the process to terminate\.

  - exitCode : int

    The exit code for the process\.

#### Comments

See also [win32api::OpenProcess](win32api.md#win32apiopenprocess)


## [win32api](win32api.md#win32api)\.ToAsciiEx

bytes = ToAsciiEx\(vk, scancode

, keyboardstate

, flags

, hlayout

\)
Translates the specified virtual-key code and keyboard state to the corresponding character or characters\.

#### Parameters

  - vk : int

    The virtual key code\.

  - scancode : int

    The scan code\.

  - keyboardstate : bytes

    A string of exactly 256 characters\.

  - flags=0 : int

    

  - hlayout=None : handle

    The keyboard layout to use


## [win32api](win32api.md#win32api)\.Unicode

[PyUnicode](PyUnicode.md) = Unicode\(\)
Creates a new Unicode object


## [win32api](win32api.md#win32api)\.UpdateResource

UpdateResource\(handle, type, name, data, language\)
Updates a resource in a PE file\.

#### Parameters

  - handle : [PyHANDLE](PyHANDLE.md)

    The update-file handle\.

  - type : [PyResourceId](PyResourceId.md)

    The type of resource to update

  - name : [PyResourceId](PyResourceId.md)

    The id/name of the resource to update

  - data : string

    The data to place into the resource\.

  - language=NEUTRAL : int

    Language to use, defaults to LANG\_NEUTRAL\.


## [win32api](win32api.md#win32api)\.VkKeyScan

int = VkKeyScan\(char, char

\)
Translates a character to the corresponding virtual-key code and shift state\.

#### Parameters

  - char : string or unicode

    A byte or unicode string of length 1\.  If a byte string is passed 

VkKeyScanA will be called, otherwise VkKeyScanW will be called\.

  - char : chr

    Specifies a character

#### Win32 API References

  - Search for VkKeyScanA at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=VkKeyScanA.md), [google](http://www.google.com/search?q=VkKeyScanA.md) or [google groups](http://groups.google.com/groups?q=VkKeyScanA.md)\.

  - Search for VkKeyScanW at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=VkKeyScanW.md), [google](http://www.google.com/search?q=VkKeyScanW.md) or [google groups](http://groups.google.com/groups?q=VkKeyScanW.md)\.


## [win32api](win32api.md#win32api)\.VkKeyScanEx

int = VkKeyScanEx\(char, hkl

\)
Translates a character to the corresponding virtual-key code and shift state\.

#### Parameters

  - char : string or unicode

    A byte or unicode string of length 1\.  If a byte string is passed 

VkKeyScanExA will be called, otherwise VkKeyScanExW will be called\.

  - hkl : [PyHANDLE](PyHANDLE.md)

    Handle to a keyboard layout at returned by [win32api::LoadKeyboardLayout](win32api.md#win32apiloadkeyboardlayout)

#### Win32 API References

  - Search for VkKeyScanExA at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=VkKeyScanExA.md), [google](http://www.google.com/search?q=VkKeyScanExA.md) or [google groups](http://groups.google.com/groups?q=VkKeyScanExA.md)\.

  - Search for VkKeyScanExW at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=VkKeyScanExW.md), [google](http://www.google.com/search?q=VkKeyScanExW.md) or [google groups](http://groups.google.com/groups?q=VkKeyScanExW.md)\.


## [win32api](win32api.md#win32api)\.WinExec

WinExec\(cmdLine, show\)
Runs the specified application\.

#### Parameters

  - cmdLine : string

    The command line to execute\.

  - show=win32con\.SW\_SHOWNORMAL : int

    The initial state of the applications window\.

#### Win32 API References

  - Search for WinExec at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=WinExec.md), [google](http://www.google.com/search?q=WinExec.md) or [google groups](http://groups.google.com/groups?q=WinExec.md)\.


## [win32api](win32api.md#win32api)\.WinHelp

WinHelp\(hwnd, hlpFile, cmd, data\)
Invokes the Windows Help system\.

#### Parameters

  - hwnd : int

    The handle of the window requesting help\.

  - hlpFile : string

    The name of the help file\.

  - cmd : int

    The type of help\.  See the api for full details\.

  - data=0 : int/string

    Additional data specific to the help call\.

#### Win32 API References

  - Search for WinHelp at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=WinHelp.md), [google](http://www.google.com/search?q=WinHelp.md) or [google groups](http://groups.google.com/groups?q=WinHelp.md)\.

#### Return Value
The method raises an exception if an error occurs\.


## [win32api](win32api.md#win32api)\.WriteProfileSection

list = WriteProfileSection\(section, data

, iniName

\)
Writes a complete section to an INI file or registry\.

#### Parameters

  - section : string

    The section in the INI file to be written\.

  - data : string

    The data to write\.  Can be None to delete the section\.  Otherwise, must be string, 

with each entry terminated with '\\\\0', followed by another terminating '\\\\0'

  - iniName=None : string

    Name of INI file\.  If specified, WritePrivateProfileSection will be called\.

#### Comments

This function is obsolete, applications should use the registry instead\.

#### Win32 API References

  - Search for WriteProfileSection at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=WriteProfileSection.md), [google](http://www.google.com/search?q=WriteProfileSection.md) or [google groups](http://groups.google.com/groups?q=WriteProfileSection.md)\.

  - Search for WritePrivateProfileSection at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=WritePrivateProfileSection.md), [google](http://www.google.com/search?q=WritePrivateProfileSection.md) or [google groups](http://groups.google.com/groups?q=WritePrivateProfileSection.md)\.


## [win32api](win32api.md#win32api)\.WriteProfileVal

WriteProfileVal\(section, entry, value, iniName\)
Writes a value to a Windows INI file\.

#### Parameters

  - section : string

    The section in the INI file to write to\.

  - entry : string

    The entry within the section in the INI file to write to\.

  - value : int/string

    The value to write\.

  - iniName=None : string

    The name of the INI file\.  If None, the system INI file is used\.

#### Comments

This function is obsolete, applications should use the registry instead\.

#### Win32 API References

  - Search for WritePrivateProfileString at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=WritePrivateProfileString.md), [google](http://www.google.com/search?q=WritePrivateProfileString.md) or [google groups](http://groups.google.com/groups?q=WritePrivateProfileString.md)\.

  - Search for WriteProfileString at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=WriteProfileString.md), [google](http://www.google.com/search?q=WriteProfileString.md) or [google groups](http://groups.google.com/groups?q=WriteProfileString.md)\.


## [win32api](win32api.md#win32api)\.keybd\_event

keybd\_event\(bVk, bScan, dwFlags, dwExtraInfo\)
Simulate a keyboard event

#### Parameters

  - bVk : BYTE

    Virtual-key code

  - bScan : BYTE

    Hardware scan code

  - dwFlags=0 : DWORD

    Flags specifying various function options

  - dwExtraInfo=0 : DWORD

    Additional data associated with keystroke

#### Win32 API References

  - Search for keybd\_event at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=keybd.md#http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=keybdevent), [google](http://www.google.com/search?q=keybd.md#http://www.google.com/search?q=keybdevent) or [google groups](http://groups.google.com/groups?q=keybd.md#http://groups.google.com/groups?q=keybdevent)\.


## [win32api](win32api.md#win32api)\.mouse\_event

mouse\_event\(dwFlags, dx, dy, dwData, dwExtraInfo\)
Simulate a mouse event

#### Parameters

  - dwFlags=0 : DWORD

    Flags specifying various function options

  - dx : DWORD

    Horizontal position of mouse

  - dy : DWORD

    Vertical position of mouse

  - dwData : DWORD

    Flag specific parameter

  - dwExtraInfo=0 : DWORD

    Additional data associated with mouse event

#### Win32 API References

  - Search for mouse\_event at [msdn](http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=mouse.md#http://search.msdn.microsoft.com/search/results.aspx?view=msdn&query=mouseevent), [google](http://www.google.com/search?q=mouse.md#http://www.google.com/search?q=mouseevent) or [google groups](http://groups.google.com/groups?q=mouse.md#http://groups.google.com/groups?q=mouseevent)\.