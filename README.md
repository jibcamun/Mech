<h1 align="center">Mech</h1>
<p align="center">A numpad for the elderly</p>

<p align="center">
  <img src="https://github.com/jibcamun/Mech/blob/main/Images/Image3.png" alt="Map">
</p>

## Purpose
### What is this?
A numpad, consisting numbers from 1 to 9.
### What does this do?
Help people easily access numbers on a keyboard.
### Why does this exists? _(Motivation to build this)_
I have seen old people who use computers only as a calculator and find it hard to type numbers because its stacked at the top and they are more used to the typical calculator layout. _(my grandparents)_

## Features
1. Uses Arduino Pro Micro.
2. Uses MX Switches (1.00u) and Cherry MX Keycaps for a better feel and feedback while pressing a key.  
3. Made it easy to connect and use with a USB connection, thus making it more accessible for the elderly.
4. Simple UX, again making it easily usable for the elderly.
5. All keycaps are angled forward making it easy for "finger typing".

## Schematics
![Schematics](https://github.com/jibcamun/Mech/blob/main/Images/Image5.png)

## PCB
![PCB_UP](https://github.com/jibcamun/Mech/blob/main/Images/Image6.png)
![PCB_DOWN](https://github.com/jibcamun/Mech/blob/main/Images/Image7.png)

## Case
![With_Case](https://github.com/jibcamun/Mech/blob/main/Images/Image1.png)
![With_Case_Side](https://github.com/jibcamun/Mech/blob/main/Images/Image4.png)

## Zine
![Zine](https://github.com/jibcamun/Mech/blob/main/Images/Mech%20Zine.png)

## Build Guide
### Step 1
Solder all components to the PCB as indicated by the schematic diagrams.
### Step 2
Take the soldered PCB and place it in an appropriate orientation on the 3D printed component named "Bottom", in accordance with the position of the screw holes.
### Step 3
Place the 3D printed component named "Top" on the assembled setup and press them together _(like a sandwich)_.

## Firmware Flashing
### Step 1
Connect the Pro Micro to your computer using the USB cable.
### Step 2
Install QMK WSYS (if on windows). Enter `qmk flash -kb mech -km default` in the terminal window, to flash the firmware.

## Links 
1. [Bill of Materials (BOM)](https://github.com/jibcamun/Mech/blob/main/Materials/BOM.csv)
2. [PCB Design](https://github.com/jibcamun/Mech/blob/main/PCB%20Design)
3. [3D Case Design](https://cad.onshape.com/documents/927574eef36e39d9a3de9231/w/e5b95da04439b4f215ef18f1/e/b08572cbae5c0041dba6a6c8?renderMode=0&uiState=69ea2cd7de772b1d4ea52e7f)
4. [CAD Export Files](https://github.com/jibcamun/Mech/blob/main/3D%20Models)
5. [3D Export of Design](https://github.com/jibcamun/Mech/blob/main/3D%20Models/mech.step)

## Links for Bill of Materials (Available in BOM)
1. PCBWay: https://www.pcbway.com/
2. ROBU.IN: https://robu.in/product/pro-micro-5v-16m-mini-leonardo-micro-controller-development-board-for-arduino
3. MECKEYS: https://meckeys.com/shop/accessories/keyboard-accessories/key-switches/gateron-mechanical-switch/?attribute_pa_gateron-key-switches=ks-9a10b060nn-x14 
4. Dexterous Manufacturing Labs Pvt Ltd: https://storefront.iamrapid.com/
5. ELECTRONICS COMP: https://www.electronicscomp.com/1n4148-diode

## Attributions 
1. Cherry MX Switches: [row 1 1u blank keycap for cherry mx style switches](https://www.thingiverse.com/thing:5616342) by [LazarosVarvatis](https://www.thingiverse.com/LazarosVarvatis/designs) is licensed under the [Creative Commons - Attribution - Non-Commercial - Share Alike](https://creativecommons.org/licenses/by-nc-sa/4.0/) license. License: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
2. Footprints: [scottokeebs](https://github.com/joe-scotto/scottokeebs)