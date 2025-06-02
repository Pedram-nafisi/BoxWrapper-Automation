# BoxWrapper Automation Project

A complete PLC-based automation system for a box wrapping machine — designed, programmed, and documented from scratch. This project demonstrates core industrial automation skills, including control logic, electrical protection, sensor integration, HMI design, and power calculation.

---

## 🚀 Features

- Two motors:
  - Up/Down motor (0.37 kW, 3-phase) controlled by VFD
  - Rotation motor (0.55 kW, 3-phase) controlled by VFD
- Limit switches for high/low endpoints
- Proximity sensors:
  - Stretch detection
  - Rotation count
  - Wrap-empty check
- Relay control (24VDC)
- HMI panel with real-time control and monitoring
- Power and protection design (cabling, MCB, power supply sizing)

---

## 🗂 Project Structure

BoxWrapper-Automation/
├── PLC_Code/ # Ladder logic code or screenshots
├── HMI_Design/ # HMI panel design (CODESYS WebVisu)
├── Docs/ # Electrical documentation (PDFs for MCB, sensors, etc.)
├── Images/ # Visuals: control diagram, wiring layout, flowcharts
├── README.md # Project description (this file)
---

## 🛠 Tools & Technologies

- **CODESYS v3.5** for PLC programming and HMI design
- **24VDC control system**
- **380V 3-phase VFDs** for motor control
- **Proximity & limit switches**
- **HMI visualization** built with WebVisu
- **Power analysis** for main circuit breaker and control components

---

## 💡 Control Logic Overview

- Sequential control using PLC ladder logic
- Rotation motor runs while film wraps the box
- Up/Down motor moves the stretch unit vertically
- Sensors track limits and count rotations
- HMI allows control of speeds and system state
- System stops automatically after 3 wrapping cycles

---

## 📷 Screenshots

> HMI Panel Design  
![HMI Panel](Images/HMI_Design/BoxWrapper_Panel.png)

> Control Algorithm Flowchart  
![Control Flowchart](Images/Overview/PLC_Algorithm_Overview.jpg)

> Ladder Logic Example  
![Ladder Logic](Images/PLC_Code/Ladder_Screenshot.png)

---

## 👨‍💻 Developed By

**Pedram Nafisi**  
Industrial Automation & Control Engineer  
📧 pedram.nafisi@yahoo.com  
🔗 [LinkedIn](https://www.linkedin.com/in/pedram-nafisi)

---

## 📌 Notes

- This project was built entirely from scratch for demonstration, learning, and portfolio purposes.
- Suggestions, collaborations, or feedback are always welcome.
