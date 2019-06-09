# Trillium V0.4 Hardware
Trillium is the on-board computer for UBC Orbit's CubeSat, Aspectu, that is being developed as part of the 5th Canadian Satellite Design Challenge. This repository contains the PCB prototype design for the fourth revision of Trillium. The design is centered around three STM32H743 microcontrollers, that continuously compare data throughout program execution to ensure that all three processing nodes are operating correctly. The board also contains eFuses to individually manage the power distribution to the three MCUs, a 4Mb MRAM chip providing non-volatile memory to the system, and various other miscellaneous components.

![TrilliumV4](https://github.com/andradazoltan/trillium_v0.4_hardware/blob/master/TrilliumV4/TrilliumV4.PNG)
