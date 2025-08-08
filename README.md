# Water Tank Control System (SCADA Simulation in Ignition)

This project simulates a complete water tank control system using **Ignition SCADA** by Inductive Automation.  
It demonstrates core industrial automation concepts: **HOA logic**, **real-time alarms**, and **historical data analysis**—all implemented in a structured, functional interface.

> ✅ This SCADA project complements my earlier **PLC + HMI** implementation using Allen-Bradley and FactoryTalk View.  
> 🔗 Related Project: [Water Tank Control Project (PLC + HMI)](https://github.com/Alwaleed-Projects/Water-Tank-Control-Project)

---

## 🎯 Key Features

- **HOA Control Logic**  
  Manual / Off / Auto control for both pump and valve.

- **PLC-style Simulation**  
  Water level is simulated using tags (LL, L, H, HH) with custom logic written to mimic real tank behavior.

- **Alarm Management System**  
  - Active & Unacknowledged alarms are displayed clearly.  
  - Visual "Attention" panel appears when critical alarms are triggered.  
  - Acknowledge button allows operator to hide alerts while keeping the alarm state active in the banner.

- **Trends and Historian Integration**  
  - Real-time Power Chart displaying:  
    - Water Level  
    - Pump Status  
    - Valve Status  
  - KPIs: Minimum, Maximum, and Average  
  - Supports time range selection and CSV export  
  - Uses SQLite Tag Historian

- **Analytical KPIs (Live)**  
  - **Water Level Avg/min**: Displays the live average water level per minute.  
  - **Pump Power Avg/min**: Displays the live average pump runtime/consumption per minute.  
  _Analytical KPIs provide real-time calculated averages for water level and pump performance, enabling trend analysis and supporting potential optimization decisions._

- **Responsive SCADA UI**  
  - Clean navigation between Main, Alarms, and Trends views  
  - Designed with readability and operator focus in mind  
  - Layout optimized for showcasing in portfolio or interview

---

## 📹 Demo Video

📌 Click on the image below to watch the full demo video on YouTube.

[![Watch the Demo](https://img.youtube.com/vi/r_gztTlsPYs/maxresdefault.jpg)](https://youtu.be/r_gztTlsPYs)

---

## 📁 Project Structure

| Component     | Description                                  |
|---------------|----------------------------------------------|
| Main View     | HOA control, real-time status, logic display |
| Alarms View   | Active alarms, Acknowledge control, warnings |
| Trends View   | Power Chart + KPIs from Tag Historian        |
| Tags & Logic  | Water level simulation, pump/valve control   |
| Historian     | SQLite-based historical data logging         |

---

## 📦 Technologies Used

- Ignition SCADA (Perspective Module)
- SQLite (Tag Historian)
- PLC-style logic (via tag scripting & tag changes)
- Power Chart (for data trends)
- Alarm Journal (basic configuration)

---

## 📩 Contact

For collaboration or questions:  
📧 alwaleedaldawsi@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/alwaleedalzahrani)
