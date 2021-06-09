# JTAG Emulator Wiring
[Return to the wiring Table of Contents](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring#table-of-contents)

The JTAG emulator flashes the MicroDriver boards with a USB connection to your computer. Note that the JTAG emulator on our Bill of Materials includes this USB connection (USB to MicroUSB). This tab describes the wiring assembly for the JTAG emulator. The actual flashing process is described in the Firmware Flashing tab from the main table of contents. 

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
1. [Pin Mapping](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/JTAG%20Emulator%20Wiring/README.md#pin-mapping)
2. [Flashing Wire](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring/JTAG%20Emulator%20Wiring#flashing-wire)
3. [Troubleshooting](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/JTAG%20Emulator%20Wiring/README.md#troubleshooting)

## Pin Mapping

| **JTAG Top View** ![image](https://user-images.githubusercontent.com/84528674/120558563-a9d5b880-c3cd-11eb-81c0-c321be55cdf8.png) |
| --- |
| **MicroDriver Top View** ![image](https://user-images.githubusercontent.com/84528674/120829285-39dd4480-c52b-11eb-8b14-d7954dc5e632.png)|


## Flashing Wire

This step focuses on making the flashing wire between the JTAG and a MicroDriver. The JTAG Emulator comes with an adapter cable from the flash cable connection on the Emulator side. We will not be using this adapter because we want to keep the connection as short as possible (about 10cm). 

| Item | Quantity | 
| --- | --- |
| EMULATOR JTAG XDS100V2 USB | 1 |
| Multi-Colored 26 AWG Wire Spool | ~90cm |
| 2.54mm Pitch Vertical Pin Headers | 13 |
| Pin Header 8 Position 1.27mm Pitch | 1 |
| 1.5mm Heat Shrink | ~10cm |
| 2.4mm Heat Shrink | ~10cm |


Follow the following steps to make the adapter. 

| Step Description | Visual | 
| --- | --- |
| Repeat the following 7 times: Cut 15cm of multi-colored 26 AWG wire. Strip about 0.5cm from one end of each wire, twisting the exposed wire after each strip. Note: this adapter will be 10cm but the extra length allows for error during the soldering process. | ![image](https://user-images.githubusercontent.com/84528674/120859950-ee3e9100-c552-11eb-9196-ed956407885b.png) |
| Follow the pin layout displayed for your chosen front/back orientation. Generally avoid using the same color next to each other for easier wire management. | ![image](https://user-images.githubusercontent.com/84528674/120832549-c9382700-c52e-11eb-9bd1-0adb6d76b141.png) ![image](https://user-images.githubusercontent.com/84528674/120859872-d49d4980-c552-11eb-9e87-e5273a453dc6.png) |
| Solder 7 wires to the 8Pos 1.27mm vertical header according to the orientation above. This is an extremely difficult process for newcomers to micro soldering, so it is highly recommmended to buy more 8position headers than just the one. We had to restart four times before succeeding (it is tedious to remove the bridged solder -- easier to start over when this happens). Note: we found the best strategy as: 1) wedge a razor between the front and back headers 2) solder a corner and use thin diameter heat shrink to cover up the connection 3) repeat for all corners 4) solder the middle headers last. 5) Cover the entire 8Position header with properly fitting heat shrink. | ![image](https://user-images.githubusercontent.com/84528674/120861059-b59fb700-c554-11eb-9cc2-ba9ece85a091.png) |
| Use pliers to obtain 7-columns from the 2.54mm Pitch Vertical Pin Headers.| ![image](https://user-images.githubusercontent.com/84528674/121409970-11d95100-c930-11eb-93ed-2ca94dd9145b.png) |
| Remove the pins displayed in this picture (orientation is extremely important). | ![image](https://user-images.githubusercontent.com/84528674/121415594-ea858280-c935-11eb-90d1-0b56909ea8f6.png) |
| Be extremely careful to map between the MicroDriver and the JTAG. | ![image](https://user-images.githubusercontent.com/84528674/121417373-d3479480-c937-11eb-9ce8-eea29bd4ac6b.png) |
| Slide 1.5mm heat shrink to the MicroDriver end of this cable for each wire. Solder the 7 exposed wires from the cable assembled above, again being very careful to follow the correct orientation. After each solder, bring the 1.5mm heat shrink forward and use the heat gun to secure the connection. | --- |
| Carefully mark the orientation to plug in the header pin. | --- |


## Troubleshooting
![image](https://user-images.githubusercontent.com/84528674/120024751-a30a0880-bfbd-11eb-9081-3ec46814fdf7.png)
