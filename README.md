# 🚀 AeroLinkers Hardware (PoC_V1)

## 📌 Overview
This repository contains the **hardware design for AeroLinkers Design Version 1**, designed at **K.S. Rangasamy College of Technology**.

The system integrates:
- Microcontroller (Nordic nRF series)
- Wi-Fi module
- Power management system (PMIC + LDO)
- IMU sensor
- Audio subsystem
- Haptic driver
- Display interface

---

## 🧠 System Architecture
The system is divided into:
- Power
- MCU
- WiFi
- IMU + Haptic + Audio + Display

---

## ⚡ Power Management
### Components:
- PMIC: NPM1300
- LDO: TPS76201

### Outputs:
- 1.8V (VAUD)
- 3.3V (VPER / MCU)

---

## 🧠 Microcontroller Unit (MCU)
### MCU Used:
- nRF5340

### Interfaces:
- I2C
- SPI
- PWM
- QSPI

---

## 📡 WiFi Module
### Module:
- nRF7002

### Features:
- 2.4 GHz connectivity
- SPI/QSPI interface

---

## 🎧 Audio Subsystem
### IC:
- SGTL5000

### Features:
- I2S interface
- Headphone output

---

## 📍 IMU Sensor
### Sensor:
- LSM6DSOX

---

## 📳 Haptic Driver
### IC:
- DRV2605

---

## 🖥️ Display Interface
- SPI-based communication

---

## 🔄 System Workflow
1. Power regulation
2. MCU initialization
3. Sensor data acquisition
4. Communication via WiFi
5. Output via display/audio/haptic

---

## 📂 Repository Structure
```
aerolinkers-hw/
│── schematics
│── pcb
│── README.md
```

---

## 🛠️ Tools Used
- KiCad
- Embedded C / Zephyr

---

## 🎯 Applications
- IoT Devices
- Wearables
- Embedded Systems

---

## 👨‍💻 Developed By
AeroLinkers Team
