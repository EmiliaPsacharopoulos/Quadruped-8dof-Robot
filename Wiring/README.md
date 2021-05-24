# Wiring
[Return to the main Table of Contents](https://github.com/EmiliaPsacharopoulos/Formatting#table-of-contents)

## Table of Contents 
1. [Wiring Schematics](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Wiring/Wiring%20Schematics/README.md#wiring-schematics)
2. [Master Board Wiring](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring/Master%20Board%20Wiring#master-board-wiring)
3. [MicroDriver Board Wiring](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring/MicroDriver%20Board%20Wiring#microdriver-board-wiring)
4. [Actuator Module Wiring](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring/Actuator%20Module%20Wiring#actuator-module-wiring)
5. [Power Supply Wiring](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring/Power%20Supply%20Wiring#power-supply-wiring)
6. [JTAG Emulator Wiring](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/tree/main/Wiring/JTAG%20Emulator%20Wiring#jtag-emulator-wiring)

## Wiring Description
The main electrical components of this 8 degree of freedom quadruped robot include:
- 8 brushless motors and encoders
- 4 MicroDriver Boards
- 1 Master Board
- 1 Inertial Measurement Unit (IMU)


The [Official GitHub page's](https://github.com/open-dynamic-robot-initiative/open_robot_actuator_hardware#electronics) electronic setup has two options for the robot's motor driver boards: Texas Instrument Evaluation Boards or Beta Layout MicroDriver Boards. We chose the MicroDrivers because these boards are smaller and newer. 

Additionally, other models of this robot used foot sensors and vicon markers, but in the first iteration of this design, we are not implementing these components. This may be an add-on feature in future iterations.

Lastly, we used and documented two distinct methods of powering this robot: 24V from an external power supply and 11.1V batteries mounted onto the robot. 
