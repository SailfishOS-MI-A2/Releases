# SailfishOS for Xiaomi MI A2

Please check releases to download the latest build.

### Flash instructions

1. [Flash LineageOS 16 to Slot A (DO NOT FLASH TWRP AS WELL!)](https://github.com/SailfishOS-MI-A2/releases/releases/download/20200713/lineage-16.0-20200322-UNOFFICIAL-jasmine_sprout.zip)
2. Switch Slot (now it will show that you're in SLOT A)
3. Flash SailfishOS
4. Reboot

### Upgrade instructions:

1. Backup your data somewhere safe.
2. Flash SailfishOS zip twice/thrice (it is required to bypass installer warnings) when Slot A is active.

### Note:

- SSH over USB is broken if MTP functionality is enabled in droid-configs (MTP is enabled btw), alternatively you can use SSH over WiFi.

### Bugs:

- Double tap to wake is disabled because it causes touch not to register after wakeup and reboot, probably something to do with proximity sensor.

- To turn on bluetooth you need to enable developer mode and set password for devel-su and then tap on bluetooth button once and finally run "devel-su bluebinder" (it usually does not work on first try and you need to to cancel it with ctrl + c and keep trying again until it works)

- Video recording breaks camera and user is forced to reboot if they want to use camera again.

- Some audio/video codecs don't work

- When phone boots screen is usually black/blank. Also screen stays awake unless you press power button to suspend the phone and wake up the phone again.

### PS. I need help to fix the above mentioned issues.
