# 🏠 ESP32 Smart Home Monitoring System

A complete IoT-based Smart Home Monitoring System built using ESP32 and multiple sensors for real-time environmental monitoring.

The system collects sensor data and displays it simultaneously on:

* 📟 SSD1306 OLED Display
* 🌐 ESP32 Web Dashboard
* 📱 Mobile Browser
* 💻 Desktop Browser

---

## 🚀 Features

✅ Temperature Monitoring (DHT11)

✅ Humidity Monitoring (DHT11)

✅ Gas Leakage Detection (MQ Sensor)

✅ Rain Detection

✅ Light Detection (LDR)

✅ Water Tank Level Monitoring (HC-SR04)

✅ OLED Real-Time Display

✅ Wi-Fi Based Dashboard

✅ Local HTTP Web Server

✅ Auto Refresh Dashboard

---

## 🛠 Hardware Used

| Component       | Function               |
| --------------- | ---------------------- |
| ESP32 Dev Board | Main Controller        |
| DHT11           | Temperature & Humidity |
| MQ Gas Sensor   | Gas Monitoring         |
| Rain Sensor     | Rain Detection         |
| LDR Module      | Light Detection        |
| HC-SR04         | Distance Measurement   |
| SSD1306 OLED    | Display Output         |

---

## 🌐 Web Dashboard

The ESP32 hosts an embedded HTTP server that generates a live monitoring dashboard.

Displayed Parameters:

* Temperature (°C)
* Humidity (%)
* Gas Level
* Rain Status
* Light Status
* Tank Distance (cm)

Dashboard refreshes automatically every 3 seconds.

---

## 🔌 ESP32 Pin Configuration

| Sensor          | GPIO    |
| --------------- | ------- |
| DHT11           | GPIO 4  |
| Rain Sensor     | GPIO 34 |
| MQ Gas Sensor   | GPIO 35 |
| LDR Sensor      | GPIO 32 |
| HC-SR04 Trigger | GPIO 5  |
| HC-SR04 Echo    | GPIO 18 |
| OLED SDA        | GPIO 21 |
| OLED SCL        | GPIO 22 |

---

## 📚 Required Libraries

* WiFi.h
* WebServer.h
* DHT.h
* Wire.h
* Adafruit_GFX.h
* Adafruit_SSD1306.h

---

## 📸 Project Setup

Add your hardware image here:

![Hardware Setup](images/hardware-setup.jpg)


## 👨‍💻 Author

**Nishit Satapara**

Roll No: 23BEC173

Electronics and Communication Engineering

Nirma University

---

## ⭐ Project Status

Completed ✅

Real-Time Monitoring System using ESP32, OLED Display, and Web Dashboard.
