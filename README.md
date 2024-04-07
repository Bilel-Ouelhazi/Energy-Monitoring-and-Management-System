Project Name: Energy Monitoring and Management System

Description:
This project aims to develop an Energy Monitoring and Management System using Flask, MongoDB, and ESP32. The system allows users to monitor and manage energy consumption data collected from various sensors deployed in a facility.

Features:

User Authentication: The system supports user authentication with different access levels (admin and user).
Real-time Data Monitoring: Users can view real-time data on energy consumption, including voltage, current, power, and energy.
Data Visualization: The system provides interactive charts and graphs to visualize daily, monthly, and yearly energy consumption trends.
Configuration Settings: Admin users can configure system settings, such as setting maximum energy consumption limits.
Data Collection from Sensors: Data from sensors connected to ESP32 microcontrollers are collected periodically and stored in a MongoDB database.
Remote Data Transmission: ESP32 devices transmit energy consumption data to the server via WiFi for real-time monitoring and analysis.
Components:

app.py: This file contains the Flask application for the web interface, including routes for user authentication, data visualization, and configuration settings.
esp32.py: This script runs on ESP32 microcontrollers to collect energy consumption data from sensors and transmit it to the server.
arduino.ino: Arduino sketch for collecting energy consumption data and transmitting it to the server via WiFi.
Technologies Used:

Python (Flask)
MongoDB
ESP32
Arduino
Usage:

Clone the repository.
Set up the Flask application and MongoDB database.
Upload the ESP32 firmware to the microcontrollers and deploy sensors.
Run the Flask application.
Access the web interface to monitor and manage energy consumption data.
