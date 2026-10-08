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
# Smart AI Blind Stick

## 📖 About the Project

The Smart AI Blind Stick is an assistive technology project designed to improve the safety, mobility, and independence of visually impaired people. The main purpose of this project is to create an affordable and practical smart walking stick that can detect different types of hazards in the user's surroundings and provide immediate warnings through sound and vibration.

The project uses two Arduino Leonardo boards to manage the different sensors and functions of the system. One Arduino handles environmental and obstacle detection, while the second Arduino handles safety and communication features.

The system uses HC-SR04 ultrasonic sensors to detect obstacles in front of the user. When an obstacle is detected within a specified distance, the Arduino activates an alert using a buzzer and vibration motor.

Flame sensors are included to detect fire or flames, while water sensors detect water or wet surfaces. These features provide additional environmental awareness and allow the user to receive warnings about potentially dangerous conditions.

A GPS module is used to obtain the user's location during an emergency. When the SOS button is pressed, the system can obtain GPS coordinates and use a GSM module to send an emergency message or make a call to a predefined contact.

The project also uses vibration motors and buzzers to provide different types of feedback. Vibration feedback can be particularly useful in noisy environments where an audible buzzer may be difficult to hear.

The electronics are powered by a rechargeable battery and are designed to be mounted on a walking stick inside a protective enclosure. A voltage regulator is used to provide a stable supply to the electronic components.

The main goal of this project is to demonstrate how Arduino, sensors, GPS, communication modules, and alert systems can be combined to create an affordable and customizable assistive device.

## ✨ Features

- 🚧 Obstacle detection
- 🔥 Flame/fire detection
- 💧 Water detection
- 📍 GPS location tracking
- 🆘 SOS emergency button
- 📱 Emergency SMS/call using GSM
- 🔊 Buzzer alerts
- 📳 Vibration alerts
- 🔋 Rechargeable battery powered
- 🧠 Dual Arduino Leonardo system

## 🧰 Hardware

See the complete Bill of Materials below.

## 📦 Bill of Materials

| Component | Quantity |
|---|---:|
| Arduino Leonardo | 2 |
| HC-SR04 Ultrasonic Sensor | 2 |
| Flame Sensor | 2 |
| Water Sensor | 2 |
| NEO-6M GPS | 1 |
| SIM800L GSM | 1 |
| SOS Button | 1 |
| Active Buzzer | 2 |
| Vibration Motor | 2 |
| 2N2222 / BC547 | 2 |
| 1N4007 Diode | 2 |
| 220Ω Resistor | 4 |
| 10kΩ Resistor | 4 |
| LED | 4 |
| Li-ion/LiPo Battery | 1 |
| 5V Buck Converter | 1 |
| On/Off Switch | 1 |

## 🔌 System Overview

The sensors continuously monitor the surrounding environment. The Arduino processes the sensor readings and activates the appropriate warning when a hazard is detected.

The SOS system uses the emergency button, GPS module, and GSM module to provide the user's location to an emergency contact.

## 🚀 Future Improvements

- Voice-based alerts
- Mobile application
- Better waterproofing
- Battery-level monitoring
- More advanced obstacle detection
- AI-based object recognition
- Improved GPS navigation
- Rechargeable integrated battery system

## 👨‍💻 Project Status

This project is currently under development. Hardware, software, sensor placement, and alert systems are being tested and improved.

## 📄 License

This project is open-source and can be modified and improved for educational and assistive-technology purposes.


![image alt](https://github.com/navaneeths1010-cmd/N-TECH-Mallu/blob/6e7fcd7b9b8d018844d038e2c69dcb27bd3e898f/ChatGPT%20Image%20Oct%208%2C%202026%2C%2009_28_36%20PM.png)
