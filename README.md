Overview
The ESP32 Air Mouse is a wireless motion-controlled mouse developed using an ESP32 DevKit V1 and MPU6050 gyroscope sensor. This project allows the user to control the computer cursor through hand movements using Bluetooth Low Energy (BLE) communication.

The MPU6050 sensor detects angular motion and transfers the data to the ESP32, which processes the motion values and converts them into mouse cursor movements. Push buttons are used for left-click and right-click operations, making the device function like a real wireless air mouse.

This project demonstrates practical implementation of:

Embedded systems
Sensor interfacing
Bluetooth communication
Human-computer interaction
Real-time motion processing
Features
Wireless BLE mouse using ESP32
Motion-controlled cursor movement
Left and right click support
Cursor smoothing using low-pass filtering
Gyroscope deadzone stabilization
Portable battery-powered design
Real-time gesture-based control
Components Used
ESP32 DevKit V1
MPU6050 Gyroscope + Accelerometer
Push Buttons (2)
18650 Li-ion Battery
XL6009 Boost Converter Module
Toggle Switch
Jumper Wires
Breadboard / PCB
Working Principle
The MPU6050 sensor continuously measures the angular rotation of the hand. The ESP32 reads the gyroscope values through I2C communication and processes the data using filtering and sensitivity algorithms.

The processed values are mapped into X and Y cursor coordinates and transmitted wirelessly to the computer using BLE mouse functionality.

Push buttons connected to the ESP32 GPIO pins are used for:

Left click
Right click
The entire system is powered using a rechargeable 18650 Li-ion battery.

Software Used
Arduino IDE
ESP32 Board Package
BLE Mouse Library
MPU6050_light Library
Applications
Wireless Air Mouse
Smart Presentation Controller
Gesture-Based Human Interface Device
Assistive Technology
IoT and Embedded Systems Projects
Future Improvements
Gesture recognition
Scroll control
Rechargeable charging module
OLED status display
Battery percentage monitoring
3D printed enclosure
AI-based gesture commands
Conclusion
This project successfully implements a portable wireless air mouse using ESP32 and MPU6050. It combines motion sensing, wireless communication, and embedded programming to create an interactive human-computer interface device. The project improves practical knowledge in IoT, BLE communication, and sensor integration while demonstrating real-time embedded system design.
