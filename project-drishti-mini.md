publishDate:2025-12-30

title:  Project Drishti Mini

excerpt: An IoT-Enabled Crowd Density and Panic Detection System using MYOSA fusion.

image: your-cover-image.jpg

tags:
- IOT
- MYOSA
- Crowd-Safety
- Sensors
---

> A Sensor-based system for early detection of crowd congestion and panic using MYOSA

---

## Acknowledgements
We thank IEEE, the MYOSA initiative, and Prof. Digant Parmar from Silver Oak University for their guidance and mentorship throughout the development of this project.

---

## Overview
Project Drishti Mini is an IoT-powered crowd monitoring and panic detection system that uses sensor fusion to measure and analyze environmental and movement parameters. The system detects early indicators of overcrowding or panic, allowing authorities to take preventive action before incidents occur.
This version of Project Drishti focuses on the MYOSA IoT ecosystem, integrating its onboard capabilities and sensor modules for real-time data acquisition, local processing, and alert generation.

---

## Demo / Examples

### Images
<p align="center">
<img src="/drishti-node.jpeg" width="800"><br/>
<i>MYOSA Crowd Monitoring Unit with connected sensors</i>
</p>

<p align="center">
<img src="/drishti-dashboard.jpeg" width="800"><br/>
<i>Live dashboard showing crowd risk levels</i>
</p>


### Videos
<video controls width="100%">
<source src="/drishti-demo.mp4" type="video/mp4">
</video>

---

## Features (Detailed)

### 1. Sensor-Based Crowd Monitoring
Each MYOSA node acts as a Crowd Monitoring Unit (CMU) deployed at strategic points. Sensors continuously collect data related to motion, proximity, temperature, pressure, and vibration.

### 2. Panic Detection Using Motion Analysis
The accelerometer and gyroscope detect sudden vibrations and abnormal movements, which are strong indicators of panic or stampede-like conditions.

### 3. Edge-Based Risk Analysis
Sensor data is processed locally on the MYOSA board to compute a Crowd Risk Index using weighted sensor fusion. This enables low-latency decision-making.

### 4. Local and Remote Alerts
OLED displays show the current risk status (Safe / Warning / Critical). LEDs and buzzers provide immediate on-site alerts, while data is transmitted wirelessly to a central dashboard.

### 5. Real-Time Dashboard Visualization
A cloud-based dashboard visualizes data from all MYOSA nodes, displaying crowd density graphs, alerts, and node status in real time.

---

## Usage Instructions
1. Power the MYOSA board using a USB cable or battery.
2. Flash the firmware to the MYOSA board.
3. Ensure sensors are properly connected.
4. Start the dashboard application.
5. Monitor real-time readings and alerts.

---

## Tech Stack
MYOSA Mini IoT Platform
Embedded C / Arduino
Wi-Fi / BLE Communication
Node.js
Firebase
OLED Display (SSD1306)

---

## Requirements / Installation

## File Structure (Optional)
project-drishti-mini/
├─ project-drishti-mini.md
├─ drishti-cover.jpg
├─ drishti-node.jpg
├─ drishti-dashboard.jpg
├─ drishti-demo.mp4

