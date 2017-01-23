# PyHDESK


## PyHDESK Object

Object representing a handle to a desktop, created by 

[win32service::CreateDesktop](win32service.md#win32servicecreatedesktop), [win32service::GetThreadDesktop](win32service.md#win32servicegetthreaddesktop) and [win32service::OpenDesktop](win32service.md#win32serviceopendesktop)\.

#### Methods

  - [SetThreadDesktop](PyHDESK.md#pyhdesksetthreaddesktop)

    Assigns desktop to calling thread&nbsp;

  - [EnumDesktopWindows](PyHDESK.md#pyhdeskenumdesktopwindows)

    Lists all top-level windows on the desktop&nbsp;

  - [SwitchDesktop](PyHDESK.md#pyhdeskswitchdesktop)

    Activates the desktop&nbsp;

  - [CloseDesktop](PyHDESK.md#pyhdeskclosedesktop)

    Closes the desktop handle&nbsp;

  - [Detach](PyHDESK.md#pyhdeskdetach)

    Releases reference to handle without closing it&nbsp;


## [PyHDESK](PyHDESK.md#pyhdesk)\.CloseDesktop

CloseDesktop\(\)
Closes the desktop handle


## [PyHDESK](PyHDESK.md#pyhdesk)\.EnumDesktopWindows

\([PyHANDLE](PyHANDLE.md),\.\.\.\) = EnumDesktopWindows\(\)
Returns a list of handles to all top-level windows on desktop


## [PyHDESK](PyHDESK.md#pyhdesk)\.SetThreadDesktop

SetThreadDesktop\(\)
Assigns this desktop to the calling thread


## [PyHDESK](PyHDESK.md#pyhdesk)\.SwitchDesktop

SwitchDesktop\(\)
Activates the desktop