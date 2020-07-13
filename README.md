# SailfishOS for Xiaomi MI A2

Please check releases to download the latest build.

## Bugs:

- Double tap to wake is disabled beacuse it causes touch not to register after wakeup and reboot

- To turn on bluetooth you need to enable developer mode and set password for devel-su and then tap on bluetooth button once and finally run "devel-su bluebinder" (it usually does not work on first try and you need to to cancel it with ctrl + c and keep trying again until it works)

- Video recording breaks camera and user is forced to reboot if they want to use camera again.

- SSH over USB is broken if MTP functionality is enabled in droid-configs (It is enabled for now), alternatively you can use SSH over WiFi

- Some audio/video codecs don't work

- When phone boots screen is usually black/blank. Also screen stays awake unless you press power button to suspend the phone and wake up the phone again.

### PS. I need help to fix the above mentioned issues.
