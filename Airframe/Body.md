# ✈️ Airframe Specifications

## 📏 Fuselage
- **Length:** 80 cm  
- **Type:** Lightweight modular fuselage  
- **Material:** Foamboard / Composite hybrid  
- **Internal Space:**  
  - Pixhawk / Flight Controller bay  
  - Battery compartment (4S 8000 mAh)  
  - Raspberry Pi + Camera mount  
  - Wiring channel for servo + ESC routing  

---

## 🕊️ Wing Configuration
### **Delta Wing**
- **Total Wingspan:** 2.0 meters  
- **Planform:** Delta (swept leading edges, wide root chord)  
- **Wing Type:** Fixed wing with tilt-rotor integration  
- **Material:**  
  - E-Glass + epoxy / foam core  
  - Carbon spar reinforcement  

### **Wing Features**
- **Control Surfaces:**  
  - 2× Ailerons  
  - 1× Elevator (tail-mounted or elevon configuration depending on setup)  

- **Reinforcement:**  
  - Carbon fiber tube spar (primary)  
  - Additional fiberglass ribs near tilt-rotor pivots  

---

## ⚙️ Tilt-Rotor Integration
- **Tilt Mechanism:**  
  - Dual-motor tilt on each wing root  
  - Controlled by 2× MG995 metal-gear servos  
- **Motor Type:** ReadytoSky 3115 900KV  
- **ESC:** 30A ReadytoSky OPTO  
- **Purpose:**  
  - VTOL lift (vertical)  
  - Forward flight propulsion (horizontal)  

---

## 📷 Payload & Sensors
- **Camera:** Raspberry Pi Camera Module V2 (8 MP, nose-mounted)  
- **Obstacle Sensor:** GYUS42 Long-range Ultrasonic  
- **Telemetry:** 433 MHz Radio Telemetry Kit (2–3 mile range)  

---

## 🔋 Power
- **Battery:** 4S 14.8V 8000 mAh LiPo (×2)  
- **Connector Standard:** XT60  

---

## 🧩 Summary
This airframe is a **compact 80 cm fuselage + 2 meter delta wing VTOL hybrid**, designed for:  

- Stable fixed-wing cruising  
- Efficient hover-to-forward transition  
- High lift surface area  
- FPV and onboard compute (Raspberry Pi)  
- Long-range telemetry  

The delta wing ensures **high stability**, **low stall risk**, and **high payload area**, making it ideal for a tilt-rotor VTOL research platform.


