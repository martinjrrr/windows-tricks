# Windows Setup
Guide on certain things Windows, removing bloat ware, freeing the system of microsofts spyware and restoring lost functionalities

![Wondows-11-Start-661424496](https://github.com/martinjrrr/windows-tricks/assets/91160845/ba9bde7e-cc04-427b-af04-5b11bc566f03)

_______________________________________________________________________________

# Cracking a windows password / bypassing the login screen

Boot Into Your Flash Drive And Type These Commands

`fdisk -l`

`mount -t ntfs /dev/(windows drive) /mnt`

`cd /mnt/Windows/System32`

`cp cmd.exe Utilman.exe`

reboot

Click On The Accesibility Button And Type This Command When The CMD Window Lauches

`net user (User) *` 

## If you try to mount the Windows drive and get an error of hibernation just use the command:

`sudo ntfsfix /dev/sdXY`

ITS POSSIBLE THAT THIS COMMAND CORRUPTS THE WINDOWS FILESYSTEM, KNOW THE POSSIBLE CONSEQUENCES BEFOREHAND 
________________________________________________________________________________

Windows 11 Local user - bypass Microsoft Account requirement







_______________________________________________________________________________

# Anti-Spyware Tool

[O&O Shutup10](https://www.oo-software.com/de/shutup10)

Kill Spyware and unnecesary bloat in Windows using this utility

make sure that you read trough your selections, this tool can temporarily block key system functions / settings

________________________________________________________________________________

# Host file sinkholing Spyware

    127.0.0.1 localhost
    ::1 localhost
    127.0.0.1 data.microsoft.com
    127.0.0.1 msftconnecttest.com
    127.0.0.1 azureedge.net
    127.0.0.1 activity.windows.com
    127.0.0.1 bingapis.com
    127.0.0.1 msedge.net
    127.0.0.1 assets.msn.com
    127.0.0.1 scorecardresearch.com
    127.0.0.1 edge.microsoft.com
    127.0.0.1 data.msn.com


# Windows 10 Functionality and Patches for Windows 11

Valinet's ExplorerPatcher restores lost Windows 10 functionalities

[Explorer Patcher](https://github.com/valinet/ExplorerPatcher)

![7cdf0ca053358108](https://github.com/martinjrrr/windows-tricks/assets/91160845/47a6be46-808c-4ead-bcf1-5fd76a711728)

