---
title: Schematic
---

## Overview

This schematic is design to function as the main processor for the robotic arm controller. The PIC18F57Q43 Curiosity Nano will be connected to a host computer via USB-c, and power will be supplied to the board via a barrel jack port on the PIC. The barrel jack's power is sent through a voltage regulator in order to be converted to 5VDC. The power produced by the voltage regulator is passed through a fuse in order to protect the board.

There are three LEDs on the board, which will be used to inform the user what the status of the board is. The three LEDs give the option of up to 8 different codes based on the pattern that the LEDs are lit. Each of the LEDs is fed power through signal ports RF1-RF3, and the signals pass through a 100 ohm resistor in order to protect the LEDs

Signals from the three other subsystems are sent to the 1x8 pin connectors in the diagram (although in the actual design we will be using 2x4 pin connectors), which are then passed directly to their respective ports as outlined in the box diagram. The ground pins for each of the 1x8 connectors are linked together, and are subsequently tied to a ground port on the Curiosity Nano.


![schematic](Main_Subsystem_Schematic%20conv%201.png)
**Figure 01:** Showing the schematic of the main subsystem.


## Resouces

The schematic as a PDF download is available [*here*](Main_Subsystem_Schematic.pdf), and the Zip folder of the project [*here*](dummyZip.zip).
