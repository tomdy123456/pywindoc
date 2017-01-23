# PyCCmdUI


## PyCCmdUI Object

A class for manipulating user-interface elements\.  Encapsulates an MFC CCmdUI

 class

#### Methods

  - [Enable](PyCCmdUI.md#pyccmduienable)

    Enables or disables the user-interface item for this command\.&nbsp;

  - [SetCheck](PyCCmdUI.md#pyccmduisetcheck)

    Sets the check state of the user-interface item for this command\.&nbsp;

  - [SetRadio](PyCCmdUI.md#pyccmduisetradio)

    Like the SetCheck member function, but operates on radio groups\.&nbsp;

  - [SetText](PyCCmdUI.md#pyccmduisettext)

    Sets the text for the user-interface item for this command\.&nbsp;

  - [ContinueRouting](PyCCmdUI.md#pyccmduicontinuerouting)

    Tells the command-routing mechanism to continue routing the current message down the chain of handlers\.&nbsp;

#### Properties

  - int m\_nIndex

    

  - int m\_nID

    

  - [PyCMenu](PyCMenu.md) m\_pMenu

    

  - [PyCMenu](PyCMenu.md) m\_pSubMenu

    


## [PyCCmdUI](PyCCmdUI.md#pyccmdui)\.ContinueRouting

ContinueRouting\(\)
Tells the command-routing mechanism to continue routing the current message down the chain of handlers\.


## [PyCCmdUI](PyCCmdUI.md#pyccmdui)\.Enable

Enable\(bEnable\)
Enables or disables the user-interface item for this command\.

#### Parameters

  - bEnable=1 : int

    TRUE if the item should be enabled, false otherwise\.


## [PyCCmdUI](PyCCmdUI.md#pyccmdui)\.SetCheck

SetCheck\(state\)
Sets the check state of the user-interface item for this command\.

#### Parameters

  - state=1 : int

    0 for unchecked, 1 for checked, or 2 for indeterminate\.


## [PyCCmdUI](PyCCmdUI.md#pyccmdui)\.SetRadio

SetRadio\(bOn\)
Like the SetCheck member function, but operates on radio groups\.

#### Parameters

  - bOn=1 : int

    TRUE if the item should be enabled, false otherwise\.


## [PyCCmdUI](PyCCmdUI.md#pyccmdui)\.SetText

SetText\(text\)
Sets the text for the user-interface item for this command\.

#### Parameters

  - text : string

    The text for the interface element\.