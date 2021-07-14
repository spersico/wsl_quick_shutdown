## Description

Is that Vmmem process eating all your RAM?. Did your WSL2 crashed, and it's not responding, even if you closed all the terminals?.

This will terminate all your running WSL distributions and the WSL 2 lightweight utility virtual machine. With a single click!! (maybe 2).

You can then open it, and try again. 😄

## Usage instructions:

- Put kill_wsl.bat in some folder (doesn't really matter which).
- Create in that folder a shortcut (left click -> new -> shortcut)
  - In the Location field, put:
    ``cmd /c "<PATH-TO>\kill_wsl.bat"``
    *For example, in my case this was ``cmd /c E:\WSL\kill_wsl.bat``*
- That shortcut already does the magic, but you can right click it and put it in the Start Menu or even the Taskbar.
- Done

