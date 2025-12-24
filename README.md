# IoT-Home-Automation-System
ESP32-based IoT Home Automation System using Blynk app

# OVERVIEW
This project implements a basic IoT-based home automation system to control from mobile application.

# PROBLEM STATEMENT
Traditional electrical switches requires manual control. This system enable remote ON/OFF control from your mobile phones. 

## System Architecture
- ESP32 microcontroller
- Relay module for load switching
- Blynk mobile application
- Wi-Fi communication

## Hardware Components
- ESP32 Development Board
- Relay Module
- Power Supply
- Electrical Load (simulated)

## Software Components
- Arduino framework (Embedded C/C++)
- Blynk IoT platform

## Working Principle
User commands from the Blynk app are sent to the ESP32 via Wi-Fi. The ESP32 controls the relay module to switch loads ON or OFF.

## Results
Reliable remote control of electrical loads with minimal latency.

## Limitations
No feedback for load status; basic security.

## Future Improvements
Add real-time status feedback, implement MQTT protocol, and enhance security.

## Project Status
Prototype / Academic project (hardware not currently available).
