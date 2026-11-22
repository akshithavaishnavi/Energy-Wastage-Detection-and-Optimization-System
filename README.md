# Energy Wastage Detection and Optimization System

An ESP32-based system for detecting unnecessary energy consumption and automating electrical appliances using sensors and IoT-based monitoring.

## About the Project

Electrical appliances such as lights and fans are often left ON even when they are not required, leading to unnecessary energy consumption.

This project aims to address this problem through a sensor-based energy optimization system. It uses an ESP32 microcontroller to monitor room occupancy and environmental conditions, automatically control electrical appliances, and monitor current consumption.

The system also uses the ThingSpeak cloud platform to visualize sensor readings.

## Objectives

- Detect human presence using a PIR sensor.
- Automate lighting based on ambient light intensity.
- Control fan operation based on room temperature.
- Monitor current consumption using an ACS712 sensor.
- Visualize collected sensor data through ThingSpeak.

## Hardware Components

| Component | Purpose |
|---|---|
| ESP32 | Main microcontroller |
| PIR Sensor | Detects human presence |
| LDR | Measures ambient light intensity |
| DHT11 | Measures temperature and humidity |
| ACS712 | Monitors current consumption |
| Relay Module | Controls electrical appliances |
| 12V LED | Demonstrates automatic lighting |
| 12V DC Fan | Demonstrates automatic fan control |

## Software and Platforms

- Arduino IDE
- Embedded C
- ThingSpeak
- ESP32 Wi-Fi

## Working Principle

1. The PIR sensor detects human presence in the room.
2. The LDR measures ambient light intensity to determine whether lighting is required.
3. The DHT11 measures room temperature and humidity.
4. The ESP32 processes the sensor readings and controls the LED and fan through relay modules.
5. The ACS712 sensor monitors current consumption.
6. Sensor readings are transmitted through the ESP32's Wi-Fi connectivity to ThingSpeak for monitoring and visualization.

## System Workflow

**Sensor Data Collection → ESP32 Processing → Automatic Appliance Control → Current Monitoring → ThingSpeak Visualization**

## Project Outcomes

- Developed a working sensor-based energy optimization prototype.
- Demonstrated automatic lighting control based on ambient light.
- Demonstrated temperature-based fan control.
- Integrated current monitoring.
- Enabled cloud-based sensor-data visualization using ThingSpeak.

## My Contribution

As a member of the project team, I contributed to hardware connections, sensor interfacing with the ESP32, relay integration and implementation of the system using adapted code. I also participated in testing the prototype and understanding the interaction between its hardware components.

## Learning Outcomes

- Practical exposure to ESP32 and sensor interfacing.
- Understanding relay-based appliance control.
- Experience with hardware integration and prototype testing.
- Exposure to IoT-based monitoring and data visualization.
- Understanding how embedded systems can be applied to everyday problems.

## Team and Project Details

**Project Type:** Academic Mini Project

**Department:** Electronics and Communication Engineering

**Institution:** G. Narayanamma Institute of Technology and Science (GNITS)

**Academic Year:** 2025–2026
## Project Gallery

### Overall Hardware Setup
![Overall Setup](images/overall%20setup.png)

### Fan Automation
**Fan OFF**

![Fan Off](images/fan%20off.png)

**Fan ON**

![Fan On](images/fan%20on.png)

### Light Automation
**Light OFF**

![Light Off](images/light%20off.png)

**Light ON**

![Light On](images/light%20on.png)

**Project Guide:** Mr. V. Shankar, Assistant Professor

---

*This project was developed as an academic prototype demonstrating sensor-based energy monitoring and automatic appliance control.*
