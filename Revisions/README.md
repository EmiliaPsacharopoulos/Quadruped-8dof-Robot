# Revisions
[Return to the main Table of Contents](https://github.com/EmiliaPsacharopoulos/Formatting#table-of-contents)

The primary flaw of the Open Dynamic Robot Initiative (ODRI) 8 degree of freedom quadruped consists of designing for highly specialized parts. The nature of open source should allow for modifications to an overarching design, instead of needing to purchase exact parts with no replacements suggested. Our three months working on this project unraveled overarching problems both from the mechanical and electrical elements:
* We are facing 6-month long setbacks on our construction of the robot because the custom PCB master board contains a chip that is out of stock and needs to be manufactured. We may need to buy a board with the chip and solder it onto the master board ourselves to bypass this delay.
* The timing belts for the actuators are so specific in size that they ship with an estimated date of 14-21 weeks. ODRI is currently waiting on their custom power distribution board, with no documentation on their reasoning for making the power distribution board custom, to release a battery powered design of the robot.
* ODRI sells an encoder kit specifically designed to their actuators (with custom sized machined pulleys) for a highly marked up price and with an estimated shipping date of 10 weeks.
* Both mechanical/electrical components are extremely expensive for the low cost purpose ([ODRI 12dof 12,000$ kit](https://solo.pal-robotics.com/solo) compared to [Stanford Doggo's](https://github.com/Nate711/StanfordDoggoProject) $2,971 8dof model)

## Table of Contents 
1. [Wiring](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Revisions/README.md#wiring)
2. [Communications](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Revisions/README.md#communications)
3. [Power Supply Organization](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Revisions/README.md#power-supply-organization)
4. [Battery Supply Organization](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Revisions/README.md#battery-supply-organization)

## Communications
We should look into switching between an ethernet tethered connection and a receiver/transmitter (ie. if we wanted to go fully untethered with the battery power supply option)


## Battery Supply Organization
There are no specific mounting slots for the batteries or push buttons or the power management board(s) on the existing CAD. We'd look into making these additions.
