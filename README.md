A simple module for Magisk which easily clear cache of all apps

Every app, they work by creating its cache in `/data/data/*/cache`. Cache is just temporary file, it may not be deleted if app doesn't use it and waste your amount of memory storage. To clear cache, you must enter **App info** Settings of every app and press **Clear cache**

## Installation

1. Open **Magisk** app, click Module tab.
2. Press **Install from storage**
3. Find my zip and flash
4. Reboot

Every time you need to wipe cache, just type:
```
su -c cc
```
