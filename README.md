# Windows 10 - Minimize all windows button

To get a button in the taskbar to minimize all opened windows:

Just download the "Minimize All Windows.lnk" file and drug and drop it to the windows taskbar.

Or you can manually create it:

1. Right click on the desktop
2. Select: New - Shortcut
3. Type/paste the next command to the "Type the location of the item" field:


        %windir%\explorer.exe shell:::{3080F90D-D7AD-11D9-BD98-0000947B0257}


4. Press the "Next" button
5. Type any convenient name for the shortcut
6. Press the "Finish" button
7. Drag and drop the created shortcut to the taskbar

Now on pressing it all the opened windows will be minimized.

You can delete the shortcut from the desktop if you don't need it here.
