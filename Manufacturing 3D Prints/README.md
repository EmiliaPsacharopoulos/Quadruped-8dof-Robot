# Manufacturing 3D Prints
[Return to the main Table of Contents](https://github.com/EmiliaPsacharopoulos/Formatting#table-of-contents)

## Table of Contents
1. [Printers](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Manufacturing%203D%20Prints/README.md#printers)
2. [Front and Side Body Structure Manufacturing](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Manufacturing%203D%20Prints/README.md#front-and-side-body-structure-manufacturing)
3. [Leg Shell Manufacturing](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Manufacturing%203D%20Prints/README.md#leg-shell-manufacturing)

## Printers
We utilized three different printers to ensure proper tolerances, print capacity, and material properties. The specific printers are described below.

### Tight Tolerance Parts
For tight tolerance parts (such as the pulleys and tensioners) we used an SLA printer, specifically a Formlabs Form 3 along with a Form Wash and Form Cure for post processing. We used Formlab's Durable Resin for its wear resistance, but any Tough/Durable family resin will suffice.
| Form 3 SLA Printer | Form Wash | Form Cure | Durable Resin | 
| --- | --- | --- | --- |
| ![image](https://user-images.githubusercontent.com/84528674/119168958-78ed9f00-ba2f-11eb-85ec-6fc6b7f32cdb.png) | ![image](https://user-images.githubusercontent.com/84528674/119169020-8b67d880-ba2f-11eb-8c8a-13b7603b735e.png) | ![image](https://user-images.githubusercontent.com/84528674/119169057-9589d700-ba2f-11eb-8097-a1d2f67731ae.png) | ![image](https://user-images.githubusercontent.com/84528674/119169291-d41f9180-ba2f-11eb-9ca7-117032d88673.png) |

### Large Structural Parts
For the larger structural pieces (such as the sides and bottom of the frame) we used a LULZBOT TAZ 5 for its print capacity ( 298mm x 275mm x 250mm). For materials we used the IC3D ABS filament.

**Pro tip**: Since the LULZBOT has no enclosure it is not ideal for printing ABS. To remedy this we applied a layer of Elmer's glue to the print bed before each print. Additionally, you could build an enclosure from cardboard. This contains the heat and prevents contamination.

| LULZBOT TAZ 5 | IC3D ABS Filament |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/84528674/119169794-6b84e480-ba30-11eb-9729-315759b24588.png) | ![image](https://user-images.githubusercontent.com/84528674/119169833-78093d00-ba30-11eb-89da-5c87a33aa44b.png) |

### Remaining Parts
For all remaining parts we used a Zortrax M200 with HATCHBOX ABS filament.

| Zortrax M200 | HATCHBOX ABS Filament |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/84528674/119170145-d9c9a700-ba30-11eb-94c2-e50c81143ff6.png) | ![image](https://user-images.githubusercontent.com/84528674/119170186-e5b56900-ba30-11eb-81b7-cdad5b576c3d.png) |

## Front and Side Body Structure Manufacturing 
### Materials Masterlist
| Item | Quantity |
| --- | --- |
| Body Structure Side | 2 |
| Body Structure Front | 2 |
| Tap Handle | 1 |
| Pin Vice | 1 |
| M3 Helicoil Insert Tool Set | 1 |
| 2.5mm Drill Bit | 1 |
| Helicoil M3x6mm | 8 |
| Helicoil M3 x 4.5 mm | 8 |
| M3 x 8 mm Socket Head Cap Screw | 16 |
| 2.5 mm Hex Wrench | 1 |
| Needle Nose Plier | 1 |
| File Set | 1 |

### Step 1: Prepare 3D Printed Parts
Remove support materials using the needle nose pliers and files. Use caution when removing supports so that you do not damage the part. 

**Pro tip**: If the supports are proving really difficult to remove, leave prints in hot water for a few minutes and try again.
| Front Pieces with Supports | Front Pieces Cleared (front and back shown) |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/84528674/119171575-c3bce600-ba32-11eb-998e-5dafda09bc29.png) | ![image](https://user-images.githubusercontent.com/84528674/119171631-d33c2f00-ba32-11eb-9e55-69242abb506d.png) |


| Side Piece Top View | Side Piece Front View  |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/84528674/119172090-77be7100-ba33-11eb-9f81-30a2d94042f2.png) | ![image](https://user-images.githubusercontent.com/84528674/119172125-82790600-ba33-11eb-8814-2f9bfb417c92.png) |

Note that some supports in the mass saving cutouts could not be removed. This is non-critical, and the solution is to include a raft layer or inverting the print orientation. After removing from the bed, the side piece may have a slight bend. This will be fixed with the bottom body structure attachment.

### Step 2: Insert Helicoils
![image](https://user-images.githubusercontent.com/84528674/119172351-d5eb5400-ba33-11eb-8583-ee55651220d8.png)

Insert helicoils into the side pieces according to the following procedure:
| Step Description | Visual |
| --- | --- |
| Clear out any remaining supports from the holes with the 2.5 mm drill bit and pin vice or a hand drill. | ![image](https://user-images.githubusercontent.com/84528674/119172608-2bbffc00-ba34-11eb-8039-533d215dbb1c.png) |
| Tap the holes using the M3 helicoil insert tool set tap. Be careful not to bottom out the tap and strip the threads. | ![image](https://user-images.githubusercontent.com/84528674/119172691-41352600-ba34-11eb-88a8-0074ee6e8256.png) |
| Using the installation tool insert the appropriate helicoil. Note that the helicoil diameter will be larger than the hole, but once threaded it will wind in. The extra compression helps with the thread grip. Insert the helicoil until it is just below the surface, and use the break-off tool to remove the tang. | ![image](https://user-images.githubusercontent.com/84528674/119172787-59a54080-ba34-11eb-9386-4cb92070b697.png) |
| You may find it difficult to initially thread a bolt into the hole as the coils need to be aligned. Thus, you can insert a bolt in and out to correct alignment. | ![image](https://user-images.githubusercontent.com/84528674/119172872-704b9780-ba34-11eb-8efb-1585af2b73c5.png) |

### Step 3: Assembly
| Use the bolts secure the side pieces to the front pieces. Pay attention to part orientation. | 
| --- |
| ![image](https://user-images.githubusercontent.com/84528674/119173204-f4058400-ba34-11eb-9121-70e96c12558e.png) ![image](https://user-images.githubusercontent.com/84528674/119173258-04b5fa00-ba35-11eb-8ce9-e3f7e5bd56ba.png) ![image](https://user-images.githubusercontent.com/57100380/119373504-7afd6b00-bc86-11eb-8c2f-e1e3261a3678.png) |

## Frame Base Assembly
### Materials Masterlist
| Item | Quantity |
| --- | --- |
| Body Structure Bottom | 1 |
| Tap Handle | 1 |
| Pin Vice | 1 |
| M3 Helicoil Insert Tool Set | 1 |
| 2.5mm Drill Bit | 1 |
| Helicoil M3 x 4.5 mm | 9 |
| M3 x 8 mm Socket Head Cap Screw | 24 |
| 2.5 mm Hex Wrench | 1 |
| Needle Nose Plier | 1 |
| File Set | 1 |

### Step 1: Prepare 3D Printed Parts
Remove support materials using the needle nose pliers and files. Use caution when removing supports so that you do not damage the part.
| --- |
| ![image](https://user-images.githubusercontent.com/57100380/119376176-aa61a700-bc89-11eb-93ed-29420af26e61.png) |

## Leg Shell Manufacturing 
To complete later
