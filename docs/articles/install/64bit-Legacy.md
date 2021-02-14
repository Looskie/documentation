# dahliaOS on 64-BIOS

# Installation 

- dahliaOS supports a wide range of devices. This guide will tell you how to flash it on a USB and what hardware you need.

## Flash the ISO

There are two ISOs to choose from, **EFI** and **Legacy** but this guide focuses on the Legacy ones.


1. Go to [releases](https://github.com/dahliaos/releases/releases/download/201215-x86_64/dahliaOS-201215-legacy.iso) and download the ISO.
2. Download [Etcher (3rd party link)](https://www.balena.io/etcher/) and flash the ISO on a USB.
3. You're almost good to go, reboot your system and go in your UEFI and go to the **Boot** tab and select the USB.
4. Your system should boot into dahliaOS.

## Requirements

### Minimum requirements

- You need at least **512 MB of RAM** and a **64 bit** dual core processor with **Intel HD graphics**

### Recommended requirements

**2 GB of RAM** and **a 64 bit** quad core processor with **Intel HD graphics**


**Note: Nvidia graphics won't work well, use onboard graphics for the best result.**

## License

<div align=left>
<img width="150" src="../img/logo/dahliaOS%20logo%20with%20text%20(drop%20shadow).png"/>
</div>

Copyright © The dahliaOS authors, contact@dahliaos.io

This project is licensed under the [Apache 2.0 license](../LICENSE)