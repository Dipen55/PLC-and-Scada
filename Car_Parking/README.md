# Smart Car Parking System using PLC & SCADA

## Overview
The Smart Car Parking System is an industrial automation mini project developed using **PLC Programming** and **SCADA/HMI visualization**.  
The system automatically monitors vehicle entry and exit, counts available parking spaces, and indicates when the parking area is full.

This project demonstrates the use of:
- PLC Ladder Logic
- Industrial Counters
- Sensor-Based Automation
- SCADA Monitoring Systems

---

# Features

- Automatic vehicle counting
- Entry and exit sensor detection
- Real-time parking status monitoring
- Parking full indication
- SCADA graphical visualization
- PLC simulation support
- Industrial automation logic implementation

---

# Technologies Used

## Software
- CX-Programmer
- CX-Supervisor

## Hardware/Concepts
- Omron PLC
- SCADA/HMI
- Ladder Logic Diagram (LAD)
- Reversible Counter
- Industrial Sensors

---

# Working Principle

1. When a vehicle enters:
   - Entry sensor gets activated
   - Counter value increases

2. When a vehicle exits:
   - Exit sensor gets activated
   - Counter value decreases

3. If parking capacity reaches the maximum limit:
   - "Parking Full" indicator turns ON

4. SCADA continuously displays:
   - Car count
   - Entry/Exit status
   - Parking area condition

---

# Ladder Logic Functions

- Entry Sensor Input
- Exit Sensor Input
- Reversible Counter
- Parking Full Output
- Master Control Switch

---

# Project Structure

```text
Smart-Car-Parking-System/
│
├── README.md
├── ladder-logic/
├── scada/
└── screenshots/
```

---

# Applications

- Shopping malls
- Apartment parking systems
- Smart city projects
- Office parking management
- Industrial vehicle monitoring

---

# Future Improvements

- RFID-based vehicle identification
- IoT monitoring system
- Mobile application integration
- Automatic gate control
- Cloud-based parking analytics

---

# Learning Outcomes

- PLC programming concepts
- SCADA/HMI development
- Industrial automation logic
- Counter operations in PLC
- Sensor integration techniques

---

# Author

## Dipendra Teli
Electrical and Electronics Engineering Student

Interested in:
- PLC & SCADA
- Industrial Automation
- IoT Systems
- Smart Grid Technologies
- Electric Vehicles

---

# License

This project is created for educational and learning purposes.
