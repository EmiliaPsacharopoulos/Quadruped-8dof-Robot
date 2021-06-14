# Power Supply Wiring
[Return to the wiring Table of Contents](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring#table-of-contents)

The robot can be powered by one of two methods: 
- External power supply
- Batteries on the robot

Below, we describe the implementation of both methods. In either case, each of the four MicroDrivers receives a supplying power cable that will connect to the MicroDriver power supply cables prepared in the MicroDriver wiring tab. 
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
| Screwdriver | 1 |

## Table of Contents
1. [External Power Supply Method](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Power%20Supply%20Wiring/README.md#external-power-supply-method)
2. [Battery Method](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Power%20Supply%20Wiring/README.md#battery-method)


## External Power Supply Method
This step explains the connection from two external power supplies to the front MicroDriver stack, and the back MicroDriver stack with the Master Board. The supply source is routed through an E-Stop switch. The following table lists the necessary tools, parts, and materials to complete this step. 

| Item | Quantity | 
| --- | --- |
| XT30 Female Connector to 4mm Banana Plug Cable | 2 cables |
| Braided Cable Sleeve | ~5 m |
| E-Stop Switch (modified) | 1 |
| 18 AWG Black Wire | ~40 m |
| 18 AWG Red Wire | ~40 m |
| XT30 Male Connectors | 6 |
| 3-Channel Wire Splice Connector | 2 | 
| 4-Channel Wire Splice Connector | 2 | 
| Socket 2Pos 1.25mm | 1 | 
| Small Zipties | ~20 |
| 1.5mm Heat Shrink | ~6 cm |

We will list the steps for completing both the front and the back stack with the Master Board. 

### Preparing the Main Power Wires (Repeat Twice)
| Step Description | Visual | 
| --- | --- |
| Cut two 8 inch sections of the red 18 AWG wire. Strip about 1cm on every end, twisting the exposed wire after each strip.  | ![image](https://user-images.githubusercontent.com/84528674/119999298-9676b780-bf9f-11eb-84d9-6db2791f4168.png) |
| Cut one 20 inch section of the black 18 AWG wire. Strip about 1cm on every end, twisting the exposed wire after each strip. | ![image](https://user-images.githubusercontent.com/84528674/120000073-6c71c500-bfa0-11eb-8a26-a3f6dd7e0c08.png) |
| Solder a red and the black wire to an XT30 male connector, using the 1.5mm heat shrink after each solder. Pay attention to the positive and negative indications. |  ![image](https://user-images.githubusercontent.com/84528674/119999166-6fb88100-bf9f-11eb-95ce-5c38bfd25464.png) |
| Connect the male XT30 end of this cable to an XT30 female (to 4mm banana) cable  | ![image](https://user-images.githubusercontent.com/84528674/119999478-caea7380-bf9f-11eb-952e-5b1c5cbb6510.png) |

The 4mm banana ends will plug into the power supply. Now, we need to route these wires through the E-Stop. 

### Routing the Main Power Wires through the E-Stop Switch (Repeat Twice)
| Step Description | Visual | 
| --- | --- |
| This step assumes that you have prepared the E-Stop Switch from the Machining tab. | ![image](https://user-images.githubusercontent.com/84528674/119998397-a93cbc80-bf9e-11eb-9e2d-5264b6bb1b21.png) |
| Thread the black 20 inch wire through the E-Stop glands (it will not connect to anything inside). | ![image](https://user-images.githubusercontent.com/84528674/120001776-21f14800-bfa2-11eb-8a50-aea53c0fc22f.png) |
| Use a screwdriver to open the **NC** side of the switch. Carefully push the **red** exposed wire from the **power side** of the cable that we just created through the cable gland then into the **NC** side of the switch. Close the switch afterward such that the wire does not budge if tugged. | ![image](https://user-images.githubusercontent.com/84528674/120002993-51548480-bfa3-11eb-826a-42cef21c54f0.png) |
| Use a screwdriver to open the other side of the switch. Carefully push the other red exposed wire that we made in previous steps through the other cable gland and into the switch. Close the switch afterward such that the wire does not budge if tugged. Snap the switch in place on one of the far end connectors (leaving the middle open). | ![image](https://user-images.githubusercontent.com/84528674/120003856-20288400-bfa4-11eb-9359-319f4c13ae5e.png) |


### Preparing the Sub Power Wires
| Step Description | Visual | 
| --- | --- |
| Cut 2 sections of about 11ft from the 18 AWG red wire and 2 sections of about 11ft from the 18 AWG black wire. Strip 11mm of wire casing one end of each of the 4 individual wires, and twist the exposed wire after each strip. | ![image](https://user-images.githubusercontent.com/84528674/120004952-5e727300-bfa5-11eb-99e6-97ba075e7714.png) |
| Use two 3-Channel Wago wire splicers, one per red/black colored power wire to separate the supply wire into two sections of sub power wire. The wago connectors require force to lift each bridge up. Make sure to follow the proper spliced length listed on the side (ours was 11mm). | ![image](https://user-images.githubusercontent.com/84528674/120005674-1142d100-bfa6-11eb-9217-8ec98f5ed7f7.png) |
| Repeat the above steps for the back stack, but cut 3 sections of 11ft from both colors to account for the Master Board power cable and use 4-way splicer connections instead. Note: we used a 5-way splicer because we did not have a 4-way splicer, but it still works the same. | ![image](https://user-images.githubusercontent.com/84528674/120821434-75741080-c523-11eb-9274-afe65af2ff90.png) ![image](https://user-images.githubusercontent.com/84528674/120822252-38f4e480-c524-11eb-928b-b947e1b5c2ef.png) |



### Finishing the Sub Power Wires 
| Step Description | Visual | 
| --- | --- |
| Strip off 0.5cm to 1cm of wire casing from the empty end of each of the 4 sub power wires. Twist the exposed wire after each strip. Slide one piece of heat shrink from the XT30 connector pack about 5-10 inches away from the exposed end on each of the 4 wires. You will need this to bind the solder. | ![image](https://user-images.githubusercontent.com/84528674/120006748-32f08800-bfa7-11eb-93d8-7890b05fecbd.png) |
| Follow this [YouTube Video](https://www.youtube.com/watch?v=_NyJbKqRtUE) for detailed instructions on soldering the two XT30 male connectors to the four exposed wires. Note: this video uses female connectors, but the soldering process is exactly the same for the male connectors. | ![image](https://user-images.githubusercontent.com/84528674/120007244-b14d2a00-bfa7-11eb-9b65-d217d60b5c91.png) |
| Repeat the above steps for two of the back stack's black/red cables (4 red/black power cables should look the same) | ![image](https://user-images.githubusercontent.com/84528674/120823586-9178b180-c525-11eb-94e4-57cbd2c6d6ae.png) |
| For the remaining red/black power cable to the Master Board, we will connect a 2-position 1.25mm Hirose socket connection by crimping. First, strip 1mm of the wire casing from the red and the black wire.  | --- |
| Align the wire and crimp terminal as straight as possible into the crimping tool. The exposed wire should be touching the end stop. | --- |
| Close the handle as far as possible. The crimps for the red and black wires should look like this: | --- |
| Use tweezers to insert the crimps into the 2-position socket (1.25mm) connector. | --- |


### Overall organization
| Step Description | Visual | 
| --- | --- |
| We seperately ziptied the front and back power supply cables. | --- |
| Afterwards, we threaded both the front and back power supply cables along with the ethernet cable through the braided cable sleeve. | --- |

### Troubleshooting
Before you connect the power wires to the battery, make sure that the circuit works. Apply 10V using a power supply, and make sure each connection reads the 10V at the robot end of the wire using a digital multimeter. Then, test that the stop switch breaks the circuit and reads 0V at the robot end.


## Battery Method
This step explains the connection from two batteries, mounted on the robot, to each of the two MicroDriver stacks. The supply source is routed through push button switches. The following table lists the necessary tools, parts, and materials to complete this step. 
| Item | Quantity | 
| --- | --- |
| --- | --- |
| --- | --- |
| --- | --- |
| --- | --- |
| --- | --- |

[Asked about on the forum.](https://odri.discourse.group/t/battery-and-push-button-wiring/281). Note: we will wait to complete this section until they complete their custom power board.
