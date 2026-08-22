<p align="center">
    <img src="https://github.com/RefurbishedCommodore/RefurbishedCommodore/blob/main/Images/LogoNew.png" alt="Description" width="400">
</p>

# Super Nintendo Entertainment System (SNES)

![Name](https://img.shields.io/badge/Serial_No.-UP12155876-white?style=plastic)
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
      <a href="#refurbishment-activities">Refurbishment activities</a>
    </li>      
    <li>
      <a href="#disassembly">Disassembly</a>
    </li> 
    <li>
      <a href="#mainboard">Mainboard</a>
      <ul>
        <li>
          <a href="#visual-inspection">Visual inspection</a>
        </li>
      </ul>
    </li>
  </ul>
</details>

<!-- MARK START -->

# Starting point

This SNES is supposedly in working condition. But, oh my, it is dirty. There is dust and grime all over the place. The pictures does not do it justice - there is much more "stuff" (some sticky thing) on the covers than is visible on the pictures.

The yellowing is very interesting. Some parts have yellowed more than others:

- The bottom cover is severely yellowed
- The top cover is the less yellowed
- The front panel with the "SUPER NINTENDO" logo is medium yellowed

But on the bright side (no pun intended) the SNES seems to be in good mechanical condition. I can not see any cracks or damage. There are some signs of tear and wear, but not something severe as far as I can see. 

❤️ - This SNES is special. It will be used to help another SNES to be repaired! By moving some of the functioning chips from this SNES to a broken SNES, it will make it easier to identify which chips are faulty on the broken SNES. What a beautiful way to serve another SNES! But this will mean that this SNES will be not-working then? Yes, for a while. But eventually new chip(s) will be sourced for this SNES also.

<p align="center">
    <img src="Images/Start_01.jpeg" alt="Description" width="600">
    <img src="Images/Start_02.jpeg" alt="Description" width="800">
    <img src="Images/Start_04.jpeg" alt="Description" width="800">
    <img src="Images/Start_03.jpeg" alt="Description" width="800">
    <img src="Images/Start_05.jpeg" alt="Description" width="800">
    <img src="Images/Start_06.jpeg" alt="Description" width="600">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Refurbishment activities

The planned refurbishment activities for this Suoer Nintendo are listed below. The order may vary, and several activities may be carried out in parallel:

- [ ] Refurbish the casing
- [ ] Refurbish mainboard
- [ ] Testing and validation

The plan can be updated during the refurbishment process. Sometimes I discover areas that need special attention.
<br>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Disassembly

To start disassembling the SNES, remove the six Gamebit screws[^1]. Note that you will need a special tool for this operation: a 4.5 mm Gamebit screwdriver.

<p align="center">
    <img src="Images/Dis_01.jpeg" alt="Description" width="600">
</p>

With the Gamebit screws out of the way, the top cover is lifted off, exposing the interior. As expected, I can see a fair amount of dust and grease inside. There seems to be a whole family of dust bunnies.

<p align="center">
    <img src="Images/Dis_02.jpeg" alt="Description" width="600">
</p>

First, the ribbon cable for the controller port PCB is disconnected (1). Next, the two screws securing the power switch are removed[^2] (2). The power switch cable can also be disconnected from the mainboard (3) at this point (optional). See the pictures below.

<p align="center">
    <img src="Images/Dis_03.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/Dis_04.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/Dis_05.jpeg" alt="Description" width="600">
</p>

The top cover appears to be in good mechanical condition without any major cracks or damage.

<p align="center">
    <img src="Images/Dis_06.jpeg" alt="Description" width="600">
</p>

Removing the cartridge eject mechanism is straightforward:

1) Lift the metal rod on the right-hand side out of the plastic holder.
2) Slide the large plastic part out of the holder on the left-hand side.
3) Remove the metal spring.

<p align="center">
    <img src="Images/Dis_07.jpeg" alt="Description" width="800">
</p>

With the cartridge eject mechanism out of the way, the next step is to remove the first RF shield (P1) and the cartridge port connector. The RF shield is secured to the PCB with four screws[^3], while the cartridge port connector is secured with two screws[^4].

When the RF shield (P1) is removed, a large section of the PCB is revealed. As can be seen from the picture below, this is an SNSP-CPU-01 mainboard. This is one of the earlier revisions of the SNES mainboard.

<p align="center">
    <img src="Images/Dis_08.jpeg" alt="Description" width="800">
</p>

Before the mainboard PCB can be lifted from the bottom cover, the three remaining screws need to be removed. One is located at the rear right-hand side of the mainboard[^5]. The other two are[^6] partially hidden beneath the P1 RF shield.

Now the mainboard PCB is lifted out of the bottom cover. The next step is to remove the screw[^7] securing the 7805 voltage regulator to the P1 RF shield, which also serves as its heatsink. **Note:** There are two washers on the screw: one flat washer and one spring lock washer. Also, for some reason, there is no thermal paste between the 7805 voltage regulator and the heatsink.

<p align="center">
    <img src="Images/Dis_09.jpeg" alt="Description" width="800">
</p>

To remove the RF shield/heatsink also marked "P1", remove the three machine screws[^8] from the underside of the mainboard. **Note:** Each screw is fitted with a toothed lock washer.

<p align="center">
    <img src="Images/Dis_10.jpeg" alt="Description" width="700">
</p>



# Mainboard

The mainboard is an SNSP-CPU-01, one of the early revisions of the SNES mainboard.

## Visual inspection

There is a substantial amount of dust and grime on the mainboard. There is also quite a lot of flux residue on both sides of the PCB, but I believe this is fairly typical for early SNES consoles. 

<p align="center">
    <img src="Images/Main_01.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Main_02.jpeg" alt="Description" width="800">
</p>

<div align="center">

The table below lists all major ICs found on the mainboard.
    
| Chip/Area | Manufactor | Version | Date code | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| CPU | Nintendo(Ricoh) | S-CPU A<br>5A22-02 | Unknown | |
| PPU#1 | Nintendo(Ricoh) | S-PPU1<br>5C77-01 | Unknown | |
| PPU#2 | Nintendo(Ricoh) | S-PPU2 B<br>5C78-03 | Unknown | |
| Work RAM | Nintendo | S-WRAM | W35 Y1992 | |
| Video RAM | CSI | CAT71C256LLK-12 | W24 Y1992 | x2 |
| Audio RAM | LSI Logic | LH5P832N-127 | Unknown | x2 |
| S-DSP | Sony | Unknown | Unknown | Marked: 207A51V |
| S-SMP | Sony | Unknown | Unknown | Marked: 231B01E|

</div>

<!-- MARK STOP -->

**Footnotes**
[^1]: Gamebit pan head (5.3 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 11.0 mm
[^2]: Phillips pan head (5.3 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.5 mm
[^3]: Phillips pan head (5.3 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.5 mm
[^4]: Phillips pan head (5.3 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 14.0 mm
[^5]: Phillips pan head (5.4 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 9.5 mm
[^6]: Phillips pan head (5.3 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 14.0 mm
[^7]: Phillips pan head (5.2 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 8.0 mm (plus flat washer and spring lock washer)
[^8]: Phillips pan head (6.2 mm), Machine screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 7.0 mm (plus tooth washer)









