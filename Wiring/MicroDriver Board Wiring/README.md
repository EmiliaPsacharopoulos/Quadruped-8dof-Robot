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

## Table of Contents
1. [Pin Mapping](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring/MicroDriver%20Board%20Wiring#pin-mapping)
2. [Resistor Soldering](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/MicroDriver%20Board%20Wiring/README.md#resistor-soldering)
3. [Pin Header Soldering](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/MicroDriver%20Board%20Wiring/README.md#pin-header-soldering)
4. [MicroDriver Power Supply Cables](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/MicroDriver%20Board%20Wiring/README.md#microdriver-power-supply-cables)
5. [MicroDriver Actuator Cables](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/MicroDriver%20Board%20Wiring/README.md#microdriver-actuator-cables)



## Pin Mapping
![image](https://user-images.githubusercontent.com/84528674/119568992-263c1c00-bd7c-11eb-98b3-80b87083d7d5.png)



## Resistor Soldering
Each MicroDriver board needs 6 resistors soldered on its back. 
| Item | Quantity | 
| --- | --- |
| Precision Resistors | 6 |

Record exact pins here (list and include image(s))

Include images documenting the soldering process.

## Pin Header Soldering
This step focuses on soldering all necessary pin headers to the MicroDriver.

| Item | Quantity | 
| --- | --- |
| Right Angle Pin Headers | 32 |
| Right Angle 5Pos Pin Header | 12 |


First, we will solder the power terminal connections. Repeat the following steps 4 times (1 time per MicroDriver).
| Step Description | Visual | 
| --- | --- |
| Shorten then solder one right angle pin header to each power terminal **name exact pin connection** pin on the MicroDriver | |


Lastly, we will solder the 5 position pin headers. The MicroDrivers will be arranged in two stacks of two MicroDrivers. We will give all MicroDrivers right angle 5 position pin headers for ideal wire management.
| Step Description | Visual | 
| --- | --- |
| Solder three right angle 5 position pin headers on each MicroDriver's bottom side of the board **include images/exact pin readouts**| --- |



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
| 20 AWG Multi-Colored Wire | ~240 cm |
| 2.4mm Heat Shrink | ~40 cm |

This is the process of connecting the cables for just one cable. You will need to repeat these steps 24-times. It is recommended to complete each step individually 24 times before moving onto another step. 

| Step Description | Visual | 
| --- | --- |
