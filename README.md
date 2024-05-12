# Z690M Hackintosh

Hackintosh Gigabyte Z690M AORUS ELITE DDR4 + I7-12700K + RX6800XT

<p align="center">
    <a href="https://www.apple.com/macos/monterey/">
        <img src="https://img.shields.io/badge/Sonoma-14.0-purple"></a>
    <a href="https://github.com/acidanthera/OpenCorePkg">
        <img src="https://img.shields.io/badge/OpenCore-1.0.0-blue"/></a>
</p>

<p align="center">
    <a href="">
        <img src="https://i.imgur.com/SzmpV4V.png" alt="Z690M Hackintosh"> </a>
</p>

# Features

| Feature                    | Status | Dependency                         |
| :------------------------- | ------ | ---------------------------------- |
| iCloud, iMessage, FaceTime | ✅     | Whitelisted Apple ID, Valid SMBIOS |
| AirDrop                    | ✅     | OCLP                               |
| Audio                      | ✅     | `AppleALC.kext`                    |
| WiFi                       | ✅     | OCLP                               |
| Bluetooth                  | ✅     | OCLP                               |
| Ethernet                   | ✅     | `AppleIGC.kext`                    |
| USB 2.0, USB 3.0, Type-C   | ✅     | `USBToolBox`                       |

# Specification

| Category  | Info                                       |
| --------- | ------------------------------------------ |
| CPU       | Intel Core i7-12700K (E-P Core enabled)    |
| SSD       | Western Digital Black SN750 500GB          |
| RAM       | 32GB DDR4 3200 Mhz                         |
| AUDIO     | ALC897                                     |
| LAN       | Intel I225-V                               |
| GPU       | SAPPHIRE PULSE Radeon RX 6800 XT 16G GDDR6 |
| WiFi & BT | BCM94360CS2                                |

## Read these before you start:

- [dortania's Hackintosh guides](https://github.com/dortania).
- [dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/).
- [dortania's OpenCore Post Install Guide](https://dortania.github.io/OpenCore-Post-Install/).
- [dortania/ Getting Started with ACPI](https://dortania.github.io/Getting-Started-With-ACPI/).
- [dortania/ opencore `multiboot`](https://github.com/dortania/OpenCore-Multiboot).
- [dortania/ `USB map` guide](https://dortania.github.io/OpenCore-Post-Install/usb/).
- [OCLP fix BCM WiFi on macOS Sonoma](https://dortania.github.io/OpenCore-Legacy-Patcher/).
- `Configuration.pdf` and `Differences.pdf` in each `OpenCore` releases.

## Wi-Fi CARD

My Wi-Fi card is BCM94360CS2, you need to get a NGFF card like this one.

<p align="center">
    <a href="">
        <img src="https://i.imgur.com/qnRNLmP.jpg" alt="Wifi Hackintosh" width="400"> </a>
</p>

# Credits

- [Apple](https://www.apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for all the kexts/utilities that they made.
- [Dortania](https://github.com/dortania) for the OpenCore Install Guide and OCLP.
