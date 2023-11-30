# MaaXBoard-HUB
![Title](https://github.com/Avnet/MaaXBoard-HUB/assets/88205887/3f4c4d19-b7d9-4991-8aae-bd9100a837e2)

Welcome to the information hub for MaaXBoard, featuring the [NXP i.MX 8M](https://www.nxp.com/products/processors-and-microcontrollers/arm-processors/i-mx-applications-processors/i-mx-8-applications-processors/i-mx-8m-family-armcortex-a53-cortex-m4-audio-voice-video:i.MX8M) applications processor based on Arm® Cortex®-A53 and Cortex-M4 cores provide advanced audio, voice and video processing for applications that scale from consumer home audio to industrial building automation and mobile computers. This repository serves as a central hub for all resources related to MaaXBoard. <br />

[Buy MaaXBoard](https://www.avnet.com/wps/portal/us/products/avnet-boards/avnet-board-families/maaxboard/maaxboard?family=&nodeClicked=d8e2c09b-9600-4ba7-b7ed-82a834b5177d)

## Table of Contents
- [MaaXBoard-HUB](#maaxboard-hub)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
    - [Processing](#processing)
    - [Form Factor \& Interfaces](#form-factor--interfaces)
    - [Memory \& Storage](#memory--storage)
    - [Software \& BSP](#software--bsp)
      - [Board Support Package](#board-support-package)
      - [Image Package](#image-package)
      - [Reference Design Tools](#reference-design-tools)
    - [Accessories](#accessories)
  - [Related Repositories](#related-repositories)
  - [Related Blog Posts](#related-blog-posts)
    - [Element14 projects](#element14-projects)
    - [Hackster.io projects](#hacksterio-projects)
  - [Getting Started and Manuals](#getting-started-and-manuals)
    - [Product Brief](#product-brief)
    - [Getting Started Guides](#getting-started-guides)
    - [Hardware Guides](#hardware-guides)
    - [Quick Start Card](#quick-start-card)
    - [Development Guides](#development-guides)
    - [Production Documents](#production-documents)
    - [Release Notes](#release-notes)
    - [Errata and Product Change Notices](#errata-and-product-change-notices)

## About
MaaXBoard is a low-cost, production ready development board in the popular and compact Raspberry Pi form-factor, which supports a versatile set of I/O interfaces. This [NXP i.MX 8M](https://www.nxp.com/products/processors-and-microcontrollers/arm-processors/i-mx-applications-processors/i-mx-8-applications-processors/i-mx-8m-family-armcortex-a53-cortex-m4-audio-voice-video:i.MX8M) processor-based platform contains everything necessary to support and create a Linux, Android, Windows 10 IoT Core, or other OS based system. MaaXBoard provides industry-leading audio, voice, and video processing for applications that scale from consumer home audio to industrial building automation and embedded computers.<br />
<p align="center">
    MaaXBoard is also AWS certified.<br />
    <img src="https://github.com/Avnet/MaaXBoard-HUB/assets/88205887/6d043334-183d-4f79-a8f8-e6214778eb92">
<br />
<details>
    <summary>More information & Specs</summary>

### Processing
The i.MX 8M device is architected with 2 separate processing domains: The application domain includes Quad Arm® Cortex®-A53 cores. The Real Time domain includes an Arm Cortex-M4F core.


### Form Factor & Interfaces
<p align="center">
    <img src="https://github.com/Avnet/MaaXBoard-HUB/assets/88205887/e0aaaa1f-f415-42d0-ba01-51400da6e6e2" width="500">
</p>
MaaXBoard is engineered in compact Raspberry Pi form-factor, which supports a versatile set of I/O interfaces. These include Gigabit Ethernet, two USB 3.0 host interfaces, MIPI DSI display and MIPI CSI camera interfaces, HDMI display supporting up to 4k resolution, Wi-Fi 802.11 b/g/n/ac, Bluetooth 4.2 (BLE), Onboard Ceramic Antenna with an optional external antenna support, a Pi-HAT compatible 40-pin header and Audio Expansion.

Power is sourced via a USB-C connector and is managed via NXP's PCA9460B PMIC on the SOM plus three additional voltage regulators.

### Memory & Storage

MaaXBoard is well resourced with 2GB DDR4 SDRAM, MicroSD Slot, plus eMMC Boot memory expansion support (optional, not populated by default).

### Software & BSP

#### Board Support Package
[Debian source files](https://github.com/Avnet/maaxboard-debian-build)

[Yocto source files](https://github.com/Avnet/meta-maaxboard)

[Android source files](https://github.com/Avnet/android-imx-platform-hardware-imx)

#### Image Package
[Debian Linux Out of Box Image (zip)](https://downloads.element14.com/downloads/zedboard/MaaxBoard/maaxboard/02LinuxShipmentImage_Debian.zip)

[Yocto Linux Out of Box Image V1.1.0r03 (zip)](https://downloads.element14.com/downloads/zedboard/MaaxBoard/maaxboard/02LinuxShipmentImage_Debian.zip)

[Android 9 Out of Box Image (zip)](https://avtinc.sharepoint.com/:u:/t/ET-Downloads/EW03iCLdcKhDqTb67jT6KfkB2xK56wNLuOeKIzSDqklaaQ?e=Qa9FX2)

#### Reference Design Tools
[Android Environment Tools (zip)](https://www.avnet.com/wps/wcm/connect/onesite/88e0cc38-5240-4e57-945e-d18661f6d1c8/AndroidTools.zip?MOD=AJPERES&CVID=nyeiRH4&CVID=nyeiRH4)

[Linux Environment Tools (zip)](https://www.avnet.com/wps/wcm/connect/onesite/5d661cb7-1508-422b-b4a4-d1a65722c92b/03LinuxTools.zip?MOD=AJPERES&CVID=nyej6SX&CVID=nyej6SX)



### Accessories 
Available accessory options include a [MIPI 7-inch display](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-acc-maax-disp2-3074457345648625681/), [MIPI CSI camera](https://www.arducam.com/product/arducam-5mp-mipi-camera-for-rzboard-v2l-with-renesas-rz-v2l-processor/), [Monarch Go Pi HAT](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-sqn-mnrchgo-ht1-g-3074457345643590213?krypto=e0lzEpB9jb7ah4ATyfiftdtPavKJ51pxv9nj8tghkWtFraife%2B18YAUtSlZZwiYtG1f3luULUju9b20mXEPp18V85bfzqsmsRUyjuptqCXtGdXnLNSvpTcsqvon3OBXd) and [5V/3A USB Type C power supply](https://www.avnet.com/shop/us/products/avnet-engineering-services/aes-acc-maax-pwrul-3074457345642357173/).

[View other Avnet boards](https://www.avnet.com/wps/portal/us/products/avnet-boards/)
</details>


## Related Repositories
- [MaaXBoard Metalayer](https://github.com/Avnet/meta-maaxboard): Contains the Yocto metalayer for MaaXBoards as well as **building information**
- [U-boot source code](https://github.com/Avnet/uboot-imx): Contains the source code for U-Boot, a boot loader for Embedded boards.
- [Linux kernel source code](https://github.com/Avnet/linux-imx): Contains the source code for the Linux kernel.
- [imx-mkimage source code](https://github.com/Avnet/imx-mkimage): i.MX Mkimage Bootloader Tool for Yocto and Android.
- [imx-atf source code](https://github.com/Avnet/imx-atf): Trusted Firmware-A (TF-A) is a reference implementation of secure world software for Arm A-Profile architectures.


## Related Blog Posts 
### Element14 projects
[MaaXBoard Chronicles](https://www.element14.com/community/community/designcenter/single-board-computers/blog/2021/08/02/maaxboard-chronicles)

### Hackster.io projects
| Topic | Description | Difficulty |
| -- | -- | -- |
| [Getting Started with MaaXBoard](https://www.hackster.io/monica/getting-started-with-maaxboard-ca362d) | Getting started guide for the Avnet MaaXBoard | Beginner |
| [Getting Started with MaaXBoard - Headless Setup](https://www.hackster.io/monica/getting-started-with-maaxboard-headless-setup-24102b) | Setup the MaaXBoard over UART so you can access it via SSH. Then setup remote desktop. | Beginner |
| [Connect to AWS IoT Core with Avnet's MaaXBoard 8M SBC](https://www.hackster.io/bwilless/connect-to-aws-iot-core-with-avnet-s-maaxboard-8m-sbc-e8ef32) | Getting started guide for connecting an Avnet MaaXBoard 8M SBC to AWS IoT Core. | Intermediate |
| [Running Machine Learning on MaaXBoard's Yocto Image: Part 1](https://www.hackster.io/monica/running-machine-learning-on-maaxboard-s-yocto-image-part-1-6a4796) | The ML Yocto image includes an eIQ layer so you can run machine learning inference efficiently on the MaaXBoard.| Advanced |

## Getting Started and Manuals
### Product Brief
[MaaXBoard Product Brief](https://www.avnet.com/wps/wcm/connect/onesite/98bb51d6-151e-4d0e-9012-033281164209/FY23_1032_MaaXBoard_Product_Brief.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-98bb51d6-151e-4d0e-9012-033281164209-osAVXgj)

### Getting Started Guides
[Getting started with AWS IoT Core and MaaXBoard](https://www.avnet.com/wps/wcm/connect/onesite/8f75806d-197d-49d7-9790-9d95e916946a/AWS-GettingStartedGuideMaaXBoard8M-V1.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-8f75806d-197d-49d7-9790-9d95e916946a-osgy.xl)

[MaaXBoard Android User Manual V1.0-EN](https://www.avnet.com/wps/wcm/connect/onesite/91c5adb3-9938-40a7-aff7-b9c9ef0da804/MaaXBoard-Android-UserManual-V1.0-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-91c5adb3-9938-40a7-aff7-b9c9ef0da804-nubPcPW)

[MaaXBoard Linux Yocto Lite User Manual V1.1-EN](https://www.avnet.com/wps/wcm/connect/onesite/121336f0-a62f-487c-aad9-48a72ea1f7fd/MaaXBoard-Linux-Yocto-Lite-UserManual-V1.1-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-121336f0-a62f-487c-aad9-48a72ea1f7fd-nZCsDkH)

[MaaXBoard-Linux-Yocto-UserManual-V2.0](https://www.avnet.com/wps/wcm/connect/onesite/3cb1a777-3aa8-4394-9ba8-135d9ffa1470/MaaXBoard-Linux-Yocto-UserManual-V2.0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-3cb1a777-3aa8-4394-9ba8-135d9ffa1470-oFe7-h-)

[MaaxBoard Linux Debian User Manual V1.2-EN](https://www.avnet.com/wps/wcm/connect/onesite/11d926e2-386d-4e38-8860-72bb0f5559f5/MaaXBoard-Linux-Debian-UserManual-V1.2-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-11d926e2-386d-4e38-8860-72bb0f5559f5-nubPsyY)

[MaaxBoard Yocto User Manual V1.1-EN](https://www.avnet.com/wps/wcm/connect/onesite/3d2d5ce9-08f3-489f-8965-1e6d4c2a0912/MaaXBoard-Yocto-UserManual-V1.1-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-3d2d5ce9-08f3-489f-8965-1e6d4c2a0912-nubPpDp)

[Windows 10 IoT for Maaxboard - User Guide V1.0](https://www.avnet.com/wps/wcm/connect/onesite/91ed4144-e121-46aa-8ad0-defc0b8ab9c9/Windows_10_IoT_Maaxboard_User_Guide_V1.0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-91ed4144-e121-46aa-8ad0-defc0b8ab9c9-nubTKeW)

### Hardware Guides
[AES-MC-SBC-IMX8M-G Development Updating Guide EMMC V1.0](https://www.avnet.com/wps/wcm/connect/onesite/08a69245-942e-47a8-a13e-0406c71d52b9/AES-MC-SBC-IMX8M-G-Development_Guide-EMMC-V1.0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-08a69245-942e-47a8-a13e-0406c71d52b9-nubLjJ7)

[MaaX LifeCycle 2020](https://www.avnet.com/wps/wcm/connect/onesite/f67500b9-ba5a-4e56-98d2-b449c7bbacd2/MaaXBoard-Linux-Development_Guide-V1.0-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-f67500b9-ba5a-4e56-98d2-b449c7bbacd2-nubVrw3)

[MaaXBoard Hardware User Manual V1.2-EN](https://www.avnet.com/wps/wcm/connect/onesite/1e83cac7-ebe8-4be4-8776-6781e3833d11/MaaXBoard-Hardware_UserManual-V1.2-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-1e83cac7-ebe8-4be4-8776-6781e3833d11-nubO0tq)

### Quick Start Card
[MaaXBoard Quick Start Guide](https://www.avnet.com/wps/wcm/connect/onesite/1c28a152-32ee-43c9-911f-ba093b0f2bd5/P20_014_Embest_Product_Booklet_KL_r3.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-1c28a152-32ee-43c9-911f-ba093b0f2bd5-nubQqTy)

### Development Guides
[MaaXBoard Android Development Guide V1.0-EN](https://www.avnet.com/wps/wcm/connect/onesite/16594184-70a8-456a-99ad-8bf28365458d/MaaXBoard-Android-Development_Guide-V1.0-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-16594184-70a8-456a-99ad-8bf28365458d-nubToKG)

[MaaXBoard Linux Development Guide V1.0-EN](https://www.avnet.com/wps/wcm/connect/onesite/f67500b9-ba5a-4e56-98d2-b449c7bbacd2/MaaXBoard-Linux-Development_Guide-V1.0-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-f67500b9-ba5a-4e56-98d2-b449c7bbacd2-nubVrw3)

[MaaXBoard Linux Yocto Lite Development Guide V1.3-EN](https://www.avnet.com/wps/wcm/connect/onesite/c21b5740-11d1-4732-b34c-ffffe54854cd/MaaXBoard-Linux-Yocto-Lite-Development_Guide-V1.3-EN.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-c21b5740-11d1-4732-b34c-ffffe54854cd-nZCsBL8)

[MaaXBoard-Linux-Yocto-Development_Guide-V2.0](https://www.avnet.com/wps/wcm/connect/onesite/70863b8d-da7f-4b9d-a97b-cb59f418907c/MaaXBoard-Linux-Yocto-Development_Guide-V2.0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-70863b8d-da7f-4b9d-a97b-cb59f418907c-oFe7OZA)

### Production Documents
[MaaXBoard Variant V1.0](https://www.avnet.com/wps/wcm/connect/onesite/8670ea9c-a49d-4de5-af20-82af8d0b86ad/MaaXBoard_Variants_V1-0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-8670ea9c-a49d-4de5-af20-82af8d0b86ad-nubSof.)

### Release Notes
[MaaXBoard Android Release Note V1.0](https://www.avnet.com/wps/wcm/connect/onesite/9d151d50-907e-4faf-96c7-0133ef796505/MaaXBoard_Android_ReleaseNote-V1.0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-9d151d50-907e-4faf-96c7-0133ef796505-nubRHez)

[MaaXBoard Linux Release Note V1.0](https://www.avnet.com/wps/wcm/connect/onesite/0e594eda-f0f1-4357-b01f-684092b525db/MaaXBoard-Linux-ReleaseNote-V1.0.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-0e594eda-f0f1-4357-b01f-684092b525db-nubR1cQ)

[MaaXBoard Linux Release Note V1.2](https://www.avnet.com/wps/wcm/connect/onesite/9bf9b035-9276-4583-bb1b-8253a99595af/MaaXBoard-Linux-ReleaseNote-V1.2.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-9bf9b035-9276-4583-bb1b-8253a99595af-nubRh1m)

[MaaXBoard Linux Yocto Lite Release Note V1.1 (pdf)](https://www.avnet.com/wps/wcm/connect/onesite/3abd82a1-3354-4942-a356-d98db0e319f9/MaaXBoard-Linux-Yocto-Lite-ReleaseNote-V1.1.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-3abd82a1-3354-4942-a356-d98db0e319f9-nZCsCKX)

### Errata and Product Change Notices
[PCN 21003 Manufacturer Changes](https://www.avnet.com/wps/wcm/connect/onesite/260403e3-abc2-4bfc-b174-3d456a1dc93f/Product+Change+Notification+PCN+21003.pdf?MOD=AJPERES&CACHEID=ROOTWORKSPACE.Z18_NA5A1I41L0ICD0ABNDMDDG0000-260403e3-abc2-4bfc-b174-3d456a1dc93f-nDEpL3N)
