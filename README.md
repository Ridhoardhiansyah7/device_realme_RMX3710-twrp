## TWRP / PBRP / OFOX device tree for Realme RMX3710 (REALME C55)

## Device specification

Basic   | Spec Sheet
-------:|:------------------------
CPU     | Octa-core (2x2.0 GHz Cortex-A75 & 6x1.8 GHz Cortex-A55)
CHIPSET | Mediatek MT6768 / Helio G88 (12 nm)
GPU     | Mali-G52 MC2
Memory  | 3GB/4GB/6GB/8GB
Shipped Android Version | Android 13, Realme UI 4.0
Storage | 64GB/128GB/256GB
Battery | Li-Po 5000 mAh
Dimensions | 165.6 x 75.9 x 7.9 mm (6.52 x 2.99 x 0.31 in)
Display | 1080 x 2400 pixels, 20:9 ratio (~392 ppi density)
Rear Camera  | 64 MP
Front Camera | 8 MP

**Specifications in detail:**  
See [GSMArena - Realme C55](https://m.gsmarena.com/realme_c55-12159.php)

---

## Features
Blocking checks
- [X] Correct screen/recovery size
- [X] Working Touch, screen
- [X] Backup to internal/microSD
- [X] Restore from internal/microSD
- [X] reboot to system
- [X] ADB
- [X] Fastbootd

Medium checks
- [X] update.zip sideload
- [X] UI colors (red/blue inversions)
- [X] Screen goes off and on
- [X] F2FS/EXT4 Support, exFAT/NTFS where supported
- [X] all important partitions listed in mount/backup lists
- [X] backup/restore to/from external (USB-OTG) storage
- [X] backup/restore to/from adb
- [X] decrypt /data (Work fine)
- [X] Correct date

Minor checks
- [X] MTP export
- [X] reboot to bootloader
- [X] reboot to recovery
- [X] poweroff
- [X] battery level
- [X] temperature
- [X] encrypted backups
- [X] input devices via USB-OTG - keyboard, mouse and disks
- [X] USB mass storage export
- [X] set brightness
- [X] vibrate
- [ ] Flashlight (Upcoming)
- [X] screenshot
- [X] partition SD card