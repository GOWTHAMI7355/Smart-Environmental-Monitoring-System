# Smart Environmental Monitoring System

A simulation-based IoT environmental monitoring system developed using Node-RED, MQTT, and ESP32 architecture.

## Project Overview

This project demonstrates real-time environmental monitoring and automated device control using an IoT-based architecture. It monitors temperature and humidity, displays readings on a dashboard, controls a fan and LED based on predefined thresholds, generates alerts, and logs sensor data.

**Note:** This project is implemented using simulation. Software-generated readings represent the DHT22 sensor data, and the device responses are simulated.

## Technologies Used

- Node-RED
- MQTT
- ESP32 architecture
- DHT22 sensor (simulated)
- FlowFuse Dashboard
- JSON
- CSV data logging

## Key Features

- Real-time temperature and humidity monitoring
- Dashboard gauges and charts
- Automatic fan control based on temperature
- Automatic LED control based on humidity
- Manual fan and LED operation
- Threshold-based alerts
- Sensor data logging

## Working Principle

The simulated sensor continuously generates temperature and humidity readings and publishes them to an MQTT broker. Node-RED receives and processes these readings and displays them on a dashboard using gauges, charts, and status indicators.

In automatic mode, the system switches the fan ON when the temperature exceeds 30°C and switches the LED ON when humidity exceeds 70%. In manual mode, users can control these devices directly through dashboard switches.

The system also generates alerts when predefined thresholds are crossed and stores the readings in a log file for future analysis.

## System Architecture

Simulated DHT22 Sensor → MQTT Broker → Node-RED Processing → Dashboard and Automatic Control

## Project Files

- `Smart_Environmental_Monitoring_Flow.json` – Node-RED flow export
- `Assignment_Report.pdf` – Project report
- `Assignment_Report.docx` – Editable project report
- `System_Flowchart.png` – System flowchart
- `README_SETUP.txt` – Setup instructions
- `screenshots/` – Dashboard and implementation screenshots

## Future Enhancements

- Physical ESP32 and DHT22 hardware integration
- Real fan and LED interfacing
- Cloud-based data storage
- Mobile notifications
- Historical data analysis

## Project Status

Completed – Simulation-based implementation.
