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
| Label Maker | 1 |


## Table of Contents
1. [Pin Mapping](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Master%20Board%20Wiring/README.md#pin-mapping)
2. [Ethernet Jack Soldering](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Master%20Board%20Wiring/README.md#ethernet-jack-soldering)
3. [LED Soldering](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Master%20Board%20Wiring/README.md#led-soldering)
4. [Micro Driver Connection Cable Assembly](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Master%20Board%20Wiring/README.md#micro-driver-connection-cable-assembly)
5. [IMU Cable Assembly](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Master%20Board%20Wiring/README.md#imu-cable-assembly)


## Pin Mapping
| **Front View:** | ![image](https://user-images.githubusercontent.com/84528674/119567724-aa8d9f80-bd7a-11eb-8e6f-2d004598f861.png) | 
| --- | --- |
| **Back View:** | ![image](https://user-images.githubusercontent.com/84528674/119568004-03f5ce80-bd7b-11eb-9032-dd6e481519e0.png) |


## Ethernet Jack Soldering
This step focuses on soldering the ethernet jack to the Master Board. The ethernet connection provides the communication interface between the robot and the computer.

| Item | Quantity | 
| --- | --- |
| Ethernet Jack | 1 |

Here are the steps for completing this connection:
| Step Description | Visual | 
| --- | --- |
| The Ethernet Jack's positioning on the Master Board | ![image](https://user-images.githubusercontent.com/84528674/122260368-2f169e00-cea1-11eb-88e0-38111e2bd007.png) |
| The Ethernet Jack should align perfectly with the pins on the Master Board. It may be necessary to slightly bend pins to fit the ethernet jack in place. Solder all pin connections. | --- |


## LED Soldering
This step focuses on soldering the LEDs to the Master Board. These multicolored LEDs serve as a status indication for the Master Board during usage.
| Item | Quantity | 
| --- | --- |
| Neo Pixel LED | 2 |

Here are the steps for completing this connection:
| Step Description | Visual | 
| --- | --- |
| The LEDs positioning on the Master Board | ![image](https://user-images.githubusercontent.com/84528674/122260155-eeb72000-cea0-11eb-9718-318d961b9f64.png) |
| Solder all pin connections, paying close attention to the orientation of the diagonal mark on the LEDs. | --- |


## Micro Driver Connection Cable Assembly
All four MicroDrivers connect to the Master Board via SPI connections. The wires need to be as short as possible because the SPI bus operates at high frequencies.
| Item | Quantity | 
| --- | --- |
| 26 AWG Multicolored, Precrimped Wire | 20 Wires |
| 2.4mm Heat Shrink | ~10 cm |
| 5Pos Hirose DF13 Socket | 8 |


Your robot frame should be completed before attempting this step. Here are the steps for completing this connection (repeated four times, once per MicroDriver):
| Step Description | Visual | 
| --- | --- |
| The SPI pin-to-pin mapping between the Master Board a MicroDriver. | ![image](https://user-images.githubusercontent.com/84528674/122260026-cfb88e00-cea0-11eb-882e-cc0b4047b27d.png) |
| Measure the shortest possible distance between the position of the MicroDrivers to your Master Board on the robot frame. These wires need to be kept as short as possible. | --- |
| Cut the multi-colored 26 AWG precrimped wires to this measurement. | --- |
| Pick a color orientation. To keep the wire management as simple as possible, use the same color orientation for each SPI wire connection you make. | --- |
| Cut the 2.4mm heat shrink into very thin slices and use it to neatly bind the wires together, leaving about 3cm unbounded on each end. | --- |
| Connect each crimped wire end to a 5Pos Socket. | --- |
| Label the wire. | --- |


## IMU Cable Assembly
The IMU connects directly to the Master Board. The original Open Dynamic Robot Initiative documentation for this connection involves connecting an IDC connection to a 4 pin Hirose socket with a ribbon cable, but after experimentation proved this to be a tedious soldering job, we decided to simplify the IMU cable assembly process. We will be connecting an IDC ribbon cable the IMU that bridges to a breakout board to dramatically facilitate the assembly. Pay close attention to follow the pin-to-pin orientations displayed below.

| Item | Quantity | 
| --- | --- |
| IDC Ribbon Cable | 10-pin Socket/Socket, 1.27mm pitch, 150mm long |
| IDC Breakout Board | 10-pin Header, 1.27mm pitch, Adafruit ADA2743 | 
| Hirose DF13 4pin Socket | 1 |
| 1.5mm Heat Shrink | ~10cm |
| 28 AWG Multicolored, Precrimped Wire | ~28cm |

Complete these steps once: 
| Step Description | Visual | 
| --- | --- |
| The pin orientation of the PCB for the rectangular connection to the IMU. | ![image](https://user-images.githubusercontent.com/84528674/122276571-ea93fe00-ceb2-11eb-9ed0-065c347881fe.png)|
| The pin orientation of the breakout board's rectangular connection (implementing the same numbering system used for the PCB shown above). | ![image](https://user-images.githubusercontent.com/84528674/122278780-4a8ba400-ceb5-11eb-9b52-23623555d33e.png) |
| Trim 4 of the precrimped, multicolored 26 AWG wire down to 4 inches. Strip and twist about 0.5cm off the end of each remaining wire. Solder the four wires to pins labeled 3, 4, 5, and 8 on the breakout board. | ![image](https://user-images.githubusercontent.com/84528674/124943562-99bb8500-dfda-11eb-8935-78829e1b697e.png) |
| Use tweezers to insert the crimps into a Hirose DF13 4pin Socket. | ![image](https://user-images.githubusercontent.com/84528674/122281077-dbfc1580-ceb7-11eb-93e6-474dbb25f1d5.png) ![image](https://user-images.githubusercontent.com/84528674/124944899-b1dfd400-dfdb-11eb-90f3-86fb19afa667.png) |
