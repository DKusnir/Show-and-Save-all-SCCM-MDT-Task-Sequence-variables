# Show-and-Save-all-SCCM-MDT-Task-Sequence-variables
 
View, Create, Edit or Save all MDT & SCCM Task Sequence variables. Normal & Secure mode. Online & Offline Task Sequence viewer. Logs Collector. Debugger tool. Task sequence comparator tool
 
 
 
![ScreenShot](https://github.com/DKusnir/Show-and-Save-all-SCCM-MDT-Task-Sequence-variables/blob/master/screenshot.png)

 
 
  
This is just a small utility that helps me to check all Task Sequence variables and their values. It also allows to easily create new Task Sequence variables, Edit existing Action variables or simply save all variables into the .log file. In case you want to hide sensitive data, you can turn on the safe mode. To read the log, you can either use this tool directly or use Microsoft CMTRACE log tool. Up from version 2.7, tool also contains small database of most known SCCM & MDT variables, so you can either directly check for the variable description or seach for the variable offline. Current version also contains Task sequence viewer. You may check the steps during running task sequence by pressing CTRL+T and TS will load automatically or offline using previously saved Task Sequence XML file. There are x86 and x64 Windows 7 versions - that uses .net 3.5 and also same distribution for Windows 10 Versions - with .Net 4 support. Please use this tool only during Task Sequence progress, otherwise there will be nothing to see. Also make sure WinPE Boot image has relevant .net Framework and Powershell packages added



===============================
 
Version History 

===============================

Version 4.0.2.1 (Current Version) - 
 
- Fix issue when TS Varialbes may not show correctly. 
- Fix opening Create & Edit task sequence windows 
- Fix when Task sequence may not generate task sequence online. 
- TS Comparator disabled when TS in Progress 
- Multiple bug fixes
 
Version 4.0.2.0 - All tool settings now saved in one place in Theme > Settings - Fix. Corrected Task Sequence Viewer when conditions were not showing at all. Themes redesign. Minor bug fixes
 
Version 4.0.1.9 - Added ability to unlock and edit text inside the console. Added support for Drag & Drop files to the console & TSViewer. Added description to log collector about collected logs and their location. Form now dragable. Fixed huge number of bugs

Version 4.0.1.8 - Added Task Sequence Comparator - Simple viewer to compare 2 task sequences side by side. Update check now connects and downloads new version directly from Github. Improved Task Sequence Viewer Auto-refresh ( Still experimental ). Added ability to rezise window with Alt+Enter. Fix - Opening Task Sequence Viewer no longer disables the Toolstrip.  Fix - Error lookup no longer disabled in the strip when outside SCCM environment. Added help switch '/?' to dump help to the log. Minor bug fixes & UI Changes
 
Version 4.0.1.7 - Added ability to work concurrently with Error Lookup. Added support for some new conditions in Task Sequence Viewer. Minor bug fixes

Version 4.0.1.6 - Fix Task Sequence Viewer disabled  sub-groups & sub-Steps. Recursing for disabled sub-groups and child steps now shows nodes correctly. Disabled CheckBox now also shown correctly. Fixed some MDT steps that were shown incorrecly. Other minor bug fixes 

Version 4.0.1.5 - Major Release - Task sequence Viewer - Opening Task sequence containing same steps & groups now shows values correctly.

Version 4.0.1.4 - Minor improvment for conditions for Task Sequence Viewer. Fix Task Sequence online viewer - Opening task sequence during deployment now generate Task Sequence correctly. Minor improvment to the Error Lookup

Version 4.0.1.3 - Added Search for Task Sequence Viewer. Groups in TSViewer now shown as Bold

Version 4.0.1.2 - Added Log Collector to be able to save deployment logs. Error database now able to search for Custom Hex error codes that are not in a database. Added MDT return codes to the database. Save Theme renamed to Save Settings - Save Settings now saves custom log location as well. Fix issue when certain combination does not hide secure variables when secure mode is ON

Version 4.0.1.1 - Added ability to export Task Sequence from previously saved log file. Minor bug fixes

Version 4.0.1.0 - Added recently opened files for Task Sequence Viewer & Variables Vewer. Task Sequence Viewer now shows path to the XML file that was recently. WinPE Save GUI Redesign. Minor bug fixes

Version 4.0.0.9 - Added Set Version for Task Sequence Viewer. When saving task sequence, you can now add version to the xml file for future reference 

Version 4.0.0.8 - Added filter for built-in variables & custom variables.

Version 4.0.0.7 - Redesign of high dpi scaling. Fix issues when dark theme not redrawing all windows properly

Version 4.0.0.6 - Check for updates impovment. Minor bug fixes

Version 4.0.0.5 - Added check for updates & Automatick check for updates

Version 4.0.0.4 - Added support for most MDT steps in the Task Sequence viewer. Various bug fixes

Version 4.0.0.3 - Enhanced Dark mode for task sequence viewer

Version 4.0.0.2 - Added Dark & Custom theme support.  Ability to save custom theme. Added ability to hide Task sequence progress UI. Reduced overall application size

Version 4.0.0.1 - Fix silent switch save. Switches without custom path now save variables correctly

Version 4.0.0.0 - Major release. Added ability to show and save variables in safe mode. This mode will hide all sensitive data. Safe mode also support silent switch /sd

Version 3.0.1.2 - Added silent switch support - you can now use /t to save task sequence

Version 3.0.1.1 - Added silent switch support - you can now use /s to save variables 

