
# Intelligent Greenhouse Monitoring System

**Academic Team Project — Ibn Zohr University**

## Overview
An ESP32-based smart greenhouse prototype for real-time environmental monitoring and automated irrigation. The system uses sensor measurements and configurable thresholds to control a water pump and ventilation fan.

## Features
- Monitoring of soil moisture, temperature, air humidity, light, and gas levels
- Automatic pump and fan control based on sensor thresholds
- Web dashboard for monitoring measurements and manually controlling actuators
- REST API for communication between the ESP32, backend, and dashboard
- Raspberry Pi 4 server configuration and router port forwarding

## Tech Stack
- **Embedded / IoT:** ESP32, environmental sensors, actuators, Wi-Fi
- **Backend:** Node.js, Express.js, HTTP/REST API
- **Frontend:** React, Tailwind CSS
- **Database:** PostgreSQL (Neon)
- **Deployment:** Railway, Netlify
- **Additional setup:** Raspberry Pi 4

The project presentation documents both a Raspberry Pi server setup and a cloud deployment architecture using Railway, Neon, and Netlify.


## My Contribution

- **Hardware Integration:** Worked on the greenhouse prototype hardware, integrating the ESP32, environmental sensors, and actuators, including the water pump and ventilation fan.
- **Web Development:** Built the web dashboard using React and Tailwind CSS to display greenhouse monitoring data and provide controls for the pump and fan.

web Dashboard: https://serre-intelligente.netlify.app/

