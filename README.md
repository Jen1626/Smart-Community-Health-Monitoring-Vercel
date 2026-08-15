# Smart Community Health Monitoring and Early Warning System

## Live Demonstration

**Virtual Dashboard:** https://smart-community-health-monitoring-v-wine.vercel.app/

## Project Overview

The **Smart Community Health Monitoring and Early Warning System** is an IoT-based solution designed for continuous monitoring of water quality and early identification of potentially unsafe conditions.

The physical system utilizes an **ESP32 microcontroller** integrated with pH, turbidity, and temperature sensors. Sensor data can be transmitted through WiFi/LoRa communication and stored through a cloud platform such as Firebase for monitoring and analysis.

The system applies predefined water-quality thresholds to classify conditions into **Safe, Caution, and High Risk** categories.

## Virtual Representation

Although the project is primarily a **hardware and IoT-based system**, this repository provides a web-based **virtual representation of the monitoring and visualization layer**.

The deployed dashboard demonstrates how sensor readings can be presented, monitored, analyzed, and classified through an interactive interface. The current web implementation uses simulated sensor data for demonstration purposes and can be integrated with the physical ESP32 and Firebase infrastructure for real-time monitoring.

## Key Components

- ESP32 Microcontroller
- pH Sensor
- Turbidity Sensor
- DS18B20 Temperature Sensor
- WiFi / LoRa Communication
- Firebase Realtime Database
- Web-Based Monitoring Dashboard
- Rule-Based Risk Classification

## Dashboard Features

- Real-time-style water-quality monitoring
- pH, turbidity, and temperature visualization
- Water Health Score
- Safe, Caution, and High Risk classification
- Parameter trend visualization
- IoT system architecture representation
- Responsive web interface

## Project Context

The physical prototype focuses on continuous measurement and monitoring of water-quality parameters, while this deployment demonstrates the **software and visualization component** of the overall system.

The project is intended to support early identification of potential water-quality issues and demonstrate how IoT, cloud connectivity, and data visualization can be integrated into a unified monitoring solution.
