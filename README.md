# MOULD PRESS MACHINE AUTOMATION
This repository contains the PLC and HMI software developed for an industrial Mould Press Machine using Mitsubishi PLC and Mitsubishi GOT HMI.
The Mould Press Machine is an automated hydraulic moulding system controlled by a Mitsubishi PLC and monitored through a Mitsubishi GOT HMI. The operator selects a product recipe from the HMI, which loads predefined moulding, pressure, ejector, and timing parameters into the PLC. Before starting a cycle, the PLC verifies all safety conditions, including the light curtain, emergency stop, and machine interlocks. During operation, the hydraulic ram moves according to recipe settings while an LVDT sensor provides continuous position feedback for accurate stroke control. The machine performs pressing, pressure holding, optional breathing cycles, mould opening, and ejector operations automatically to ensure consistent product quality. The HMI provides real-time monitoring of production data, machine status, alarms, safety interlocks, work hours, and process parameters, while data logging and recipe management features improve traceability, productivity, and ease of operation.

### PLC
* Mitsubishi PLC
* GX Works Programming Software
* Ladder Logic Programming

### HMI
* GT Designer

### Sensors & Field Devices
* LVDT (Linear Variable Differential Transformer)
* Safety Light Curtain Sensor
* Hydraulic Pressure Sensors
* Limit Switches
* Solenoid Valves
* Emergency Stop Circuit

## Machine Functions

### Automatic Production Cycle
1. Safety validation
2. Mould closing
3. Press operation
4. Pressure holding
5. Breathing cycle
6. Mould opening
7. Ejector operation
8. Cycle completion

## Safety System
The machine incorporates multiple safety interlocks including:
* Light Curtain Monitoring
* Emergency Stop Monitoring
* Hydraulic Safety Conditions
* Mould Position Verification
* Operator Safety Interlocks

Machine operation is blocked whenever any safety condition is violated.

## LVDT Position Control
LVDT feedback is used for:
* Ram position monitoring
* Press stroke control
* Process repeatability
* Precision mould positioning

## HMI Features
### Production Monitoring
* Cycle Status
* Machine Status
* Production Counter
* Real-Time Process Monitoring

### Recipe Management
* Product Recipe Creation
* Recipe Selection
* Recipe Storage
* Recipe Recall

### Moulding Parameters
Operator-adjustable settings for:
* Press Stroke
* Cycle Timing
* Process Parameters

### Pressure Parameters
* Pressure Setpoints
* Pressure Monitoring
* Process Control

### Ejector Parameters
* Ejector Position Settings
* Ejector Timing Control

### Breathing Parameters
Configuration of breathing cycles during mould pressing operation.

### Delay Time Settings
Adjustment of process delays and sequencing times.

### Data Logging
* Production Analysis
* Troubleshooting
* Performance Monitoring

## PLC Features
### Automatic Mode
Complete automatic machine operation with sequence control.

### Recipe Handling
Recipe data transfer between HMI and PLC for fast product changeovers.

### Alarm Handling

Machine alarms include:
* Safety Faults
* Sensor Faults
* Pressure Faults
* Position Faults
* Operator Warnings

## Skills Demonstrated
* Mitsubishi PLC Programming
* Mitsubishi GOT HMI Development
* Hydraulic Press Automation
* Analog Signal Processing
* LVDT Integration
* Safety System Integration
* Recipe Management Systems
* Industrial Machine Automation
* Alarm & Fault Handling
* Production Monitoring
* Data Logging
* Industrial Troubleshooting

## Author
Ritesh Mohanty




