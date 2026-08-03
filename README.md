# Battery-Discharge-Simulation
Simulink model of a 24A battery discharge circuit analyzing safe current delivery to 4 loads from 4 batteries (2 ohms each) with switching logic to discharge one battery for every load until all batteries are discharged.

# 24A Battery Discharge Circuit Simulation (Simulink)

## Overview
Simulink model of a sequential battery discharge system, cycling through 4 lithium-ion batteries through resistive loads with automatic switchover based on voltage threshold.

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
The simulation demonstrates a sequential discharge system where each battery is automatically disconnected once its terminal voltage drops below a safe threshold, and the next battery is switched in. The voltage plot confirms the expected staircase discharge pattern across all four cells.
