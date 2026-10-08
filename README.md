# N-TECH-Mallu
smart blind stick that helps blinds from various hazards.I am developing this to help blinds.The Smart AI Blind Stick is a safety-focused assistive device designed to help visually impaired people navigate their surroundings more safely and independently. The project uses two Arduino Leonardo boards to process information from multiple sensors, including ultrasonic sensors for obstacle detection, flame sensors for detecting fire or high heat, and water sensors for detecting wet surfaces or water. A GPS module provides the user's location, while an SOS button can be used to trigger an emergency alert when assistance is needed. Buzzers and vibration motors provide immediate warnings to the user through sound and vibration. The system is powered by a rechargeable battery and is designed to be compact, lightweight, and suitable for mounting on a walking stick. The main goal of this project is to combine obstacle detection, environmental hazard alerts, location tracking, and emergency assistance into one affordable and practical smart blind stick.
<img width="1312" height="1199" alt="ChatGPT Image Oct 8, 2026, 09_28_36 PM" src="https://github.com/user-attachments/assets/a4051c99-556d-4dba-a9d4-69814e515b4d" />
<img width="962" height="582" alt="Screenshot 2026-10-08 203704" src="https://github.com/user-attachments/assets/9984509e-fb56-478b-b7c8-d9465b1b1910" />
<img width="597" height="335" alt="bstick" src="https://github.com/user-attachments/assets/5546b6c4-3481-40d9-bbc2-6277da5683eb" />
[smart_blind_stick_BOM.csv](https://github.com/user-attachments/files/33213310/smart_blind_stick_BOM.csv)
No.,Component,Quantity,Purpose
1,Arduino Leonardo,2,Main controllers
2,HC-SR04 Ultrasonic Sensor,2,Obstacle detection
3,Flame Sensor Module,2,Fire/flame detection
4,Water Sensor Module,2,Water detection
5,NEO-6M GPS Module,1,Location tracking for SOS
6,SIM800L GSM Module,1,SOS SMS/call communication
7,SOS Push Button,1,Emergency alert trigger
8,Active Buzzer,2,Audio alerts
9,Vibration Motor,2,Silent vibration alerts
10,2N2222 or BC547 NPN Transistor,2,Drive vibration motors
11,1N4007 Diode,2,Motor protection
12,220 ohm Resistor,4,LED current limiting
13,10k ohm Resistor,4,Pull-up/pull-down circuits
14,LED,4,Status indication
15,Breadboard,2,Prototyping
16,Jumper Wires,1,Electrical connections
17,USB Cable for Arduino Leonardo,2,Programming/power
18,Li-ion/LiPo Battery,1,Portable power
19,5V Buck Converter/Regulator,1,Stable regulated supply
20,On/Off Switch,1,Main power control
21,Project Enclosure,1,Protect electronics
22,Walking Stick/Cane,1,Physical body of the project
