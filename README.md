# HP-15ay513tx-Hackintosh-Opencore
This uses Opencore's latest 0.7.8 release along with faster boot time and a modern MacOs- like multibooter.

Currently Running:
Component	Version
macOS version	11.1 (20C69)
OpenCore	0.6.6
Hardware Info
Component	Model
CPU	Intel® Core™ i3-6006U (2 GHz, 3 MB cache, 2 cores)
Memory	8 GB DDR4-2133 SDRAM (1 x 8 GB)
Video Graphics [DGPU]	AMD Radeon™ 520 Graphics (2 GB DDR3 dedicated)
Storage	Toshiba 1 TB 5400 rpm SATA//
Display	39.62 cm(15.6) diagonal FHD SVA anti-glare WLED-backlit (1920 x 1080)
GPU [iGPU]	Intel HD 520
Camera	HP TrueVision HD Camera with integrated digital microphone
WLAN	Realtek RTL8723DE 802.11b/g/n (1x1) and Bluetooth® 4.0 combo
Touchpad	Synaptics SMBus Touchpad with multi-touch gesture support
Battery Type	4-cell, 41 Wh Li-ion
Kexts
Kext	Version	Remark
AppleALC	1.6.1	Fixes onboard audio
Lilu	1.5.3	Kext patcher
SMCBatteryManager	1.2.4	Battery indicator
SMCProcessor	1.2.4	CPU temp monitoring
SMCSuperIO	1.2.4	Monitor fan speed, not working
VirtualSMC	1.2.4	SMC chip emulation
VoodooRMI	1.3.3	Trackpad driver
VoodooSMBUS	1.3.3	SMBUS driver
VoodooPS2Controller	2.2.3	Enable keyboard
WhateverGreen	1.5.0	Graphics
RealtekRTL8111	2.4.2	Ethernet
BrightnessKeys	1.0.2	Fixes Brighness function keys
ACPI patches

All of the following SSDT's have been manually compiled by me such that they improve performance and boot time. These will not work for other laptops.

Patch	Remark
SSDT-GPIO	Trackpad fix
SSDT-PLUG	x86 plugin injection fix
SSDT-PNLF	Backlight fix
SSDT-EC-USBX	USBX patch
SSDT-dGPU-Off	Disabled Radeon Discrete Graphics
Status
Working
 Keyboard (including all media keys except for brightness)
 Battery indicator
 Audio
 Ethernet(With some issue of speed and Replugging ethernet requires witching ethernet of then on to work again or reboot)
 USB Tethering Supported working very good with great speed
 iCloud services - iMessage, FaceTime, AppStore
 GPU acceleration
 Camera
 Microphone
 Mac-like booting interface for multiboot
 Sleep/wake
 Trackpad and gestures
 HDMI video up to 4k (Audio does not work)
 Brightness keys with pressing fn key
Working, sort of
 Native CPU power management. It seems that Mac OS Drains more battery than windows.

Not Working at the moment
 Wifi(Card Not supported- realtek rtl8723be)
 Bluetooth (Card Not supported)
 Display auto brightness
 Handoff, continuity
 AirPlay


CREDITS
sortedcord
Acidanthera
Dortania OC guide
Rehabman's battery patch guide and Rehabman's ACPI hotpatching guide
CorpNewt's tools
VoodooRMI

