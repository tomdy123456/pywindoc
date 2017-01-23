# PyIConnectionPoint


## PyIConnectionPoint Object

A Python wrapper of a COM IConnectionPoint interface\.

#### Methods

  - [GetConnectionInterface](PyIConnectionPoint.md#pyiconnectionpointgetconnectioninterface)

    Retrieves the IID of the interface represented by the connection point\.&nbsp;

  - [GetConnectionPointContainer](PyIConnectionPoint.md#pyiconnectionpointgetconnectionpointcontainer)

    Gets the connection point container for the object\.&nbsp;

  - [Advise](PyIConnectionPoint.md#pyiconnectionpointadvise)

    Establishes a connection between the connection point object and the client's sink\.&nbsp;

  - [Unadvise](PyIConnectionPoint.md#pyiconnectionpointunadvise)

    Terminates an advisory connection previously established through [PyIConnectionPoint::Advise](PyIConnectionPoint.md#pyiconnectionpointadvise)\.&nbsp;

  - [EnumConnections](PyIConnectionPoint.md#pyiconnectionpointenumconnections)

    Creates an enumerator to iterate through the connections for the connection point&nbsp;




## [PyIConnectionPoint](PyIConnectionPoint.md#pyiconnectionpoint)\.Advise

int = Advise\(unk\)
Establishes a connection between the connection point object and the client's sink\.

#### Parameters

  - unk : [PyIUnknown](PyIUnknown.md)

    The client's advise sink

#### Return Value
The result is the connection point identifier used by [PyIConnectionPoint::Unadvise](PyIConnectionPoint.md#pyiconnectionpointunadvise)


## [PyIConnectionPoint](PyIConnectionPoint.md#pyiconnectionpoint)\.EnumConnections

[PyIEnumConnections](PyIEnumConnections.md) = EnumConnections\(\)
Creates an enumerator to iterate through the connections for the connection point


## [PyIConnectionPoint](PyIConnectionPoint.md#pyiconnectionpoint)\.GetConnectionInterface

[PyIID](PyIID.md) = GetConnectionInterface\(\)
Retrieves the IID of the interface represented by the connection point\.


## [PyIConnectionPoint](PyIConnectionPoint.md#pyiconnectionpoint)\.GetConnectionPointContainer

[PyIConnectionPointContainer](PyIConnectionPointContainer.md) = GetConnectionPointContainer\(\)
Gets the connection point container for the object\.


## [PyIConnectionPoint](PyIConnectionPoint.md#pyiconnectionpoint)\.Unadvise

Unadvise\(cookie\)
Terminates an advisory connection previously established through IConnectionPoint::Advise\. The dwCookie parameter identifies the connection to terminate\.

#### Parameters

  - cookie : int

    The connection token