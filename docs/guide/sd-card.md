# The SD Card

When running a CFW, special attention must be paid attention to the SD card, as it holds many important files.

## Operating System

### emuNAND

While using emuNAND, recall that your operating system is run off the SD card, instead of the Switch's internal memory. This means that you should **NEVER** eject the SD card from the Switch while it is on. Doing so would be equivalent to yanking out your hard drive of your computer while it is operational.

### sysNAND

While using sysNAND, the operating system is run off of the Switch's internal memory, so removing the SD card is less catastrophic. That being said, all the files that allow the CFW to work in the first place are stored only on the SD card, so removing whist the Switch is operational is not a very good idea.

<hr>

!!! danger "TL;DR"
    Basically, if the Switch is on, **DO NOT EJECT** the SD card. You risk corrupting data you have on the SD card and your Switch's internal memory. Use one of the methods listed below to safely eject the SD card.

<hr>

## Removing SD Card Properly

So you've seen how terrible it would be to remove the SD card while the Switch is on, but how do you actually do it if you need to? You have two options:

### Power Off Switch

The simplest way to achieve safe ejection is to power off the Switch fully:

1. Power off the Switch
2. Remove the SD card
3. Transfer whatever files you need
4. Put the SD card back
5. Power on and [re-inject your payload](./startup-shutdown.md#from-cold-boot) to get into the CFW.

### Boot into Hekate

Powering off and re-injecting payloads is a bit annoying if you have to eject the SD card a lot, so there is a faster but slightly more complex way to achieve the same result:

1. Access Hekate (the bootloader) by [restarting the Switch and holding Volume Down](./startup-shutdown.md#accessing-bootloader-with-auto-boot)
2. Remove the SD card (yes, while Hekate is on-screen!)
    - A dialog box should come up. _Don't worry about clicking anything here_.
3. Transfer whatever files you need
4. Put the SD card back
    - Once inserted, Hekate should respring automatically without any further input.
5. [Boot into Atmosphère](./startup-shutdown.md#launching-cfw) by selecting it from the "Launch" list

## Transferring Files with FTP

If you just need to transfer small files and don't actually need to remove the SD card, then it may be more convenient to transfer files over the network. This does not require you to power off the Switch by any means to transfer files.

Please refer to the [section detailing FTPd Pro](./homebrews.md#ftpd-pro) for instructions on how to use it.
