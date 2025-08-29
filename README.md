# MATLAB-FIS-System_-Cruise-Control-System
Cruise control system for vehicles using MATLAB to simulate a Fuzzy interference system using parameters to control acceleration and simulate cruise control like outout. 
# 🚗 Fuzzy Cruise Control System (MATLAB)

This project implements a **Fuzzy Logic-based Cruise Control System** using MATLAB’s Fuzzy Logic Toolbox.  
It adjusts vehicle acceleration smoothly and human-like, based on:
- **Traffic Distance (m)** – distance to the car ahead
- **Speed Difference (km/h)** – relative speed between ego and lead vehicle

## 📌 Features
- Fuzzy Inference System (Mamdani type)
- Two inputs (Distance, Speed Difference)
- One output (Acceleration Command)
- 9 well-defined fuzzy rules
- Smooth & human-like decision-making

## 📊 System Design
Inputs:
- **Traffic Distance:** Close, Medium, Far
- **Speed Difference:** Negative, Zero, Positive

Output:
- **Acceleration Command:** StrongBrake, LightBrake, Maintain, LightAccelerate, StrongAccelerate

## 🔧 How to Run
1. Open MATLAB.
2. Load the `.fis` file:
   ```matlab
   fis = readfis('neuralnetwork.fis');
