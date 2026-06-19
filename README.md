project Name : Environmental Monitoring Controller
Introduction
The Internet of Things (IoT) enables physical devices to connect and communicate over the internet. In this project, ESP32 is used as the main controller because it has built-in WiFi capability. The system reads sensor data and sends it to Firebase Realtime Database. A web page is used to display the live data.
This project helps to understand IoT communication, cloud data storage, and real-time monitoring systems.
Components Used
ESP32 Microcontroller
WiFi Network (Wokwi / Mobile Hotspot)
Firebase Realtime Database
HTML, JavaScript
Arduino IDE / Wokwi Simulator
Working Principle
ESP32 is powered ON
It connects to WiFi network
Sensor values (temperature & humidity) are generated or read
ESP32 sends data to Firebase using HTTP REST API
Firebase stores data in real time
Web page reads Firebase data
Data is displayed in browser
System updates continuously every few seconds
 Block Flow
ESP32 → WiFi → Firebase → Web Dashboard → User
