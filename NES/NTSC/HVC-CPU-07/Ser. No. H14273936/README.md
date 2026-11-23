<p align="center">
    <img src="https://github.com/RefurbishedCommodore/RefurbishedCommodore/blob/main/Images/LogoNew.png" alt="Description" width="400">
</p>

# Family Computer (FAMICOM)

![Name](https://img.shields.io/badge/Serial_No.-H14273936-white?style=plastic)
<br>
![Name](https://img.shields.io/badge/Revision-HVC_CPU_07-white?style=plastic)
![Name](https://img.shields.io/badge/Video_format-NTSC-white?style=plastic)

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
    </li>
      <ul>
          <li>
            <a href="#visual-inspection">Visual inspection</a>
          </li>
          <li>
            <a href="#initial-testing">Initial testing</a>
          </li>
      </ul>
    <li>
      <a href="#casing">Casing</a>
    </li>
    <li>
      <a href="#testing">Testing</a>
    </li>    
    <li>
      <a href="#final-result">Final result</a>
    </li>    
  </ul>
</details>

# Starting point

There is a first time for everything. I have never refurbished a Family Computer (FAMICOM) from Nintendo. Actually, I have never seen one in real life before neither! So, it is both very exciting, and with a certain sense of awe, to try to refurbish this console.

It is unclear whether or not this console works or not. The console is made for the Japanese market with both 110 V grid voltage, and 60 Hz NTSC RF-video output. This makes it harder to both test and repair the console, but I will figure it out as the refurbishment progress.

From the outside it looks to be in fine condition. It is severely yellowed, but from a mechanical point of view it seems to be without any damage. It is likely that this console has been taken good care of. Not only does the console itself look to be in good condition, but the cardboard box - and the user manuals - are also in fine condition. Nice! There is some dirt and grease on the plastic shells, but this should come off with some gentle cleaning.

Also, the two controllers appears to be in good condition. There are some signs of tear and wear on the metal plates, but that this is to be expected.

Below are some pictures of the Family Computer (FAMICOM) before refurbishment.

<p align="center">
    <img src="Images/Start_01.jpeg" alt="Description" width="800">
</p>

<p align="center" float="left">
    <img src="Images/Start_02.jpeg" alt="Description" width="800">
</p>

<p align="center" float="left">
    <img src="Images/Start_03.jpeg" alt="Description" width="800">
</p>

<p align="center" float="left">
    <img src="Images/Start_04.jpeg" alt="Description" width="800">
</p>

<p align="center" float="left">
    <img src="Images/Start_05.jpeg" alt="Description" width="800">
</p>

<p align="center">
    <img src="Images/Start_06.jpeg" alt="Description" width="800">
</p>

Below are some pictures of the cardboard box and the user manuals accompanying the console. 

<p align="center" float="left">
    <img src="Images/Start_07.jpeg" alt="Description" width="600">
</p>

<p align="center" float="left">
    <img src="Images/Start_08.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/Start_09.jpeg" alt="Description" width="600">
</p>

[![Back to TOC](https://img.shields.io/badge/TOC-grey?style=plastic)](#table-of-contents)

# Disassembly

To start disassembling the FAMICOM the six screws at the bottom are removed [^1]. Note that I believe that these are JIS screws (and not Phillips), so a J1 low torque screwdriver is recommended. When the screws are removed the nice little "cracking" sound is heard. This console has probably never been opened before.

<p align="center">
    <img src="Images/Dis_01.jpeg" alt="Description" width="700">
</p>

With the screws out of the way, the bottom cover is lifted from the top cover. Now the interior is exposed, and the the backside of the two PCBs are visible. At first glance I can see some dust inside, and there are some residue on the PCB that could be the start of corrosion (needs to be investigated later). The two PCBs are held in place by eight screws (see arrows in picture below). These are the same size and model as the screws holding the bottom cover[^1]. 

<p align="center">
    <img src="Images/Dis_02.jpeg" alt="Description" width="800">
</p>

Another thing I notice is that Nintendo used a simple, but yet effective, way of cable strains. By winding the controller cables around the internal screw posts both controller was effectively prevented from being ripped out of the console. Clever Japanese engineering.

<p align="center">
    <img src="Images/Dis_03.jpeg" alt="Description" width="700">
</p>

Now the PCBs, and the controllers, can be lifted from the top cover. The top cover and power switch are now completely exposed.

<p align="center">
    <img src="Images/Dis_04.jpeg" alt="Description" width="700">
</p>

The cartridge locking mechanism is now removed by carefully lifting one side of the spring away from the plastic arm (see arrow in the picture below). With the spring removed, the whole cartridge mechanism can be removed.

<p align="center">
    <img src="Images/Dis_05.jpeg" alt="Description" width="600">
</p>

During the disassembly of the cartridge mechanism, the power switch is also disassembled. This is held to the top cover with two screws - also the same dimensions as the bottom cover screws[^1].

<p align="center">
    <img src="Images/Dis_06.jpeg" alt="Description" width="500">
</p>

The top cover is now disassembled and ready for cleaning. Note that the two plastic keys is part of the top cover assembly, but is not fastened in any way.

<p align="center">
    <img src="Images/Dis_07.jpeg" alt="Description" width="700">
</p>

# Mainboard

The mainboard consists of two PCBs. The large PCB, model HVC-CPU-07, is the logic board the CPU, PPU and glue logic. The smaller PCB is used supplying power to the other PCB and RF audio/video output to the TV set. The RF-modulator is marked with E210026 // 8D28A85B-J.

<p align="center">
    <img src="Images/Main_01.jpeg" alt="Description" width="1000">
</p>

<p align="center">
    <img src="Images/Main_02.jpeg" alt="Description" width="1000">
</p>

## Visual inspection

The first thing I notice is that there is quite a lot of dust and grease on the PCBs. This is normal after several years of storage, but this is something that needs to be cleaned off. One are where there is quite a lot of dirt is inside the RF-modulator - the old glue used to hold the components in place has gathered much dirt. 

<p align="center">
    <img src="Images/Main_03.jpeg" alt="Description" width="600">
</p>

<p align="center">
    <img src="Images/Main_04.jpeg" alt="Description" width="500">
</p>

I can not see any bulging capacitors or any signs of rework. I mentioned earlier that I noticed something that could be early corrosion. After closer inspection this does not seem to be the case. There are some residue, but after cleaning with isopropanol the PCB looks fine.

The table below lists all major custom ICs found on the mainboard. The custom chips have date codes in the Year/Month/Week format. According to these this FAMICOM was produced in the winter, or early spring, in 1988.

<div align="center">
    
| Chip/Area | Manufactor | Version | Date code | Socket | Note |
|:----------:|:----------:|:----------:|:----------:|:----------:|:----------:|
| CPU/APU | RICOH | RP2A03G | Week 1/March/Year 1988 | No | NTSC version |
| PPU | RICOH | RP2C02G-0 | Week 2/March/Year 1988 | No | NTSC version | 
| S-RAM | SONY | CXK5816SPS-15L |  Week 1/December/Year 1987 | No |  |
| Glue logic | Matsushita, Fujistu and SGS Thomson |  |  |  |  |

</div>

## Initial testing

Performing some initial testing of the FAMICOM is not so straightforward due to lack of a TV set supporting NTSC and a proper power supply. Nevertheless, I manage to do some initial testing by using:

- A 9 V DV power supply from a European SNES (**NOTE:** the 9 V DC must be center negative)
- A PAL TV set tuned to a channel "C77"

<div align="center">
    
| Area | Test | Result | Note |
|:----------:|:----------:|:----------:|:----------|
| Video | Display game graphics | PASS | There is a lot of noise in the video signal due to wrong TV set (PAL) |
| Audio | Play game music | FAILED | This could very well be caused by wrong TV set (PAL) |
| Controls | Play game cartridge | PASS |  |

</div>

<p align="center">
    <img src="Images/Init_01.jpeg" alt="Description" width="700">
</p>



**Footnotes**
[^1]: JIS pan head (5.2 mm), Sheet metal screw, Fully threaded, Thread diameter: 3.0 mm, Fastener length: 11.5 mm

