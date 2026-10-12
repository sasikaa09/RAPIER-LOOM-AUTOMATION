# Rapier Loom Automation Using PLC, HMI and IoT

## 1. Project Overview
The Rapier Loom Automation project demonstrates a PLC-based monitoring and control concept for textile loom operations. It combines ladder logic, sensor status monitoring, an HMI interface, and an Adafruit IO dashboard.

## 2. Objectives
- Monitor gripper, cutter, and suction sensor status.
- Check yarn tension against configured minimum and maximum limits.
- Monitor pressure-related conditions.
- Display sensor and actuator status through an HMI.
- Visualize selected monitoring parameters using an IoT dashboard.

## 3. Technologies Used
- PLC programming software: SELEC PLC software
- Programming method: Ladder Logic
- HMI design software: DOPSoft
- IoT platform: Adafruit IO
- Sensors and outputs: As represented in the uploaded screenshots

## 4. System Modules

### 4.1 PLC Ladder Logic
The ladder logic screenshots show start/stop control, sensor conditions, yarn tension limit checks, pressure checking, and digital output logic.

### 4.2 HMI
The HMI screenshot presents start and stop controls, gripper/cutter/suction sensor indications, actuator values, and a fault status display.

### 4.3 IoT Dashboard
The Adafruit IO screenshot presents monitoring widgets for sensor status, yarn tension, encoder angle, and suction pressure.

## 5. Project Screenshots
The repository contains the following visual evidence:

- `LADDER 1.png` — PLC ladder logic, first section
- `LADDER 2.png` — Tension and pressure logic
- `LADDER 3.png` — Sensor conditions and output logic
- `HMI.png` — HMI design
- `ADAFRUIT.png` — Adafruit IO dashboard

## 6. Current Project Status
This repository currently contains five project screenshots and documentation. The original PLC source project file has not been provided. Therefore, a complete program compilation, hardware execution, and end-to-end functional validation cannot be confirmed from these screenshots alone.

## 7. Future Work
- Add the original PLC source project or supported export files.
- Document PLC input/output addresses and sensor wiring.
- Verify PLC-to-HMI communication.
- Document Adafruit IO feed configuration and data transmission.
- Add actual simulation results and hardware testing evidence.

## 8. Conclusion
This repository documents the proposed Rapier Loom Automation workflow through PLC ladder logic screenshots, HMI visualization, and an IoT dashboard. Original source files and verified test evidence are required to reproduce and validate the complete system.
