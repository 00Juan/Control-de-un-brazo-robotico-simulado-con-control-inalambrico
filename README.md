# Wireless Control of a Simulated Robotic System 🤖📡

This project is the result of my final thesis for the **Industrial Automation and Robotics** CFGS (Vocational Training Degree), completed at **IES Politécnico Hermenegildo Lanz (Granada, Spain)**.

## 🧠 Overview

The system allows full control of a simulated ABB robotic arm using a wireless physical interface based on a **Wii Nunchuk** controller. The communication and control chain combines **Arduino, ESP32, TIA Portal, WinCC**, and **ABB RobotStudio**, using both standard and custom protocols.

---

## 🔧 Technologies Used

- **Hardware**
  - ESP32 microcontrollers (2x)
  - Arduino UNO
  - Wii Nunchuk (joystick, accelerometer, buttons)
  - LCD display 16x2 (I2C)
  - ENC28J60 Ethernet module
  - LiPo battery + voltage booster
  - LEDs, resistors, protoboards

- **Software**
  - [RobotStudio (ABB)](https://new.abb.com/products/robotics/es/robotstudio)
  - [TIA Portal V16 (Siemens)](https://new.siemens.com/global/en/products/automation/industry-software/automation-software/tia-portal.html)
  - PLCSIM Advanced
  - WinCC RT Advanced
  - Arduino IDE + PlatformIO
  - Custom OPC Server: **ABB IRC5 OPC**

---

## 🔄 Communication Protocols

- **I2C**: Sensor communication with Wii Nunchuk  
- **ESP-NOW**: Wireless data transfer between ESP32 devices  
- **J2WC**: Custom 2-wire communication protocol  
- **Modbus TCP/IP**: Arduino to Siemens PLC (via ENC28J60)  
- **OPC**: PLC <-> ABB RobotStudio data exchange  
- **SCADA / HMI**: Built in WinCC

---

## 🎯 Main Features

- Real-time wireless control of a robotic arm simulation
- Configurable HMI interface with status indicators
- Latency and cycle time monitoring
- Full code modularity and object-oriented logic blocks (TIA Portal)
- Open-source, low-cost components

---

## 🎥 Demo

👉 [Watch the demo video here](https://youtu.be/hsgEAXDb1Do)  

---

## 📄 Full Report

📥 [Download the final project report (PDF)](https://github.com/00Juan/robotstudio-wireless-control/blob/main/TFC_ARI_Juan_Estevez_Delgado.pdf)  

---

## 👨‍🏫 Acknowledgements

- **IES Politécnico Hermenegildo Lanz** (Granada, Spain)  
- My tutors and professors from the Electricity Department  
---

## 📃 License

MIT License. Feel free to use, modify, and adapt this project for learning or development purposes. Credit appreciated!

---

## 📫 Contact

Juan Estévez Delgado  
📧 juanesteveus@gmail.com 
🌐 https://www.linkedin.com/in/juanestevezdelgado/

---
