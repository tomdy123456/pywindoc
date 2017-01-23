# PyIPersistPropertyBag


## PyIPersistPropertyBag Object

A Python wrapper for a COM IPersistPropertyBag interface\.

#### Methods

  - [InitNew](PyIPersistPropertyBag.md#pyipersistpropertybaginitnew)

    Called by the container when the control is initialized to initialize the property bag\.&nbsp;

  - [Load](PyIPersistPropertyBag.md#pyipersistpropertybagload)

    Called by the container to load the control's properties\.&nbsp;

  - [Save](PyIPersistPropertyBag.md#pyipersistpropertybagsave)

    Called by the container to save the object's properties\.&nbsp;




## [PyIPersistPropertyBag](PyIPersistPropertyBag.md#pyipersistpropertybag)\.InitNew

InitNew\(\)
Called by the container when the control is initialized to initialize the property bag\.


## [PyIPersistPropertyBag](PyIPersistPropertyBag.md#pyipersistpropertybag)\.Load

Load\(bag, log\)
Called by the container to load the control's properties\.

#### Parameters

  - bag : [PyIPropertyBag](PyIPropertyBag.md)

    the caller's property bag\.

  - log=None : [PyIErrorLog](PyIErrorLog.md)

    the caller's error log, or None


## [PyIPersistPropertyBag](PyIPersistPropertyBag.md#pyipersistpropertybag)\.Save

Save\(bag, clearDirty, saveProperties\)
Called by the container to save the object's properties\.

#### Parameters

  - bag : [PyIPropertyBag](PyIPropertyBag.md)

    the caller's property bag\.

  - clearDirty : int

    Specifies whether to clear the dirty flag\.

  - saveProperties : int

    Specifies whether to save all properties or just those that have changed