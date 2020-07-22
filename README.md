# SailfishOS for Xiaomi MI A2

Please check [releases](https://github.com/SailfishOS-MI-A2/Releases/releases) to download the latest build.

### Flash instructions

1. [Flash LineageOS 16 to Slot A (DO NOT FLASH TWRP AS WELL!)](https://github.com/SailfishOS-MI-A2/Releases/releases/download/20200713/lineage-16.0-20200322-UNOFFICIAL-jasmine_sprout.zip)
2. Switch Slot (now it will show that you're in SLOT A)
3. Flash SailfishOS
4. Reboot

### Upgrade instructions:

1. Backup your data somewhere safe.
2. Flash SailfishOS zip twice/thrice (it is required to bypass installer warnings) when Slot A is active.

### Note:

- SSH over USB is broken if MTP functionality is enabled in droid-configs (MTP is enabled btw), alternatively you can use SSH over WiFi.

### Bugs:

- Double tap to wake causes touch not to register after wakeup and reboot so it is disabled by default in source

- Some codecs don't work i.e. some telegram videos don't work at all (change made, yet to be tested)

- When phone starts screen is black/ blank or just keeps showing default splash screen of device. Also screen stays awake unless you press power button to suspend the phone and wake up the phone again.

Others:

- In rare occassions bluetooth may not work, to enable it, you will need to enable developer mode and set a password. Then you need to launch terminal and type "devel-su bluebinder" and enter password. It may not work on first try, so if it's stuck use Ctrl + C button to cancel and try running the command again.


### PS. I need help to fix the above mentioned issues.
