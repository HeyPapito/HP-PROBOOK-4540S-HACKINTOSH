# Mac OS X 10.15.7 FOR HP PROBOOK 4540S

<img align="right" src="https://dortania.github.io/docs/latest/Logos/Logo-.png" alt="Critter" width="200">

* Bootloader: [OpenCore 0.6.2](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.6.2)
* Please note that although this EFI works for my laptop (almost) perfect, it may damage your hardware (especially because I don't use the pre-built ACPI), if you try this on your laptop, I am not responsible so this should be used for testing purposes. You have been warned.
* Need to generate your own serial number, UUID and MLB to prevent potential ban from Apple Services for multiple devices with same info.
Generate your own here: https://github.com/corpnewt/GenSMBIOS

# Screenshots
![1](./screenshoot/1.png)
![2](./screenshoot/2.png)
![3](./screenshoot/3.png)
![4](./screenshoot/4.png)

# Specs
```
Model              HP Probook 4540s
Mainboard          Mobile Intel HM76 chipset
CPU                Intel® Core i5 processors, Dual Core (3-MB L3 cache, 35W)
Memory             8GB DDR4 1333MHz (4G+4G)
Graphics           Intel HD Graphics 4000
Audio              IDT 92HD87
Ethernet           Realtek RTL8151FH-CG 10/100/1000
Wi-Fi              Broadcom BCM94352HMB
Monitor            HD 1366x768
BIOS Verison       F.68 Rev.A
macOS Verison      10.15.6 Catalina
OpenCore Version   0.6.2
```
## What is working?  
* Battery Indicator
* Continuity (Handoff, Sidecar (untested but should work), Markup/Sketch, Camera, Universal Clipboard, AirDrop)
* Internal Speaker + Headphone + HDMI + HDMI Sounds
* Ethernet + WiFi + Bluetooth
* USB
* Trackpad & some gestures
* Brightness, FN Brightness
* Sleep + Wake + Shutdown + Restart
* CPU Power Management
* IGPU / QE/CI working good
* iServices
* Webcam

## What doesn't work?  
* Apple Watch unlock (Unreliable and rarely connects)
* Please submit an issue if you find anything

# Thanks to:
## **Developers of OpenCore**:
* [al3xtjames](https://github.com/al3xtjames)
* [Andrey1970AppleLife](https://github.com/Andrey1970AppleLife)
* [Download-Fritz](https://github.com/Download-Fritz)
* [Goldfish64](https://github.com/Goldfish64)
* [nms42](https://github.com/nms42)
* [PMHeart](https://github.com/PMHeart)
* [savvamitrofanov](https://github.com/savvamitrofanov)
* [vit9696](https://github.com/vit9696)  
For their wonderful, powerful [OpenCore bootloader](https://github.com/acidanthera/OpenCorePkg)
## **Guide Writer**
* [CorpNewt](https://github.com/corpnewt)
* [Midi](https://github.com/midi1996)
* [DhinakG](https://github.com/dhinakg)
* [Khronokernel](https://github.com/khronokernel)
* [and the rest of the dortania team](https://github.com/dortania)  
For their best, extremly easy to understand [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/) which help me almost everything in setting my EFI

## Credits
@RehabMan for all add in patch hp probook 4530s/4540s
@chriss111 for theme
nguyenhung9x2020 for original EFI creation and support
