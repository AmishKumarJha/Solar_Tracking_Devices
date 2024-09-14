# Solar_Tracking_Devices
This project is a solar tracking system using four Light Dependent Resistors (LDRs) to detect sunlight intensity and relays to control the movement of a solar panel on both the X and Y axes. The system adjusts the solar panel's position every 15 minutes to maximize sunlight exposure.

Hardware Requirements
Arduino (or any microcontroller)
4 Light Dependent Resistors (LDRs)
4 Relays
Solar panel (or any adjustable platform)
Connecting wires
Resistors (appropriate value for LDRs)
Breadboard
Power supply

Software Requirements
Arduino IDE
Circuit Setup
LDRs: Connect the LDRs to analog pins A0, A1, A2, and A3 of the Arduino, with appropriate resistors in a voltage divider configuration.

A0: Top Left LDR
A1: Top Right LDR
A2: Bottom Left LDR
A3: Bottom Right LDR
Relays: Connect the control pins of the relays to digital pins:

9: X-axis clockwise relay
10: X-axis counterclockwise relay
11: Y-axis clockwise relay
12: Y-axis counterclockwise relay
Power: Ensure that the relay and LDR circuits are powered correctly from the power supply.
