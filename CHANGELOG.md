# Change log

## 1.8
**2020-10-08**

* Fixed issue where performing operations on project files in the Solution Explorer would check out all project items. Now only .filters are checked out too.

## 1.7
**2020-10-02**

* Add and Delete command now supported.

## 1.6
**2020-10-01**

* Auto-checkout is now avaiable in the Options page.

Auto-checkout will checkout edited read-only files on save/build.

## 1.5
**2020-09-28**

* Checking out files will now run commands on associated files. E.g. checking out a project will also checkout the .filters file, checking out a C# form will checkout the .resx and .cs, etc.
* Multiselection now supported when using right-click context menu in Solution Explorer.

(Thanks to Tom Seddon for the following changes)

* Can now view P4 command logging and results in P4EditVS output pane.
* Can now choose Allow Environment for workspace setting which will use config as shown by P4 Set (or see P4V Connection -> Environment Settings).
* Workspace selection is now saved per Solution in the .suo file.

## 1.4
**2020-07-14**

* Fixed diff against have revision not working somtimes

## 1.3.1
**2020-06-25**

* Fixed history icon on solution explorer menu.

## 1.3
**2020-06-25**

* Added new commands.
   * Diff against have revision.
   * History.
   * Time-lapse view.
   * Revision graph.
* Renamed checkout command so it can be identified easier in the keyboard shortcuts window.

## 1.2
**2020-06-23**

* Now supports up to 6 workspace settings.

## 1.1
**2020-06-15**

* Added commands to solution explorer context menus for files, solutions and projects.
* Fixed crash when no file was open and top level menu was accessed.
