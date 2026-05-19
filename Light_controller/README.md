# PLC-Based Sequential Lamp Control using CX-Programmer & CX-Supervisor

## 📌 Project Overview

This project demonstrates a **Sequential Lamp Control System** using:

- Omron CX-Programmer (PLC Ladder Logic)
- CX-Supervisor (SCADA/HMI)

The system controls multiple lamps in sequence using timer-based ladder logic and visualizes the operation through a SCADA interface.

---

# 🛠 Software Used

| Software | Purpose |
|---|---|
| CX-Programmer | PLC Ladder Logic Development |
| CX-Supervisor | SCADA/HMI Visualization |
| Omron PLC Simulator | PLC Simulation |

---

# ⚙️ Project Working

The system works in the following sequence:

1. User presses the START switch.
2. Timer 1 activates Lamp 1.
3. Timer 2 activates Lamp 2.
4. Timer 3 activates Lamp 3.
5. Timer 4 activates Lamp 4.
6. Lamps operate sequentially using PLC timers.
7. The SCADA interface displays the real-time lamp status.

---

# 🧠 PLC Logic

The ladder logic uses:

- TIM Instructions
- Sequential Timer Operation
- Lamp Output Control
- Start Switch Input
- Timer Interlocking

---

# 🖥 SCADA Interface Features

The CX-Supervisor interface includes:

- ON/OFF Control Switch
- Real-time Lamp Indication
- PLC Tag Communication
- Visual Monitoring Interface

---

# 📂 Project Structure

```text
Project
│
├── PLC Ladder Logic (CX-Programmer)
│
├── SCADA/HMI Interface (CX-Supervisor)
│
└── PLC Simulation
```

---

# 🔄 System Workflow

```text
START SWITCH
      ↓
PLC Ladder Logic
      ↓
Timer Sequence
      ↓
Lamp Outputs
      ↓
SCADA Visualization
```

---

# 📸 Screenshots

## PLC Ladder Logic

- Timer-based sequential control
- Multiple timer operation
- Lamp output sequencing

## SCADA Interface

- Lamp monitoring system
- ON/OFF switch control
- Real-time visualization

---

# 🚀 Future Improvements

Possible future enhancements:

- Automatic ON/OFF Scheduling
- IoT-based Monitoring
- Remote SCADA Access
- Fault Detection System
- Smart Lighting Automation
- Energy Monitoring

---

# 🎯 Learning Outcomes

Through this project, concepts learned include:

- PLC Programming
- Ladder Logic Design
- Timer Operations
- SCADA Development
- Industrial Automation
- HMI Design
- PLC-SCADA Communication

---

# 👨‍💻 Developed By

Dipendra Teli  
Electrical & Electronics Engineering

---
