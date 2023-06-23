# Dell_Inspiron_13-7378-Hackintosh
[Alpha] [WIP] An OpenCore Bootloader EFI for the Dell Inspiron 13 7378 2-in-1 Laptop.

# My Specifications:
- Intel Core i5-7200U (Kaby Lake) CPU
- Intel HD Graphics 620 GPU
- SK Hynix 16GB (2x8GB) DDR4-2400 RAM
- WD Green M.2 2280 240GB SSD
- BOE 1080p Touchscreen Panel
- RealTek USB 2.0 Card Reader (0BDA-0177)
[Probably the RTS51XX family as per [this](https://github.com/0xFireWolf/RealtekCardReader#:~:text=RTS5179-,USB,-2.0/3.0%20Card) and [this](https://deviceinbox.com/usb/vid-0BDA-pid-0177.html#:~:text=10%0Av.10.0.22621.31277-,Realtek%20USB%202.0/3.0%20CR%20RTS51XX%20Driver,-Windows%2010%2C%20Windows)]
- RealTek ALC225 Sound Card ([AppleALC Info](https://github.com/acidanthera/AppleALC/blob/master/Resources/ALC225/Info.plist))
- Intel Dual Band Wireless AC 3165 Card (Supported by [itlwm](https://openintelwireless.github.io/itlwm/Compat.html#dvm-iwn:~:text=Intel(R)%20Dual%20Band%20Wireless%20AC%203165))
- Intel Integrated Bluetooth Module (8087-0A2A) (Supported by [IntelBluetoothFW](https://openintelwireless.github.io/IntelBluetoothFirmware/Compat.html#supported-devices:~:text=USB%20IDs%20are%3A-,0x8087%2C%200x0a2a,-0x8087%2C%200x07dc))
