# This project has been permanently moved to [gitlab](https://gitlab.com/morfikov/android_device_tp-link_tp902a). It will no longer be maintained here. Please, refer to [gitlab](https://gitlab.com/morfikov/android_device_tp-link_tp902a) repository for updates.

TeamWin Recovery Project

Device configuration for TP-LINK Neffos X1 (TP902A)
=====================================

Basic   | Spec Sheet
-------:|:-------------------------
CHIPSET | MediaTek MT6755
CPU     | 4x 1.0 GHz & 4x 1.8 GHz ARM Cortex A53 CPU
GPU     | ARM Mali-T860 MP2
Memory  | 2 GB / 3 GB
Shipped Android Version | Android 6.0 (Marshmallow)
Storage | 16 GB / 32 GB
MicroSD | Up to 128 GB
Battery | 2250 mAh
Dimensions | 152 x 76 x 8.95 mm
Display | 1280 x 720 pixels 5.0" (293.7 PPI)
Rear Camera  | 13.0 MP
Front Camera | 5.0 MP
Release Date | September 2016

![TP-LINK Neffos X1](http://www.neffos.com/res/upfile/product/20160901112338.png "TP-LINK Neffos X1")

How to compile the image
=====================================
You can get the minimal OMNI source [from here](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni).
The full HowTo can be found [here](https://forum.xda-developers.com/showthread.php?t=1943625).

TWRP Functional Checklist
=====================================

Blocking checks
- [x] Correct screen/recovery size
- [x] Working Touch, screen
- [x] Backup to internal/microSD
- [x] Restore from internal/microSD
- [x] reboot to system
- [x] ADB

Medium checks
- [x] update.zip sideload
- [x] UI colors (red/blue inversions)
- [x] Screen goes off and on
- [x] F2FS/EXT4 Support, exFAT/NTFS where supported
- [x] all important partitions listed in mount/backup lists
- [x] backup/restore to/from external (USB-OTG) storage
- [ ] backup/restore to/from adb (https://gerrit.omnirom.org/#/c/15943/)
- [x] decrypt /data
- [x] Correct date

Minor checks
- [x] MTP export
- [x] reboot to bootloader
- [x] reboot to recovery
- [x] poweroff
- [x] battery level
- [x] temperature
- [x] encrypted backups
- [x] input devices via USB (USB-OTG) - keyboard, mouse and disks
- [x] USB mass storage export
- [x] set brightness
- [x] vibrate
- [x] screenshot
- [x] partition SD card
