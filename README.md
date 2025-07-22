# Fingerprint-Based Door Lock System

This project is an IoT-enabled smart door lock system that uses fingerprint authentication for secure access. Built using ESP32, the AS608 fingerprint sensor, and Blynk for real-time monitoring and alerts.

## Objective

The goal of this project is to enhance physical security by replacing traditional locks with a biometric-based access system. The system allows only authorized fingerprints to unlock the door and sends alerts to the user via the Blynk app in case of unauthorized attempts.

## Technologies & Components Used

- ESP32 microcontroller
- AS608 fingerprint sensor
- Blynk IoT platform (for mobile monitoring)
- Arduino IDE (for programming)
- Jumper wires, breadboard, power supply

## Features

- Fingerprint-based authentication
- Real-time mobile alerts via Blynk
- Cloud-based access monitoring
- Easy setup and enrollment of new fingerprints
- Compact and portable design suitable for home security

## Getting Started

### Hardware Setup

1. Connect the AS608 fingerprint sensor to the ESP32 using UART pins.
2. Connect the relay module to control the door lock.
3. Power the ESP32 via USB or external power source.

### Software Setup

1. Install the required libraries in Arduino IDE:
   - Adafruit Fingerprint Sensor Library
   - Blynk Library
   - SoftwareSerial (if needed for testing)

2. Clone the project:

   ```bash
   git clone https://github.com/PrabeshTaksari/Fingerprint-Based-Door-Lock-System.git
## Project Structure
pgsql
Copy
Edit
Fingerprint-Based-Door-Lock-System/
├── Fingerprint_Door_Lock.ino
├── README.md
├── wiring_diagram.jpg
└── images/

## Future Improvements
Add support for mobile fingerprint enrollment

Integrate with a database to log entry/exit timestamps

Enable voice control or face recognition as secondary methods

Design a 3D-printed casing for better housing
