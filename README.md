# Project Name

> Custom ESC for Fixed Wing UAV

## Project Owner

**Name:** Owen Burden  
**Virginia Tech Email:** owenburden@vt.edu

## Project Overview

The goal of this project is to develop an Electronic Speed Controller (ESC) compatible with an off-the-shelf Flight Controller (FC) and motors for a Fixed Wing UAV.

The ESC receives battery power through the FC’s power distribution board and throttle commands from the FC. The ESC will use those to properly power the motors, so they spin efficiently and at the speed relayed by the FC.

## What I Hope to Learn

Through developing a custom ESC I hope to: 
Learn in-depth how ESCs work
Improve PCB design skills
Develop LTspice modeling skills
Refine PCB assembly and soldering skills
Understand motor control and power electronics

## Design and Implementation

Document the design of your project as it develops.

<img width="981" height="545" alt="image" src="https://github.com/user-attachments/assets/b25ce65a-f18c-4747-b6e5-930e59db9380" />

<img width="985" height="547" alt="image" src="https://github.com/user-attachments/assets/00c6c0b4-85d7-4941-8b74-d9e146e27a6b" />

<img width="982" height="556" alt="image" src="https://github.com/user-attachments/assets/260dc1b6-da94-4f49-8e98-188e98ec16f7" />


## Bill of Materials

Document the major components and materials used for the project.

| Item | Quantity | Estimated Cost | Link |
|---|---:|---:|---|
| Microcontroller (STM32G071, AM32 G071 target package) | 1 | $2.50 | [Link](https://www.digikey.com/en/products/result?keywords=STM32G071) |
| MCU decoupling caps (100 nF + 4.7 µF X7R, 0402/0603) | 4 | $0.20 | [Link](https://www.digikey.com/en/products/result?keywords=100nF%20X7R%200402) |
| Status LED + resistor (0603 LED, 1 kΩ) | 1 | $0.10 | [Link](https://www.digikey.com/en/products/result?keywords=0603%20LED) |
| 3-phase gate driver (Fortior FD6288Q) | 1 | $0.80 | [Link](https://www.lcsc.com/search?q=FD6288Q) |
| Bootstrap capacitors (1 µF X7R, 25 V+) | 3 | $0.15 | [Link](https://www.digikey.com/en/products/result?keywords=1uF%2025V%20X7R) |
| Gate resistors (~10 Ω, 0402) | 6 | $0.12 | [Link](https://www.digikey.com/en/products/result?keywords=10%20ohm%200402) |
| MOSFETs (N-channel 30–40 V, low RDS(on), 5×6, e.g. Infineon OptiMOS 40 V) | 6 | $9.00 | [Link](https://www.digikey.com/en/products/result?keywords=OptiMOS%2040V) |
| Bulk capacitor (low-ESR electrolytic, 35 V, ~470 µF) | 1 | $0.80 | [Link](https://www.digikey.com/en/products/result?keywords=470uF%2035V%20low%20ESR) |
| Ceramic bus capacitors (10 µF X7R, 35 V, 1206) | 6 | $1.20 | [Link](https://www.digikey.com/en/products/result?keywords=10uF%2035V%20X7R%201206) |
| 3.3 V regulator (TI TPS70933 LDO) | 1 | $0.60 | [Link](https://www.digikey.com/en/products/result?keywords=TPS70933) |
| Back-EMF dividers (0402 1% resistors, AM32 reference values) | 9 | $0.18 | [Link](https://www.digikey.com/en/products/result?keywords=0402%201%25%20resistor) |
| Battery voltage divider (10 kΩ / 1 kΩ, 0603 1%) | 2 | $0.04 | [Link](https://www.digikey.com/en/products/result?keywords=10k%200603%201%25) |
| Signal series resistor (220 Ω, 0402) | 1 | $0.02 | [Link](https://www.digikey.com/en/products/result?keywords=220%20ohm%200402) |
| Signal ESD protection (Nexperia PESD5V0S1BL) | 1 | $0.20 | [Link](https://www.digikey.com/en/products/result?keywords=PESD5V0S1BL) |
| Battery + motor wire (12–16 AWG silicone) | 1 set | $2.00 | [Link](https://www.amazon.com/s?k=14+AWG+silicone+wire) |
| **Total per board** | | **$17.91** | |
| Servo tester (Tizuqe High Accuracy Servo Tester) | 1 | $10.00 | [Link](https://www.amazon.com/s?k=Tizuqe+servo+tester) |
| Motor (T-MOTORHOBBY F60 Pro V 1750KV) | 3 | $81.00 | [Link](https://www.amazon.com/s?k=T-Motor+F60+Pro+V+1750KV) |
| PCB fabrication (JLCPCB) | 1 | $40.00 | [Link](https://jlcpcb.com) |
| Stencil | 1 | $15.00 | [Link](https://jlcpcb.com) |
| Shipping and tariffs | 1 | $45.00 | — |
| **Total for project (4 boards)** | | **$262.64** | |
**Estimated Total Cost:** $0.00

## Timeline and Milestones

Outline the major stages of the project and update them as work progresses.

| Milestone | Target Date | Status |
|---|---|---|
| Project planning | 11/15/26 | In Progress |
| PCB Schematic | 12/18/26 | Not Started |
| PCB Layout | 2/1/27 | Not Started |
| Prototype | 3/1/27 | Not Started |
| Testing | 4/1/27 | Not Started |
| Project completion | 4/8/27 | Not Started |

## Progress Log

Use this section to document meaningful progress throughout the project.

### YYYY-MM-DD

Describe what you worked on, what was completed, any problems you encountered, and what you plan to work on next.

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
