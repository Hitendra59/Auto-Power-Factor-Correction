# Auto-Power-Factor-Correction
Arduino Uno-based Auto Power Factor Correction system that improves power factor by automatically switching capacitor banks. Includes code, circuit diagrams, and simulations to enhance efficiency, reduce reactive power losses, and ensure reliable power system performance.
# Auto Power Factor Correction (APFC) System

## Overview
This project implements an Auto Power Factor Correction (APFC) system using Arduino Uno, relays, and capacitor banks.  
It continuously monitors the power factor of inductive loads and automatically switches capacitors to maintain it near unity, improving system efficiency and power quality.

## Key Features
- Real-time power factor monitoring  
- Automatic capacitor bank switching  
- Improved power factor (from 0.72 → 0.96)  
- Reduction of reactive power losses  
- Enhances efficiency of AC loads and industrial systems  

## Components & Tools
- Hardware: Arduino Uno, Relays, Capacitor Banks, Current Sensor (ACS712), Voltage Sensor (ZMPT101B)  
- Software: Arduino IDE, Proteus (circuit design), MATLAB/Simulink (simulation)  

## Repository Contents
- `Arduino_Code/` → Embedded C code for APFC control logic  
- `Circuit_Diagram/` → Circuit design files & schematics  
- `Simulation/` → MATLAB/Simulink models & test cases  
- `Report/` → Documentation & project report  

## How It Works
1. The system measures load voltage & current.  
2. Calculates power factor (cos φ).  
3. If PF falls below threshold, Arduino switches capacitor banks via relays.  
4. Restores PF closer to unity and reduces reactive power flow.  

## Results
- Unity power factor achieved under varying inductive load conditions  
- Reduced kVA demand, improved load efficiency  
- Demonstrated practical application of Power Electronics & Machines concepts  

## More Projects
For more Electrical Engineering & Power Electronics projects: [My GitHub Profile](https://github.com/yourprofile)

