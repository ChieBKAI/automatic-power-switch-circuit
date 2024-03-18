# Automatic Power Switch with Adjustable Time using Infrared Sensor
This project aims to create a circuit that can automatically switch a power source on and off based on the presence or absence of an object detected by an infrared sensor. The circuit features an adjustable time delay, allowing users to set the desired duration before the power source is turned off after the object is no longer detected.

## Features
-  Automatic power switching using an infrared sensor
-  Adjustable time delay for turning off the power source
-  Visual indication of the countdown timer using 7-segment displays
-  Ability to enable or disable the 7-segment display as needed
-  Relay-based power switching for compatibility with various loads

## Components and Modules
The project utilizes various electronic components and modules, including:
- Infrared sensor module (IR transmitter and receiver)
- Voltage regulator (7805) for converting 12V to 5V
- NE555 timer IC for generating a 1Hz clock signal
- SN74LS190N counter IC for countdown timer implementation
- SN74LS47N BCD-to-7-segment decoder IC
- Logic gates (AND, OR, and inverters)
- Relay module for power switching
- DIP switches for time delay adjustment
- 7-segment displays for countdown timer visualization
- LEDs for status indication

## Circuit Design and Implementation
The circuit design follows a modular approach, with separate modules for the infrared sensor, voltage regulation, clock generation, countdown timer, and power switching. The modules are interconnected to achieve the desired functionality.

The infrared sensor module detects the presence or absence of an object, triggering the countdown timer. The time delay can be adjusted using the DIP switches, which set the initial value for the countdown timer based on binary weighting. As the countdown progresses, the 7-segment displays show the remaining time. When the timer reaches zero, the relay module opens, cutting off the power supply.

The circuit is designed using Altium Designer software, with the schematic capture, PCB layout, and 3D rendering included in the project files.
![](https://i.imgur.com/AF5vq47.png)
![](https://i.imgur.com/ClULvM9.png)
![](https://i.imgur.com/AOiqcRz.png)

## Usage
1. Connect the circuit to a 12V power supply.
2. Set the desired time delay using the DIP switches.
3. Enable or disable the 7-segment display as needed using the toggle switch.
4. Connect the load to the output terminals of the relay.
5. When an object is detected by the infrared sensor, the countdown timer will start, and the power will be turned on.
6. Once the object is no longer detected, the countdown timer will continue, and the power will be turned off when the timer reaches zero.
