# **VTOL RC Plane — Pixhawk + Raspberry Pi**

An autonomous **VTOL (Vertical Takeoff and Landing) fixed-wing aircraft** built using a Pixhawk flight controller and a Raspberry Pi companion computer.  
Developed as a **4th Semester Aerospace Engineering project**, planned for completion in **10 weeks**.

---

## ✈️ 1. Project Overview

This project aims to build a small-scale intelligent VTOL aircraft capable of:

- Vertical takeoff and landing  
- Stable forward flight in fixed-wing mode  
- Autonomous GPS waypoint navigation  
- Real-time HD video streaming  
- Basic obstacle detection  
- Weekly documentation of results, tests, and updates

---

## 🔧 2. Main Hardware Components

- **Pixhawk 2.4.8** (ArduPlane RC Plane enabled)  
- **Raspberry Pi 4** (4GB / 8GB)  
- **Fixed-wing foam aircraft** (~2 m wingspan)  
- **Motors & Servos**
  - 2× 900 KV brushless motors + 30 A ESCs  
  - 6× MG995 servos (ailerons, elevator, rudder, tilt)
- **Battery:** 4S LiPo (≈ 6000 mAh)  
- **Sensors:** NEO-6M GPS + compass, HC-SR04 ultrasonic  
- **Camera:** Raspberry Pi Camera v2  
- **Telemetry:** 900 MHz / 433 MHz radio  
- **RC transmitter + receiver** (PPM/SBUS)

A complete Bill of Materials will be available in:  
`hardware/bom_components.md`

---

## 🧠 3. Software Stack

- **Flight Controller:** ArduPlane (RC Plane mode enabled)  
- **Companion OS:** Raspberry Pi OS (64-bit)  
- **Programming:** Python  
- **Libraries & Tools:**
  - DroneKit / pymavlink  
  - MAVLink telemetry  
  - OpenCV (vision experiments)  
  - GStreamer (video streaming)  
  - Mission Planner (GCS)

---

## 📁 4. Repository Structure

```text
vtol-quadplane-raspberrypi-pixhawk/
│
├── README.md                   # Project overview (this file)
│
├── hardware/
│   └── bom_components.md       # Components list + links + prices
│
├── firmware/
│   ├── pixhawk/                # Parameters, missions, logs
│   └── raspberry_pi/           # Python scripts (autonomy, vision)
│
├── docs/
│   └── design_notes.md         # Design, diagrams, calculations
│
├── tests/                      # Bench tests, flight tests
│
└── logs/                       # Bench & flight test logs
