# Smart IoT Door Lock System using ESP32-CAM

## Project Overview

The Smart IoT Door Lock System is an IoT-based home security project developed using the ESP32-CAM module and Telegram platform for remote monitoring and access control.

When a visitor presses the doorbell switch, the ESP32-CAM captures the visitor image and sends it to the owner's Telegram application through WiFi. The owner can remotely verify the visitor and control the electronic door lock from anywhere.

This project enhances security by combining IoT communication, image capture, and remote authentication in a single smart access system.

---
## Features

- WiFi-based smart door lock system
- Visitor image capture using ESP32-CAM
- Real-time Telegram notifications
- Remote lock and unlock control
- Electronic door lock integration
- IoT-based remote monitoring
- Smart visitor verification system

---
## Components Used

| Component | Description |
|---|---|
| ESP32-CAM Board | Main microcontroller with camera module |
| 12V Electronic Lock | Door locking mechanism |
| TIP122 NPN Transistor | Drives the electronic lock |
| 7805 Voltage Regulator | Provides regulated 5V supply |
| 1k & 10k Resistors | Circuit biasing and protection |
| 1N4007 Diode | Reverse current protection |
| Push Switch | Doorbell trigger switch |
| 12V DC Supply | Power source for the system |

---
## Software Used

- Arduino IDE
- Embedded C Programming
- Telegram Bot API
- ESP32 Board Package
- WiFi Communication Protocol

---
## Working Principle

1. The visitor presses the doorbell push switch.
2. The ESP32-CAM activates and captures the visitor image.
3. The captured image is transmitted through WiFi.
4. The image is sent to the owner's Telegram application.
5. The owner verifies the visitor remotely.
6. The owner sends a lock/unlock command through Telegram.
7. The ESP32-CAM controls the electronic lock accordingly.

---
## System Flow

Visitor → Push Button → ESP32-CAM → Image Capture → WiFi → Telegram → User Decision → Lock/Unlock Signal → Electronic Lock

---
## Applications

- Smart home security systems
- Office access control
- Hostel and apartment security
- Remote visitor monitoring
- IoT-based surveillance systems

---
## Future Improvements

- Face recognition-based authentication
- Mobile application integration
- Cloud database storage
- AI-based intruder detection
- Voice assistant support
- OTP-based visitor verification

---
## Key Learning Outcomes

- Hands-on experience with ESP32-CAM
- Understanding of IoT communication using WiFi
- Integration of hardware and software systems
- Working with APIs (Telegram Bot API)
- Real-time system design and debugging
- Embedded system programming

---
