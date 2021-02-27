# remove_apps.ps1
Removes Windows 10 store apps bloats after installing Windows



1. Save remove_apps.ps1 to somewhere like the desktop
2. On the keyboard, press Windows Button + R
3. type "CMD" without quotes in the run box
4. Press Ctrl+Shift+Enter to run CMD as admin
5. Change the directory to the location where the file was saved in step 1.
  Example: CD /d "%userprofile%\desktop"
6. Type the below command to run the script:
powershell.exe -ExecutionPolicy Bypass .\remove_apps.ps1
