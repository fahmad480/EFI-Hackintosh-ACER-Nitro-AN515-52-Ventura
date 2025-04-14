# EFI Hackintosh ACER Nitro AN515-52 Ventura (And Sequoia)

![Desktop Screenshot](https://github.com/fahmad480/EFI-Hackintosh-ACER-Nitro-AN515-52-Ventura/blob/main/Documentation/SS1.jpg?raw=true)

## Installation
Please follow this [Dortania Guide](https://dortania.github.io/OpenCore-Install-Guide/) and download RAW Hackintosh Ventura from [Olarila](https://www.olarila.com/topic/6278-olarila-vanilla-images-macos-installer/)

The Sequoia version is available in the "OpenCore (Sequoia)" folder.

## My Device Condition
- Dual Boot (Windows 11 & Hackintosh Ventura (And Sequoia))
- EFI on 1TB SSD VenomRX, but all bootable (Windows and Hackintosh) is from 512GB NVME M.2 Adata XPG SX8200 Pro
- Bootable manually update using BooticeX64

## Specification:
- Processor: Intel Core i5-8300H
- RAM: 24GB DDR4 PC21000 / 2666Mhz
- iGPU: Intel UHD 630
- eGPU: NVIDIA GTX 1050
- Storage: 1x 1TB SSD VenomRX + 1x NVME M.2 512GB Adata XPG SX8200 Pro
- Ethernet: Realtek RTL8168
- Wi-Fi: Intel AC9560 Wi-Fi + Bluetooth
- USB: Intel Chipset
- Audio Codec: Realtek ALC255
- Touchpad: ELAN ELAN0504 I2C Interface
- Display Size: 15.6 Inch
- Monitor Resolution: Full HD 1920 x 1080
- Boot Mode: UEFI
- Clover version: OpenCore r0.9.5
- OS Version: macOS Ventura 13.6.6 (From Olarila)

## What's Working?
- QE/CI Graphics Of iGPU UHD Graphics 630
- Restart, Sleep and Shutdown
- Internal Speaker, Headphone audio and Internal Mic
- Brightness
- Brightness Button Up / Down
- Audio Button Up / Down
- Backlight Keyboard
- Touchpad
- Ethernet
- Wi-Fi (Works but can't connect to iOS tethering)
- Bluetooth (Works but can't connect to any device even wireless mouse)
- Battery Indicator
- All USB Ports (2x USB Type A 2.0, 1x USB Type A 3.0, 1x USB Type C)
- Airdrop (But you need to change M.2 WiFi & Bluetooth card to BCM94360NG Wi-FI & Bluetooth M.2 Card)
- Etc

## What's Not Working?
- Nvidia GTX1050 (GTX 1050 is not supported by Ventura above)
- HDMI Output and Audio (Because HDMI Port routed from eGPU/Nvidia)