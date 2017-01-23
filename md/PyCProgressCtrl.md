# PyCProgressCtrl


## PyCProgressCtrl Object

A windows progress bar control\.  Encapsulates an MFC CProgressCtrl

 class\.  Derived from [PyCControl](PyCControl.md)\.

#### Methods

  - [CreateWindow](PyCProgressCtrl.md#pycprogressctrlcreatewindow)

    Creates the window for a new progress bar object\.&nbsp;

  - [SetRange](PyCProgressCtrl.md#pycprogressctrlsetrange)

    Sets the lower and upper bounds for the progress bar\.&nbsp;

  - [SetPos](PyCProgressCtrl.md#pycprogressctrlsetpos)

    Set the control's position&nbsp;

  - [OffsetPos](PyCProgressCtrl.md#pycprogressctrloffsetpos)

    Advances the progress bar control's current position by the increment specified\.&nbsp;

  - [SetStep](PyCProgressCtrl.md#pycprogressctrlsetstep)

    Specifies the step increment for a progress bar control\.&nbsp;

  - [StepIt](PyCProgressCtrl.md#pycprogressctrlstepit)

    Advances the current position for a progress bar control by the step increment\. Returns previous position\.&nbsp;


## [PyCProgressCtrl](PyCProgressCtrl.md#pycprogressctrl)\.CreateWindow

CreateWindow\(style, rect, parent, id\)
Creates the actual control\.

#### Parameters

  - style : int

    The style for the control\.

  - rect : \(left, top, right, bottom\)

    The size and position of the control\.

  - parent : [PyCWnd](PyCWnd.md)

    The parent window of the control\.  Usually a [PyCDialog](PyCDialog.md)\.

  - id : int

    The control's ID\.


## [PyCProgressCtrl](PyCProgressCtrl.md#pycprogressctrl)\.OffsetPos

int = OffsetPos\(nPos\)
Advances the progress bar control's current position by the increment specified

#### Parameters

  - nPos=1 : int

    Amount to advance the position\.


## [PyCProgressCtrl](PyCProgressCtrl.md#pycprogressctrl)\.SetPos

int = SetPos\(nPos\)
Set the control's position

#### Parameters

  - nPos=1 : int

    New position of the progress bar control\.


## [PyCProgressCtrl](PyCProgressCtrl.md#pycprogressctrl)\.SetRange

SetRange\(nLower, nUpper\)
Set the control's bounds

#### Parameters

  - nLower=1 : int

    Specifies the lower limit of the range \(default is zero\)\.

  - nUpper=1 : int

    Specifies the upper limit of the range \(default is 100\)\.


## [PyCProgressCtrl](PyCProgressCtrl.md#pycprogressctrl)\.SetStep

int = SetStep\(nStep\)
Specifies the step increment for a progress bar control\.

#### Parameters

  - nStep=1 : int

    New step increment\.


## [PyCProgressCtrl](PyCProgressCtrl.md#pycprogressctrl)\.StepIt

int = StepIt\(\)
Advances the current position for a progress bar control by the step increment\. Returns previous position\.