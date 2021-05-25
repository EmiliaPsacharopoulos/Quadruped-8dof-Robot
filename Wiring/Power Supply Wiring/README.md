# Power Supply Wiring
[Return to the wiring Table of Contents](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring#table-of-contents)

The robot can be powered by one of two methods: 
- External power supply
- Batteries on the robot

Below, we describe the implementation of both methods. In either case, each of the four MicroDrivers receives a supplying power cable. 

## Table of Contents
1. [MicroDriver Power Supply Cables](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Power%20Supply%20Wiring/README.md#microdriver-power-supply-cables)
2. [External Power Supply Method](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Power%20Supply%20Wiring/README.md#external-power-supply-method)
3. [Battery Method](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Power%20Supply%20Wiring/README.md#battery-method)

## MicroDriver Power Supply Cables
This step focuses on soldering power supply cables to the MicroDriver that will serve as the consumer connection, regardless of chosen power supply method. The following table lists the necessary tools, parts, and materials to complete this step. 
| Item | Quantity | 
| --- | --- |
| Soldering Iron | 1 |
| Solder Spool | 1 |
| Solder Holder | 1 |
| Cleaning Sponge | 1 |
| Filter Fan | 1 |
| Heat Gun | 1 |
| Wire Cutter | 1 |
| Wire Stripper | 1 |
| 20 AWG Black Wire | 80 cm |
| 20 AWG Red Wire | 80 cm |
| Female XT30 Connectors | 4 |
| Heat Shrink from XT30 Pack | 4 Red, 4 Black |
| 2.4mm Heat Shrink | ~10 cm |
| Right Angle Pin Header | 8 |

Repeat the following steps 4 times (1 time per MicroDriver)
| Step Description | Visual | 
| --- | --- |
| Cut a red and a black 20 AWG (0.5mm^2) wire to 20cm. Strip off about 0.5 cm to 1 cm of the wire casing on one side of each wire and twist the exposed wire.  | <img src="https://user-images.githubusercontent.com/84528674/119542755-e2d2b500-bd5d-11eb-8f42-fa994dd837c3.png" height = "300" width = "400">  |
| Follow this [YouTube Video](https://www.youtube.com/watch?v=_NyJbKqRtUE) for detailed instructions on soldering the XT30 female connectors to the exposed wire. | <img src="https://user-images.githubusercontent.com/84528674/119542893-0eee3600-bd5e-11eb-8e56-316c2be91cdf.png" height = "300"  width = "400"> |
| The connection will look like this before proceeding to the next step: |  <img src="https://user-images.githubusercontent.com/84528674/119543052-3ba24d80-bd5e-11eb-9977-65cba2f650c6.png" width = 400>|
| Cut thin strips of 2.4mm heat shrink, and apply heat to attach them about 5cm apart on each power chord for better wire management. | |
| Shorten then solder one right angle pin header to each power terminal pin on the MicroDriver | |
| Strip about 0.5cm to 1cm of the wiring casing of a power chord, twist the exposed wire, then solder the power chord to the corresponding positive or negative right angle pin header from the previous step. Apply heat shrink from the XT30 pack after each solder. | |


## External Power Supply Method


## Battery Method

