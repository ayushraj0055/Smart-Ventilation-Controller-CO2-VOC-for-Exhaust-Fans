# Smart-Ventilation-Controller-CO2-VOC-for-Exhaust-Fans
# Smart Ventilation Controller using CO₂ and VOC Sensors for Exhaust Fans

## Overview

The Smart Ventilation Controller is an IoT-based system that automatically controls exhaust fans based on indoor air quality. The system continuously monitors Carbon Dioxide (CO₂) and Volatile Organic Compounds (VOC) levels and activates ventilation when pollutant levels exceed predefined thresholds.

This helps maintain healthy indoor air quality while reducing unnecessary energy consumption.

---

## Problem Statement

Poor indoor air quality can cause health issues, discomfort, and reduced productivity. Traditional exhaust fans operate manually, which can lead to inefficient ventilation and energy waste.

The objective of this project is to develop an intelligent ventilation system that automatically controls exhaust fans using real-time air quality measurements.

---

## Objectives

* Monitor CO₂ concentration in indoor environments.
* Detect VOC gases and pollutants.
* Automatically control exhaust fans.
* Improve indoor air quality.
* Reduce power consumption through smart automation.
* Provide real-time monitoring and alerts.

---

## Features

* Real-time CO₂ monitoring
* VOC gas detection
* Automatic exhaust fan control
* Threshold-based decision making
* Energy-efficient operation
* Indoor air quality improvement
* Scalable IoT architecture

---

## Hardware Components

* ESP32 / Arduino
* CO₂ Sensor (MH-Z19B or equivalent)
* VOC Sensor (SGP30 / CCS811 / MQ135)
* Relay Module
* Exhaust Fan
* Power Supply
* Connecting Wires

---

## Software Requirements

* Arduino IDE
* Embedded C/C++
* ESP32 Libraries
* Sensor Libraries

---

## System Architecture

Sensors → Microcontroller → Decision Logic → Relay Module → Exhaust Fan

1. Sensors measure CO₂ and VOC levels.
2. Microcontroller processes sensor data.
3. Air quality values are compared against thresholds.
4. Relay activates exhaust fan if pollution exceeds limits.
5. Fan turns OFF when air quality returns to normal.

---

## Working Principle

### Normal Condition

* CO₂ level below threshold
* VOC level below threshold
* Exhaust fan remains OFF

### Poor Air Quality

* CO₂ level exceeds threshold OR
* VOC level exceeds threshold

System automatically:

* Activates relay
* Turns ON exhaust fan
* Ventilates indoor environment

### Safe Condition Restored

* Pollutant levels decrease
* Fan automatically turns OFF

---

## Applications

* Smart Homes
* Offices
* Laboratories
* Classrooms
* Hospitals
* Industrial Workspaces
* Conference Rooms

---

## Advantages

* Improved indoor air quality
* Reduced human intervention
* Lower energy consumption
* Healthier environment
* Cost-effective solution

---

## Future Enhancements

* Mobile App Integration
* Cloud Monitoring Dashboard
* AI-based Ventilation Prediction
* Wi-Fi Alerts and Notifications
* Historical Data Analytics

---

## Contributors
MADHU SHARMA
NAVNIT KUMAR
AYUSH RAJ
 

---

## License

This project is developed for educational and research purposes.
