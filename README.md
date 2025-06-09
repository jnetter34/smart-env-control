# Smart Environmental Monitoring & Control System

This project is a self-contained environmental automation platform built on the ESP32 microcontroller. It monitors temperature, humidity, and soil moisture — and controls devices like fans or humidifiers based on data threshold triggers

## Features
-  DHT22 and soil moisture sensors for real-time environmental data
-  Relay-driven activation of devices (e.g., fan, humidifier)
-  ESP32-hosted interface with live data, control sliders, and Chart.js graphs
-  Saves sensor readings to SD card every 5 minutes for long-term analysis

## Hardware 
- ESP32-WROOM Dev Board  
- DHT22 Temperature & Humidity Sensor  
- LM393 Soil Moisture Sensor  
- HiLetGo Micro SD Card Module  
- 5V Relay Module(s)  
- USB Fan + Humidifier (or other 5V devices)  
- 1602 I2C LCD Display  

## Application
Originally built for controlled indoor agricultural environments, this platform can be adapted to any closed system requiring smart feedback control — such as hydroponics, greenhouse research, or automated plant terrariums.

## Future Plans
- ESP32-CAM integration for live camera monitoring & time-lapse
- Graphical threshold setting via the web interface

## Images 
> ![Screenshot 2025-06-09 130141](https://github.com/user-attachments/assets/cb1f9f83-92c6-4e2b-8595-b7d969648fa5)



## Author
Julian Netter  
Mechanical Engineering @ Purdue University
