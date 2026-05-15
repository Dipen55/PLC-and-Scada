Water Sprinkler Automation System with SCADA Monitoring
Overview

This project demonstrates a PLC-controlled water sprinkler system integrated with a SCADA interface for real-time monitoring and control.
The system uses ladder logic programming to automate irrigation using sensor inputs and timers.

Objectives
To design and implement an automated sprinkler system
To control irrigation using PLC ladder logic
To monitor the system using SCADA
To simulate industrial automation concepts
Technologies Used
PLC Software: CX-Programmer
SCADA Software: CX-Supervisor
Programming Language: Ladder Logic
Simulation Mode: PLC Simulator
System Components
Temperature Sensor
Grass Valve
Flower Valve
PLC Timers
SCADA Control Panel
Working Principle
The temperature sensor activates the system.
Timer 1 turns ON the Grass Valve.
After Timer 1 finishes, Timer 2 starts.
Timer 2 turns ON the Flower Valve.
The system stops automatically after the timers complete.
Ladder Logic Explanation
Input:
Temperature Sensor (0.00)
Outputs:
Grass Valve (100.00)
Flower Valve (100.01)
Timers:
Timer 1 (T0000)
Timer 2 (T0001)
Logic
Sensor ON = Timer 1 starts
Timer 1 active = Grass Valve ON
Timer 2 active = Flower Valve ON
Timer completion = System OFF
SCADA Interface Features
Real-time monitoring
Valve status indicators
ON/OFF visualization
User-friendly interface
SCADA Interface

Ladder Logic Diagram

![Ladder Logic](./ladder diagram.png)

How to Run the Project
Open project in CX-Programmer
Compile the ladder logic
Run PLC Simulation
Open CX-Supervisor
Load the SCADA file
Start monitoring
Applications
Smart irrigation systems
Agricultural automation
Garden watering systems
Future Improvements
Add soil moisture sensors
Implement IoT monitoring
Add weather-based automation
