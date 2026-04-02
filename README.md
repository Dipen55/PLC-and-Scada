# PLC-Based Trolley Control System with SCADA Monitoring

## Overview
This project demonstrates a PLC-controlled trolley system integrated with a SCADA interface for real-time monitoring and control.
The system uses ladder logic programming to control trolley movement based on inputs like start, stop, and sensor signals.

## Objectives
* To design and implement a trolley automation system
* To control operations using PLC ladder logic
* To monitor and operate the system using SCADA (CX-Supervisor)
* To simulate industrial automation concepts

## Technologies Used
* PLC Software: CX-Programmer
* SCADA Software: CX-Supervisor
* Programming Language: Ladder Logic
* Simulation Mode: PLC Simulator

## System Components
* Start Push Button
* Stop Push Button
* Sensor Input
* Trolley Motor Output
* SCADA Control Panel

## Working Principle
1. When the Start button is pressed, the trolley system is activated.
2. The Stop button is used to halt the system.
3. A sensor input ensures controlled operation (e.g., position detection).
4. The trolley output is latched using ladder logic.
5. The SCADA interface displays:
   * System status (ON/OFF)
   * Alerts (NULL / inactive states)
   * Real-time control buttons

## Ladder Logic Explanation
* Input Conditions:
  * Start (0.00)
  * Stop (0.01)
  * Sensor (0.02)

* Output:
  * Trolley (100.00)

### Logic
* Start + Sensor = Trolley ON
* Stop = Trolley OFF
* Trolley uses self-holding (latching) logic
  
## SCADA Interface Features
* Graphical control panel for trolley system
* Real-time status indicators
* ON/OFF visualization
* Alarm/NULL indication
* User-friendly interface

### SCADA Interface
![SCADA](./scada.png)

### Ladder Logic Diagram
![Ladder Logic](./ladder diagram.png)


## How to Run the Project
1. Open project in CX-Programmer
2. Compile the ladder logic
3. Run PLC in Simulation Mode
4. Open CX-Supervisor
5. Load the SCADA file
6. Start simulation and monitor system

## Applications
* Industrial conveyor systems
* Automated transport systems
* Smart factory automation
* Material handling systems

## Future Improvements
* Add timer-based control
* Include multiple sensors
* Implement fault detection system
* IoT-based remote monitoring

## Author
Dipendra Teli
Electrical & Electronics Engineering Student

## Notes
* This is a simulation-based project
* Designed for learning industrial automation concepts
