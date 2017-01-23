# Tabs


## Tabs and indentation in the editor

The use of tabs and the meanings of the tab defaults is not completely 

clear\.  Unfortunately, this is very hard to fix without losing the smart 

indentation \(eg, when indenting lists or function parameters\)\. 

If the use of smart indentation has been disabled \(the default is enabled\) 

then the indentation should always follow your preferences, regardless 

of any existing indentation in the source\. 

 

Otherwise, the preferences for tab settings are only used when a new file is created\. 

If smart-tabs are enabled and an existing file is opened, its first 

block is located, and the indentation 

it uses overrides the default\.  Thus, regardless of your preferences, if the first 

indent in the file is a tab, Pythonwin uses tabs for the entire file \(and 

similarly, uses spaces if the first block is indented with spaces\) 

 

Things can appear to get wierd when editing a file with mixed tabs and spaces\. 

Although mixed tabs and spaces in the same indent is evil, there are a number 

of source files that have certain classes/functions indented with spaces, and others 

that use tabs\.  The editor will not correctly adjust to the current block - whatever 

was used for the first block is used for the entire file\. 

 

Another common scenario where things go wrong is when pasting code into a new file\. 

You create a new file \(which sets the tabs to your defaults\), then 

paste in a huge chunk of code that is indented differently\.  The editor is still using 

the defaults, which dont reflect the code that now exists in the buffer\. 

 

The "tab-timmy" shows up these problems very quickly, and you can quickly toggle the 

current tab settings by pressing Ctrl\+T, or change the indent width by pressing Ctrl\+U\.