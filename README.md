# Windows API Code Pack v1.1 #
<https://github.com/timdetering/Microsoft.Windows_API_Code_Pack>

**NOTE:** I do not own this code.  This is an archive of the orignal Microsoft code.

Windows® API Code Pack for Microsoft® .NET Framework provides a source code library that can be used to access some features of Windows 7 and Windows Vista from managed code. These Windows features are not available to developers today in the .NET Framework.

The individual features supported in this version (v1.1) of the library are:
Windows 7 Taskbar
Jump Lists, Icon Overlay, Progress Bar, Tabbed Thumbnails, and Thumbnail Toolbars
Windows Shell
Windows 7 Libraries
Windows Shell Search API support
Explorer Browser Control
A hierarchy of Shell Namespace entities
Windows Shell property system
Drag and Drop for Shell Objects
Windows Vista and Windows 7 Common File Dialogs, including custom controls
Known Folders and non-file system containers
Shell Object Watcher
Shell Extensions API support
DirectX
Direct3D 11.0, Direct3D 10.1/10.0, DXGI 1.0/1.1, Direct2D 1.0, DirectWrite, Windows Imaging Component (WIC) APIs
Windows Vista and Windows 7 Task Dialogs
Sensor Platform APIs
Extended Linguistic Services APIs
Power Management APIs
Application Restart and Recovery APIs
Network List Manager APIs
Command Link control and System defined Shell icons

What’s New in this update (v1.1): 

The enhancements in this update of Code Pack are:
Many FxCop violations and PREfast warnings have been addressed
Bug fixes across various features and samples
Includes many API improvements
New features
Shell Object Watcher
Preview Handler APIs
Thumbnail Handler APIs
New samples for the new features
Visual Studio 2010 compliance
Initial xUnit test coverage
String localization
Signed assemblies

Requirements:
Minimum .NET Framework version required to use this library is 3.5 SP1. The APIs for Shell Extensions require .NET 4.
This library targets the Windows 7 RTM version, though many of the features will work on Windows Vista as well.
DirectX features require Windows SDK for Windows 7 RTM. Additionally, some Direct3D samples require the August 2009 release of DirectX SDK.

Building and using the Library:
To build the library (except the DirectX related features) in Visual Studio 2008, execute 'Windows API Code Pack Self Extractor.exe' and extract the contents of the ‘Windows API Code Pack 1.1.zip’ file. Build the included ‘WindowsAPICodePack.sln’ file located in the 'WindowsAPICodePack' directory (within the 'source' directory).
To build the DirectX features, build the 'DirectX.sln' file inside the DirectX directory. Additional information on using the DirectX features of the Code Pack can be found in the 'DirectXCodePack_Requirements.htm' document available as a separate download.

Samples:
The Code Pack also contains sample applications built using this library. Most samples are available in C# and VB.NET version and can found found in the 'Samples' directory (within the 'source_' directory).

Documentation:
The Code Pack also includes the following documentation:
API References
Windows API Code Pack Help.chm
Windows API Code Pack DirectX Help.chm
API Changes since the previous release
Windows API Code Pack API Changes.html
Overview of the release (including new features)
Windows API Code Pack Release Notes.htm
All documentation is located in the 'documentation' directory.


Some relevant blog entries:
Windows Shell programming with Windows API Code Pack
Introducing DirectX features of Windows API Code Pack
Direct2D and DirectWrite with Windows API Code Pack

Videos:
Two minute videos demonstrating some features in the previous release:
Explorer Browser
Common File Dialog


Note:
Some users may experience a security related issue when opening the help files or the Visual Studio solution. Contents of help files may not be visible or a security warning similar to “Unknown Publisher” or “This file came from another computer and might be blocked” may pop up. If that happens, the user won't be able to load the solution projects because Windows will block it.

To fix this error, please unblock the help files and zip file before extracting it (right click the file | select properties | click Unblock button).

<http://web.archive.org/web/20130727034633/http://archive.msdn.microsoft.com/WindowsAPICodePack>