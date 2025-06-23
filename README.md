# Smart Parking System

A microcontroller-based smart parking solution that uses sensor-driven logic and mobile app integration to manage vehicle entry. This project leverages the ESP8266 Wi-Fi module, IR sensors, a servo motor, and Blynk IoT platform to create a real-time, responsive parking management system.

---

## 📌 Project Overview

This Smart Parking System was built to automate parking lot access based on real-time slot availability. Designed with embedded hardware and coded using the Arduino IDE, it demonstrates how IoT and automation can simplify urban mobility.

---

## 🔧 Features

- **Automatic Gate Control**: Uses IR sensors to check for free slots and operates a servo motor to lift/lower the gate.
- **Real-Time Slot Detection**: Continuously monitors parking lot occupancy.
- **Blynk Mobile App Integration**: Displays the live status of each IR sensor on a mobile dashboard.
- **Fail-Safe Logic**: Gate remains closed if all slots are occupied.

---

## 🧠 System Logic

1. **IR Sensors** detect the presence or absence of vehicles in each parking slot.
2. **ESP8266** processes this data and applies the following logic:
   - If **at least one slot is free**, the servo motor lifts the gate.
   - If **all slots are occupied**, the gate remains closed.
3. The **Blynk App** shows live sensor data, offering a simple, remote interface to view parking slot status.

---

## 📲 Blynk App Integration

The ESP8266 is connected to the **Blynk IoT platform**, which:
- Displays the status of each IR sensor (occupied or free)
- Acts as a user-friendly interface for monitoring parking availability
- Communicates over Wi-Fi via the ESP8266’s built-in capabilities

---

## 🛠️ Hardware Components

| Component     | Description                                      |
|---------------|--------------------------------------------------|
| **ESP8266**   | Wi-Fi enabled microcontroller (NodeMCU)          |
| **IR Sensors**| Detect vehicle presence in parking slots         |
| **Servo Motor**| Controls gate movement (up/down)                |
| **Breadboard & Wires**| Circuit connections                     |
| **Power Supply**| USB or battery powered                         |

---

## 💻 Software Tools

- **Arduino IDE**: For writing and uploading C++ code to the ESP8266
- **Blynk App**: Mobile app to visualize real-time sensor data
- **No backend or web interface used**

---

## ❌ Code Availability

The source code for this project was deployed directly to the ESP8266 microcontroller via Arduino IDE and is no longer available. However, a **full video demonstration** is included in this repository to document the implementation and logic.

---

## 🎥 Demonstration

Watch the working prototype in action:

[▶️ Watch Video Demo](assets/video_demonstration.mp4)

*(Note: GitHub may not preview video inline. Download or open directly to view.)*

---
