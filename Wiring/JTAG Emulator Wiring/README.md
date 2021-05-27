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

## Pin Mapping
**INSERT PIN READOUTS**
![IMG_3848](https://user-images.githubusercontent.com/84528674/119847684-30276180-bed9-11eb-9b2a-64afcdeaa6c6.jpg)

![image](https://user-images.githubusercontent.com/84528674/119844406-67484380-bed6-11eb-8c5e-64900b046b1f.png)



## Flashing Wire

This step focuses on making the flashing wire between the JTAG and a MicroDriver. The JTAG Emulator comes with an adapter cable from the flash cable connection on the Emulator side. We will not be using this adapter because we want to keep the connection as short as possible (about 10cm). 

| Item | Quantity | 
| --- | --- |
| EMULATOR JTAG XDS100V2 USB | 1 |
| Vertical Header 8Pos 1.27mm | 1 |
| Multi-Colored 26 AWG Wire Spool | **FILL IN LATER** |
| 2.54mm Pitch Vertical Pin Headers | 13 |
| 1.5mm Heat Shrink | ~10cm |
| 2.4mm Heat Shrink | ~10cm |


Follow the following steps to make the adapter. Note: we elected to use individual wires on this step because ribbon cables are tedious to solder, but it would be equally valid to use a ribbon cable following these steps.

| Step Description | Visual | 
| --- | --- |
| Repeat the following 8 times: Cut **XYZ**cm of multi-colored 26 AWG wire. Strip both ends of the wire, twisting the exposed wire after each strip. | --- |
| Separate the 8Pos 1.27mm vertical headers into 8 pieces by gently breaking the connecting plastic. This will make the soldering process much easier. | --- |
| Solder 7 wires to 7 8Pos 1.27mm vertical headers. Use the 1.5mm heat shrink after each solder to carefully cover the connection. | --- |
| Orient the wires in the MicroDriver pin connection. It would be helpful to avoid placing repeated colors next to each other. (**include pin readouts and images**) | --- |
| Carefully slide the 2.4mm heat shrink to cover directly over the connection. Be extremely careful while using the heat gun to avoid applying heat directly on the MicroDriver board. | --- |
| --- | --- |
| --- | --- |
