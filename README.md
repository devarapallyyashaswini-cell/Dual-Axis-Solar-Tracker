# <h1 align="center">🌞 DUAL-AXIS SOLAR TRACKING SYSTEM 🌞</h1>

<p align="center">
An automatic Dual-Axis Solar Tracking System that continuously aligns a solar panel with the sun using two LDR sensors, a TDA2822 IC, and DC geared motors to improve solar energy collection.
</p>

---

# 📑 Table of Contents

- Overview
- Project Images
- Problem Statement
- Tools and Technologies
- Hardware Components
- Circuit Diagram
- System Architecture
- Working Methodology
- How to Run This Project
- Future Improvements
- Project Structure
- Author & Contact

---

# 📖 Overview

This project presents the design and implementation of a **Dual-Axis Solar Tracking System** that automatically adjusts the orientation of a solar panel in both horizontal (azimuth) and vertical (elevation) directions to maximize sunlight exposure.

The system uses **two Light Dependent Resistors (LDRs)** to detect differences in sunlight intensity. These signals are processed using a **TDA2822 IC**, which controls **two DC geared motors** responsible for rotating the panel until it faces the direction of maximum sunlight.

The project demonstrates a simple and low-cost approach to automatic solar tracking suitable for educational purposes and small-scale renewable energy applications.

---

# 📷 Project Images

## Prototype

<p align="center">
<img src="images/Prototype.jpg" width="600">
</p>

## Final Setup

<p align="center">
<img src="images/Final_Model.jpg" width="600">
</p>

---

# ❓ Problem Statement

Conventional solar panels remain fixed after installation and cannot continuously face the sun. As the sun changes position throughout the day, the panel receives less direct sunlight, reducing the amount of energy generated.

This project aims to develop a simple, affordable Dual-Axis Solar Tracking System that automatically adjusts the panel position using light sensors and DC motors to maintain maximum exposure to sunlight.

---

# 🛠 Tools and Technologies

## Hardware

- Solar Panel
- 2 × LDR Sensors
- TDA2822 IC
- 2 × DC Geared Motors
- 9V Battery
- Connecting Wires
- Mounting Frame

## Software

- Fritzing
- Microsoft Word
- Microsoft PowerPoint

## Technologies

- Solar Energy
- Renewable Energy Systems
- Embedded Hardware
- Analog Signal Processing

---

# 🔩 Hardware Components

| Component | Quantity |
|-----------|----------|
| Solar Panel | 1 |
| LDR Sensor | 2 |
| TDA2822 IC | 1 |
| DC Geared Motor | 2 |
| 9V Battery | 1 |
| Connecting Wires | As Required |
| Mounting Frame | 1 |

---

# ⚡ Circuit Diagram

The following circuit shows the hardware connections used in the project.

<p align="center">
<img src="circuit/Circuit_Diagram.png" width="750">
</p>

### Circuit Description

- Two LDR sensors detect the direction of maximum sunlight.
- The voltage difference between the LDRs is processed by the TDA2822 IC.
- The IC drives the DC geared motors.
- The motors rotate the solar panel in horizontal and vertical directions until balanced illumination is achieved.
- The circuit is powered using a 9V battery.

---

# 🏗 System Architecture

```
             Sunlight
                 │
                 ▼
          Two LDR Sensors
                 │
                 ▼
            TDA2822 IC
                 │
                 ▼
         DC Geared Motors
                 │
                 ▼
      Dual-Axis Panel Movement
                 │
                 ▼
      Maximum Sunlight Exposure
```

---

# ⚙ Working Methodology

1. Assemble the supporting frame.
2. Mount the solar panel.
3. Install the two LDR sensors.
4. Connect the LDRs to the TDA2822 IC.
5. Connect the two DC geared motors.
6. Connect the 9V battery.
7. Place the system under sunlight.
8. The LDRs continuously detect light intensity.
9. The TDA2822 IC processes the signal difference.
10. The motors rotate the panel until it faces the sun.
11. The process repeats automatically throughout the day.

---

# ▶ How to Run This Project

### Step 1 — Hardware Assembly

- Mount the solar panel.
- Install the two LDR sensors.
- Connect the TDA2822 IC.
- Connect the DC geared motors.
- Connect the 9V battery.

### Step 2 — Testing

- Place the setup under direct sunlight.
- Power ON the circuit.
- Observe the movement of the solar panel.
- Verify smooth tracking in both axes.

---

# 🚀 Future Improvements

- ESP32-based controller
- IoT monitoring
- Mobile application
- Weather monitoring
- MPPT integration
- Solar data logging

---

# 📂 Project Structure

```
Dual-Axis-Solar-Tracking-System/
│
├── README.md
│
├── hardware/
│   └── materials.md
│
├── circuit/
│   └── Circuit_Diagram.png
│
└── images/
```

---

# 👩‍💻 Author & Contact

**Project:** Dual-Axis Solar Tracking System

**Author:** Yashaswini Devarapally

**Institution:** VNR VJIET, Hyderabad

**Department:** Electronics and Communication Engineering (ECE)

📧 **Email:** devarapally.yashaswini@gmail.com

🐙 **GitHub:** https://github.com/devarapallyyashaswini-cell

💼 **LinkedIn:** https://www.linkedin.com/in/yashaswini-devarapally-93960039a/

---

⭐ **If you found this project helpful, consider giving it a Star on GitHub!**
