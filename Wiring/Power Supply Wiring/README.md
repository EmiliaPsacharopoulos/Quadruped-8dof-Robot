# Power Supply Wiring
[Return to the wiring Table of Contents](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring#table-of-contents)

**NOTE: remove the banana plugs from the BOM**

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


## Table of Contents
1. [External Power Supply Method](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Power%20Supply%20Wiring/README.md#external-power-supply-method)
2. [Battery Method](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Power%20Supply%20Wiring/README.md#battery-method)


## External Power Supply Method
This step explains the connection from two external power supplies to each of the two MicroDriver stacks. The supply source is routed through an E-Stop switch. The following table lists the necessary tools, parts, and materials to complete this step. 
| Item | Quantity | 
| --- | --- |
| XT30 Female Connector to 4mm Banana Plug Cable | 2 cables |
| Braided Cable Sleeve | ~10 m |
| E-Stop Switch | 1 |
| Extra E-Stop Switch Mechanism | 1 |
| Cable Gland | 2 | 
| 18 AWG Black Wire | ~40 m |
| 18 AWG Red Wire | ~40 m |
| XT30 Male Connectors | 6 |
| 3-Channel Wire Splice Connectors | 4 | 
| Small Zipties | ~20 |
| 1.5mm Heat Shrink | ~6 cm |

### Preparing the Main Power Wires
| Step Description | Visual | 
| --- | --- |
| Cut two 8 inch sections of the red 18 AWG wire. Strip about 1cm on every end, twisting the exposed wire after each strip.  | --- |
| Cut one 20 inch section of the black 18 AWG wire. Strip about 1cm on every end, twisting the exposed wire after each strip. | --- |
| Solder a red and the black wire to an XT30 male connector, using the 1.5mm heat shrink after each solder. Pay attention to the positive and negative indications. | --- |
| Connect an XT30 male connector to the XT30 female connector in the XT30 female to 4mm banana cable connection | --- |

### Routing the Main Power Wires through the E-Stop Switch
| Step Description | Visual | 
| --- | --- |
| This step assumes that you have prepared the E-Stop Switch from the Machining tab. | ![image](https://user-images.githubusercontent.com/84528674/119998397-a93cbc80-bf9e-11eb-9e2d-5264b6bb1b21.png) |
| Thread the black 20 inch wire through the E-Stop glands (it will not connect to anything inside). | --- |
| Position the red 8 inch wire that is  | --- |

### Preparing the Sub Power Wires
| Step Description | Visual | 
| --- | --- |
| Choose your desired length from the E-Stop switch to the robot. Account extra length for wire management on the robot. Cut 4 sections of this length from the 18 AWG red wire and 4 sections of this length from the 18 AWG black wire. We chose to cut **XYZ** inches, four times from each colored wire. | --- |
| Strip 0.5cm of wire casing from the other end of each of the 8 individual wires, and twist the exposed wire after each strip. | --- |


### Connecting the Sub and Main Power Wires
| Step Description | Visual | 
| --- | --- |
| Route each red main power wire through the single entry side of the 2 channel wire splice connector. Route any two red subwires through the two channel side of the splice connector. | --- |
| Repeat the above step for the black wires | --- |
| Use a ziptie on each splice connector to ensure the bridge stays shut. | --- |

### Finishing the Sub Power Wires
| Step Description | Visual | 
| --- | --- |
| Cut thin strips of 2.4mm heat shrink. Straighten out the four pairs of subwire from the spliced connection (2 red pairs, 2 black pairs), and use the heat shrink on each pair individually to straighten the connection. Leave at least 5cm of wire from the ends unbounded. | |
| Strip off 0.5cm to 1cm of wire casing from the empty end of each of the 8 wires. Twist the exposed wire after each strip. | --- |
| Follow this [YouTube Video](https://www.youtube.com/watch?v=_NyJbKqRtUE) for detailed instructions on soldering the XT30 male connectors to the exposed wire. Note: this video uses female connectors, but the soldering process is exactly the same for the male connectors. | --- |
| At this stage, there should be four completed sub power wires branching from the wire splice connection:  | --- |

### Overall organization
| Step Description | Visual | 
| --- | --- |
| Encapsulate the fully assembled wires with the braided cable sleeve. You will have to cut the cable accordingly to the lengths used in previous steps. Use zipties to secure the attachment on each end of the cable. Zipties are prefered over heat shrink for this attachment incase a wire needs to be replaced inside. | --- |



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
