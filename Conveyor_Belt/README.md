# PLC-Based Conveyor Control System with SCADA Monitoring

## 📌 Overview
This project demonstrates a **PLC-controlled conveyor system** integrated with a **SCADA monitoring interface** using:

- Omron CX-Programmer
- Omron CX-Supervisor

The system uses a **light sensor**, **counter logic**, and **SCADA visualization** to automate conveyor operation and monitor the process in real time.

---

# 🛠 Software Used

- Omron CX-Programmer
- Omron CX-Supervisor

---

# ⚙ System Components

## Inputs

| Address | Component |
|----------|-----------|
| 0.00 | Light Sensor |
| 0.01 | Reset Push Button |
| 0.02 | Start Switch |

---

## Outputs

| Address | Component |
|----------|-----------|
| 100.00 | Conveyor |
| 100.01 | Lamp |

---

## Internal Components

| Address | Function |
|----------|-----------|
| C0000 | Counter |

---

# 🚀 Working Principle

1. The **Start Switch** starts the conveyor.
2. The **Light Sensor** detects objects moving on the conveyor.
3. Every detection increments the counter.
4. The counter preset value is set to **5**.
5. When the count reaches 5:
   - Conveyor stops
   - Lamp turns ON
6. Pressing the **Reset Switch** resets the counter and restarts the process.

---

# 🧠 Ladder Logic Description

## Counter Logic
- The light sensor triggers the `CNT` instruction.
- Counter `C0000` counts detected objects.
- Preset count value = `#5`

---

## Conveyor Control
The conveyor runs when:
- Start switch is ON
- Counter completion condition is FALSE

---

## Lamp Indication
The lamp turns ON when the counter reaches the preset value.

---

# 🖥 SCADA Features

The CX-Supervisor SCADA interface provides:

- Real-time conveyor monitoring
- Sensor indication
- Start switch control
- Reset switch control
- Conveyor visualization
- Lamp status indication

---

# 📷 Project Screenshots

## Ladder Logic
_Add ladder logic screenshot here_

## SCADA Interface
_Add SCADA interface screenshot here_

---

# 🎯 Applications

- Industrial Conveyor Automation
- Object Counting Systems
- Packaging Industries
- Production Line Monitoring
- PLC-SCADA Integration Projects

---

# 🔮 Future Improvements

- Emergency Stop System
- Conveyor Speed Control
- Object Detection Animation
- Alarm System
- Production Data Logging
- HMI Enhancements

---

# 👨‍💻 Author

**Dipendra Teli**  
Electrical and Electronics Engineering (EEE)  
Aditya College of Engineering and Technology
