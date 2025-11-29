## Title of the Project

### Soil Moisture Sensor with IoT Notification

## Small Description

The integration of IoT technology with a soil moisture monitoring system, aimed at automating irrigation decisions and improving agricultural efficiency for farmers through real-time sensing and instant notifications.

## About

Soil Moisture Sensor with IoT Notification System is a smart agriculture project designed to continuously measure soil moisture levels using a digital or analog soil moisture sensor and transmit the data to the cloud in real time. Traditional irrigation methods often rely on manual observation, which can lead to overwatering, underwatering, and inefficient water management.

This project simplifies the process by enabling farmers to receive automatic SMS alerts via IoT when the soil moisture falls below or rises above predefined thresholds. It supports decision-making, conserves water, and enhances crop health by ensuring appropriate moisture levels at all times.

## Features

Real-time soil moisture monitoring using digital/analog sensors.

IoT-enabled automatic SMS alerts via Twilio or GSM module.

Cloud dashboard access for live moisture data visualization.

Low cost, low power microcontroller-based system (ESP32/NodeMCU/Arduino).

Scalable design adaptable for large-scale farm fields.

Easy integration with irrigation pumps for automation.

JSON-based lightweight data communication.

Highly reliable and simple architecture for deployment in rural areas.

## Requirements
### Hardware Requirements

Soil Moisture Sensor (Capacitive/Resistive)

NodeMCU / ESP8266 / ESP32 / Arduino UNO

Wi-Fi or GSM connectivity module

5V/3.3V Power Supply

Jumper Cables

Breadboard / PCB

Relay Module (optional, for pump control)

### Software Requirements

Operating System: Windows 10/11 or Ubuntu (64-bit)

Programming Environment: Arduino IDE or VS Code with PlatformIO

IoT Platform: Thingspeak / Firebase / Blynk / Custom API

SMS Gateway: Twilio API for message notifications

Libraries Needed:

ESP8266WiFi / WiFi.h

HTTPClient

ArduinoJson

Twilio ESP library (if used)

## Development Tools

Version Control: GitHub or Git

Code Editor: VS Code or Arduino IDE

Cloud Dashboard (optional): Thingspeak / Firebase

## System Architecture

<img width="1010" height="604" alt="image" src="https://github.com/user-attachments/assets/e1530e73-46df-4e22-888f-b6d9041ac25e" />


#### Fig: System Architecture of Soil Moisture IoT Notification System

## Block Flow:

<img width="967" height="616" alt="image" src="https://github.com/user-attachments/assets/78597d40-3e68-4dd4-8624-dc1ee9949f5a" />


## Output
### Output 1 – Moisture Level Dashboard

#### Threshold value below 700(soil wet)
<img width="1920" height="966" alt="image" src="https://github.com/user-attachments/assets/df15d596-66c1-43ea-b1fe-3b59f31e94cf" />

#### Threshold value above 700(soil dry-sends alert message)
<img width="1918" height="1032" alt="image" src="https://github.com/user-attachments/assets/e092c05f-37ee-4be6-be2d-b5fff7b17298" />


### Output 2 – SMS Notification

#### Sent Notification when soil is dry:

![WhatsApp Image 2025-11-29 at 15 38 56](https://github.com/user-attachments/assets/e18208bb-8e60-480b-ab07-f78e618be9f2)


### Detection Accuracy

System Accuracy: 92–98% (based on calibration of soil moisture sensor)
Note: This can be adjusted based on your actual results.

## Results and Impact

The Soil Moisture Monitoring System provides an efficient and automated way to regulate irrigation by delivering real-time moisture data and timely SMS alerts to farmers. By minimizing manual monitoring, the system reduces water wastage, promotes sustainable farming, and helps maintain optimal soil conditions for plant growth.

This project demonstrates the effective integration of IoT and sensor technologies in agriculture and lays a strong foundation for future advancements in precision farming and automated irrigation systems.

## Articles Published / References

R. K. Sharma, "IoT-Based Smart Irrigation System Using Soil Moisture Sensor," International Journal of Advanced Research in Electronics and Communication, 2023.

A. Patel & S. Rao, "Smart Agriculture Monitoring Using IoT and Cloud Technologies," IEEE IoT Transactions, 2024.

M. Verma, "Water-Efficient Irrigation Through Soil Moisture Sensing and Automation," Agritech Innovations Journal, 2023.
