# Office Automation System

## Overview

The Office Automation System is an Arduino-based project designed to enhance office environments by monitoring and controlling various factors such as lighting, temperature, and smoke levels. This system provides both automatic and manual control modes for increased convenience and safety.

## Features

- **Automatic Lighting Control:** Adjusts the brightness of a bulb based on ambient light sensor readings.
- **Temperature-Based Fan Control:** Regulates the fan speed according to the current temperature.
- **Smoke Detection:** Monitors smoke levels and triggers visual and auditory alerts if smoke is detected.
- **Manual Override:** Allows users to manually adjust the bulb brightness through serial commands.

## Components

- **Arduino Uno:** Main microcontroller for processing sensor data and controlling outputs.
- **Light Dependent Resistor (LDR):** Measures ambient light levels to adjust bulb brightness.
- **Temperature Sensor:** Monitors the temperature and adjusts the fan speed accordingly.
- **Smoke Sensor:** Detects smoke and activates alarms if levels exceed a threshold.
- **Bulb:** Controlled using PWM to vary brightness.
- **Fan:** Adjusted for speed based on temperature readings.
- **Red LED & Buzzer:** Provide alerts for smoke detection.
