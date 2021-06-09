# Master Board Wiring
[Return to the wiring Table of Contents](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring#table-of-contents)

We provide instructions for all soldered components on the Master Board, and the assembly of all cables that route to the Master Board from other components in this section.
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
| Hirose DF13 Crimp Tool | 1 |
| Label Maker | 1 |


## Table of Contents
1. [Pin Mapping](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Master%20Board%20Wiring/README.md#pin-mapping)
2. [Ethernet Jack Soldering](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Master%20Board%20Wiring/README.md#ethernet-jack-soldering)
3. [LED Soldering](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Master%20Board%20Wiring/README.md#led-soldering)
4. [Micro Driver Connection Cable Assembly](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Master%20Board%20Wiring/README.md#micro-driver-connection-cable-assembly)
5. [IMU Cable Assembly](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Master%20Board%20Wiring/README.md#imu-cable-assembly)


## Pin Mapping
| **Top View:** | ![image](https://user-images.githubusercontent.com/84528674/119567724-aa8d9f80-bd7a-11eb-8e6f-2d004598f861.png) | 
| --- | --- |
| **Bottom View:** | ![image](https://user-images.githubusercontent.com/84528674/119568004-03f5ce80-bd7b-11eb-9032-dd6e481519e0.png) |


## Ethernet Jack Soldering
This step focuses on soldering the ethernet jack to the Master Board. The ethernet connection provides the communication interface between the robot and the computer.

| Item | Quantity | 
| --- | --- |
| Ethernet Jack | 1 |

Here are the steps for completing this connection:
| Step Description | Visual | 
| --- | --- |
| The Ethernet Jack's positioning on the Master Board | ![image](https://user-images.githubusercontent.com/84528674/121056442-34326980-c78c-11eb-84dc-fafc50e6bb67.png) |
| The Ethernet Jack should align perfectly with the pins on the Master Board. It may be necessary to slightly bend pins to fit the ethernet jack in place.  | --- |
| Solder all pin connections | --- |


## LED Soldering
This step focuses on soldering the LEDs to the Master Board. These multicolored LEDs serve as a status indication for the Master Board during usage.
| Item | Quantity | 
| --- | --- |
| Neo Pixel LED | 2 |

Here are the steps for completing this connection:
| Step Description | Visual | 
| --- | --- |
| The LEDs positioning on the Master Board | ![image](https://user-images.githubusercontent.com/84528674/121061202-8e81f900-c791-11eb-816f-ac227d8059ec.png) |
| Solder all pin connections | --- |


## Micro Driver Connection Cable Assembly
All four MicroDrivers connect to the Master Board via SPI connections. The wires need to be as short as possible because the SPI bus operates at high frequencies.
| Item | Quantity | 
| --- | --- |
| 26 AWG 5 Pack Wire Kit | **Need to think about positioning on the robot first** |
| 2.4mm Heat Shrink | ~10 cm |
| Crimp Terminals | 40 |
| 5Pos Sockets | 8 |


Your robot frame should be completed before attempting this step. Here are the steps for completing this connection (repeated four times, once per MicroDriver):
| Step Description | Visual | 
| --- | --- |
| https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware/blob/master/electronics/details/details_wiring.md#spi-wires | ![image](https://user-images.githubusercontent.com/84528674/121066752-3e5a6500-c798-11eb-8d1a-6fae2d53bdc1.png) |
| Measure the distance between the position of the MicroDriver and your Master Board on the robot frame. Add three inches to this measurement. For example, we measured **XYZ** inches, so our final measurement would be **XYZ + 3** inches. | --- |
| Cut the five multi-colored 26 AWG wires to this measurement. Strip off about 0.5cm on each end of the wire. Twist the exposed wire after each strip. | --- |
| Crimp each exposed wire using the Hirose DF13 crimping tool and the DF13 crimping terminals **add a lot of pictures/explanation here**  | --- |
| Pick a color orientation. To keep the wire management as simple as possible, use the same color orientation for each SPI wire connection you make. | --- |
| Cut the 2.4mm heat shrink into very thin slices and use it to neatly bind the wires together, leaving about 3cm unbounded on each end. | --- |
| Connect each crimped wire end to a 5Pos Socket. | --- |
| Label the wire. | --- |

**Include wire pin readouts//lots of images of the finished connection**

## IMU Cable Assembly
The IMU connects directly to the Master Board. The original Open Dynamic Robot Initiative documentation for this connection involves connecting an IDC connection to a 4 pin Hirose socket with a ribbon cable, but after experimentation proved this to be a tedious soldering job, we decided to simplify the IMU cable assembly process. We will be connecting an IDC ribbon cable the IMU that bridges to a breakout board to dramatically facilitate the assembly. Pay close attention to follow the pin-to-pin orientations displayed below.

| Item | Quantity | 
| --- | --- |
| IDC Ribbon Cable | 10-pin Socket/Socket, 1.27mm pitch, 150mm long |
| IDC Breakout Board | 10-pin Header, 1.27mm pitch, Adafruit ADA2743 | 
| Hirose DF13 4pin Socket | 1 |
| Hirose DF13 Crimp Terminals | 4 Terminals |
| 1.5mm Heat Shrink | ~10cm |

Complete these steps once: 
| Step Description | Visual | 
| --- | --- |
| The pin orientation of the PCB for the rectangular connection to the IMU. Note that the notch will point away from the IMU. | ![image](https://user-images.githubusercontent.com/84528674/121386169-c4e98080-c917-11eb-8c3b-5a86cd7973af.png) ![image](https://user-images.githubusercontent.com/84528674/121387904-09295080-c919-11eb-8a78-72ad1bbda48f.png) |
| The pin orientation of the breakout board's rectangular connection (implementing the same numbering system used for the PCB shown above). | ![image](https://user-images.githubusercontent.com/84528674/121389939-e5670a00-c91a-11eb-9e6a-0edaa310f9d2.png) |


**Insert picture of final attachment**
