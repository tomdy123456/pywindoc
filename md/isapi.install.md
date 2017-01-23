# isapi.install


## Module isapi\.install

Installation utilities for Python ISAPI filters and extensions\.

#### Methods

  - [RemoveScriptMaps](isapi.install.md#isapi.installremovescriptmaps)

    Remove script maps from the already installed virtual directory&nbsp;

  - [UninstallModule](isapi.install.md#isapi.installuninstallmodule)

    Remove the extension&nbsp;

  - [get\_unique\_items](isapi.install.md#isapi.installget_unique_items)

    Return items in sequence that can't be found in reference\.&nbsp;

  - [InstallModule](isapi.install.md#isapi.installinstallmodule)

    Install the extension&nbsp;

  - [AssignScriptMaps](isapi.install.md#isapi.installassignscriptmaps)

    Updates IIS with the supplied script map information\.&nbsp;

  - [LocateWebServerPath](isapi.install.md#isapi.installlocatewebserverpath)

    Find an IIS web server whose name or comment matches the provided&nbsp;

  - [split\_path](isapi.install.md#isapi.installsplit_path)

    Get the parent path and basename\.&nbsp;

  - [MergeStandardOptions](isapi.install.md#isapi.installmergestandardoptions)

    Take an options object generated by the command line and merge&nbsp;

  - [FindWebServer](isapi.install.md#isapi.installfindwebserver)

    Legacy function to allow options to define a \.server property&nbsp;

  - [AddExtensionFiles](isapi.install.md#isapi.installaddextensionfiles)

    Register the modules used by the filters/extensions as a trusted&nbsp;

  - [HandleCommandLine](isapi.install.md#isapi.installhandlecommandline)

    Perform installation or removal of an ISAPI filter or extension\.&nbsp;

  - [GetWebServer](isapi.install.md#isapi.installgetwebserver)

    Load the web server instance \(COM object\) for a given instance&nbsp;


## [isapi\.install](isapi.install.md#isapi.install)\.AddExtensionFiles

AddExtensionFiles\(params, options\)
Register the modules used by the filters/extensions as a trusted 

'extension module' - required by the default IIS6 security settings\.

#### Parameters

  - params : 

    params

  - options : 

    options


## [isapi\.install](isapi.install.md#isapi.install)\.AssignScriptMaps

AssignScriptMaps\(script\_maps, target, update\)
Updates IIS with the supplied script map information\.

#### Parameters

  - script\_maps : 

    script\_maps

  - target : 

    target

  - update='replace' : 

    update

#### Comments

script\_maps is a list of ScriptMapParameter objects

target is an IIS Virtual Directory to assign the script maps to

update is a string indicating how to update the maps, one of  \('start', 

'end', or 'replace'\)


## [isapi\.install](isapi.install.md#isapi.install)\.FindWebServer

FindWebServer\(options, server\_desc\)
Legacy function to allow options to define a \.server property 

to override the other parameter\.  Use GetWebServer instead\.

#### Parameters

  - options : 

    options

  - server\_desc : 

    server\_desc


## [isapi\.install](isapi.install.md#isapi.install)\.GetWebServer

GetWebServer\(description\)
Load the web server instance \(COM object\) for a given instance 

or description\. 

If None is specified, the default website is retrieved \(indicated 

by the identifier 1\.

#### Parameters

  - description=None : 

    description


## [isapi\.install](isapi.install.md#isapi.install)\.HandleCommandLine

HandleCommandLine\(params, argv, conf\_module\_name, default\_arg, opt\_parser, custom\_arg\_handlers\)
Perform installation or removal of an ISAPI filter or extension\.

#### Parameters

  - params : 

    params

  - argv=None : 

    argv

  - conf\_module\_name=None : 

    conf\_module\_name

  - default\_arg='install' : 

    default\_arg

  - opt\_parser=None : 

    opt\_parser

  - custom\_arg\_handlers=\{\} : 

    custom\_arg\_handlers

#### Comments

This module handles standard command-line options and configuration 

information, and installs, removes or updates the configuration of an 

ISAPI filter or extension\.

You must pass your configuration information in params - all other 

arguments are optional, and allow you to configure the installation 

process\.


## [isapi\.install](isapi.install.md#isapi.install)\.InstallModule

InstallModule\(conf\_module\_name, params, options, log\)
Install the extension

#### Parameters

  - conf\_module\_name : 

    conf\_module\_name

  - params : 

    params

  - options : 

    options

  - log=function lambda at 0x0000000002825588 : 

    log


## [isapi\.install](isapi.install.md#isapi.install)\.LocateWebServerPath

LocateWebServerPath\(description\)
Find an IIS web server whose name or comment matches the provided 

description \(case-insensitive\)\.

#### Parameters

  - description : 

    description

#### Comments

or

&gt&gt&gt LocateWebServerPath\('1'\) \#doctest: \+SKIP

&gt&gt&gt LocateWebServerPath\('Default Web Site'\) \# doctest: \+SKIP


## [isapi\.install](isapi.install.md#isapi.install)\.MergeStandardOptions

MergeStandardOptions\(options, params\)
Take an options object generated by the command line and merge 

the values into the IISParameters object\.

#### Parameters

  - options : 

    options

  - params : 

    params


## [isapi\.install](isapi.install.md#isapi.install)\.RemoveScriptMaps

RemoveScriptMaps\(vd\_params, options\)
Remove script maps from the already installed virtual directory

#### Parameters

  - vd\_params : 

    vd\_params

  - options : 

    options


## [isapi\.install](isapi.install.md#isapi.install)\.UninstallModule

UninstallModule\(conf\_module\_name, params, options, log\)
Remove the extension

#### Parameters

  - conf\_module\_name : 

    conf\_module\_name

  - params : 

    params

  - options : 

    options

  - log=function lambda at 0x0000000002825668 : 

    log


## [isapi\.install](isapi.install.md#isapi.install)\.get\_unique\_items

get\_unique\_items\(sequence, reference\)
Return items in sequence that can't be found in reference\.

#### Parameters

  - sequence : 

    sequence

  - reference : 

    reference


## [isapi\.install](isapi.install.md#isapi.install)\.split\_path

split\_path\(path\)
Get the parent path and basename\.

#### Parameters

  - path : 

    path
&gt&gt&gt split\_path\('/'\)

\['', ''\]

&gt&gt&gt split\_path\(''\)

\['', ''\]

&gt&gt&gt split\_path\('foo'\)

\['', 'foo'\]

&gt&gt&gt split\_path\('/foo'\)

\['', 'foo'\]

&gt&gt&gt split\_path\('/foo/bar'\)

\['/foo', 'bar'\]

&gt&gt&gt split\_path\('foo/bar'\)

\['/foo', 'bar'\]