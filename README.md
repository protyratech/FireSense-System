# FireSense-System

## 🔥 Overview

**FireSense-System** is an Arduino Uno–based environmental monitoring and fire detection system designed to provide real-time temperature, humidity, and flame detection capabilities. The system continuously monitors environmental conditions using a DHT temperature and humidity sensor during normal operation.

When a flame or fire source is detected, the system automatically switches from monitoring mode to emergency mode and activates a buzzer alarm to provide an immediate warning. This project demonstrates a simple, low-cost, and reliable approach for early fire detection and safety applications.

---

## 🚀 Features

- 🌡️ Real-time temperature monitoring
- 💧 Humidity measurement using DHT sensor
- 🔥 Flame detection using flame sensor
- 🚨 Automatic fire alarm activation
- 🔊 Buzzer-based emergency alert system
- ⚡ Arduino Uno-based control system
- 📊 Continuous environmental monitoring
- 💡 Low-cost and easy-to-build safety solution

---

## 🛠️ Hardware Components

| Component | Quantity | Description |
|-----------|----------|-------------|
| Arduino UNO | 1 | Main microcontroller used for sensor data processing and system control |
| DHT11 Temperature & Humidity Sensor | 1 | Measures real-time temperature and humidity of the surrounding environment |
| Flame Sensor Module | 1 | Detects fire or flame using infrared light sensing technology |
| 16x2 LCD Display | 1 | Displays temperature, humidity, and system status messages |
| Piezo Buzzer | 1 | Generates an audible alarm during fire detection |
| 10KΩ Potentiometer | 1 | Used for adjusting LCD display contrast |
| Jumper Wires | As required | Used for electrical connections between components |
| Breadboard | 1 | Provides a platform for circuit prototyping |
| Power Supply | 1 | Provides required power to the Arduino-based system |

---

## ⚙️ Working Principle

The system operates in two modes:

### 1. Normal Monitoring Mode
- The DHT sensor continuously measures temperature and humidity.
- The Arduino processes sensor data and monitors environmental conditions.
- The system remains in standby mode while no flame is detected.

### 2. Fire Detection Mode
- When the flame sensor detects a fire source, the Arduino immediately identifies the danger condition.
- The buzzer is activated to generate an audible fire alarm.
- The system provides a quick response for emergency situations.

---

## 🔌 Applications

- Home fire safety systems
- Laboratory safety monitoring
- Industrial safety applications
- Small-scale automation projects
- Educational IoT and embedded system projects

---

## 📂 Project Structure

```text
FireSense-System
│
├── Code
│   └── FireSense_System_code.ino
│
├── Circuit
│   └── CKT.jpg
│
└── README.md
```


---

## 🔮 Future Improvements

- 🌐 Wi-Fi-based remote monitoring using **Arduino UNO R4 WiFi / ESP32**.
- 📱 Mobile alerts for fire detection
- ☁️ IoT cloud data logging
- 📊 Sensor data analysis and storage
- 🤖 Automatic fire suppression integration
- 📷 Intelligent camera-based fire verification

---

## 👨‍💻 Developed By

Developed by **Rajdip Dutta**  
at **Protyra Tech**

Embedded Systems | IoT | Electronics Projects

---

## 📜 License

Copyright © 2026 Protyra Tech. All rights reserved.
