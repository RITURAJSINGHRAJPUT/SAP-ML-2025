# 🌾 Farm-Web: Smart Agriculture with ESP32 + Firebase

![Farm-Web Banner](https://img.shields.io/badge/IoT-ESP32-green?style=for-the-badge) ![Firebase](https://img.shields.io/badge/Firebase-Backend-yellow?style=for-the-badge) ![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

> A smart agriculture web dashboard that uses real-time sensor data from an ESP32 microcontroller to monitor and control irrigation systems intelligently. Designed for precision farming, security alerts, and efficient water usage.

---

## 🔥 Features

- 📡 **Real-Time Sensor Data**
  - Temperature, Humidity, Soil Moisture, Heat Index
- 🚿 **Smart Irrigation Control**
  - Manual & AI-based irrigation schedule
- 🔐 **Security Alerts**
  - Anti-theft system integration
- 📊 **Graphical Visualization**
  - Real-time charts and trend graphs
- 🌐 **Firebase Integration**
  - Realtime Database + Authentication
- ⚙️ **ESP32 Auto Wi-Fi Configuration**
  - Using WiFiManager
- 📅 **Smart Scheduling**
  - ML-based prediction for next 5 irrigation sessions
- 📲 **Responsive Web Dashboard**
  - Works on both desktop and mobile
- 🧠 **ML Integration**
  - Predicts irrigation based on crop & environment

---

## 🧠 Technologies Used

| Frontend | Backend | IoT & ML |
|----------|---------|----------|
| HTML, CSS, JS | Node.js, Express.js | ESP32, Firebase, ML Model |
| Bootstrap, Chart.js | Firebase Auth & DB | DHT11, Soil Moisture Sensor, pH Sensor |

---

## 📷 Screenshots

### Dashboard View
![Dashboard](https://your-screenshot-link.png)

### Mobile Responsive View
![Mobile View](https://your-screenshot-link.png)

---

## ⚙️ Hardware Used

- ESP32 Dev Board
- Soil Moisture Sensor
- DHT11 Temperature & Humidity Sensor
- pH Sensor
- Water Pump (for irrigation)
- Relay Module
- Power Supply
- Jumper Wires & Breadboard

---

## 🚀 Setup Instructions

### 1. ESP32 Firmware

- Install the necessary libraries (WiFiManager, FirebaseESP32, DHT sensor)
- Flash the ESP32 with the `/firmware` code using Arduino IDE

### 2. Web App

```bash
git clone https://github.com/your-username/Farm-Web.git

