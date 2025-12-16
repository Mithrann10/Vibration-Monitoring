# Vibration-Monitoring
# MEMS based Machine Vibration Monitoring and Management System

An **IoT-based vibration monitoring solution** using **ESP32**, **ADXL345 accelerometer**, **GSM module**, and **Blynk IoT platform** to monitor machine health in real time and enable predictive maintenance.

---

## 📌 Project Overview

Machine vibration is a critical indicator of mechanical health. Abnormal vibration often points to issues such as imbalance, misalignment, bearing wear, or loose components. This project continuously monitors vibration levels of industrial machines and alerts users when unsafe conditions are detected.

The system measures vibration along **X, Y, and Z axes**, processes the data using an **ESP32**, and visualizes it on the **Blynk Web Console and Mobile App**. Alerts are sent instantly via **SMS (GSM module)** and **push notifications** whenever vibration exceeds the threshold.

This project is designed to be **low-cost, portable, and scalable**, making it suitable for **small and medium-scale industries**.

---

## 🎯 Objectives

* Continuous real-time vibration monitoring
* Early fault detection to prevent machine failure
* Wireless data transmission using IoT
* Local and remote visualization of vibration data
* Instant alert generation for abnormal vibration

---

## 🛠️ Hardware Components

* **ESP32 Microcontroller** – Central processing and Wi-Fi communication
* **ADXL345 Accelerometer** – 3-axis vibration sensing (X, Y, Z)
* **GSM Module (SIM800L or equivalent)** – SMS alert system
* **16x2 LCD Display** – Local real-time data display
* **Power Supply** – 5V regulated supply / Li-ion battery with charging module

---

## 💻 Software & Platforms Used

* **Arduino IDE** – Firmware development
* **Blynk IoT Platform (Web & Mobile App)** – Real-time data visualization and alerts
* **ESP32 Libraries** – Wi-Fi, I2C, sensor interfacing
* **ADXL345 Sensor Library**

---

## ⚙️ System Architecture

1. ADXL345 measures vibration in X, Y, Z axes
