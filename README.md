# Vaahan 🚗💡

## Overview
Vaahan is an **IoT-based Arduino Smart Car** integrated with a **Mobile API** for control and monitoring.  
This project demonstrates how IoT and embedded systems can be combined with mobile applications to create an intelligent vehicle system.

## Features
- 🚘 Remote control of the car using a mobile app (APK included)
- 📡 IoT integration via Arduino
- 🛠️ Prototype built with Arduino Uno and motor driver
- 📱 Android mobile application for car control

## Tech Stack
- Arduino (C/C++ with `.ino` code)
- IoT Modules (WiFi/Bluetooth)
- Android (Java, APK provided)
- Mobile API integration

## Repository Structure
```
/arduino-code/Prototype_code.ino   # Arduino source code
/mobile-app/app-debug.apk          # Android app (ready to install)
/docs/                             # Documentation & media (add here)
README.md                          # Project documentation
```

## Installation & Usage

### Arduino Setup
1. Open `Prototype_code.ino` in the Arduino IDE.
2. Connect your Arduino board and upload the sketch.
3. Ensure motor driver and IoT module are connected properly.

### Mobile App Setup
1. Install `app-debug.apk` on your Android device.
2. Connect your phone to the same IoT network as Arduino (if using WiFi).
3. Control the car directly from the app.

## Demo
(Add images/videos of the prototype in `/docs` or link here)

## Future Improvements
- Add obstacle detection using ultrasonic sensors
- Enable live camera feed for remote monitoring
- Cloud data logging for movement analytics

## License
This project is licensed under the MIT License. Feel free to use, modify, and share!

---
Made with ❤️ for IoT & Smart Mobility
