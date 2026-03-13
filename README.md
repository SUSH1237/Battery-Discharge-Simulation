# Battery-Discharge-Simulation
Simulink model of a 132A battery discharge circuit analyzing safe current delivery to a load

# 132A Battery Discharge Circuit Simulation (Simulink)

## Overview
This project models a **132 A battery discharge circuit** using **MATLAB/Simulink**. The goal of the model is to analyze **safe current delivery from a battery to a connected load** and observe how current and voltage behave during high-current discharge conditions.

This simulation was developed as part of research work in a **PV/EV charging systems laboratory**.

## Model Description
The Simulink model represents a battery connected to a load through a controlled circuit designed to safely handle high discharge current.

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
https://github.com/SUSH1237/Battery-Discharge-Simulation/blob/65581117db23b680878c1106cc799e120804efd5/discharge2023.slx

https://github.com/SUSH1237/Battery-Discharge-Simulation/blob/95db6fba303f65aa500bf9b5516343b9674123a6/discharge2023.slx

## Tools Used
- MATLAB
- Simulink
- Simscape Electrical (if used)

## Example Model Diagram


## Example Simulation Results


## Future Improvements
- Add **multiple load branches**
- Implement **switching control using MOSFETs**
- Simulate **irradiance changes in PV-connected systems**
- Implement **duty cycle control for power regulation**
