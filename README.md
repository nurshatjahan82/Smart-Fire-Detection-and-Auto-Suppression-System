# Smart Fire Detection and Auto Suppression System

1. Project Overview

The **Smart Fire Detection and Auto Suppression System** is an Arduino-based safety system designed to detect fire and smoke and automatically activate a water suppression mechanism.

The system uses flame sensors and an MQ-2 smoke sensor to identify potential fire hazards. When fire or smoke is detected, the system activates a water pump through a relay-controlled mechanism, while a buzzer and LEDs provide immediate warnings. A GSM module is also included to send emergency alerts.

The main goal of this project is to reduce fire-related risks by providing an automated detection and response mechanism.

2. Objectives

- Detect fire using flame sensors.
- Identify smoke using an MQ-2 smoke sensor.
- Automatically activate a water pump when a fire condition is detected.
- Provide visual and audio warnings using LEDs and a buzzer.
- Send emergency notifications through a GSM module.
- Reduce the need for immediate human intervention during initial fire detection.

3. Components Used

| Component | Purpose |
|---|---|
| Arduino | Main controller of the system |
| Flame Sensors | Detect flames |
| MQ-2 Smoke Sensor | Detect smoke and combustible gases |
| Servo Motor | Controls the mechanical movement of the suppression mechanism |
| Relay Module | Controls the water pump |
| Water Pump | Provides water for fire suppression |
| Buzzer | Provides an audible warning |
| LEDs | Provide visual indications |
| GSM Module | Sends emergency alerts |

4. Working Principle

The system continuously monitors the surrounding environment using flame sensors and the MQ-2 smoke sensor.

The operation follows these general steps:

1. The sensors monitor the environment for fire and smoke.
2. The Arduino processes the sensor readings.
3. When a fire or smoke condition is detected, the system activates the warning mechanism.
4. The buzzer and LEDs provide alerts.
5. The relay controls the water pump to activate the suppression mechanism.
6. The GSM module is used to send an emergency notification.

This automated process is designed to provide an early response to potential fire hazards.

 5. Key Features

- Automatic fire detection.
- Smoke detection.
- Automatic water pump activation.
- Audio and visual warning system.
- GSM-based emergency notification.
- Arduino-based control system.

 6. Hardware and Software Requirements

**Hardware:**
- Arduino board
- Flame sensors
- MQ-2 smoke sensor
- Servo motor
- Relay module
- Water pump
- Buzzer
- LEDs
- GSM module
- Connecting wires and power supply

**Software:**
- Arduino IDE
- Arduino programming language (C/C++)

 7. Repository Structure

Smart-Fire-Detection-and-Auto-Suppression-System/
│
├── LICENSE
├── README.md
└── fire_detection_system.ino
```

 8. Installation and Setup

1. Download or clone this repository.
2. Open `fire_detection_system.ino` using the Arduino IDE.
3. Connect the required hardware components to the Arduino according to the circuit connections.
4. Select the correct Arduino board and COM port.
5. Upload the code to the Arduino board.
6. Power the system and test the sensor responses and alert mechanisms.

Note: Verify the power requirements and wiring of the pump, relay, and GSM module before operating the system.

 9. Future Improvements

- Integration of IoT-based remote monitoring.
- Real-time fire status monitoring through a mobile application.
- Improved fire detection accuracy to reduce false alarms.
- Battery backup for operation during power failures.
- Enhanced emergency notification features.

 10. Applications

- Homes and residential buildings.
- Offices and commercial spaces.
- Laboratories.
- Small industrial environments.
- Storage facilities.

 11. Safety Disclaimer

This project is developed for educational and demonstration purposes. It is not a certified fire protection system and should not replace professionally installed fire detection or suppression equipment.

12. License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

Project: Smart Fire Detection and Auto Suppression System  
Platform: Arduino  
Category: Embedded Systems / IoT / Fire Safety
