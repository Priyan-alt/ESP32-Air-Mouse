# ESP32 Air Mouse using MPU6050

## Overview

The **ESP32 Air Mouse** is a wireless motion-controlled mouse developed using an **ESP32 DevKit V1** and **MPU6050 Gyroscope Sensor**. This project allows users to control a computer cursor through hand movements using **Bluetooth Low Energy (BLE)** communication.

The MPU6050 sensor detects angular motion and transfers the data to the ESP32, which processes the motion values and converts them into mouse cursor movements. Push buttons are used for left-click and right-click operations, making the device function like a real wireless air mouse.

This project demonstrates practical implementation of:

- Embedded Systems
- Sensor Interfacing
- Bluetooth Communication
- Human-Computer Interaction
- Real-Time Motion Processing

---

## Features

- Wireless BLE Mouse using ESP32
- Motion-Controlled Cursor Movement
- Left and Right Click Support
- Cursor Smoothing using Low-Pass Filtering
- Gyroscope Deadzone Stabilization
- Portable Battery-Powered Design
- Real-Time Gesture-Based Control

---

## Components Used

| Component | Quantity |
|------------|----------|
| ESP32 DevKit V1 | 1 |
| MPU6050 Gyroscope + Accelerometer | 1 |
| Push Buttons | 2 |
| 18650 Li-ion Battery | 1 |
| XL6009 Boost Converter Module | 1 |
| Toggle Switch | 1 |
| Jumper Wires | As Required |
| Breadboard / PCB | 1 |

---

## Working Principle

The MPU6050 sensor continuously measures the angular rotation of the hand. The ESP32 reads the gyroscope values through I2C communication and processes the data using filtering and sensitivity algorithms.

The processed values are mapped into X and Y cursor coordinates and transmitted wirelessly to the computer using BLE Mouse functionality.

### Button Functions

- Left Click
- Right Click

The entire system is powered using a rechargeable **18650 Li-ion Battery**.

---

## Software Used

- Arduino IDE
- ESP32 Board Package
- BLE Mouse Library
- MPU6050_light Library

---

## Applications

- Wireless Air Mouse
- Smart Presentation Controller
- Gesture-Based Human Interface Device (HID)
- Assistive Technology
- IoT and Embedded Systems Projects

---

## Future Improvements

- Gesture Recognition
- Scroll Control
- Rechargeable Charging Module
- OLED Status Display
- Battery Percentage Monitoring
- 3D Printed Enclosure
- AI-Based Gesture Commands

---

## Conclusion

This project successfully implements a portable wireless air mouse using ESP32 and MPU6050. It combines motion sensing, wireless communication, and embedded programming to create an interactive human-computer interface device.

The project enhances practical knowledge in IoT, BLE communication, sensor interfacing, and real-time embedded system design while demonstrating the application of motion-based human-computer interaction.

---

## Author

**Priyan S**  
B.Tech ECM, VIT Chennai
