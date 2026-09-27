# Project Name

> Class D Amplifier Permanent Housing

## Project Owner

**Name:** Evan Shelton  
**Virginia Tech Email:** evans06@vt.edu

## Project Overview

This project converted a Class D audio amplifier originally developed in ECE 2804 – Integrated Design Project from a breadboard-based prototype into a compact, permanent, and self-contained system.

The original amplifier was distributed across multiple breadboards with numerous external connections. While this configuration worked well for prototyping and testing, it was not practical as a permanent device. The goal of this project was to preserve the functionality of the original amplifier while improving its organization, durability, portability, and appearance.

To accomplish this, I designed a custom printed circuit board (PCB) to consolidate the amplifier circuitry and wiring onto a single board. I also designed and 3D printed a custom enclosure to house the electronics and provide mounting locations for the user controls, OLED display, power input, and power switch.

The completed project transformed the original laboratory prototype into a standalone Class D amplifier housed in a purpose-built enclosure.


## Project Goals

The primary goals of the project were to:

- Convert the breadboard amplifier into a permanent PCB-based design.
- Reduce the amount of external wiring and improve circuit organization.
- Design a custom enclosure around the completed electronics.
- Integrate the potentiometers, OLED display, power input, and power switch into the enclosure.
- Improve the durability and portability of the original amplifier.
- Gain practical experience with PCB design, soldering, CAD, 3D printing, and electromechanical system integration.

## Original Amplifier

The project was based on a Class D amplifier previously developed for ECE 2804.

The amplifier consists of several major stages:

- Three-band audio equalizer
- PWM modulation stage
- Comparator and dead-time circuitry
- MOSFET switching stage
- Passive output low-pass filter
- OLED display and audio visualization system

The original circuit was developed and tested using breadboards before being transferred to the custom PCB developed for this project.

## PCB Design

One of the main objectives of the project was to replace the breadboard implementation with a single custom PCB.

The PCB was designed around the existing amplifier circuitry while accounting for:

- Component placement
- Signal routing
- Power distribution
- Connections between the different amplifier stages
- Potentiometer connections
- OLED display connections
- Power input and output connections
- Physical dimensions required by the enclosure

After completing the PCB design, the board was manufactured and populated with the amplifier components. The completed PCB significantly reduced the wiring required compared with the original breadboard implementation and provided a much more permanent platform for the amplifier.

## Enclosure Design

A custom enclosure was designed using CAD to house the completed PCB and supporting hardware.

The enclosure was designed around the dimensions of the PCB and included mounting locations for the amplifier's external controls and connections.

The design incorporated:

- PCB mounting points
- Potentiometer access
- OLED display mounting
- Audio connections
- Power input
- Power switch
- Internal wire routing
- Access for assembly and maintenance

The enclosure was then 3D printed and used for the final assembly of the amplifier.

## Assembly and Integration

After the PCB and enclosure were completed, the electronic and mechanical portions of the project were integrated into a single system.

The PCB was mounted inside the enclosure, and the potentiometers, OLED display, power connector, and power switch were installed in their respective locations. The remaining electrical connections were completed internally, allowing the amplifier to operate as a self-contained device.

The finished system replaced the original multi-breadboard setup with a much cleaner and more durable package.

## Final Result

The completed project successfully converted the original Class D amplifier prototype into a permanent standalone system.

The final device combines:

- A custom amplifier PCB
- A custom 3D-printed enclosure
- Integrated user controls
- An OLED display
- A dedicated power input
- A physical power switch

The project provided experience taking an electrical prototype through the later stages of product development, including PCB layout, manufacturing, soldering, mechanical design, 3D printing, assembly, and final system integration.

## Skills and Experience Gained

Through this project, I gained practical experience with:

- PCB schematic capture and layout
- PCB manufacturing preparation
- Soldering
- Circuit debugging and testing
- CAD modeling
- Design for 3D printing
- Mechanical and electrical integration
- Component and connector placement
- Designing an enclosure around existing electronics
- Transitioning a prototype into a finished device


## Bill of Materials

| Item | Quantity | Cost | Link |
|---|---:|---:|---|
| Custom PCB (JLCPCB) | 1 | $65.26 | [JLCPCB](https://jlcpcb.com/) |
| 12 V DC Power Supply | 1 | $9.97 | [Amazon](https://www.amazon.com/dp/B07VQGHSWY) |
| XL5430 Dual-Output DC-DC Converter | 1 | $9.99 | [Amazon](https://www.amazon.com/dp/B0FFSHCGSX) |
| 10 kΩ Linear Potentiometers | 3 | $9.99 | [Amazon](https://www.amazon.com/dp/B082FCRQS2) |
| 3.5 mm Audio Jacks | 2 | $6.19 | [Amazon](https://www.amazon.com/dp/B07KY7XX34) |
| Resistors | Various | Already Owned | — |
| Capacitors | Various | Already Owned | — |
| Op-Amps | Various | Already Owned | — |
| Comparators | Various | Already Owned | — |
| Arduino Nano | 1 | Already Owned | — |
| MOSFETs | Various | Already Owned | — |
| Power Switch | 1 | Already Owned | — |
| OLED Display | 1 | Already Owned | — |
| 3D Printing Filament | — | Already Owned | — |
| Hardware / Fasteners | Various | Already Owned | — |
| Wire | Various | Already Owned | — |

**Total Out-of-Pocket Project Cost:** $101.40

Many components were already available from previous coursework and personal projects, so the listed project cost reflects only items purchased specifically for this build.

## Project Timeline

| Milestone | Status |
|---|---|
| Project planning | Complete |
| PCB schematic development | Complete |
| PCB layout and routing | Complete |
| PCB manufacturing | Complete |
| PCB assembly and soldering | Complete |
| Electrical testing | Complete |
| Enclosure CAD design | Complete |
| Enclosure 3D printing | Complete |
| System integration | Complete |
| Final assembly | Complete |
| Project completion | Complete |

## Project Files

Organize and document important project files in this repository. Depending on the project, this may include:

- Source code
- KiCad files
- Schematics
- PCB layouts
- CAD files
- Datasheets
- Test results
- Documentation

## Useful Links

Add any references, datasheets, documentation, tutorials, or other resources relevant to the project.

## Project Image

Replace the `hero.png` file in the root of this repository with an image representing your project.

**Keep the filename as `hero.png`.**

This image is used as the project cover image on the AMP Lab website.
