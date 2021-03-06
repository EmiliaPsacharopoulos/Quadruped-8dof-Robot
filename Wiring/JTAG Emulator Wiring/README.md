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
| **Connection Visual** ![image](https://user-images.githubusercontent.com/84528674/122424989-28e5f780-cf5d-11eb-819a-17f694ca2c6f.png) |


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
| Follow the pin layout displayed for your chosen front/back orientation. Generally avoid using the same color next to each other for easier wire management. | ![image](https://user-images.githubusercontent.com/84528674/121560628-b6699a80-c9e5-11eb-897f-c82d7ffd1984.png) ![image](https://user-images.githubusercontent.com/84528674/121560583-a94cab80-c9e5-11eb-82c0-0d42cee83169.png) |
| Solder 7 wires to the 8Pos 1.27mm vertical header according to the orientation above. This is an extremely difficult process for newcomers to micro soldering, so it is highly recommmended to buy more 8position headers than just the one. We had to restart four times before succeeding (it is tedious to remove the bridged solder -- easier to start over when this happens). Note: we found the best strategy as: 1) wedge a razor between the front and back headers 2) solder a corner and use thin diameter heat shrink to cover up the connection 3) repeat for all corners 4) solder the middle headers last. 5) Cover the entire 8Position header with properly fitting heat shrink. 6) Trim all wires down to 10cm.| ![image](https://user-images.githubusercontent.com/84528674/120861059-b59fb700-c554-11eb-9cc2-ba9ece85a091.png) |
| Use pliers to obtain 7-columns from the 2.54mm Pitch Vertical Pin Headers. Remove the pin displayed in this picture. |![image](https://user-images.githubusercontent.com/84528674/121578465-b1faad00-c9f8-11eb-955f-73eaedc492e1.png)|
| Slide 1.5mm heat shrink to the MicroDriver end of this cable for each wire. Solder the 7 exposed wires from the cable assembled above and a bridge wire, again being very careful to follow the correct orientation. After each solder, bring the 1.5mm heat shrink forward and use the heat gun to secure the connection. Do not touch the pin headers while applying heat -- the pins and solder will slide out and you will need to shorten the wires and restart the 2.54mm header soldering. | ![image](https://user-images.githubusercontent.com/84528674/121595946-d496c100-ca0c-11eb-9b40-102944f7ea11.png) |
| If the header pins are sliding around after you have soldered the connections, apply large diameter heat shrink over the entire header pin. Also, we decided to remove the unused pins. Note that there is still only one orientation that will plug into the JTAG socket pins. | ![image](https://user-images.githubusercontent.com/84528674/121595164-00657700-ca0c-11eb-9aba-4c1784846ae4.png) |

![image](https://user-images.githubusercontent.com/84528674/121599765-8932e180-ca11-11eb-8af7-15308f1c09c8.png)


## Troubleshooting
Use a digital multimeter to ensure the pins correctly follow their corresponding positions between the 1.27mm header and the 2.54mm header (ie. place prongs at either end and use the signal function). Lastly, make sure that the total length of the cable is 10cm or less.
