# 🩺 IoT-Based Health Monitoring System

A smart and portable IoT health monitoring system developed using **ESP32**, designed to track **SpO2**, **heart rate**, **ECG**, and **temperature** in real-time. This system is ideal for remote healthcare applications, academic projects, and DIY biomedical monitoring setups.

## 📦 Features

- **MAX30102** – SpO2 and Heart Rate Monitoring
- **AD8232** – ECG Signal Acquisition
- **LM35 / DHT22** – Body or Ambient Temperature Measurement
- **ESP32** – WiFi-enabled Microcontroller for IoT Connectivity
- **128x64 OLED Display** – Real-time vitals preview
- **3D-Printed Enclosure** – Designed in **SolidWorks** for portability and protection

## 🛠️ Technologies Used

- Arduino IDE
- ESP32 Board
- SolidWorks (3D Enclosure Design)
- I2C and Analog Communication Protocols
- ThingSpeak (or other IoT platforms)

## ⚙️ Setup Instructions

1. **Hardware Connections**  
   - MAX30102 → I2C (SDA, SCL)
   - AD8232 → Analog pin for ECG, Digital pins for LO+
   - LM35/DHT22 → Analog/Digital input pin
   - OLED Display → I2C (SDA, SCL)
   - ESP32 → Core microcontroller

2. **Software Setup**  
   - Install ESP32 board in Arduino IDE  
   - Install necessary libraries:
     - `Adafruit_GFX`
     - `Adafruit_SSD1306`
     - `SparkFun MAX3010x`
     - `DHT` and `ECG` related libraries

3. **Upload Code**  
   - Flash the code to ESP32
   - Connect to WiFi if ThingSpeak/Cloud is used
   - Monitor data on OLED or cloud dashboard

## 🧪 Challenges We Faced

- Calibration issues across sensors
- Handling analog signal noise in ECG
- Multi-sensor integration and timing conflicts
- 3D enclosure fitting and wire routing

## 📷 Project Showcase

Photos and design files are available in the `/images` and `/enclosure` folders.

## 🤝 Team

Developed by:
- [DINESH BHANUKA]
- [SASINDU AMESH]

## 📬 Contact

For questions, collaborations, or suggestions, feel free to open an issue or reach out!

---

> This project is part of our effort to make health monitoring smarter, portable, and more accessible using open-source tools. 🧠📡🛠️
