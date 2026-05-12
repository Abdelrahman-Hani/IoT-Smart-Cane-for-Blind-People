# 🦯 Smart Blind Stick - IoT Obstacle Detection

## 📌 Overview
This project is an IoT-based Smart Blind Stick designed to assist visually impaired people in detecting obstacles in their path.  
The system uses an ultrasonic sensor to measure the distance between the stick and nearby objects and triggers an alert when an obstacle is detected within a predefined range.

---

## 🎯 Features
- Real-time obstacle detection
- Distance measurement using ultrasonic sensor
- Audio alert using buzzer
- Low-cost and simple design
- Portable and battery-powered

---

## ⚙️ Components Used
- Arduino UNO
- Ultrasonic Sensor (HC-SR04)
- Buzzer
- Jumper wires
- Power supply (Battery / Power bank)

---

## 🧠 How It Works
1. The ultrasonic sensor sends a sound wave.
2. The wave reflects back from obstacles.
3. Arduino calculates the distance using the time taken.
4. If the distance is less than a threshold (e.g., 50 cm), the buzzer is activated.

---

## 📏 Distance Formula
