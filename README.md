# DecodeLabs Internship
## Internet of Things (IoT) Projects

## Overview
This repository contains a collection of Internet of Things (IoT) projects developed using the ESP32 microcontroller as part of my DecodeLabs Industrial Training in IoT. These projects demonstrate practical implementations of sensor interfacing, automation, cloud connectivity, edge computing, safety systems, and real-time monitoring.

Each project focuses on solving real-world engineering problems while providing hands-on experience with embedded systems, IoT simulation, sensor communication, automation logic, and wireless monitoring.

---

## Projects

### Project 1 – Smart Environmental Monitor
The Smart Environmental Monitor is an ESP32-based system that measures temperature and humidity using the DHT22 sensor. The system periodically acquires environmental data and displays the measured values on the Serial Monitor. This project demonstrates sensor interfacing, GPIO configuration, and real-time environmental monitoring.

### Project 2 – Automated Irrigation Controller
This project implements an automated irrigation system using ESP32, a soil moisture sensor simulation (potentiometer), LED pump indicator, LCD display, and buzzer alert system. The system continuously monitors soil moisture levels and automatically controls irrigation based on threshold values. This project demonstrates automation logic, actuator control, and smart agriculture concepts.

### Project 3 – Cloud-Connected Security Node
The Cloud-Connected Security Node uses ESP32 and an HC-SR04 ultrasonic sensor to monitor the distance of nearby objects and detect intrusions. When an object crosses the defined threshold distance, an alert is generated using LED, buzzer, and LCD display. Sensor data can be monitored locally and prepared for cloud-based IoT telemetry using ThingSpeak.

### Project 4 – Edge-Computing Smart Home Appliance
This project presents an intelligent edge-computing smart home safety system using ESP32, PIR motion sensor, gas sensor simulation, LEDs, buzzer, LCD display, and hardware interrupts. Motion detection activates smart lighting, while unsafe gas levels immediately trigger emergency override, alarm alerts, and fail-safe protection. This project demonstrates interrupt-driven embedded systems and real-time safety logic.

---

## Technologies Used
- ESP32 Development Board
- Arduino IDE
- Embedded C / C++
- DHT22 Temperature & Humidity Sensor
- Potentiometer (Sensor Simulation)
- HC-SR04 Ultrasonic Sensor
- PIR Motion Sensor
- I2C LCD Display
- Piezo Buzzer
- Wokwi Simulator
- ThingSpeak Cloud Platform
- GPIO Interrupts
- Sensor Interfacing

---

## Repository Structure
```text
decodelabs_tasks/
│
├── task1_project1/
│   ├── report.pdf
│   ├── code.ino
│   ├── circuit.png
│   └── output.png
│
├── task2_project2/
│   ├── report.pdf
│   ├── code.ino
│   ├── circuit.png
│   └── output.png
│
├── task3_project3/
│   ├── report.pdf
│   ├── code.ino
│   ├── circuit.png
│   └── output.png
│
└── task4_project4/
    ├── report.pdf
    ├── code.ino
    ├── circuit.png
    └── output.png
```

---

## Author
**Gokul K**  

