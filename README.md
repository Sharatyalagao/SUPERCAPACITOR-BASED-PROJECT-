# SUPERCAPACITOR-BASED-PROJECT-
Supercapacitor-based UPS providing ~10s instant backup for low-power systems. Uses a 10F supercapacitor, LM7805 regulators, and diode OR-ing for seamless switching. Arduino monitors voltage and displays status. Designed and tested using Tinkercad simulation.
UPS  

[Arduino](https://img.shields.io/badge/Arduino-ATmega328P-blue)
![Simulation](https://img.shields.io/badge/Simulation-Tinkercad-orange)
![Backup](https://img.shields.io/badge/Backup-10s-green)
![Status](https://img.shields.io/badge/Status-Working-success)
![License](https://img.shields.io/badge/License-Educational-lightgrey)

## 📌 Overview  

This project implements a Supercapacitor-Based Uninterruptible Power Supply (UPS) that provides instant ~10-second backup for low-power systems.  

It uses a 10F supercapacitor for fast charge and discharge, ensuring seamless power transition using diode-based power OR-ing. An Arduino Uno monitors voltage and displays system status on a 16×2 LCD.  

The complete design is developed and tested using Tinkercad simulation.  

## 🚀 Features  

- Instant backup (~10s)  
- Zero-delay switching  
- Fast charging and discharging  
- High efficiency and long lifecycle  
- Real-time monitoring using Arduino  
- Fully simulated in Tinkercad  

## 🔧 Components  

- Arduino Uno (ATmega328P)  
- Supercapacitor (10F, 5.5V)  
- LM7805 Voltage Regulators  
- Diode (1N4007)  
- 9V Power Supply  
- 16×2 LCD Display  
- Resistors and Capacitors  
- LED and Push Button  

## ⚙️ Working  

During normal operation, the power supply runs the load and charges the supercapacitor. During power failure, the supercapacitor instantly supplies power without interruption. The Arduino detects voltage drop and updates the system status.  

## 📊 Key Equations  

Backup time:  
`t = C (Vstart - Vmin) / I`  

Energy stored:  
`E = 1/2 × C × V²`  

## 🧪 Simulation  

Platform: Tinkercad  

- Charging behavior  
- Discharge during power failure  
- Seamless switching  
- Backup achieved: ~10 seconds  

## 📷 Screenshots  

(Add your Tinkercad circuit images here)  

## 🔮 Future Scope  

- Hybrid system (battery + supercapacitor)  
- Solar integration  
- IoT-based monitoring  

## 📄 License  

Educational use only
