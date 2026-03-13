# Battery-Discharge-Simulation
Simulink model of a 132A battery discharge circuit analyzing safe current delivery to a load
Overview

This project models a 132 A battery discharge circuit using MATLAB/Simulink. The goal of the model is to analyze safe current delivery from a battery to a connected load and observe how current and voltage behave during high-current discharge conditions.

This simulation was developed as part of research work in a PV/EV charging systems laboratory.

Model Description

The Simulink model represents a battery connected to a load through a controlled circuit designed to safely handle high discharge current.

Key elements of the model include:

Battery source model

Load resistance

Current measurement

Voltage measurement

Simulink power electronics blocks

The simulation allows analysis of:

Battery discharge current

Load voltage behavior

System response under high current conditions
Tools Used

MATLAB

Simulink

Simscape Electrical (if you used it)

Example Model Diagram

(Insert screenshot of your Simulink model here)

Example Simulation Results

(Insert plots of current or voltage here)

Future Improvements

Add multiple load branches

Implement switching control using MOSFETs

Simulate irradiance changes in PV-connected systems

Implement duty cycle control for power regulation
