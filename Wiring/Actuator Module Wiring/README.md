# Actuator Module Wiring
[Return to the wiring Table of Contents](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring#table-of-contents)

We provide instructions for all soldered components on the motors, and the assembly of the connection from a motor to a MicroDriver. Note that the encoder wiring is addressed in the MicroDriver wiring section. This section assumes that the motors have already been modified. You will need all of the following tools and materials to properly complete the instructions below:

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
1. [Motor Phase Wires](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Actuator%20Module%20Wiring/README.md#motor-phase-wires)

## Motor Phase Wires
This step focuses on making the connection between the MicroDriver phase wires and the motor. https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware/blob/master/mechanics/actuator_module_v1/details/details_motor_preparation.md#details-motor-preparation

| Item | Quantity | 
| --- | --- |
| 1.5mm Heat Shrink | ~20cm |
| Brushless Motors | 8 |
| 26 AWG Multi-Colored Wire | **Dependent on robot component positioning** |

The following will be repeated 8 times, once per stator:


First, we will prepare the stator wiring.
| Step Description | Visual | 
| --- | --- |
| Use wire cutters to carefully remove the heat shrink from the phase wires. (Lots of pictures!!!) | --- |
| Trim the phase wires to be 3cm from the base of the stator. | --- |
| Use a soldering iron set at 400 degrees Celsius with a little bit of solder on the tip of the iron to expose about 5mm of silver wire on each wire. | --- |
| Use the 1.5mm heat shrink to cover up the exposed wire, leaving only a little amount of the gold wire casing showing.  | --- |

Then, we will prepare the extension wires. The length of these wires is dependent on the positioning of the motors on the robot and the distance to the MicroDriver stator wires. 

| Step Description | Visual | 
| --- | --- |
| Choose a color scheme for the given stator-Motor Driver connection. We decided to make each MicroDriver's phase connection a distinct color for easier wire management. | --- |
| Measure the required cable length from the stator placement to the MicroDriver placement on your robot. Add about 6 inches to that length. For example, we measured **XYZ** inches and therefore **XYZ + 6** inches was our final length. | --- |
| Cut three lengths of this measurement in the designated color from the 26 AWG wire. Strip about 0.5cm to 1cm of wire casing on one end of each of the three wires, twisting the exposed wire after each strip. | --- |
| --- | --- |
