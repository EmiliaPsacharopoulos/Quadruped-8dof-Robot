# ESP32 Module Wiring
[Return to the wiring Table of Contents](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring#table-of-contents)

The ESP32 Module flashes the Master Board with a micro USB connection to your computer. This tab describes the wiring assembly for the ESP32 Module. The actual flashing process is described in the Firmware Flashing tab from the main table of contents. 

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



## Table of Contents
1. [Pin Mapping](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/ESP32%20Module%20Wiring/README.md#pin-mapping)
2. [Flashing Connections](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/ESP32%20Module%20Wiring/README.md#flashing-connections)

## Pin Mapping

| ![image](https://user-images.githubusercontent.com/84528674/122427941-7f543580-cf5f-11eb-80d2-2de51eb9eb42.png) |
| --- |
| ![image](https://user-images.githubusercontent.com/84528674/122426204-0c968a80-cf5e-11eb-95d8-46f7425488d0.png) |

## Flashing Connections
This step focuses on making the flashing connection circuit between the ESP32 and the Master Board. You will need to purchase a micro USB to serial adapter.

| Item | Quantity | 
| --- | --- |
| 26 AWG Multi-Colored Wire | ~70cm |
| Hirose DF13 Crimping Tool | 1 |
| DF13 Crimp Terminals | 7 |
| 2 Position Hirose Socket | 1 |
| 5 Position Hirose Socket | 1 |


Follow the following steps to make the circuit. 

| Step Description | Visual | 
| --- | --- |
| Remove the ESP8266 module by directing a heat gun towards the board until the module falls out (no force required - simply use tweezers to brush the component out once you see solder liquify on the board). Use a filter fan directly pointing towards the board. It is a good idea to purchase extra boards in case a component burns during this process. | ![image](https://user-images.githubusercontent.com/84528674/121551068-4fe07e80-c9dd-11eb-90ca-2c6ccfd8c7f7.png) ![image](https://user-images.githubusercontent.com/84528674/122426345-2d5ee000-cf5e-11eb-9f7f-a0f571c6017a.png) |
| Shorted 7 sections of 26 AWG multicolored, precrimped wire to 15cm. Strip about 0.25cm of wire casing on the exposed end of each wire, twisting the exposed wire after each strip. Solder the wires to the ESP32 board according to the pin mapping above. | ![image](https://user-images.githubusercontent.com/84528674/124772282-e5522e00-df09-11eb-89a7-3e1ced09b951.png) ![image](https://user-images.githubusercontent.com/84528674/124772192-cd7aaa00-df09-11eb-9d1b-a1e380243e10.png) |
| Place the power and programming wires into the designated positions in the respective 2 and 5 position sockets displayed above. **REPLACE IMAGES WHEN BOARDS ARRIVE** | ![image](https://user-images.githubusercontent.com/84528674/124774094-868db400-df0b-11eb-83ca-713b8f93bfb1.png) |
