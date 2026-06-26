# Zoom Noise Reduction Audio Sony Xperia 10 Magisk Module

## DISCLAIMER
- Sony blobs are owned by Sony™.
- The MIT license specified here is for the Magisk Module only, not for Sony blobs.

## Descriptions
- Audio quality enhancement for audio/video recordings ported from Sony Xperia 10 (I4113) and integrated as a Magisk Module for all supported and rooted devices with Magisk
- Pre process type sound effect
- There is no user interface

## Sources
https://dumps.tadiphone.dev/dumps/sony/i4113 kirin_dsds-user-10-53.1.A.2.2-053001A00020000200894138764-release-keys

## Changelog

v1.2
- Support NoMount metamodule
- Resets module folders/files permissions at post-fs-data
- Move _uninstall.log to /data/adb/logs/

v1.1
- Fix wrong target in latest KernelSU
- Improve detections

v1.0
- Tidy up aml.sh
- Exclude \*audio\*effects\*haptic\*.xml
- Fix wrong file permissions in some ROMs

v0.9
- Improve /odm and /my_product support detection

v0.8
- Fix architecture detection in some weird ROMs
- Fix bug in uninstall.sh

v0.7
- Allow installation in Android Emulator
- Fix architecture detection

v0.6
- Change module name
- Fix architecture detection
- Fix installation via Recovery if Magisk installed

v0.5
- Improve \*audio\*effects\*.xml patch detection
- Fix conflict with modules_update while installing via recovery if Magisk installed

v0.4
- Redirect /sdcard to /data/media/\"$UID\"
- Add optional debug.log=1 for more detailed install log
- Abort installation if ROM doesn't support 32 bit library
- Kitsune Mask detection
- Restarts android.hardware.audio@4.0-service-mediatek

v0.3
- Sets ro.audio.ignore_effects to false
- Move uninstall log to /data/media/0/..._uninstall.log

## Requirements
- armeabi-v7a or arm64-v8a with armeabi-v7a support architecture
- 32 bit HIDL audio service
- Magisk or Kitsune Mask or KernelSU or Apatch installed

## Installation Guide & Download Link
- Install this module via Magisk app or Kitsune Mask app or KernelSU app or Apatch app or Recovery if Magisk or Kitsune Mask installed
- Install AML Magisk Module https://t.me/ryukinotes/34 only if using any other else audio mod module
- Reboot

## Optionals
Global: https://t.me/ryukinotes/35

## Troubleshootings
Global: https://t.me/ryukinotes/34

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- https://t.me/viperatmos
- https://t.me/androidryukimodsdiscussions
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Sponsors
https://t.me/ryukinotes/25


