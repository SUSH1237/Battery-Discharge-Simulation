# Battery-Discharge-Simulation
Simulink model of a 24A battery discharge circuit analyzing safe current delivery to 4 loads from 4 batteries (2 ohms each) with switching logic to discharge one battery for every load until all batteries are discharged.

# 24A Battery Discharge Circuit Simulation (Simulink)

## Overview
This project models a **24 A battery discharge circuit** using **MATLAB/Simulink**. The goal of the model is to analyze **safe current delivery from a battery to a connected load** and observe how current and voltage behave during high-current discharge conditions.

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
- slx file (2023 compatible): https://github.com/SUSH1237/Battery-Discharge-Simulation/blob/d8615c3b63a395293b920b9fe8580478b4d02f85/dischargelogic.slx


## Tools Used
- MATLAB
- Simulink
- Simscape Electrical

## Model Diagram
![img alt](https://github.com/SUSH1237/Battery-Discharge-Simulation/blob/4ad4ea0aa870774de2e39e557eedde470012cc15/discharge6sc.png)

## Simulation Results
![img alt](https://github.com/SUSH1237/Battery-Discharge-Simulation/blob/4ad4ea0aa870774de2e39e557eedde470012cc15/discharge6graph.png)

## Future Improvements
-Implement **cheaper load system to reach current requirements and Power requirements**
- Implement **switching control using MOSFETs**
- Simulate **irradiance changes in PV-connected systems**
- Implement **duty cycle control for power regulation**
