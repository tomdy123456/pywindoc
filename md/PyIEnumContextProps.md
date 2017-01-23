# PyIEnumContextProps


## PyIEnumContextProps Object

A Python interface to IEnumContextProps

#### Methods

  - [Next](PyIEnumContextProps.md#pyienumcontextpropsnext)

    Retrieves a specified number of items in the enumeration sequence\.&nbsp;

  - [Skip](PyIEnumContextProps.md#pyienumcontextpropsskip)

    Skips over the next specified elementes\.&nbsp;

  - [Reset](PyIEnumContextProps.md#pyienumcontextpropsreset)

    Resets the enumeration sequence to the beginning\.&nbsp;

  - [Clone](PyIEnumContextProps.md#pyienumcontextpropsclone)

    Creates another enumerator that contains the same enumeration state as the current one\.&nbsp;


## [PyIEnumContextProps](PyIEnumContextProps.md#pyienumcontextprops)\.Clone

[PyIEnumContextProps](PyIEnumContextProps.md#pyienumcontextprops) = Clone\(\)
Creates another enumerator that contains the same enumeration state as the current one


## [PyIEnumContextProps](PyIEnumContextProps.md#pyienumcontextprops)\.Next

\(\([PyIID](PyIID.md), int, [PyIUnknown](PyIUnknown.md)\), \.\.\.\) = Next\(num\)
Retrieves a specified number of items in the enumeration sequence\.

#### Parameters

  - num=1 : int

    Number of items to retrieve\.

#### Return Value
Returns a tuple of 3-tuples representing ContextProperty structs: 

 First item is GUID identifying the property, second is Flags \(reserved\), third is the interface set as the property value


## [PyIEnumContextProps](PyIEnumContextProps.md#pyienumcontextprops)\.Reset

Reset\(\)
Resets the enumeration sequence to the beginning\.


## [PyIEnumContextProps](PyIEnumContextProps.md#pyienumcontextprops)\.Skip

Skip\(\)
Skips over the next specified elementes\.