# PyCRichEditView


## PyCRichEditView Object

A class which implementes a CRichEditView\.  Derived from PyCRichEditView and [PyCRichEditCtrl](PyCRichEditCtrl.md)\.

#### Methods

  - [GetRichEditCtrl](PyCRichEditView.md#pycricheditviewgetricheditctrl)

    Returns the underlying rich edit control object\.&nbsp;

  - [SetWordWrap](PyCRichEditView.md#pycricheditviewsetwordwrap)

    Sets the wordwrap state for the control\.&nbsp;

  - [WrapChanged](PyCRichEditView.md#pycricheditviewwrapchanged)

    Calls the underlying WrapChanged method\.&nbsp;

  - [SaveTextFile](PyCRichEditView.md#pycricheditviewsavetextfile)

    Saves the control to a text file&nbsp;


## [PyCRichEditView](PyCRichEditView.md#pycricheditview)\.GetRichEditCtrl

[PyCRichEditCtrl](PyCRichEditCtrl.md) = GetRichEditCtrl\(\)
Returns the underlying rich edit control object\.


## [PyCRichEditView](PyCRichEditView.md#pycricheditview)\.SaveTextFile

None = SaveTextFile\(FileName\)
Saves the contents of the control as a test file

#### Parameters

  - FileName : str

    Name of file to save

#### Comments

Theere is no equivilent MFC method\.  This is implemented in this module for performance reasons\.


## [PyCRichEditView](PyCRichEditView.md#pycricheditview)\.SetWordWrap

None = SetWordWrap\(wordWrap\)
Sets the wordwrap state for the control\.

#### Parameters

  - wordWrap : int

    The new word-wrap state\.

#### MFC References

  - CRichEditCtrl::m\_nWordWrap


## [PyCRichEditView](PyCRichEditView.md#pycricheditview)\.WrapChanged

None = WrapChanged\(\)
Calls the underlying WrapChanged method\.

#### MFC References

  - CRichEditCtrl::WrapChanged