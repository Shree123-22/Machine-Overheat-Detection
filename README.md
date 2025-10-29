# Machine Overheat Detection with Alert

This project is about building a simple IoT system that can detect when a machine starts overheating and send alerts to the user.  
It was developed as part of my Electronics and Communication Engineering coursework to explore how sensors and connectivity can improve safety in small industrial setups.

---

## Overview
The system uses a **NodeMCU (ESP8266)** board and a **DS18B20 temperature sensor** to measure temperature in real time.  
When the temperature crosses a set limit, it automatically sends alerts using:
- **Twilio API** for SMS messages  
- **Blynk App** for live updates  
- **GSM module** for alerts when Wi-Fi is unavailable

Programming was done in **C** using the Arduino IDE. The project focuses on automation, safety, and reliability.

---

## How It Works
1. The DS18B20 sensor continuously reads the machine’s temperature.  
2. NodeMCU checks if the temperature is above the safe threshold.  
3. If it is, an SMS and app notification are sent instantly.  
4. The system goes back to monitoring once the temperature drops.

---

## Features
- Real-time temperature monitoring  
- Dual alert system (Wi-Fi + GSM)  
- Low-cost and easy to set up  
- Reduces the risk of equipment damage  

---

## Future Scope
- Add data logging for trend analysis  
- Include email alerts  
- Integrate predictive maintenance using temperature history  

---

## About
**Created by:** Shreedevi Bagewadi  
B.E. Electronics and Communication Engineering  
📧 [shreekaviraj26@gmail.com](mailto:shreekaviraj26@gmail.com)
