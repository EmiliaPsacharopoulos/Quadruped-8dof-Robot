# Revisions
[Return to the main Table of Contents](https://github.com/EmiliaPsacharopoulos/Formatting#table-of-contents)

The primary flaw of the Open Dynamic Robot Initiative (ODRI) 8 degree of freedom quadruped consists of designing for highly specialized parts. The nature of open source should allow for modifications to an overarching design, instead of needing to purchase exact parts with no replacements suggested. Our three months working on this project unraveled overarching problems both from the mechanical and electrical elements:
* We are facing 6-month long setbacks on our construction of the robot because the custom PCB master board contains a chip that is out of stock and needs to be manufactured. We may need to buy a board with the chip and solder it onto the master board ourselves to bypass this delay.
* The timing belts for the actuators are so specific in size that they ship with an estimated date of 14-21 weeks. ODRI is currently waiting on their custom power distribution board, with no documentation on their reasoning for making the power distribution board custom, to release a battery powered design of the robot.
* ODRI sells an encoder kit specifically designed to their actuators (with custom sized machined pulleys) for a highly marked up price and with an estimated shipping date of 10 weeks.
* Both mechanical/electrical components are extremely expensive for the low cost purpose ([ODRI 12dof 12,000$ kit](https://solo.pal-robotics.com/solo) compared to [Stanford Doggo's](https://github.com/Nate711/StanfordDoggoProject) $2,971 8dof model)

## Table of Contents 
1. [Mechanical Revisions](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Revisions/README.md#mechanical-revisions)
2. [Electrical Revisions](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Revisions/README.md#electrical-revisions)
3. [Cost Analysis](https://github.com/EmiliaPsacharopoulos/Quadruped-8dof-Robot/blob/main/Revisions/README.md#cost-analysis)


## Mechanical Revisions
To reduce the cost of mechanical components and increase manufacturability, we redesigned the actuator module. The primary goals of the redesign were to use the same brushless motors from the original design, retain the same structural integrity, and implement a belt pulley transmission system with a 9:1 speed reduction (identical to the original design). Thus, this design can be implemented with the same control system as the original 8dof quadruped. The following table details the cost motivated design revisions and their associated impacts (assuming eight actuator components are built for the 8dof quadruped).

Table 2. Cost Motivated Design Revisions and Relative Impact
| Old Component/Design | Revised Component/Design | Associated Monetary Benefit (USD) |
| --- | --- | --- |
| AT3 GEN III Timing Belts (five week lead time, and difficult to source in the U.S.) | MXL Series Timing Belt (available from McMaster-Carr) | 51.60 |
| ODRI Encoder Kit and machined pulleys. (6 week lead time) | Purchase encoder and codewheel separately. Removed machined pulleys and replaced with 3D printed components. | 520.00 |
| 7 bearings | 5 bearings | 200.16 |
| Helicoil inserts (includes specific tooling) | Heat inserts (only need a soldering iron and are less prone to failure) | 125.09 |
| Machining/ finishing, and motor reconfiguration (end mills and reamer) | Print components on with SLA and eliminate post processing steps/toolings and motor reconfiguration. | 194.15 |
| Fasteners | Reduced count and relative cost. | 19.32 |
|   | Total | 1,110.32 |


## Electrical Revisions


## Cost Analysis
