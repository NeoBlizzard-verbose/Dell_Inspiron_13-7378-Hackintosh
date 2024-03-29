# OpenCore BSP - Dell Inspiron 13 7378
## For educational purposes only

<img width="698" alt="Screen Shot 2024-02-25 at 9 56 11 PM" src="https://github.com/NeoBlizzard-verbose/Dell_Inspiron_13-7378-Hackintosh/assets/44337253/a4f51524-6c49-46c9-88b9-77cde22deecd">


## Specs

| Component      | Brand                                     |
|----------------|-------------------------------------------|
| **CPU**        | `Intel Core i5-7200U`                     |
| **iGPU**       | `Intel HD Graphics 620`                   |
| **Storage**    | `WD Green M.2 2280 SATA III 240GB`        |
| **Audio Code** | `Realtek ALC225` [AppleALC Info✨](https://github.com/dreamwhite/ChonkyAppleALC-Build/blob/master/Realtek/ALC225.md)                          |
| **WiFi Card**  | `Fenvi Broadcom BCM94360NG`               |
| **OS**         | `macOS Monterey`                          |
| **BIOS**       | `v1.36.0`                                 |

## Supported versions

| Version 	| Supported 	|
|---	|---	|
| 10.13.x 	| :heavy_exclamation_mark: Untested! Should work, theoretically	|
| 10.14.x 	| :white_check_mark: 	|
| 10.15.x 	| :white_check_mark: 	|
| 11.x 	| :white_check_mark: 	|
| 12.x 	| :white_check_mark: 	|
| 13.x 	| ❓ 	|
| 14.x 	| ❓ 	|

----------------------------------
### Working/Not working:

###### Click on the arrow icons to expand the spoilers
<details>
<summary>iGPU</summary>
  
- [x] Intel HD 530 iGPU Backlight support
- [ ] Intel HD 530 iGPU HDMI1.4b Output (1920x1080@120Hz)
- [x] Intel HD 530 iGPU Type-C to HDMI Output
- [x] Intel HD 530 iGPU - H264 & HEVC
</details>

<details>
<summary>Audio</summary>
ALC225
  
- [x] Internal Speakers
- [x] Internal Microphone
- [x] Combojack headphones
- [ ] Combojack microphone
- [ ] HDMI Audio Output
- [ ] Type-C to HDMI Audio Output
- [x] Type-C Audio Output
</details>

<details>
<summary>USB</summary>
  
- [x] All USB ports working and mapped
- [x] SD Card Reader (USB based)
- [x] Webcam (USB based)
</details>

<details>
<summary>Keyboard</summary>
  
- [x] Keyboard (PS2 based)
- [x] HID Key PWRB & SLPB 
- [x] F11 & F12 remapped brightness keys
- [ ] F13 Print Screen remapped key
- [x] Multimedia control sound keys on the side
</details>

<details>
<summary>Trackpad</summary>
  
- [x] I2C Touchpad with gestures
- [ ] Force Touch
</details>


<details>
<summary>Misc</summary>
  
- [x] SpeedStep
- [x] Sleep/Wake using both `hibernatemode` `0` and `25`
- [x] SATA/NVMe PCIe Gen3x4 on M.2 slot
- [x] Sensors CPU, iGPU, Battery, NVMe, Fans
- [x] Native ACPI Battery 8-bit support
- [x] Native NVRAM support
- [x] Recovery (macOS) boot from OpenCore
- [x] Windows 10/Linux boot from OpenCore
- [ ] macOS Ventura Continuity Camera
</details>

### Documentation

TBA

## Brightness keys

Fluid brightness switch steps with 'enable-backlight-smoother' WhateverGreen property. Fixed brightness key presses using appropriate SSDTs. [Reference](https://dortania.github.io/Getting-Started-With-ACPI/Laptops/trackpad-methods/manual.html#osi-to-xosi:~:text=584f5349-,Dell%20Machines,-%23)

# IORegistryExplorer dump

TBA

## Issues

Currently known issues are found in the issues tab at the top.
If you encounter any other issue, feel free to file it. However, there's no guarantee that it will be worked upon...

## Credits

* **Apple** for macOS
* [**Acidanthera**](https://github.com/acidanthera) for OpenCore and the majority of the kexts
* pixotna for fixing touchscreen and touchpad
* Dreamwhite for this readme layout
* **every other people that contributed to the hackintosh world :haha:**
