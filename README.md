# IoT-Based Elderly People Monitoring System

## Overview
Current healthcare systems integrate technology for remote patient monitoring, focusing on chronic disease tracking and tele-medical ECG systems. However, these solutions face limitations such as high costs, short-range wireless transfer, and difficulties in transmitting vital signs.

Our **IoT-based elderly monitoring system** overcomes these challenges with a **modular architecture**, advanced sensors, and a cloud-based platform for real-time **health monitoring and predictive alerts**.

## Features
- ✅ **Modular Sensor Integration** – Supports heart rate, blood pressure, temperature, and activity tracking.
- ✅ **Real-Time Monitoring** – Continuous health tracking with automatic alerts for abnormalities.
- ✅ **Cloud-Based Data Storage** – Secure storage and analysis on ThingSpeak.
- ✅ **Predictive Alerts & Early Intervention** – Notifies doctors, hospitals, and triggers ambulance dispatch.

## Technology Stack
- **Hardware:** Arduino/Raspberry Pi, IoT sensors (Heart Rate, Temperature, BP, etc.).
- **Software:** ThingSpeak for real-time data storage.
- **Communication:** Wi-Fi, GSM module for remote alerts and connectivity.

## System Workflow
1. **Data Collection:** Sensors measure real-time health parameters.
2. **Cloud Processing:** Data is securely stored and analyzed using ThingSpeak.
3. **Monitoring & Alerts:** Doctors access patient data; alerts trigger if anomalies are detected.
4. **Emergency Response:** Automated notifications to doctors, hospitals, and ambulance services.

## How to Run the Project?
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/Elderly-Monitoring-System.git
   ```  
2. Set up the hardware (Arduino, sensors, Wi-Fi/GSM module).
3. Configure ThingSpeak for real-time data storage.
4. Run the code backend to process and send alerts  
