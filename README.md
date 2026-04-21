# ⚡ Shared Renewable Energy System – Communication Interface

## 📌 Overview
This project focuses on the design and implementation of a communication interface for a peer-to-peer energy trading platform in Lebanon. Due to frequent power outages, households increasingly rely on solar energy systems. This project enables efficient energy sharing within microgrids.

---

## 🚀 Key Features
- 🔌 Smart Meter Integration for real-time monitoring  
- 🔁 Peer-to-Peer Energy Trading support  
- 📡 Hybrid Communication System:
  - RS485 (Inverter ↔ Smart Meter)
  - LoRaWAN / Wi-Fi (Smart Meter ↔ Data Concentrator)
- 🧠 SCADA System for centralized monitoring  
- ⚙️ Remote control using RTU and relay switches  

---

## 🏗️ System Architecture
The system consists of:

- **Inverters** – Convert DC to AC power  
- **Smart Meters** – Measure energy consumption and production  
- **Data Concentrator** – Collects and uploads data to cloud  
- **RTU (Remote Terminal Unit)** – Controls inverters  
- **SCADA System** – Monitors and manages the grid  

---

## 🔍 Technologies & Protocols
- RS485 / RS232  
- LoRaWAN  
- Wi-Fi / 3G  
- DLMS/COSEM  
- Modbus  

---

## ⚡ Key Challenges
- Limited access to inverter APIs  
- Hardware availability constraints  
- Grid instability and infrastructure limitations  

---

## 💡 Final Solution
A hybrid architecture combining smart meters, data concentrators, and RTUs.  
RTUs control relay switches to safely disconnect inverters when needed, ensuring grid stability without relying on proprietary inverter APIs.

---

## 🔮 Future Work
- Improve system security and data protection  
- Develop a user-friendly interface  
- Scale the system for larger communities  
