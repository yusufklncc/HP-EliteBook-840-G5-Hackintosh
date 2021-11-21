<!-- omit in toc -->
# macOS on HP EliteBook 840 G5

<h3> 
    English
</h3>

<img align="right" src="https://i.loli.net/2021/02/17/KqIEFsp6SjneLTY.png" width="250px" alt="preview">

OpenCore config for Hackintosh OpenCore HP EliteBook 840 G5.

[![macOS](https://img.shields.io/badge/macOS-11.6.1-orange)](https://www.apple.com/tr/macos/big-sur/)
[![OpenCore](https://img.shields.io/badge/OpenCore-0.7.4-9cf)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/download-lastest%20version-blue.svg)](https://github.com/relaxewdy/HP-EliteBook-840-G5-Hackintosh/releases)



<!-- omit in toc -->
# Laptop's Hardware

| **HP** | Details                                                  |
| ------------------- | ------------------------------------------- |
| Model Name      | HP Elitebook 840 G5      |
| CPU              | Intel(R) Core(TM) i7-8550U CPU @ 1.80GHz (max 4.00Ghz) Kaby Lake R             |
| RAM           | 32 GB 2400 MHz DDR4    |
| Internal Graphics Card | Intel® UHD Graphics 620                     |
| Wi-Fi             | Intel 8265 (replaced by BCM94360CS2) |
| Ethernet          | Intel I219  |
| Audio       | Conexant CX8200                      |

# Update History
- [x] macOS Big Sur 11.6.1
- [x] macOS Big Sur 11.0.1

# What's Working?
|                                 |                                    |
| -----------------------------------  | -------- |
|  Turbo boost and CPU frequency stage |  ✅  |
|  Intel UHD Graphics 620              |  ✅  |
|  Brightness control                  |  ✅  |
|  HDMI                                |  ✅  |
|  Audio Conexant CX8200         |  ✅  |
|  Intel I219 Ethernet                      |  ✅  | 
|  BCM94360CS2 Wi-Fi and Bluetooth, Airdrop, Handoff, SideCar, iMessage...         |  ✅  |
|  USB 3.0 and Type-C (with Port Map)        |  ✅  |
|  Touchpad (14 gestures are working)   |  ✅  |
|  Battery status   |  ✅  |
|  Camera   |  ✅  |
|  Shutdown / Reboot   |  ✅  |
|  Fn shortcut keys   |  ✅  | 

# What's not working?
|                                 |                                    |
| -----------------------------------  | -------- |
|  S3 Sleep / Wake   | ❌  |
|  S4 Hibernation / Wake   |  ❌  |

# What You Have to Do?
|                                 |                                    |
| -----------------------------------  | -------- |
|  SMBIOS Settings  | ⚠️ |

With OpenCore Configurator you should definitely set your SMBIOS settings because the config does not contain SMBIOS information MacBook Pro 16.3
