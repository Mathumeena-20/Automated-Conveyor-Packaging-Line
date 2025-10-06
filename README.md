# Automated Conveyor & Packaging Line

This project demonstrates an **industrial automation system** using PLC programming, HMI design, and Factory I/O simulation.  
The system automates a conveyor and packaging line with object counting, packaging triggers, and jam detection.

## 🛠️ Tools & Technologies
- Siemens TIA Portal (S7-1200 PLC, Ladder Logic)
- PLCSIM for simulation
- Factory I/O for 3D conveyor model
- WinCC HMI for operator interface

## ⚙️ System Design
- Conveyor controlled via Start/Stop/Emergency Stop
- IR Sensor counts objects on conveyor
- After 10 objects, actuator triggers to simulate packaging
- Jam switch stops conveyor and triggers alarm
- HMI shows controls, counters, and alarms

## 📂 Repo Structure
- `/docs` → Block diagram, HMI screenshots, Factory I/O layout
- `/ladder-logic` → Exported ladder logic code (PDF/XML)
- `/hmi-design` → WinCC screenshots and tag lists
- `/simulation` → Factory I/O setup screenshots

## 🚀 How to Run
1. Open TIA Portal → Import ladder program (from `/ladder-logic`)
2. Run PLCSIM and test logic
3. Open Factory I/O → Load Conveyor model → Map I/O
4. Start simulation and control system via HMI

## 📸 Screenshots
![System Design](docs/System_Design.png)
![HMI Screen](docs/WinCC_HMI.png)

## 🔮 Future Improvements
- Add SCADA integration for remote monitoring
- Use multiple conveyors with different speeds
- Implement defect rejection using vision sensors

---
👨‍💻 Author: [Mathumeena](https://github.com/Mathumeena-20/Automated-Conveyor-Packaging-Line)
