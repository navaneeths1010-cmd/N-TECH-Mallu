# N-TECH-Mallu
smart blind stick that helps blinds from various hazards.I am developing this to help blinds.The Smart AI Blind Stick is a safety-focused assistive device designed to help visually impaired people navigate their surroundings more safely and independently. The project uses two Arduino Leonardo boards to process information from multiple sensors, including ultrasonic sensors for obstacle detection, flame sensors for detecting fire or high heat, and water sensors for detecting wet surfaces or water. A GPS module provides the user's location, while an SOS button can be used to trigger an emergency alert when assistance is needed. Buzzers and vibration motors provide immediate warnings to the user through sound and vibration. The system is powered by a rechargeable battery and is designed to be compact, lightweight, and suitable for mounting on a walking stick. The main goal of this project is to combine obstacle detection, environmental hazard alerts, location tracking, and emergency assistance into one affordable and practical smart blind stick.## Smart AI Blind Stick

The Smart AI Blind Stick is an assistive technology project designed to improve the safety, mobility, and independence of visually impaired people. The main purpose of this project is to create an affordable and practical smart walking stick that can detect different types of hazards in the user's surroundings and provide immediate warnings through sound and vibration. Instead of relying only on a traditional walking stick, this system combines multiple sensors, microcontrollers, GPS, emergency communication, and alert mechanisms into a single portable device.

The project uses two Arduino Leonardo boards to manage the different sensors and functions of the system. The first Arduino is mainly responsible for environmental and obstacle detection, while the second Arduino handles safety and communication features. Using two microcontrollers allows the system to divide the workload between different functions and makes it easier to expand the project with additional sensors and features in the future.

For obstacle detection, HC-SR04 ultrasonic sensors are used to detect objects in front of the user. The sensors measure the distance between the stick and nearby objects and allow the Arduino to determine when an obstacle is too close. When an obstacle is detected, the system can warn the user using a buzzer and/or vibration motor. This can help the user identify obstacles that may not be detected easily with a traditional walking stick.

The Smart Blind Stick also includes flame sensors for detecting fire or flames and water sensors for detecting water or wet surfaces. These sensors provide additional environmental awareness and can warn the user when potentially dangerous conditions are detected. The alerts can be provided through different sound or vibration patterns so that the user can distinguish between an obstacle, water, or fire warning.

A GPS module is included to provide location information during an emergency. When the user presses the SOS button, the system can obtain the current GPS coordinates and use a GSM communication module such as the SIM800L to send an emergency SMS or make a call. This feature can help communicate the user's approximate location to a predefined emergency contact. The GPS module itself provides location data, while the GSM module is responsible for communicating that information over the cellular network.

The project uses both audio and vibration feedback to make the device more useful. Buzzers can provide audible warnings, while vibration motors can provide tactile feedback directly to the user. Using vibration is especially useful when the user may not be able to clearly hear the buzzer because of environmental noise. Different alert patterns can be programmed for different hazards, making it easier for the user to understand what type of warning has been detected.

The entire system is designed to operate from a rechargeable battery and can be placed inside a protective enclosure mounted on the walking stick. A voltage regulator or buck converter is used to provide an appropriate and stable supply voltage to the electronics. Proper power management is important because modules such as the GSM module can require relatively high current during communication. The electronics can be arranged so that the sensors are positioned where they can effectively detect hazards while the main electronics remain protected inside the enclosure.

The project is designed with affordability and expandability in mind. Since the system is based on commonly available Arduino boards and sensor modules, it can be assembled and modified by students, makers, and electronics enthusiasts. Future versions could include additional distance sensors, better environmental sensing, voice feedback, rechargeable battery monitoring, mobile-phone connectivity, improved waterproofing, and more advanced navigation or artificial-intelligence features.

The overall goal of the Smart AI Blind Stick is to demonstrate how embedded electronics and sensors can be combined to create a useful assistive device. By integrating obstacle detection, fire detection, water detection, GPS location tracking, SOS communication, buzzer alerts, and vibration feedback, the project aims to provide an additional layer of safety and environmental awareness for visually impaired users while remaining affordable and customizable.

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
[smart_blind_stick_BOM.csv](https://github.com/user-attachments/files/33213486/smart_blind_stick_BOM.csv)No.,Component,Quantity,Purpose
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


19,5V Buck Converter/Regulator,1,Stable regulated supply
20,On/Off Switch,1,Main power control
21,Project Enclosure,1,Protect electronics
22,Walking Stick/Cane,1,Physical body of the project
