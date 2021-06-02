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
We will be 
| **JTAG Top View** ![IMG_3848](https://user-images.githubusercontent.com/84528674/119847684-30276180-bed9-11eb-9b2a-64afcdeaa6c6.jpg) |
| --- |
| **JTAG Pin Mapping** 
![image](https://user-images.githubusercontent.com/84528674/120558433-72ffa280-c3cd-11eb-9c50-8eed8fc993aa.png)|


**From the forum**
![image](https://user-images.githubusercontent.com/84528674/120024751-a30a0880-bfbd-11eb-9081-3ec46814fdf7.png)



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
| Repeat the following 8 times: Cut 10cm of multi-colored 26 AWG wire. Strip both ends of the wire, twisting the exposed wire after each strip. | --- |
| Solder 7 wires to 7 8Pos 1.27mm vertical headers. Use the 1.5mm heat shrink after each solder to carefully cover the connection Generally avoid using the same color next to each other for easier wire management. **include pin layouts** | --- |
| Carefully slide the 2.4mm heat shrink to cover directly over the 8Pos header. Be careful while using the heat gun to avoid applying heat directly on the MicroDriver board. | --- |
| Slide about 3cm of 1.5mm heat shrink over each individual wire, placing these strips as far as possible from the exposed end. Do not use the heat gun yet, this will be done in later steps. | --- |
| Orient the wires on the JTAG emulator connection according to the pin readouts in the Pin Mapping section above. Be extremely careful to map between the MicroDriver and the JTAG. | --- |
| Solder the 7 exposed wires from the cable assembled above, again being very careful to follow the correct orientation. After each solder, bring the 1.5mm heat shrink forward and use the heat gun to secure the connection. | --- |
| We will now make the bridge wire. Cut about 4cm of the 26 AWG wire. Strip both ends of the wire, twisting the exposed wire after each strip. Slide two ~1cm strips of 1.5mm heat shrink to the center of the wire.| --- |
| Solder the bridging wire to the following pin headers on the JTAG 12pin header, using the heat gun to bind each shrink strip after each solder. | --- |
