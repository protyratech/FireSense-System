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

| Component | Description |
|-----------|-------------|
| Arduino Uno | Main microcontroller for system control |
| DHT Sensor | Measures temperature and humidity |
| Flame Sensor | Detects presence of fire/flame |
| Buzzer | Provides emergency alarm indication |
| LED (Optional) | Visual status indication |
| Breadboard & Jumper Wires | Circuit connections |
| Power Supply | Provides required power to the system |

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
│   └── FireSense_System.ino
│
├── Circuit
│   └── CKT.jpg
│
└── README.md
```


---

## 🔮 Future Improvements

- Add Wi-Fi connectivity using ESP32 for remote monitoring
- Send mobile notifications during fire detection
- Add OLED/LCD display for real-time sensor values
- Integrate IoT cloud platforms for data logging
- Add automatic fire suppression control

---

## 👨‍💻 Developed By

**Protyra Tech**

Embedded Systems | IoT | Electronics Projects

---

## 📜 License

This project is licensed under the **Apache License 2.0**.
