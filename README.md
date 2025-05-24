# ⛽ Fleet Fuel Management System

A smart IoT-enabled system to automate vehicle fuel level monitoring, deliver real-time alerts, guide drivers to the nearest petrol stations, and enhance fuel efficiency and safety through GSM and GPS integration.

---

## 📄 Abstract

The Fleet Fuel Management System automates the monitoring of vehicle fuel levels and simplifies the process of finding nearby petrol stations. A fuel level sensor continuously tracks the petrol level, and when it drops below a threshold, the system alerts the driver via a dashboard interface. Upon driver confirmation, it uses GPS to locate nearby petrol stations and sends the driver's name, contact, and location to the selected station. This ensures timely refueling, prevents breakdowns, and supports a seamless and safe driving experience.

---

## ❗ Problem Statement

- Manual fuel level checks are unreliable and inconvenient.
- Drivers lack real-time alerts for low fuel.
- Finding nearby petrol stations can be difficult in unfamiliar areas.
- Running out of fuel poses serious safety risks.

---

## ✅ Solution Overview

- **Continuous Fuel Monitoring**: A fuel sensor measures fuel levels and sends real-time data to the microcontroller (MCU).
- **Automated Alerts**: Drivers are alerted via the dashboard when fuel falls below the threshold.
- **Location-Based Station Discovery**: The GSM module enables GPS-based search of nearby petrol stations.
- **Secure Communication**: On confirmation, the driver’s information is sent to the selected petrol station.
- **Customizable and Scalable**: Thresholds can be user-defined; the system can support multiple vehicles.

---

## 🧠 Features

- Real-time fuel monitoring
- Low-fuel alert system
- GPS integration for locating petrol stations
- GSM module for remote communication
- Permission-based alert transmission
- Dedicated dashboard interface
- Custom fuel alert thresholds
- Scalable to fleet-level deployment

---

## 🛠 System Components

- Fuel Level Sensor
- Microcontroller Unit (MCU)
- LCD Dashboard Interface
- GPS Module
- GSM Module
- Buttons/Controls
- Communication System
- Backend Database

---

## ⚙️ System Workflow

1. Fuel level is read by the sensor.
2. Data is sent to MCU for analysis.
3. If fuel < threshold, alert is triggered.
4. Driver can dismiss or find petrol stations.
5. If accepted, GPS determines nearby stations.
6. Driver selects station → details sent via GSM.
7. Monitoring continues post-action.

---

## 📜 Core Claims

- **Claim 1**: Real-time fuel monitoring and alerting when fuel falls below threshold.
- **Claim 2**: GPS-based station discovery and driver-station communication.
- **Claim 3**: Full integration of sensor, GSM, GPS, and dashboard interface.
- **Claim 4**: Permission-based notification before contacting petrol stations.
- **Claim 5**: Improves fuel efficiency by timely refueling.
- **Claim 6**: Enhances safety by avoiding fuel shortages in remote areas.
- **Claim 7**: Dedicated in-vehicle UI for alerts and instructions.
- **Claim 8**: Integrated with petrol station network for faster service.
- **Claim 9**: Scalable across fleets and customizable for different networks.
- **Claim 10**: Thresholds can be adjusted per user or vehicle specs.

---

## 🔮 Future Enhancements

- Integration with national petrol station databases
- Encrypted data communication
- Support for electric vehicles (EVs)
- Companion mobile application for remote monitoring
- AI-based predictive fuel consumption and routing

---

> “Fuel emergencies shouldn’t be a surprise. This system ensures they never are.”

