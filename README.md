# Clover configuration for MSI GE70 2PC
MSI GE70 2PC Hackintosh configuration for macOS Mojave

## Hardware

* CPU: Intel i5-4200H Haswell
* GPU: Intel HD4600
  * ID: 0x416
* Chipset: Intel HM86 Lynx Point
* Memory 16GB
* Audio: Realtek ALC892
* Network: Qualcomm Atheros Killer E220x
* WiFi: Qualcomm Atheros AR9285 PSIe (only 2.4Gz)
* SSD: Intel 530 series 240Gb

## Applied DSDT Patches

TODO

## Kexts

TODO

## What is working

* GPU Acceleration (for success work and avoiding 8 apples required UEFI+CSM settings in BIOS)
* Battery indicator
* Backlight (fn+Up/Down and fn+F3/F5)
* Sound (tested only build-in speakers and microphone). CodecCommander.kext used to keep sound working after sleep.
* Touchpad with gestures
* Sleep
* SSD Trim is disabled for APFS otherwise you will have long boot and lot of warnings during boot
* Wi-Fi
* Network must working but not tested

## Partially working

* USB ports working but with issues because of MSI EPF USB device (keyboard backlight). Required additional configuration.

## TODO

* Web Camera sometimes working. Need to finalize USB configuration.
* Check and fix if Intel SpeedStep working and configured correctly
*
