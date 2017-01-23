# PyIPersistFile


## PyIPersistFile Object

Description of the interface

#### Methods

  - [IsDirty](PyIPersistFile.md#pyipersistfileisdirty)

    Checks an object for changes since it was last saved to its current file\.&nbsp;

  - [Load](PyIPersistFile.md#pyipersistfileload)

    Opens the specified file and initializes an object from the file contents\.&nbsp;

  - [Save](PyIPersistFile.md#pyipersistfilesave)

    Saves the object into the specified file\.&nbsp;

  - [SaveCompleted](PyIPersistFile.md#pyipersistfilesavecompleted)

    Notifies the object that it can revert from NoScribble mode to Normal mode\.&nbsp;

  - [GetCurFile](PyIPersistFile.md#pyipersistfilegetcurfile)

    Gets the current name of the file associated with the object\.&nbsp;


## [PyIPersistFile](PyIPersistFile.md#pyipersistfile)\.GetCurFile

str = GetCurFile\(\)
Gets the current name of the file associated with the object\.


## [PyIPersistFile](PyIPersistFile.md#pyipersistfile)\.IsDirty

IsDirty\(\)
Checks an object for changes since it was last saved to its current file\.

#### Return Value
This method returns the raw COM error code without raising the normal COM exception\. 

You should treat any error return codes as an indication that the object has changed\. 

Unless this method explicitly returns S\_FALSE, assume that the object must be saved\.


## [PyIPersistFile](PyIPersistFile.md#pyipersistfile)\.Load

Load\(FileName, Mode\)
Opens the specified file and initializes an object from the file contents\.

#### Parameters

  - FileName : str

    Absolute path of the file to open

  - Mode=STGM\_READ : int

    Specifies the access mode from the STGM enumeration\.


## [PyIPersistFile](PyIPersistFile.md#pyipersistfile)\.Save

Save\(FileName, fRemember\)
Saves the object into the specified file\.

#### Parameters

  - FileName : str

    absolute path of the file where the object is saved\.

  - fRemember : int

    Specifies whether the file is to be the current working file or not\.


## [PyIPersistFile](PyIPersistFile.md#pyipersistfile)\.SaveCompleted

SaveCompleted\(FileName\)
Notifies the object that it can revert from NoScribble mode to Normal mode\.

#### Parameters

  - FileName : str

    Absolute path of the file where the object was saved\.