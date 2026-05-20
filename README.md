# CATRON-A-Cable-Tunnel-Inspection-Robot

CATRON is an IoT-based tunnel inspection robot designed for monitoring underground cable tunnel environments using multiple sensors, cloud connectivity, and real-time surveillance.

The system integrates Raspberry Pi 3B+, ESP8266, LiDAR, gas sensors, temperature and humidity monitoring, and live video streaming to improve tunnel safety and preventive maintenance.

---

## Features

- Real-time tunnel monitoring
- Semi-autonomous navigation
- LiDAR-based obstacle detection
- Live video streaming
- Remote data access
- Gas leakage detection
- Temperature and humidity monitoring
- Cloud dashboard monitoring
- Sensor data logging

---

## Hardware Components

| Component | Purpose |
|---|---|
| Raspberry Pi 3B+ | Main processing unit |
| ESP8266 | Sensor communication |
| MQ5 | Gas detection |
| DHT11 | Temperature & humidity |
| VL53L1X | Obstacle detection |
| MPU6050 | Motion sensing |
| BMM150 | Orientation sensing |
| L298N | Motor driver |
| USB Camera | Visual monitoring |

---
## Software Stack

- Python
- Flask
- HTML/CSS/JavaScript
- Arduino IDE
- Firebase
- Raspberry Pi OS

-------------------------------------------------------------------------------------------------

## System Architecture

 Figure: Block diagram
 
<img width="737" height="486" alt="block diagram" src="https://github.com/user-attachments/assets/9bc6c5f5-d261-428b-8f7a-979ecfe728db" />
 

 ----------------

  Figure: Hardware design
  
<img width="737" height="486" alt="Circuit dia" src="https://github.com/user-attachments/assets/2166fc52-e8ff-4f93-95f6-0c455aba7dcc" />

 
-------------------------------------------------------------------------------------------------

## Working Principle

The ESP8266 collects sensor data from gas, temperature, motion, and distance sensors and transmits it to the Raspberry Pi.

The Raspberry Pi processes the data, controls robot movement, streams live video, and uploads inspection data to a cloud-based dashboard for remote monitoring.

-------------------------------------------------------------------------------------------------

## Output

### Hardware Setup

<img width="700" height="600" alt="Hardware 1" src="https://github.com/user-attachments/assets/07f43e3c-a797-45b7-8152-71eea6a70f3a" />

<img width="600" height="797" alt="Hardware 2" src="https://github.com/user-attachments/assets/7eea7eb9-659f-4a31-a5ab-5f49fae451ae" />

### Dashboard Output

<img width="700" height="400" alt="webpage" src="https://github.com/user-attachments/assets/9d3c1989-3d58-47e5-8531-ea3d11b4a05a" />

-------------------------------------------------------------------------------------------------

## Future Scope

- SLAM-based autonomous navigation
- AI-based defect detection
- Thermal imaging integration
- LoRa/5G communication
- Predictive maintenance analytics

-------------------------------------------------------------------------------------------------

## Authors
---
- Gowthami S
- Arya Sasikumar
- Dhanush P
- Mahitha M

----------------------------------------------  


Project Status: Completed ✅

