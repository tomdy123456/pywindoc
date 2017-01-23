# PyIMAPIContainer


## PyIMAPIContainer Object

An COM interface to MAPI's IMAPIContainer interface\. 

Derived from [PyIMAPIProp](PyIMAPIProp.md)

#### Methods

  - [OpenEntry](PyIMAPIContainer.md#pyimapicontaineropenentry)

    Opens an object and returns an interface object for further access\.&nbsp;

  - [GetContentsTable](PyIMAPIContainer.md#pyimapicontainergetcontentstable)

    Returns an object representing the container's contents table\.&nbsp;

  - [GetHierarchyTable](PyIMAPIContainer.md#pyimapicontainergethierarchytable)

    Returns an object representing the container's hierarchy table\.&nbsp;


## [PyIMAPIContainer](PyIMAPIContainer.md#pyimapicontainer)\.GetContentsTable

[PyIMAPITable](PyIMAPITable.md) = GetContentsTable\(flags\)
Returns an object representing the container's contents table\.

#### Parameters

  - flags : int

    The flags to use\.


## [PyIMAPIContainer](PyIMAPIContainer.md#pyimapicontainer)\.GetHierarchyTable

[PyIMAPITable](PyIMAPITable.md) = GetHierarchyTable\(flags\)
Returns an object representing the container's hierarchy table\.

#### Parameters

  - flags : int

    The flags to use\.


## [PyIMAPIContainer](PyIMAPIContainer.md#pyimapicontainer)\.OpenEntry

PyIInterface

 = OpenEntry\(entryId, iid

, flags

\)
Opens an object and returns an interface object for further access\.

#### Parameters

  - entryId : string

    The EntryID to open\.

  - iid : [PyIID](PyIID.md)

    The IID of the returned interface, or None for the default interface\.

  - flags : int

    Flags for the call\.  May include MAPI\_BEST\_ACCESS, MAPI\_DEFERRED\_ERRORS, MAPI\_MODIFY and possibly others \(see the MAPI documentation\)