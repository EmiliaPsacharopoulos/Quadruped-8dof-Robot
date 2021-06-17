# MicroDriver Board Wiring
[Return to the wiring Table of Contents](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring#table-of-contents)

We provide instructions for all soldered components on the MicroDriver, and the assembly of the MicroDriver's power cable in this section.
You will need all of the following tools and materials to properly complete the instructions below:

| Item | Quantity | 
| --- | --- |
| Soldering Iron | 1 |
| Solder Spool | 1 |
| Solder Holder | 1 |
| Soldering Vise | 1 |
| Cleaning Sponge | 1 |
| Filter Fan | 1 |
| Heat Gun | 1 |
| Wire Cutter | 1 |
| Wire Stripper | 1 |
| Fine Point Tweezer | 1 |
| Hirose DF13 Crimping Tool | 1 |


## Table of Contents
1. [Pin Mapping](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring/MicroDriver%20Board%20Wiring#pin-mapping)
2. [Resistor Soldering](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/MicroDriver%20Board%20Wiring/README.md#resistor-soldering)
3. [Pin Header Soldering](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/MicroDriver%20Board%20Wiring/README.md#pin-header-soldering)
4. [MicroDriver Power Supply Cables](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/MicroDriver%20Board%20Wiring/README.md#microdriver-power-supply-cables)
5. [MicroDriver Actuator Cables](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/MicroDriver%20Board%20Wiring/README.md#microdriver-actuator-cables)
6. [MicroDriver Encoder Cables](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/MicroDriver%20Board%20Wiring/README.md#microdriver-encoder-cables)



## Pin Mapping

|![image](https://user-images.githubusercontent.com/84528674/119568992-263c1c00-bd7c-11eb-98b3-80b87083d7d5.png)|
|---|
| ![image](https://user-images.githubusercontent.com/84528674/122284501-a2c5a480-cebb-11eb-9fb0-62474935fce0.png) |


## Resistor Soldering
Each MicroDriver board needs 6 resistors soldered on its back. 
| Item | Quantity | 
| --- | --- |
| Precision Resistors | 24 |

Solder 6 resistors per Micro Driver:
| Step Description | Visual | 
| --- | --- |
| Resistor positioning on the back side of the Micro Driver. | ![image](https://user-images.githubusercontent.com/84528674/122285331-91c96300-cebc-11eb-8318-642516a88a4f.png) |
| Soldering step/image | --- |

## Pin Header Soldering
This step focuses on soldering all necessary pin headers to the MicroDriver.

| Item | Quantity | 
| --- | --- |
| Right Angle Pin Headers | 32 |
| Right Angle 5Pos Pin Header | 12 |


First, we will solder the power terminal connections. Repeat the following steps 4 times (1 time per MicroDriver).
| Step Description | Visual | 
| --- | --- |
| The power terminal pin connections visualized | ![image](https://user-images.githubusercontent.com/84528674/122409424-21205600-cf51-11eb-9a10-fe105deaaeb5.png) |
| Shorten then solder one right angle pin header to each power terminal on the MicroDriver | |


We will solder the 5 position pin headers to the back side of the MicroDrivers. These will act as the connections to the two encoders per board and the one SPI connection to the Master Board. The MicroDrivers will be arranged in two stacks of two MicroDrivers. We will give all MicroDrivers right angle 5 position pin headers for ideal wire management.
| Step Description | Visual | 
| --- | --- |
| The connections visualized. | ![image](https://user-images.githubusercontent.com/84528674/122419090-ace9b080-cf58-11eb-94e2-42729c06d024.png) |
| Solder three right angle 5 position pin headers on each MicroDriver's bottom side of the board.| --- |


Lastly, we will solder the right angle pin headers on the front side of the MicroDrivers. These will act as the connections to the motor phase wires per board. 
| Step Description | Visual | 
| --- | --- |
| The connections visualized. | ![image](https://user-images.githubusercontent.com/84528674/122422951-8e38e900-cf5b-11eb-8655-d8ac591d0068.png) |
| Solder six right angle pin headers on each MicroDriver's top side of the board.| --- |

## MicroDriver Power Supply Cables
This step focuses on soldering power supply cables to the MicroDriver that will serve as the consumer connection, regardless of chosen power supply method. The following table lists the necessary tools, parts, and materials to complete this step. 
| Item | Quantity | 
| --- | --- |
| 20 AWG Black Wire | 80 cm |
| 20 AWG Red Wire | 80 cm |
| Female XT30 Connectors | 4 |
| Heat Shrink from XT30 Pack | 4 Red, 4 Black |
| 2.4mm Heat Shrink | ~10 cm |

Repeat the following steps 4 times (1 time per MicroDriver)
| Step Description | Visual | 
| --- | --- |
| Cut a red and a black 20 AWG (0.5mm^2) wire to 20cm. Strip off about 0.5 cm to 1 cm of the wire casing on one side of each wire and twist the exposed wire.  | ![image](https://user-images.githubusercontent.com/84528674/119555096-7363c200-bd6b-11eb-9350-bc18d5e0b461.png)  |
| Follow this [YouTube Video](https://www.youtube.com/watch?v=_NyJbKqRtUE) for detailed instructions on soldering the XT30 female connectors to the exposed wire. The most important step is to use heat shrink after soldering each individual connection. | ![image](https://user-images.githubusercontent.com/84528674/119555167-8bd3dc80-bd6b-11eb-8664-31d39b653cda.png) |
| The connection will look like this before proceeding to the next step: | ![image](https://user-images.githubusercontent.com/84528674/119555219-9bebbc00-bd6b-11eb-9fdc-051f036b84de.png)|
| Cut thin strips of 2.4mm heat shrink, and apply heat to attach them about 5cm apart on each power chord for better wire management. | |
| Strip about 0.5cm to 1cm of the wiring casing of a power chord, twist the exposed wire, then solder the power chord to the corresponding positive or negative right angle pin header from the Pin Header Soldering step. Apply heat shrink from the XT30 pack after each solder. | |



## MicroDriver Actuator Cables
This step focuses on soldering the cable connection to the MicroDriver that will eventually connect to each motor stator. The right angle connectors should already be soldered on the MicroDriver from the above instructions. 

Two motor stators will connect per MicroDriver board. Each stator will have three phase wires. Therefore, we will be making six actuator cables per MicroDriver board. There will roughly be 10 cm per actuator cable, and 24 cables.


| Item | Quantity | 
| --- | --- |
| 20 AWG Black Wire | ~240 cm |
| 2.4mm Heat Shrink | ~40 cm |
| 2mm Female Gold Connectors | 24 |

This is the process of connecting the cables for one MicroDriver board. You will need to complete these steps four times:

| Step Description | Visual | 
| --- | --- |
| Cut 8: 10cm long, 20AWG wires. Cut 8: 11cm long, 20AWG wires. Cut 8: 12cm long, 20AWG wires. We are doing slightly different lengths to account for the positioning on the MicroDriver Board. It is not necessary to do the slightly different lengths. | ![image](https://user-images.githubusercontent.com/84528674/120827114-1a451c80-c529-11eb-93f0-1a3ee2893e6f.png) |
| Strip about 0.5cm to 1cm on one end per wire, twisting the exposed wire after each cut.  | ![image](https://user-images.githubusercontent.com/84528674/120827175-28933880-c529-11eb-9fb8-45dccbb20ca0.png) |
| Solder one 2mm female gold connector per wire. Make sure the orientation is correct before each solder (confirm a male connector can be inserted). | ![image](https://user-images.githubusercontent.com/84528674/120827242-3cd73580-c529-11eb-83fa-507fd5ea4237.png) |
| Use the 2.4mm heat shrink to cover the entire connection after each solder. | ![image](https://user-images.githubusercontent.com/84528674/121407812-b6a65f00-c92d-11eb-8ec7-c10ce14d6569.png) |
| Strip about 0.5cm to 1cm on one the other end of each wire, twisting the exposed wire after each cut.  | --- |
| Push a few cm of 1.5mm heat shrink on each wire, and slide the heat shrink to the gold connection side of the wire. (**do not** use the heat gun on this yet). | --- |
| Solder each wire to a right angle pin header on the MicroDriver. Use the 1.5mm heat shrink to cover the connection after each solder. | --- |


## MicroDriver Encoder Cables
This step focuses on soldering the cable connection to the MicroDriver that will eventually connect to each encoder. The 5pin right angle connectors should already be soldered on the MicroDriver from the above instructions. 

Two encoders will connect per MicroDriver board. Each encoder will have one cable. Therefore, we will be making 8 encoder cables. Note: soldering these cables to the encoders  will be addressed here rather than the Actuator Module Wiring tab. 

| Item | Quantity | 
| --- | --- |
| Encoders | 8 |
| 26 AWG Multi-Colored Wires | **Depends on mounting positions** |
| Crimp Terminals | 40 |
| 1.5mm Heat Shrink | ~40 cm |
| 2.4mm Heat Shrink | ~20 cm |
| 5Pin Socket Connector | 8 |

https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware/blob/master/mechanics/actuator_module_v1/details/details_encoder_preparation.md#details-encoder-preparation 
**This step assumes that the encoders have already been manufactured/modified** First, we need to solder the wires to the encoder. Complete these steps 8 times:
| Step Description | Visual | 
| --- | --- |
| Cut **XYZ** inches of different colored 26 AWG wire. Strip about 1cm of casing from one end of each wire, and twist the exposed wire after each cut.  | --- |
| **MAKE A WIRING DIAGRAM OF PIN to PIN CONNECTIONS** Solder the wires according to this pin layout. Use 1.5mm heat shrink to secure the connection after each solder. | ![image](https://user-images.githubusercontent.com/84528674/121066265-b07e7a00-c797-11eb-98c0-c31794eb715e.png) |
| Use thin strips of 2.4mm heat shrink for wire management, leaving at least 10cm of unbounded wire at the exposed end. | --- |
| Strip about 0.25cm of wire casing on each of the five exposed wires.  | --- |
| Use the crimping tool to crimp each wire (to do: insert a lot of details and pictures). | --- |
| Use tweezers to insert the wires into the 5pin socket connector, making sure to abide by the correct pin to pin connection. | --- |

