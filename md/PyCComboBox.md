# PyCComboBox


## PyCComboBox Object

A windows combo control\.  Encapsulates an MFC CComboBox

 class\.  Derived from a [PyCControl](PyCControl.md) object\.

#### Methods

  - [AddString](PyCComboBox.md#pyccomboboxaddstring)

    Add a string to the listbox portion of a combo box\.&nbsp;

  - [DeleteString](PyCComboBox.md#pyccomboboxdeletestring)

    Delete a string to the listbox portion of a combo box\.&nbsp;

  - [Dir](PyCComboBox.md#pyccomboboxdir)

    Fill the listbox portion of a combo with a file specification\.&nbsp;

  - [GetCount](PyCComboBox.md#pyccomboboxgetcount)

    Get the count of items in the listbox portion of a combo box\.&nbsp;

  - [GetCurSel](PyCComboBox.md#pyccomboboxgetcursel)

    Get the current selection in the listbox portion of a combo box\.&nbsp;

  - [GetEditSel](PyCComboBox.md#pyccomboboxgeteditsel)

    Gets the edit control selection from a combo box\.&nbsp;

  - [GetExtendedUI](PyCComboBox.md#pyccomboboxgetextendedui)

    Gets the ExtendedUI flag for a combo box\.&nbsp;

  - [GetItemData](PyCComboBox.md#pyccomboboxgetitemdata)

    Retrieves the application-specific object associated with a combobox entry&nbsp;

  - [GetItemValue](PyCComboBox.md#pyccomboboxgetitemvalue)

    Retrieves the application-specific value associated with a combobox entry&nbsp;

  - [GetLBText](PyCComboBox.md#pyccomboboxgetlbtext)

    Gets the text from the edit control in a combo box\.&nbsp;

  - [GetLBTextLen](PyCComboBox.md#pyccomboboxgetlbtextlen)

    Gets the length of the text in the edit control of a combo box\.&nbsp;

  - [InsertString](PyCComboBox.md#pyccomboboxinsertstring)

    Inserts a string into the listbox portion of a combo box\.&nbsp;

  - [LimitText](PyCComboBox.md#pyccomboboxlimittext)

    Limit the length of text in the edit control portion of a combo box\.&nbsp;

  - [ResetContent](PyCComboBox.md#pyccomboboxresetcontent)

    Remove all items from the listbox portion of a combo box\.&nbsp;

  - [SelectString](PyCComboBox.md#pyccomboboxselectstring)

    Select a string in the listbox portion of a combo box\.&nbsp;

  - [SetCurSel](PyCComboBox.md#pyccomboboxsetcursel)

    Sets the current selection in the listbox portion of a combo box\.&nbsp;

  - [SetEditSel](PyCComboBox.md#pyccomboboxseteditsel)

    Sets the current selection in the edit control portion of a combo box\.&nbsp;

  - [SetExtendedUI](PyCComboBox.md#pyccomboboxsetextendedui)

    Sets the ExtendedUI flag for a combo box\.&nbsp;

  - [SetItemData](PyCComboBox.md#pyccomboboxsetitemdata)

    Sets the application-specific object associated with a combobox entry&nbsp;

  - [SetItemValue](PyCComboBox.md#pyccomboboxsetitemvalue)

    Sets the application-specific value associated with a combobox entry&nbsp;

  - [ShowDropDown](PyCComboBox.md#pyccomboboxshowdropdown)

    Shows the listbox portion of a combo box\.&nbsp;


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.AddString

int = AddString\(object\)
Adds a string to a combobox\.

#### Parameters

  - object : any

    Any object\.  If not a string, \_\_str\_\_, \_\_repr\_\_ or a default repr\(\) will be used

#### MFC References

  - CComboBox::AddString

#### Return Value
The zero based index of the new string\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.DeleteString

int = DeleteString\(pos\)
Deletes an item from a combobox\.

#### Parameters

  - pos : int

    The zero based index of the item to delete\.

#### MFC References

  - CComboBox::DeleteString

#### Return Value
The count of the items remaining in the list\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.Dir

int = Dir\(attr, wild

\)
Fills the list portion of a combobox with a directory listing\.

#### Parameters

  - attr : int

    The attributes of the files to locate

  - wild : string

    A file specification string - eg, \*\.\*

#### MFC References

  - CComboBox::Dir

#### Return Value
The index of the last file name added to the list\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.GetCount

int = GetCount\(\)
Returns the count of items in the combobox\.

#### MFC References

  - CListBox::GetCount

#### Return Value
Returns the number of items currently in the combobox\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.GetCurSel

int = GetCurSel\(\)
Returns the index of the currently selected item\.

#### Comments

Should not be called for a multiple selection listbox\.

#### MFC References

  - CComboBox::GetCurSel


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.GetEditSel

int = GetEditSel\(\)
Returns the selection of the edit control portion of a combo box\.

#### MFC References

  - CComboBox::GetEditSel

#### Return Value
A 32-bit value that contains the starting position in the low-order word and 

the position of the first nonselected character after the end of 

the selection in the high-order word\. If this function is used on a combo box 

without an edit control, an exception is raised\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.GetExtendedUI

int = GetExtendedUI\(\)
Indicates if the combo has the extended interface\.

#### MFC References

  - CComboBox::GetExtendedUI

#### Return Value
Nonzero if the combo box has the extended user interface; otherwise 0\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.GetItemData

object = GetItemData\(item\)
Retrieves the application-specific object associated with an item\.

#### Parameters

  - item : int

    The index of the item whose data is to be retrieved\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.GetItemValue

int = GetItemValue\(item\)
Retrieves the application-specific value associated with an item\.

#### Parameters

  - item : int

    The index of the item whose data is to be retrieved\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.GetLBText

string = GetLBText\(index\)
Gets the string from the list of a combo box\.

#### Parameters

  - index : int

    The index of the item to return the string for\.

#### Return Value
The requested string\. If index does 

not specify a valid index, no exception is raised\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.GetLBTextLen

int = GetLBTextLen\(index\)
Returns the length of a string in the list of a combobox\.

#### Parameters

  - index : int

    The index of the item to return the length of\.

#### MFC References

  - CComboBox::GetLBTextLen 

rdesc Returns the length of the string \(in bytes\), or raises an exception on error\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.InsertString

int = InsertString\(pos, object

\)
Insert a string into a combobox\.

#### Parameters

  - pos : int

    The zero based index in the combobox to insert the new string

  - object : any

    The object to be added to the combobox

#### MFC References

  - CComboBox::InsertString

#### Return Value
The zero based index of the new string added\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.LimitText

int = LimitText\(max\)
Limits the amount of text the edit portion of a combo box can hold\.

#### Parameters

  - max : int

    The maximum number of characters the user can enter\.  If zero, the size is set to \(virtually\) unlimited\.

#### MFC References

  - CComboBox::LimitText


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.ResetContent

ResetContent\(\)
Clear all the items from a combobox\.

#### MFC References

  - CComboBox::ResetContent


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.SelectString

SelectString\(after, string\)
Searches for a combobox item that matches the specified string, and selects it\.

#### Parameters

  - after : int

    Contains the zero-based index of the item before the first item to be searched, or -1 for the entire combobox\.

  - string : string

    The string to search for\.

#### MFC References

  - CComboBoxBox::SelectString

#### Return Value
The return value is always None - an exception is raised if the string can not be located\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.SetCurSel

SetCurSel\(index\)
Selects an item in a combobox\.

#### Parameters

  - index : int

    The zero based index of the item to select\.

#### MFC References

  - CComboBox::SetCurSel


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.SetEditSel

SetEditSel\(start, end\)
Sets the selection in the edit control portion of a combo box\.

#### Parameters

  - start : int

    Specifies the starting position\. If the starting position is set to -1, then any existing selection is removed\.

  - end : int

    Specifies the ending position\. If the ending position is set to -1, then all text from the starting position to the last character in the edit control is selected\.

#### MFC References

  - PyCComboBox::SetEditSel

#### Return Value
The return value is always None - an exception is raised if the combo is a dropdown style, or does not have an edit control\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.SetExtendedUI

SetExtendedUI\(bExtended\)
Selects the Extended UI mode for a combo box\.

#### Parameters

  - bExtended=1 : int

    Indicates if the combo should have the extended user interface\.

#### Comments

A combo box with the Extended UI flag set can be identified in the following ways:~ 

Clicking the static control displays the list box only for combo boxes with the CBS\_DROPDOWNLIST style\.~ 

Pressing the DOWN ARROW key displays the list box \(F4 is disabled\)\.~ 

Scrolling in the static control is disabled when the item list is not visible \(the arrow keys are disabled\)\.

#### MFC References

  - CListBox::SetExtendedUI


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.SetItemData

int = SetItemData\(item, Data

\)
Sets the item's application-specific object value\.

#### Parameters

  - item : int

    Index of the item whose Data is to be set\.

  - Data : object

    New value for the data\.

#### Comments

Note that a reference count is not added to the object\.  This it is your 

responsibility to make sure the object remains alive while in the list\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.SetItemValue

int = SetItemValue\(item, data

\)
Sets the item's application-specific value\.

#### Parameters

  - item : int

    Index of the item whose Data is to be set\.

  - data : int

    New value for the data\.


## [PyCComboBox](PyCComboBox.md#pyccombobox)\.ShowDropDown

ShowDropDown\(bShowIt\)
Shows or hides the listbox portion of a combo box\.

#### Parameters

  - bShowIt=1 : int

    Indicates if the listbox should be shown or hidden\.