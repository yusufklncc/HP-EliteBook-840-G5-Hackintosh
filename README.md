<!-- omit in toc -->
# <img align="left" src="https://github.com/yusfklncc/HP-EliteBook-840-G5-Hackintosh/blob/main/Apple.png" width="30px" alt="preview">macOS on HP EliteBook 840 G5

<h3> 
    English
</h3>

<img align="right" src="https://i.loli.net/2021/02/17/KqIEFsp6SjneLTY.png" width="250px" alt="preview">

OpenCore config for Hackintosh OpenCore HP EliteBook 840 G5.

[![macOS](https://img.shields.io/badge/macOS-11.6-orange)](https://www.apple.com/tr/macos/big-sur/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.7.3-9cf)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/download-lastest%20version-blue.svg)](https://github.com/relaxewdy/HP-EliteBook-840-G5-Hackintosh/releases)

## Screenshot
<details>
<summary>Big Sur</summary>

![]()

</details>

<!-- omit in toc -->
## Hardware

| **HP** | Detail                                                  |
| ------------------- | ------------------------------------------- |
| Model Name      | HP Elitebook 840 G5      |
| CPU              | Intel(R) Core(TM) i7-8550U CPU @ 1.80GHz (max 4.00Ghz) Kaby Lake R             |
| RAM           | 32 GB 2400 MHz DDR4    |
| Graphic Card | Intel® UHD Graphics 620                     |
| Wi-Fi             | BCM94360CS2 |
| Sound       | Conexant CX8200                      |

## What are working

| **Details**                                |                                    |
| -----------------------------------  | -------- |
|  Turbo boost and CPU frequency stage |  ✅  |
|  Intel UHD Graphics 620              |  ✅  |
|  Brightness control                  |  ✅  |
|  HDMI                                |  ✅  |
|  Audio Conexant CX8200         |  ✅  |
|  Intel Ethernet                      |  ✅  | 
|  BCM94360CS2 Wi-Fi and Bluetooth, Airdrop, Handoff, SideCar, iMessage...         |  ✅  |
|  USB 3.0 and Type-C (with Port Map)        |  ✅  |
|  Touchpad (14 gestures are working)   |  ✅  |
|  Battery status   |  ✅  |
|  Camera   |  ✅  |
|  Fn shortcut keys   |  ✅  |

## What aren't working

| **Details**                                |                                    |
| -----------------------------------  | -------- |
|  S3 Sleep / Wake   | ❌  |
|  S4 Hibernation / Wake   |  ❌  |


## What You Have to Do

- SMBIOS Settings

With OpenCore Configrator you should definitely set your SMBIOS settings because the config does not contain SMBIOS information.
  - MacBookPro16,3
