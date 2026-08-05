<p align="center">
    <img src="https://github.com/RefurbishedCommodore/RefurbishedCommodore/blob/main/Images/LogoNew.png" alt="Description" width="400">
</p>

# Super Nintendo Entertainment System (SNES)

![Name](https://img.shields.io/badge/Serial_No.-UP11370647-white?style=plastic)
<br>
![Name](https://img.shields.io/badge/Revision-SNSP_CPU_01-white?style=plastic)
![Name](https://img.shields.io/badge/Video_format-PAL-white?style=plastic)

# Table of contents

<!-- TABLE OF CONTENTS -->
<details>
<summary>TOC - Click to enlarge</summary>
  <ul>
    <li>
      <a href="#starting-point">Starting point</a>
    </li>
    <li>
      <a href="#disassembly">Disassembly</a>
    </li>
    <li>
      <a href="#initial-testing">Initial testing</a>
    </li>
  </ul>
</details>

<!-- MARK START -->

# Starting point

Oh... What is this? Some kind of ultra-rare Commodore peripheral? No, not at all! Say hello to the famous Super Nintendo Entertainment System (SNES)! This is the first time I have ever tried to refurbish a Nintendo device. And I have hardly ever used a SNES, so this will be a first.

The plan is to replace the capacitors, and give it a bit of "nip-and-tuck". If the device is not working I am probably going to be very challenged as I have zero spare parts for these devices. But, let´s see!

From the outside the SNES is quite dirty and severely yellowed. I can hear, vaguely, some kind of rattling sound inside as if something is loose inside. I do not know if the SNES works or not, but beside from dust and grease, it does looks to be in good mechanical condition.

Below are some pictures of the SNES before refurbishment.

<p align="center">
    <img src="Images/Start_02.jpeg" alt="Description" width="600">
    <img src="Images/Start_03.jpeg" alt="Description" width="800">
    <img src="Images/Start_04.jpeg" alt="Description" width="800">
    <img src="Images/Start_05.jpeg" alt="Description" width="800">
    <img src="Images/Start_06.jpeg" alt="Description" width="800">
    <img src="Images/Start_01.jpeg" alt="Description" width="600">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Initial testing

Before the SNES is opened the device is connected to TV, powered and started. This is the result:

- With no cartridge installed: **POWER LED ON, BLACK SCREEN and NO AUDIO** // **POWER LED ON, NO VIDEO and NO AUDIO**
- With game cartridge installed: **POWER LED ON, BLACK SCREEN and NO AUDIO**

This is unfortunate. It can be an issue with oxidized cartridge port, blown fuse or poor voltages, broken traces (due to leaking capacitors) or a broken IC. Sometimes the device fail to produce a video output at all when powered on.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Disassembly

To start disassembling the SNES the six Gamebit screws[^1]. Note that you need a special tool for this operation: a Gamebit 4.5 mm screwdriver.

<p align="center">
    <img src="Images/Dis_01.jpeg" alt="Description" width="600">
</p>

With the Gamebit screws out of the way, the top cover is lifted. The interior is exposed, and I can see quite some dust and grease inside.

<p align="center">
    <img src="Images/Dis_02.jpeg" alt="Description" width="600">
</p>

First, the ribbon cable for the control-port PCB is removed (1). Then the two screws holding the power switch are removed[^2] (2), and then finally the power switch cable is removed from the PCB (3). See pictures below.

<p align="center">
    <img src="Images/Dis_04.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/Dis_05.jpeg" alt="Description" width="1000">
</p>

The top cover appears to be in good mechanical condition.

<p align="center">
    <img src="Images/Dis_03.jpeg" alt="Description" width="600">
</p>

Removing the cartridge eject mechanism is straighforward:

1) Lift the metal-rod on the right hand side from the plastic holder
2) Slide the large plastic part out from the holder on the left side
3) Remove the metal spring

<p align="center">
    <img src="Images/Dis_06.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Dis_07.jpeg" alt="Description" width="700">
</p>

With the cartridge eject mechanism out of the way, the next step is to remove the first RF-shield (P2) and the cartridge port connector. The RF-shield is held to the PCB with four screws[^3], and the cartridge connector is held by two screws[^4]. But now I notice something: The leftmost screw on the cartridge port connector is not fully fastened. Also, both the heads on these two Pozidriv screws are slightly damaged. Probably due to using a screwdriver of wrong size. This should not be much of a problem, but is something to investigate when troubleshooting.

<p align="center">
    <img src="Images/Dis_08.jpeg" alt="Description" width="800">
</p>

<p align="center" float="left">
    <img src="Images/Dis_09.jpeg" alt="Description" width="500">
    <img src="Images/Dis_10.jpeg" alt="Description" width="500">
</p>

When the RF-shield (P2) is removed a large part of the PCB is revealed. As can be seen from the picture below, this is a SNSP-CPU-01 mainboard. This is one of the early versions of the mainboard, and unfortunately known for failing (due to a bad `CPU-01`).

<p align="center">
    <img src="Images/Dis_11.jpeg" alt="Description" width="800">
</p>

Before the mainboard PCB can be lifted from the bottom cover, the three remaining screws needs to be removed. One is located at the rear (right side)[^5] of the mainboard. The other two are[^6] partly hidden by the P1 RF shield. See pictures below.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

<!-- MARK STOP -->

**Footnotes**
[^1]: Gamebit pan head (5.3 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 11.5 mm
[^2]: Phillips pan head (5.4 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.5 mm
[^3]: Phillips pan head (5.4 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.5 mm
[^4]: Phillips pan head (5.3 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 13.5 mm
[^5]: Phillips pan head (5.4 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.5 mm
[^6]: Phillips pan head (5.3 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 13.5 mm


