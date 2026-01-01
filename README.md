#  Smart Soil Moisture Irrigation System

An Automatic Dual Sensor Irrigation System using Arduino that intelligently waters plants by monitoring real-time soil moisture levels to prevent over-watering and under-watering.

---

##  Project Overview

This project automates irrigation using two soil moisture sensors and a water pump controlled through a relay module.  
The system continuously monitors soil conditions and supplies water only when required, helping to save water and improve plant health.

---

##  Key Features

- Dual soil moisture sensing  
- Automatic pump control  
- Prevents water wastage  
- Low power consumption  
- Easy to build and maintain  
- Suitable for gardens, farms, and greenhouses  

---

##  Hardware Requirements

| Component | Quantity |
|----------|---------|
| Arduino Uno | 1 |
| Soil Moisture Sensor | 2 |
| Relay Module | 1 |
| DC Water Pump | 1 |
| External Power Supply | 1 |
| Jumper Wires | As required |

---

##  Pin Connections

| Arduino Pin | Connected Device |
|------------|------------------|
| A0 | Soil Moisture Sensor 1 |
| A1 | Soil Moisture Sensor 2 |
| D8 | Relay IN |
| 5V | Relay VCC |
| GND | Relay GND |

---

##  Working Principle

1. The Arduino reads both moisture sensors.  
2. It calculates the average moisture value.  
3. If the soil is dry, the water pump turns ON.  
4. If the soil is wet, the pump turns OFF.  
5. This process repeats automatically every few seconds.

---

##  Software Requirements

- Arduino IDE  
- USB Cable  

---

##  Calibration

| Soil Condition | Typical Sensor Reading |
|---------------|-----------------------|
| Wet Soil | 300 – 400 |
| Dry Soil | 650 – 800 |

Set the threshold value between wet and dry readings (recommended ≈ 550).

---

##  Installation Steps

1. Connect all components as per the wiring table.  
2. Upload `irrigation.ino` to the Arduino board.  
3. Open Serial Monitor and observe sensor values.  
4. Adjust the threshold for best performance.  
5. Your smart irrigation system is now ready to use 🌿  

