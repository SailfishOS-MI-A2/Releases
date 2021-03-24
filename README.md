# SailfishOS for Xiaomi MI A2

Please check [releases](https://github.com/SailfishOS-MI-A2/Releases/releases) to download the latest build.

### Flash instructions

0. Set slot to B and boot TWRP
1. [Flash LineageOS 16 (DO NOT FLASH TWRP AS WELL!)](https://github.com/SailfishOS-MI-A2/Releases/releases/download/20200713/lineage-16.0-20200322-UNOFFICIAL-jasmine_sprout.zip)
2. Switch Slot (now it will show that you're in SLOT A)
3. Reboot to bootloader
4. Boot TWRP again
5. Flash SailfishOS
6. Reboot

### Upgrade instructions:

1. Backup your data somewhere safe.
2. Flash SailfishOS zip twice/thrice (it is required to bypass installer warnings) when Slot A is active.

### Note:

- SSH over USB is broken if MTP functionality is enabled in droid-configs (MTP is enabled btw), alternatively you can use SSH over WiFi.

### Bugs:

- To turn on bluetooth you need to enable developer mode and set password for devel-su and then tap on bluetooth button once and finally run "devel-su bluebinder" (it usually does not work on first try and you need to to cancel it with ctrl + c and keep trying again until it works)

- Video recording breaks camera and user is forced to reboot if they want to use camera again.

- Double tap to wake causes touch not to register after wakeup and reboot so it is disabled by default in source

- When phone starts screen is black/ blank or just keeps showing default splash screen of device. Also screen stays awake unless you press power button to suspend the phone and wake up the phone again.

### PS. I need help to fix the above mentioned issues.

[Want to help or need support?](https://t.me/shoukolab)
