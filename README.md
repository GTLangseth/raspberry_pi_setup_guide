# Raspberry Pi Setup Guide
### Written for Genspace's Open Plant Community Project

The goal of this guide is to create the minimal lowest cost setup for a Raspberry Pi (including associated peripherals) and fastest setup time, intended for new users to get up and running quickly.  

![Rpi0W hardware-labelled+cropped](https://user-images.githubusercontent.com/12764347/90338534-40102d80-dfb8-11ea-94ee-dae62fd3cc1c.jpg)

### What you'll need (physically):
- Raspberry Pi 0 W
- microSD card (>= 4GB)
- microSD card adapter
- 5V (2.5A) power supply
- computer with SD card reader

### What you'll need (digitally), please download:
- Raspberry Pi OS (previously called Raspbian OS)
  - [ZIP](https://downloads.raspberrypi.org/raspios_full_armhf_latest)
  - [TORRENT](https://downloads.raspberrypi.org/raspios_full_armhf_latest.torrent)
    - NOTE: if you can torrent, that's much faster, the ZIP file seems to be speed limited no matter how fast your internet connection is
- [Balena Etcher](https://www.balena.io/etcher/)
- Windows users: [PuTTY](https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html)
  - Under Package Files > MSI: 
      - Choose the 64-bit installer if your OS can support it, if you're not sure what you have, it's fine to use 32-bit

### Let's get started:

##### 0. Download all the above (this could take awhile)

##### 1. Flash the OS onto microSD card
- Open up Balena Etcher
  - Flash from file
    - Select your Raspbian OS ZIP file 
  - Select target
    - Check your microSD card
      - Size should be between 4 - 64 GB
        - Sizes >= 64 GB will need to be reformatted, see [here] (https://www.raspberrypi.org/documentation/installation/sdxc_formatting.md)
      - Location should NOT be the C:\ drive
  - Flash!
    - Windows users: you may need to grant permission to the command line to start the flashing process by selecting "Yes"
  - Eject
    - Windows user: Right click the USB/attached drive icon in the bottom right of the task bar
      - Select your microSD card
        - It should then say "[microSD card] can be safely removed now"
          - Press the card into the slot, it's spring-loaded so it should pop back out

##### 2. Prepare the boot partition

##### 3. SSH 



