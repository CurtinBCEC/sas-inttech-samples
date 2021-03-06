# SAS Program Harness
***
This repository is contains an example that shows 
how to use SAS Integration Technologies from a Microsoft .NET
application.  This version is implemented in C#.

Written by [Chris Hemedinger](http://blogs.sas.com/content/sasdummy) as part of
a published paper at SAS Global Forum 2013.

## About this example
This sample application has the following features:
- Connects to a SAS Workspace session using a server that you define in a dialog window
- Allows you to connect to a "local" instance of SAS -- no configuration required.
- Features three windows: a program editor, a log viewer, and a listing viewer.  (Does that seem familiar?)
- Allows you to run a SAS program on a background thread, keeping the main user interface responsive
- Retrieves the SAS log and listing output, and colors each line of output as appropriate (errors, warnings, notes, page boundaries)
- Provides a simple Data Set viewer: open a data set from SAS library, apply a filter (WHERE= option)

## Screen shots
![main form](main.png "Main screen example")
![data grid view](datagrid.png "Data grid example")

For more details, see the community page for this paper:
[Create Your Own Client Apps Using SAS Integration Technologies](https://communities.sas.com/t5/SAS-Communities-Library/Create-your-own-client-apps-using-SAS-Integration-Technologies/ta-p/418253)

