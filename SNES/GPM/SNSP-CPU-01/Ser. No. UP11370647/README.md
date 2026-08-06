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

# Starting point

Oh... What's this? Some kind of ultra-rare Commodore peripheral? No, not at all! Say hello to the famous Super Nintendo Entertainment System (SNES)! This is the first time I have ever tried to refurbish a Nintendo console. I have also hardly ever used a SNES, so this will be a first.

The plan is to replace the capacitors and give it a bit of a "nip and tuck." If the console is not working, I will probably be quite challenged, as I have no spare parts for these machines. But let's see!

From the outside, the SNES is quite dirty and severely yellowed. I can faintly hear some kind of rattling sound inside, as if something has come loose. I do not know whether the SNES works or not, but apart from the dust and grease, it appears to be in good mechanical condition.

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

Before opening the SNES, the console is connected to a TV, powered on, and tested. The results are as follows:

- Without a cartridge installed: **POWER LED ON, BLACK SCREEN, NO AUDIO** (occasionally: **POWER LED ON, NO VIDEO, NO AUDIO**)
- With a game cartridge installed: **POWER LED ON, BLACK SCREEN, NO AUDIO**

This is unfortunate. The fault could be caused by an oxidised cartridge connector, a blown fuse, incorrect supply voltages, broken PCB traces (due to leaking capacitors), or a faulty IC. Occasionally, the console fails to produce any video output at all when powered on.

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Disassembly

To start disassembling the SNES, remove the six Gamebit screws[^1]. Note that you will need a special tool for this operation: a 4.5 mm Gamebit screwdriver.

<p align="center">
    <img src="Images/Dis_01.jpeg" alt="Description" width="600">
</p>

With the Gamebit screws out of the way, the top cover is lifted off, exposing the interior. As expected, I can see a fair amount of dust and grease inside.

<p align="center">
    <img src="Images/Dis_02.jpeg" alt="Description" width="600">
</p>

First, the ribbon cable for the controller port PCB is disconnected (1). Next, the two screws securing the power switch are removed[^2] (2). Finally, the power switch cable is disconnected from the mainboard (3). See the pictures below.

<p align="center">
    <img src="Images/Dis_04.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/Dis_05.jpeg" alt="Description" width="1000">
</p>

The top cover appears to be in good mechanical condition, with no obvious signs of cracks or other damage.

<p align="center">
    <img src="Images/Dis_03.jpeg" alt="Description" width="600">
</p>

Removing the cartridge eject mechanism is straightforward:

1) Lift the metal rod on the right-hand side out of the plastic holder.
2) Slide the large plastic part out of the holder on the left-hand side.
3) Remove the metal spring.

<p align="center">
    <img src="Images/Dis_06.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Dis_07.jpeg" alt="Description" width="700">
</p>

With the cartridge eject mechanism out of the way, the next step is to remove the first RF shield (P2) and the cartridge port connector. The RF shield is secured to the PCB with four screws[^3], while the cartridge port connector is secured with two screws[^4].

At this point, I notice something interesting: the leftmost screw securing the cartridge port connector is not fully tightened. In addition, the heads of both Pozidriv screws are slightly damaged, probably due to the use of an incorrectly sized screwdriver.

This should not be a major problem, but it is something worth investigating during the troubleshooting process.

<p align="center">
    <img src="Images/Dis_08.jpeg" alt="Description" width="800">
</p>

<p align="center" float="left">
    <img src="Images/Dis_09.jpeg" alt="Description" width="500">
    <img src="Images/Dis_10.jpeg" alt="Description" width="500">
</p>

When the RF shield (P2) is removed, a large section of the PCB is revealed. As can be seen from the picture below, this is an SNSP-CPU-01 mainboard. This is one of the earlier revisions of the SNES mainboard and, unfortunately, is known for reliability issues due to the faulty `CPU-01` chipset.

<p align="center">
    <img src="Images/Dis_11.jpeg" alt="Description" width="800">
</p>

Before the mainboard PCB can be lifted from the bottom cover, the three remaining screws need to be removed. One is located at the rear right-hand side of the mainboard[^5]. The other two are[^6] partially hidden beneath the P1 RF shield. See the pictures below.

<p align="center">
    <img src="Images/Dis_12.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/Dis_13.jpeg" alt="Description" width="600">
</p>

<!-- MARK START -->

Now the mainboard PCB is lifted from the bottom cover. Next action is to remove the screw[^7] on the 7805 voltage regulator which is mounted to the P1 RF-shield (which for the 7805 voltage regulator function as a heatsink). **NOTE:** There are two washers on the screw; one flat washer, and one spring lock washer. Also, for some reason, there are no thermal heat paste between the 7805 voltage regulator and the heatsink. 

<p align="center">
    <img src="Images/Dis_14.jpeg" alt="Description" width="600">
</p>

To remove the RF-shield/hearsink marked "P1" the three machine screws[^8] at the underside of the mainboard are removed. **NOTE:** There are tooth washers on the screws.

<p align="center">
    <img src="Images/Dis_15.jpeg" alt="Description" width="700">
</p>

Now the SNES is completely disassembled. The mainboard is now ready for inspection, and the top and bottom covers are ready for cleaning. 

<p align="center">
    <img src="Images/Dis_16.jpeg" alt="Description" width="700">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

<!-- MARK STOP -->

**Footnotes**
[^1]: Gamebit pan head (5.3 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 11.5 mm
[^2]: Phillips pan head (5.4 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.5 mm
[^3]: Phillips pan head (5.4 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.5 mm
[^4]: Phillips pan head (5.3 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 13.5 mm
[^5]: Phillips pan head (5.4 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.5 mm
[^6]: Phillips pan head (5.3 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 13.5 mm
[^7]: Phillips pan head (5.2 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 8.0 mm (plus flat washer and spring lock washer)
[^8]: Phillips pan head (6.2 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 7.0 mm (plus tooth washer)



