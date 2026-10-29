---
title: Individal Block Diagram
tags:
- tag1
- tag2
---

## Overview
The main subsystem includes the following attributes in its block diagram:

* This subsystem will use 5V at 1.5A
* This subsystem doesn't have a local sensor, however it will utilize sensor data from the Motor Encoder subsystem and the Load/Heat Subsystem
* This subsystem doesn't have a local actuator, however it has 3 LEDs which will indicate the status of the subsystem
* This subsystem is connected through 2 pins to the Motor Driver and Motor Encoder subsystems
  * It is also connected to the Load/Heat subsystem via 4 pins
* This subsystem will be connected directly to a host computer for motion inputs
  * The power for the subsystem will be derived from the host computer's USB port
    
## Block Diagram 
The following image is the block diagram for this subsystem

![Indivial Block diagram](MAIN%20Subsystem.drawio%20(2).png)
