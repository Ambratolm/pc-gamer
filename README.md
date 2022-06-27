# 🚀 PC Gamer

[![Markdown](https://img.shields.io/badge/Markdown%20Document-00a2ed?style=for-the-badge&color=e3e3e3&logoColor=3d3d3d&logo=markdown)](https://github.com/topics/markdown)
[![Windows](https://img.shields.io/badge/Windows%20Computer-e3e3e3?style=for-the-badge&logoColor=00a2ed&logo=windows)](https://github.com/topics/windows)

**Quick and summarized Gaming PC build guide** for a multi-purpose fair computer to comfortably use for any type of activities either production (developement, graphic design, video editing, ...etc) or entertainment (gaming, video playback, ...etc).

<!-- ![Screenshot](./screenshot.gif?raw=true) -->

<!-- toc -->

- [📖 The Guide](#%F0%9F%93%96-the-guide)
  - [1. Processor (CPU)](#1-processor-cpu)
    - [CPU Cooler [Optional]](#cpu-cooler-optional)
  - [2. Graphic Card (GPU)](#2-graphic-card-gpu)
  - [3. Motherboard](#3-motherboard)
  - [4. Memory (RAM)](#4-memory-ram)
  - [5. Storage (SSD + HDD)](#5-storage-ssd--hdd)
  - [6. Case](#6-case)
  - [7. Power Supply (PSU)](#7-power-supply-psu)
  - [8. Monitor](#8-monitor)
- [📚 References](#%F0%9F%93%9A-references)
- [📄 License](#%F0%9F%93%84-license)

<!-- tocstop -->

## 📖 The Guide

### 1. Processor (CPU)

| Specification                     | Available           | Recommanded           |
| --------------------------------- | ------------------- | --------------------- |
| Manufacturer                      | Intel, AMD          | Any                   |
| Socket                            | LGA?, AM4, ...etc   | Motherboad Compatible |
| Cores                             | 1 - 64 Cores        | 6 - 16 Cores          |
| Threads (Cores x 2)               | 2 - 128 Threads     | 12 - 32 Threads       |
| Performance Core Clock            | 1.3 - 4.7 GHz       | 3 - 4 GHz             |
| Performance Boost Clock (Turbo)   | None, 2.1 - 5.5 GHz | 4 - 5 GHz             |
| Total Cache Memory (L1 + L2 + L3) | 1 - 32 MB           | High (~ 22)           |
| Simultaneous Multithreading (SMT) | No, Yes             | Yes                   |
| Integrated Graphics (iGPU)        | None, [Some iGPU]   | None                  |
| Thermal Design Power (TDP)        | 20 - 280 W          | Average (~ 100)       |

| Brand                     | Generation (Serie)    | Recommanded               |
| ------------------------- | --------------------- | ------------------------- |
| Intel Core i3, i5, i7, i9 | 1 - 12 (1000 - 12000) | i7 - i9 @ 1000 - 12000    |
| AMD Ryzen 3, 5, 7, 9      | 1 - 5 (1000 - 7000)   | Ryzen 5 - 9 @ 5000 - 7000 |

- 💡 [Intel and AMD CPU Naming Scheme](./images/cpu-naming.jpg?raw=true)
- 💡 [CPU Name Suffixes](./images/cpu-name-suffixes.png?raw=true)

#### CPU Cooler [Optional]

| Specification                      | Available      | Recommanded |
| ---------------------------------- | -------------- | ----------- |
| Fan Rotations Per Minute (Fan RPM) | 100 - 5500 RPM | Highest     |
| Noise Level                        | 0 - 56 dB      | Lowest      |
| Radiator Size                      | 120 - 420 mm   | Average     |

### 2. Graphic Card (GPU)

| Specification | Available                      | Recommanded       |
| ------------- | ------------------------------ | ----------------- |
| Chipset       | Nvidia, AMD                    | Nvidia            |
| Memory (VRAM) | 0.125 - 48 GB (GDDR5 - GDDR6X) | 6 - 24 GB (GDDR6) |
| Core Clock    | 115 - 2593 MHz                 | 1400 - 1700 MHz   |
| Boost Clock   | None / 720 - 2825 MHz          | 1500 - 1800 MHz   |
| Length        | 69 - 356 mm                    | Average           |

| Brand              | Generation (Serie)    | Recommanded        |
| ------------------ | --------------------- | ------------------ |
| Nvidia GeForce GTX | 10 - 16 (1000 - 1600) | GTX 1650 - 1660 Ti |
| Nvidia GeForce RTX | 20 - 30 (2000 - 3000) | RTX 2060 - 3090 Ti |
| AMD Radeon RX      | 4 - 6 (5000 - 6000)   | RX 5700 X          |

- 💡 [GPU Naming Scheme](./images/gpu-naming.webp?raw=true)

### 3. Motherboard

| Specification      | Available                      | Recommanded           |
| ------------------ | ------------------------------ | --------------------- |
| CPU Socket         | LGA?, AM4, ...etc              | CPU Compatible        |
| Form Factor        | mini ITX, micro ATX, ATX, EATX | ATX                   |
| Memory (RAM) Max   | 2 - 128 GB                     | 128 GB                |
| Memory (RAM) Slots | 1 - 16                         | 4 - 16                |
| Memory (RAM) Speed | DDR 333 - DDR5 6600            | DDR4 2000 - DDR4 4000 |

### 4. Memory (RAM)

| Specification                      | Available               | Recommanded          |
| ---------------------------------- | ----------------------- | -------------------- |
| Speed (Bus Clock)                  | DDR 333 - DDR5 6600 MHz | DDR4 2000 - 3000 MHz |
| Modules                            | 1 x 512 MB - 8 x 32 GB  | 2 x 8 GB - 2 x 16 GB |
| Column Access Strobe (CAS) Latency | 3 - 40 CL               | Low (~ 14 CL)        |
| Timing                             | 4-4-4-12 - 40-40-40-96  | Low (~ 14-14-14-20)  |
| First Word Latency\*               | 6 - 18.018 ns           | Low (~ 10 ns)        |
| Voltage\*                          | 1.1 - 2.5 V             | 1.2 V                |
| Heat Spreader                      | No / Yes                | Yes                  |

- 💡 First Word Latency = CAS x 2000 / Speed
- 💡 Up to 2666 MHz runs at 1.2 V by default. Overlocking (XMP Profile) to 3000 MHz turns to 1.35 V.

### 5. Storage (SSD + HDD)

| Specification | Available                   | Recommanded                |
| ------------- | --------------------------- | -------------------------- |
| Type          | SSD, HDD                    | SSD (256 GB), HDD (1 TB)   |
| Capacity      | 8 - 20 TB                   | 0.256 - 1 TB               |
| Cache         | 2 - 131072 MB               | 512 - 1024 MB              |
| Form Factor   | 2.5", 3.5" , M.2-2280       | 3.5" (HDD), M.2-2280 (SDD) |
| Interface     | SAS - SATA (3.0 - 6.0 Gb/s) | SATA 6.0 Gb/s              |

### 6. Case

| Specification               | Available                          | Recommanded    |
| --------------------------- | ---------------------------------- | -------------- |
| Type                        | ATX Mid - Full Tower, ...etc       | ATX Mid Tower  |
| Motherboard Form Factor     | mini ITX, micro ATX, ATX, EATX     | ATX            |
| Power Supply (PSU)          | None / 60 - 1350 W                 | None           |
| Side Panel Window           | None, Acrylic, Mesh, ...etc        | Any            |
| Power Supply Shroud         | No / Yes                           | Yes            |
| Front Panel USB             | None, USB 3.2 Gen 1 Type-A, ...etc | Any            |
| External 5.25" Bays         | 0 - 12                             | Fair (~ 4)     |
| External 3.5" Bays          | 0 - 15                             | Fair (~ 4)     |
| Internal 5.25" Bays         | 0 - 20                             | Fair (~ 4)     |
| Internal 3.5" Bays          | 0 - 17                             | Fair (~ 4)     |
| Full-Height Expansion Slots | 0 - 11                             | Fair (~ 7)     |
| Half-Height Expansion Slots | 0 - 6                              | Fair (~ 3)     |
| Provided Fans               | 0 - 6                              | High (~ 4)     |
| Case Materials              | Metal, Plastic,...etc              | Plastic, Metal |

### 7. Power Supply (PSU)

| Specification     | Available                                    | Recommanded  |
| ----------------- | -------------------------------------------- | ------------ |
| Form Factor       | SFX, Flex ATX, ATX, TFX, ...etc              | ATX          |
| Efficiency Rating | 80+ Bronze, Silver, Gold, Platinum, Titanium | 80+ Gold     |
| Wattage           | 180 - 2000 W                                 | 650 - 1000 W |
| Modular Cabling   | No / Semi / Full                             | Full         |

### 8. Monitor

| Specification       | Available                                  | Recommanded       |
| ------------------- | ------------------------------------------ | ----------------- |
| Screen Size         | 15" - 65"                                  | High (~ 27")      |
| Resolution          | 178 x 178 - 7680 x 4320 (SD - 8K)          | High (~ 4K)       |
| Refresh Rate        | 30 - 360 Hz                                | High (~ 144 Hz)   |
| Response Time (G2G) | 0.1 - 25 ms                                | Low (~ 1 ms)      |
| Panel Type          | AHVA, PLS, IPS, OLED, PVA, QD-OLED, TN, VA | IPS               |
| Aspect Ratio        | 1:1 - 683:240                              | 16:9              |
| Brightness          | 30 - 1600 cd/m²                            | Fair (~250 cd/m²) |
| Widescreen          | No / Yes                                   | Yes               |
| Curved Screen       | No / Yes                                   | ?                 |
| Frame Sync          | None / Nvidia G-Sync, AMD FreeSync, ...etc | FreeSync          |
| Built-in Speakers   | No / yes                                   | Yes               |
| Inputs              | DisplayPort, ...etc                        | All               |

- 💡 [Monitor Resolution Comparison Chart](./images/monitor-resolutions.png?raw=true)
- 💡 [Monitor Screen Sizes](./images/monitor-screen-sizes.jpg?raw=true)
- 💡 [Monitor Panel Types](./images/monitor-panel-types.webp?raw=true)

## 📚 References

- 🌐 [PC Part Picker](https://pcpartpicker.com/)
- 🌐 [Ultra PC](https://www.ultrapc.ma/)
- 📄 [What Is CPU Cache? (L1, L2, And L3 Cache)](https://cpuninja.com/cpu-cache/)
- 📄 [Intel Processor Names and Numbers](https://www.intel.com/content/www/us/en/processors/processor-numbers.html)
- 📄 [Understanding AMD Processor Names](https://glennsqlperformance.com/2020/07/22/understanding-amd-processor-names/)
- 📄 [CPU Sockets Types [LGA, PGA, ZIF, BGA], Intel vs AMD Sockets](https://digitalworld839.com/types-of-cpu-sockets/#Intel_vs_AMD_CPU_Sockets)
- 📄 [Do Monitor Refresh Rates Matter? Everything You Need to Know](https://www.makeuseof.com/tag/60hz-vs-144hz/)
- 📄 [LCD Panel Types Explored](https://pcmonitors.info/articles/lcd-panel-types-explored/)
- 📄 [TN vs. VA vs. IPS Which Monitor Panel is Best for Gaming?](https://www.benq.com/en-us/knowledge-center/knowledge/how-to-choose-between-tn-va-and-ips-panels-for-the-games-you-play.html)
- 📕 [The Complete Build Your Own Pc Manual](https://www.google.com/search?q=The+Complete+Build+Your+Own+Pc+Manual)
<!-- - 📹 [Channel: ...]() -->

## 📄 License

- Images: Referenced images are picked from Google Images. 😺
- Guide without images: [MIT](./LICENSE)
