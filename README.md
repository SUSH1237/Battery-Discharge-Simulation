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
![img alt](https://github.com/SUSH1237/Battery-Discharge-Simulation/blob/7caba38148a02183c8936d2e9b17ff4e9c2bfbc5/dischargelogic1.png)

## Battery Diagram
![img alt](https://github.com/SUSH1237/Battery-Discharge-Simulation/blob/7caba38148a02183c8936d2e9b17ff4e9c2bfbc5/dischargelogic2.png)
## Load Diagram
![img alt](https://github.com/SUSH1237/Battery-Discharge-Simulation/blob/7caba38148a02183c8936d2e9b17ff4e9c2bfbc5/dischargelogic3.png)
## Simulation Results
![img alt](https://github.com/SUSH1237/Battery-Discharge-Simulation/blob/7caba38148a02183c8936d2e9b17ff4e9c2bfbc5/dischargelogic4.png)

## Conclusion
The simulation successfully demonstrates a sequential battery discharge system in Simulink. Four Samsung INR 13S lithium-ion batteries (46.8V nominal, 10.8Ah) are discharged individually through 2Ω resistive loads at approximately 24A. The switching logic automatically disconnects a battery and activates the next one when terminal voltage drops below 42.9V, the manufacturer's minimum safe voltage. The voltage plot confirms the staircase discharge pattern; each battery discharges from ~53V to 42.9V in approximately 1,572 seconds (~27 minutes), consistent with the theoretical 2.17C discharge rate. Total simulated discharge time across all four batteries is approximately 1.8 hours. This simulation validates the switching threshold and sequencing logic prior to hardware implementation, providing a verified reference for programming the Arduino relay controller in the next phase of the project.
