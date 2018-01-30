+++
date = 2017-10-02
lastmod = 2017-10-02
draft = false
tags = ["Raspbian", "Raspberry Pi operating system"]
title = "install Raspberry Pi operating system"
math = true
summary = """
In this Tutorial I’ll explain, How to install Raspberry Pi operating system image on SD Card. Raspberry Foundation recommended two startups operating system for Your Raspberry PI device. 
"""

[header]
image = "install-raspberry-pi-operating-system.jpg"
caption = "install Raspberry Pi operating system"

+++

In this Tutorial I’ll explain, How to install Raspberry Pi operating system image on SD Card. Raspberry Foundation recommended two startups operating system for Your Raspberry PI device.

    Noobs – which is designed to be very easy to use.
    Raspbian – Image with desktop based on Debian Jessie.

| `Install Raspbian` |
| --- |
| ![Install Raspbian](https://sajal.info/img/install-raspbian.png) |

There are many another third party Operating system founded in Download Page. If you using raspberry pi 3 model B or greater device, I recommend you to use Raspbian Jessie with PIXEL. Raspbian pixel released in November 2016 & current Kernel version is 4.4.

We’re 3 step away from installing Raspberry Pi operating system image on SD Card. Let’s do this.

**Download the image file**

Go to Raspberry Pi [official download page](http://www.raspberrypi.org/downloads/) and grab it.  You can download Raspbian pixel by following above link.

**Writing an image to the SD card**

Before writing an image file on SD card, don’t forget to properly format it. To write your system image file on SD card, you need to Extract it first on your computer. After Extracting image file in the computer, You are able to write it on your SD card by image burner software. Please follow my instruction to do this.

**For Windows computer**

Download SD card Formatter software called [SDFormatter](https://www.sdcard.org/downloads/formatter_4/) and install it.  Download [Win32 Disk Imager](https://sourceforge.net/projects/win32diskimager/) software from SourceForge and install it also. first open SDFormatter by Run as administrator and click format button (if you already inserted your SD card on Windows PC). Open also Win32 Disk Imager by Run as administrator and select your extracted image file as source, then click “write” button & wait for the write to complete. You can exit Imager & Eject the SD card.

**For Linux Machine**

Please follow official raspberry pi website’s[ instruction](https://www.raspberrypi.org/documentation/installation/installing-images/linux.md/) .

**For MAC OS**

Please follow official raspberry pi website’s[ instruction](https://www.raspberrypi.org/documentation/installation/installing-images/mac.md/) .

**Boot UP your PI**

After completed writing process, your SD card is ready for boot. Insert your SD card in Raspberry pi device, then plug your pi power cable. Wait few minutes to boot it up. When you got the raspbian desktop, you must connect with internet to update it. To update your raspberry Pi please run a command sudo apt-get update then upgrade it by commandsudo apt-get upgrade. Now your 24 bit Linux machine is ready to use.
