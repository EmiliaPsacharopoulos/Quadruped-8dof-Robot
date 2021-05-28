# Manufacturing 3D Prints
[Return to the main Table of Contents](https://github.com/EmiliaPsacharopoulos/Formatting#table-of-contents)

## Table of Contents
1. [Printers](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Manufacturing%203D%20Prints/README.md#printers)
2. [Printing Specifications](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Manufacturing%203D%20Prints/README.md#printing-specifications)
3. [Front and Side Body Structure Post Processing](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Manufacturing%203D%20Prints/README.md#front-and-side-body-structure-post-processing)
4. [Frame Asembly](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Manufacturing%203D%20Prints/README.md#frame-assembly)
5. [Leg Shell Post Processing](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Manufacturing%203D%20Prints/README.md#leg-shell-post-processing)
6. [Output Pulley Preperation](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Manufacturing%203D%20Prints/README.md#output-pulley-preperation)

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

## Printing Specifications
Please refer to the [CAD Masterlist](https://github.com/EmiliaPsacharopoulos/Formatting/tree/main/CAD%20Masterlist) documentation on how to print each component, specific quantities, and material.

## Front and Side Body Structure Post Processing
### Materials Masterlist
| Item | Quantity |
| --- | --- |
| Body Structure Side (3D Print) | 2 |
| Body Structure Front (3D Print) | 2 |
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
| Using the installation tool insert the appropriate helicoil. Note that the helicoil diameter will be larger than the hole, but once threaded it will wind in. The extra compression helps with the thread grip. Insert the helicoil until it is just below the surface. | ![image](https://user-images.githubusercontent.com/84528674/119172787-59a54080-ba34-11eb-9386-4cb92070b697.png) |
| Use the break-off tool to remove the tang. | ![image](https://user-images.githubusercontent.com/57100380/119379481-886a2380-bc8d-11eb-8a4f-6f4890f085c0.png) |
| You may find it difficult to initially thread a bolt into the hole as the coils need to be aligned. Thus, you can insert a bolt in and out to correct alignment. | ![image](https://user-images.githubusercontent.com/84528674/119172872-704b9780-ba34-11eb-8efb-1585af2b73c5.png) |

### Step 3: Assembly
Use the bolts secure the side pieces to the front pieces. Pay attention to part orientation.

| Bolt Location | Full Assembly |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/84528674/119173204-f4058400-ba34-11eb-9121-70e96c12558e.png) | ![image](https://user-images.githubusercontent.com/57100380/119373504-7afd6b00-bc86-11eb-8c2f-e1e3261a3678.png) |

## Frame Assembly
### Materials Masterlist
| Item | Quantity |
| --- | --- |
| Body Structure Bottom (3D Print) | 1 |
| Body Structure Top (3D Print) | 1 |
| Tap Handle | 1 |
| Pin Vice | 1 |
| M2 Tap | 1 |
| 1.5 mm Drill Bit | 1 |
| M2.5 Tap | 1 |
| 2 mm Drill Bit | 1 |
| M3 Helicoil Insert Tool Set | 1 |
| 2.5mm Drill Bit | 1 |
| Helicoil M3 x 4.5 mm | 17 |
| M3 x 8 mm Socket Head Cap Screw | 24 |
| 2.5 mm Hex Wrench | 1 |
| Needle Nose Plier | 1 |
| File Set | 1 |

### Step 1: Prepare 3D Printed Parts
Remove support materials using the needle nose pliers and files. Use caution when removing supports so that you do not damage the part.

To remove supports from the holes, use the pin vice and the 2.5mm drill bit to carefully remove the material.
| Support Removal for Holes | Top Piece With Supports |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/57100380/119377605-4f30b400-bc8b-11eb-8d1d-5b68d1528a10.png) | ![image](https://user-images.githubusercontent.com/57100380/119667600-6f37b300-be04-11eb-8add-dfa75dc24d93.png) |

### Step 2: Inserting Heatcoils
Follow the previous procedure to insert the M3 4.5mm helicoils according to the following layout:

![image](https://user-images.githubusercontent.com/57100380/119378982-e21e1e00-bc8c-11eb-99c4-75f5de41c8dc.png)
![image](https://user-images.githubusercontent.com/57100380/119586768-50510680-bd9b-11eb-95ac-cf8a798702d0.png)

### Step 3: Tapping Electronics Mounts
Use the 1.5 mm drill bit with the M2 tap, and 2 mm drill bit with the M2.5 tap to thread holes in the appropriate locations:

![image](https://user-images.githubusercontent.com/57100380/119379155-1eea1500-bc8d-11eb-8bee-0a9705fd3b62.png)

### Threading Procedure
| Step Description | Visual |
| --- | --- |
| Clear out the hole with the appropriate drill bit (1.5 mm for the M2 tap, and 2 mm for the M2.5 tap) | ![image](https://user-images.githubusercontent.com/57100380/119382095-95881200-bc8f-11eb-8486-5943e062f071.png) |
| Use the appropriate tap and tap handle or pin vice to make the threads. Use caution not to bottom out the tap. | ![image](https://user-images.githubusercontent.com/57100380/119382301-d7b15380-bc8f-11eb-9620-e4bdffe32d60.png) |

**Caution**: Do not bottom out the tap as the peg may separate from the part and break off.

**Pro Tip**: If you do happen to break off a peg you can glue it back on with the 406 Loctite.

### Step 4: Assembly
Use the 2.5 mm hex wrench and M3x8 mm socket head bolts to assemble the base piece according to the following layout (use the 2.5 mm drill bit and pin vice to clear out holes clogged by supports): 

![image](https://user-images.githubusercontent.com/57100380/119383037-dc2a3c00-bc90-11eb-8f18-1579a5e8b42f.png)

| Bolt Insertion | Assembly with Bottom Piece | Assembly with Top Piece |
| --- | --- | --- |
| ![image](https://user-images.githubusercontent.com/57100380/119383202-0976ea00-bc91-11eb-9f09-3d71e02a8b94.png) | ![image](https://user-images.githubusercontent.com/57100380/119383263-1bf12380-bc91-11eb-997b-2676b2b3659d.png) | ![image](https://user-images.githubusercontent.com/57100380/119588093-103f5300-bd9e-11eb-9a20-73e80db2d5ba.png) |
## Leg Shell Post Processing
### Materials Masterlist
| Item | Quantity |
| --- | --- |
| Hip Module Shell Base | 4 |
| Hip Module Shell Cover | 4 |
| Upper Leg Module Shell Base | 4 |
| Upper Leg Module Shell Cover | 4 |
| 2.5mm Drill Bit | 1 |
| 3mm Drill Bit | 1 |
| M3 Tap | 1 |
| M2.5 Helicoil Insert Tool Set | 1 |
| Helicoil M2.5 x 3.8mm | 64 |
| M3 Helicoil Insert Tool Set | 1 |
| Helicoil M3 x 6mm | 8 |
| 8mm End Mill | 1 |
| 32mm End Mill | 1 |
| 32mm x 25mm x 4mm bearing | 16 |
| 8mm x 4mm x 2mm bearing | 24 |
| Vice | 1 |
| M2.5 x 6 mm Socket Head Cap Screw | 40 |
| M2.5 x 10 mm Socket Head Cap Screw | 24 |
| 2.5mm Hex Wrench | 1 |
| Needle Nose Pliers | 1 |
| File Set | 1 |
| Pin Vice | 1 |
| Tap Handle | 1 |

### Step 1: Prepare 3D Printed Parts
First use the needle nose pliers and file set to remove supports and check that the shell modules sit flat on a table:
| Hip Module Base | Hip Module Cover |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/57100380/119695653-6652db80-be1c-11eb-83b5-354d6e8afd62.png) | ![image](https://user-images.githubusercontent.com/57100380/119695712-74a0f780-be1c-11eb-8949-3b9a31057c04.png) |

**Pro Tip**: Some of the supports are difficult to remove and you may damage the parts or seperate the layers during this process. If so, use the 406 Loctite to repare damages areas or consider reprinting.

| Damaged Print |
| --- |
| ![image](https://user-images.githubusercontent.com/57100380/119696274-0577d300-be1d-11eb-9a30-839be015743b.png) |

### Step 2: Checking Hole Clearances
Use the 2.5mm and 3mm drill bits to clean out supposts from the holes in the following locations:

![image](https://user-images.githubusercontent.com/57100380/119696827-92229100-be1d-11eb-9bda-5bc142cf5cbf.png)

### Step 3: Cutting Threads
Use the M3 tap and tap handle or pin vice to cut threads in teh following locations:

![image](https://user-images.githubusercontent.com/57100380/119696938-b3837d00-be1d-11eb-8f76-5b174c3087f2.png)

## Step 4: Inserting Helicoils
Use the previous procedure and the M2.5 Helicoil Insert Tool Set to insert M2.5 x 3.8mm helicoils into the following locations: 

![image](https://user-images.githubusercontent.com/57100380/119697664-7075d980-be1e-11eb-8432-2c3e96ad4b3a.png)

## Step 5: Inserting the Hip Module Helicoils
**Note**: This step is only for the hip module base pieces which can be distinguished by the hole in the center of one end. There are 4 of these pieces.

Use the previous procedure and the M3 Helicoil Insert Tool Set to insert M3 x 6mm helicoils into the following locations:

![image](https://user-images.githubusercontent.com/57100380/119698136-f2660280-be1e-11eb-9543-b21e2c38808e.png)

| Hip vs. Upper Leg Base Pieces |
| --- |
| ![image](https://user-images.githubusercontent.com/57100380/119698266-132e5800-be1f-11eb-92b2-1b3ddb579150.png)
The top leg assembly shows the upper leg base piece with no hole on the left end. The bottom leg assembly shows the hip module base piece with a hole on the left end. |

### Step 6: Clearning Bearing Locations
Use the 8mm and 32mm end mills along with the pin vice or table-top vice to manually clear out extra material in the bearing locations.

**Caution**: Be careful not to take out any material not highlighted in yellow:

![image](https://user-images.githubusercontent.com/57100380/119699240-ef1f4680-be1f-11eb-8e7d-0387a1bae135.png)

**Pro tip**: I found it easiest to clear out all the holes by hand (this gave me the most control and limited mistakes). Also, for the 32mm holes I secured the end mill in the vice and rotated the part around the cutter by hand. This step takes some practice, so take it slow and be careful. You could potentially do this step in an actual mill or drill press, but putting the 3D print in a vice will likely damage it and the cutter will have a tendency to pull it up and out of the vice. Thus, I strongly suggest you do this by hand.

| 32mm End Mill Clearing | 8mm End Mill Clearing |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/57100380/119699940-ad42d000-be20-11eb-8a59-0746588a840d.png) | ![image](https://user-images.githubusercontent.com/57100380/119699972-b633a180-be20-11eb-95ec-e1b7aeb8f277.png) |

## Step 7: Seating the Bearings
Insert the 8x4x2mm and 32x24x4mm bearings into their appropriate loactions by pushing evenly along the edge with your fingers. Be carefull not to crack the print during this process. You can use the needle nose pliears to clean out any remaining material blocking the bearing from seating properly.

| Inserting a 8x4x2mm Bearing | Inserting a 32x24x4mm Bearing |
| --- | --- |
| ![image](https://user-images.githubusercontent.com/57100380/119700768-9ea8e880-be21-11eb-9260-c41d268247e8.png) | ![image](https://user-images.githubusercontent.com/57100380/119700799-a9637d80-be21-11eb-89ac-918517e736e2.png) |

### Step 8: Assembly
To check for fits attach the cover shells to the bases with the M2.5 x 6mm and M2.5 x 10 mm socket head screws.

**Note**: The hip and upper leg covers are identical and interchangeable.

| Bolt Locations |
| --- |
| ![image](https://user-images.githubusercontent.com/57100380/119701345-3b6b8600-be22-11eb-9ce0-f9b6d134d903.png) 
Note: At this stage you will **NOT** have the motors or pulleys attached as shown in the CAD |

## Output Pulley Preperation
### Materials Masterlist
| Item | Quantity |
| --- | --- |
| Transmission Pulley AT3 T30 Output | 8 |
| M3 Helicoil Insert Tool Set | 1 |
| Helicoil M3 x 6mm | 16 |
| 32mm x 25mm x 4mm Bearing | 1 |
| Needle Nose Pliers | 1 |
| File Set | 1 |
| Pin Vice | 1 |
| Hand Countersink Tool | 1 |

### Step 1: Prepare 3D print
Use the file set and pliers to remove supports.

| You can file down any bumps left from the supports on cirtical surfaces. |
| --- |
| ![image](https://user-images.githubusercontent.com/57100380/120029495-2cbcd480-bfc4-11eb-9e43-4cb9b5972709.png) |

The pulley bearing face is oversized and needs to be brought down to the size of the 32mm x 25mm x 4mm bearing internal diameter. This can be done on a lathe using a 25mm collet, but the following procedure is how we were able to bring it down to size without a lathe.

| Description | Image |
| Insert the Pulley onto the closed pliers to serve as the work-holding. Then work your way around the bearing sufrace with a file to evenly take off material. Flip over and follow the same procedure for teh other side | ![image](https://user-images.githubusercontent.com/57100380/120030905-09932480-bfc6-11eb-8efd-c3e574ac7583.png) |

### Step Inserting Helicoils
Keep the pulley oriented as follows:

![image](https://user-images.githubusercontent.com/57100380/120026797-9b982e80-bfc0-11eb-96a7-2869bba220b9.png)

| Description | Image |
| --- | --- |
| Use the contersink tool to cut a small countersink into the pulley holes | ![image](https://user-images.githubusercontent.com/57100380/120029540-3e05e100-bfc4-11eb-8d10-74d58a3e3f89.png) |
| The cutouts should not be very large. They are only to guide the drill bits | ![image](https://user-images.githubusercontent.com/57100380/120029637-5e35a000-bfc4-11eb-8be4-348fcb15230a.png) |
| 
