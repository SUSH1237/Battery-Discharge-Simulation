# Battery-Discharge-Simulation
Simulink model of a 132A battery discharge circuit analyzing safe current delivery to a load

# 132A Battery Discharge Circuit Simulation (Simulink)

## Overview
This project models a **132 A battery discharge circuit** using **MATLAB/Simulink**. The goal of the model is to analyze **safe current delivery from a battery to a connected load** and observe how current and voltage behave during high-current discharge conditions.

This simulation was developed as part of research work in a **PV/EV charging systems laboratory**.

## Model Description
The Simulink model represents a battery connected to multiple loads through a controlled circuit designed to safely handle high discharge current.

Key elements of the model include:
- Battery source model
- Load resistance
- Current measurement
- Voltage measurement
- Simulink power electronics blocks

The simulation allows analysis of:
- Battery discharge current
- Load voltage behavior
- System response under high current conditions

## Files
- slx file (2023 compatible): https://github.com/SUSH1237/Battery-Discharge-Simulation/blob/9d41769fa09f4f949d5cfaa3344d1f4c1d400ccc/discharge6.slx


## Tools Used
- MATLAB
- Simulink
- Simscape Electrical

## Model Diagram
![img alt](https://github.com/SUSH1237/Battery-Discharge-Simulation/blob/968e9554ace7262ba511f29ad0c59c794223476b/dischargesc.png)

## Simulation Results
![img alt](https://github.com/SUSH1237/Battery-Discharge-Simulation/blob/c03dfb22da8264b755110ff7ea40f7af6a42c0d4/DischargeGraph%20(1).png)

## Future Improvements
- Implement **switching control using MOSFETs**
- Simulate **irradiance changes in PV-connected systems**
- Implement **duty cycle control for power regulation**
