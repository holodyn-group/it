Building Windows Installer
--------------------------
Install Inno Setup https://jrsoftware.org/isdl.php, if you haven't.

Build release.

The first time, you need to run windeployqt:
	>C:\Qt\6.10.1\msvc2022_64\bin\windeployqt.exe C:\Users\Usuario\Code\it\build\Desktop_Qt_6_10_1_MSVC2022_64bit-Release\it.exe --release

Edit wininstall.iss (check if paths are correct).

Open wininstall.iss with Inno Setup.

Select "Compile". This will place the installer (itsetup.exe) into .../Code/It/Output
