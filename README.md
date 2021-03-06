# EFI folder for Ryzentosh installation (macOS Big Sur Version 11.1)

based on [Dortania's OpenCore Guide](https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#starting-point).

![Screenshot](/screenshot.png?raw=true)

## Specification

| **Component** | **Model**                                    |
| ------------- | -------------------------------------------- |
| CPU           | AMD Ryzen 9 3950X 16-Core @ 3.5GHz           |
| MB            | ASUS ROG Strix X570-F Gaming                 |
| GPU           | Gigabyte Radeon RX 580 Gaming 8G             |
| RAM           | 32 GB G.Skill Trident Z Neo DDR4 @ 3600MHz   |
| SSD           | 1 TB Corsair Force Series MP600 Gen.4 PCIe   |
| WIFI, BT      | Apple Broadcom BCM94360CD Wifi Bluetooth 4.0 |

## Installation

Create the [macOS installer](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install.html#downloading-macos-modern-os)

Use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) to generate your SMBIOS data for your `config.plist`.

Follow [Dortania's OpenCore Big Sur Installation Guide](https://dortania.github.io/OpenCore-Install-Guide/extras/big-sur/#table-of-contents).

## Working

- Wifi, Bluetooth, Ethernet
- iMessage, iCloud, Facetime, App Store
- Airdrop, Airplay, AirPods Handoff, Sidecar
- All USB ports
- Authenticate with Apple Watch
