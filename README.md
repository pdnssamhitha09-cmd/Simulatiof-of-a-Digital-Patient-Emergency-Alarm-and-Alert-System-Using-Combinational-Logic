# Simulatiof-of-a-Digital-Patient-Emergency-Alarm-and-Alert-System-Using-Combinational-Logic
Digital  Ptient Emergency Alarm and Alert System using Combinational Logic

## Project Description
This project presents the design and simulation of a Digital Patient Emergency Alarm and Alert System using combinational logic.
The system monitors four emergency conditions. When any one or more emergency conditions are detected, the emergency alarm is activated.

## Inputs
- A – High Temperature
- B – Abnormal Heart Rate
- C – Low Oxygen Level
- D – Emergency Button

## Output
- Y – Emergency Alarm

## Boolean Expression
Y = A + B + C + D

Here, + represents the OR operation.

## Working
The four emergency inputs are connected using OR gates.

- If A = B = C = D = 0, the alarm is OFF.
- If any one or more inputs are 1, the alarm is ON.

For example, if the oxygen level is low:

A = 0, B = 0, C = 1, D = 0

Therefore:

Y = 0 + 0 + 1 + 0 = 1

The emergency alarm is activated.

## Truth Table

The complete truth table is provided in:

`Truth_Tables.png`

## Circuit Simulation

The circuit is designed and simulated using Logisim / Logisim Evolution.

The Logisim circuit file is:

`Patient_Emergency_Alarm.circ`

## Project Report

The complete project report is provided in:

`Project_Report.pdf`

## Files Included

- `README.md` – Project description and working
- `Patient_Emergency_Alarm.circ` – Logisim circuit file
- `Truth_Tables.png` – Truth table
- `Project_Report.pdf` – Complete project report

## Software Used

- Logisim / Logisim Evolution
- GitHub

## Result

The emergency alarm is activated whenever at least one emergency input is HIGH.

## Note

This project is developed for educational and simulation purposes. It is not intended for use as an actual medical device.

