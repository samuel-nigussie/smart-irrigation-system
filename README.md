
Automated sensor-based irrigation system built with Arduino, featuring real-time remote monitoring via Blynk IoT dashboard and solar power management.

## Features

- Multi-sensor integration (soil moisture, temperature, light, water flow)
- Blynk IoT dashboard for remote monitoring and manual override
- GSM SMS alerts for critical system events
- Solar power management for 24/7 operation
- Automated pump control with configurable thresholds

## Hardware

- Arduino Uno
- Soil Moisture Sensor
- LM50 Temperature Sensor
- LDR Light Sensor
- Water Level Sensor
- Flow Sensor
- SIM900D GSM Module
- Relay Module
- LCD 20×4 (I2C)
- Solar Panel + Battery

## Software

- Proteus 8 Professional (simulation)
- Arduino IDE
- Blynk IoT Platform

## Simulation Results

| Condition | Soil Moisture | Temperature | Tank Level | Pump Status |
|-----------|---------------|-------------|------------|-------------|
| Dry Soil | 750 | 28°C | 900 | ON |
| Moist Soil | 500 | 29°C | 900 | OFF |
| Low Tank | 600 | 30°C | 150 | OFF |

## Team Members

This was a group project by Electromechanical Engineering students at Addis Ababa Science and Technology University:

- Mihret Teget
- Mussie Kifle
- Rolih Degarege
- Samuel Lemma
- Zemenu Teshager
- Samuel Nigussie

Supervised by: Mr. Abera
*This repository maintained by Samuel Nigussie*
