# OrangeFox Recovery R12.1 - Samsung Galaxy A31 (SM-A315G/F/N)

Maintained by **Zyoo-0X** (`OF_MAINTAINER`, `FOX_VARIANT`, `FOX_MAINTAINER_PATCH_VERSION` in BoardConfig.mk).
Builds OrangeFox 12.1 from the official OrangeFox sync script.

## Build (from phone browser)
GitHub -> Actions -> "OrangeFox - Build A31 (Zyoo-0X)" -> Run workflow.
Download the artifact (recovery.img / recovery.tar / OrangeFox-*.zip) when it finishes.

## Flash
Odin (AP, recovery.tar) or Install Image -> Recovery from an existing recovery. vbmeta must already be disabled. Keep a backup of your working recovery.

## /data
Kernel is 4.14 with file-based encryption, no metadata encryption. If /data shows 0 MB or "unable to mount": Wipe -> Format Data (type yes), reboot recovery.

## Credits (please keep)
OrangeFox Recovery Project and TeamWin (TWRP)
