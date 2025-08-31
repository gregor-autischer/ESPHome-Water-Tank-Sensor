# ESPHome Water Tank Sensor

ESPHome configuration code for monitoring water tank levels using ESP32 and HC-SR04 ultrasonic sensor.

## Description

This project provides ESPHome configuration code for creating a smart water tank level sensor using an ESP32 microcontroller and HC-SR04 ultrasonic sensor. Perfect for home automation integration with Home Assistant.

## Features

- Real-time water level monitoring
- Integration with Home Assistant
- Configurable alerts and notifications
- WiFi connectivity for remote monitoring
- Battery-friendly deep sleep support

## Hardware Requirements

- ESP32 development board
- HC-SR04 ultrasonic sensor
- Waterproof housing (see 3D Print Model below)
- M5 bolts and nuts for mounting

## 3D Print Model

My 3D printable housing is available here:
[ESP32 Ultrasonic Water Level Sensor Housing](https://www.printables.com/model/1333286-esp32-ultrasonic-water-level-sensor-housing-with-h)

This robust housing system includes:
- Inner housing for ESP32 and HC-SR04
- Outer housing for weather protection
- Mounting template for tank lid installation

## Installation

### Hardware Assembly

1. Insert the ESP32 into the inner housing
2. Connect the ultrasonic sensor:
    - Vcc → 3V3
    - GND → GND
    - Trig → GPIO 12
    - Echo → GPIO 14
3. Assemble everything and fasten it to the lid with M4 screws

### Software Setup

ESPHome configuration instructions will be added here.

## License

Apache License 2.0
