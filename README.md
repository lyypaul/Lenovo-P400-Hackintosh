# Lenovo-P400-Hackintosh
OC for lenovo ideapad P400    10.15 works

! Brightness not work !

01/02/2021 
Modifed the Opencore (EFI_Latest) and now the battery and wifi card works.

12/30/2020 
Just changed wifi and hasn't modified the OC to load it. 
Remember to use a small tape to block the right first chin of bluetooth.
Changed wifi card to BCM94352HMB. Blocked the whitelist followed the guidance from these two website:
https://www.jianshu.com/p/93426e1a1de8
https://blog.huangyz.name/tech/2017/03/08/hackintosh-wirelesscard.html

Firstly delete the white list and load the new wifi card. Read the Device ID and SUBSYS ID.
Then modifie the white list to include the new wifi card to make the system stable.
Fpt only run in dos mode. (Remember to open lagency support to boot to Dos)

