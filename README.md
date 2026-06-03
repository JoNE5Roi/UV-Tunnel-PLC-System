# 🏭 UV Sterilization Tunnel Control System Upgrade

![Project Overview](for_github/uv_tunnel_overview.jpg)

A Cooperative Education Project developed at **CPRAM Co., Ltd.** Developed and upgraded a PLC-HMI based UV Tunnel control system for food safety applications. The project transitioned a legacy system into a modern architecture, focusing on safety interlock implementation, alarm monitoring, HMI development, electrical control panel integration, and overall system reliability improvement.

## 🏆 Key Results
* **Downtime Reduction:** Reduced maintenance time from 2 hours to just 30–60 minutes.
* **Improved Operational Safety:** Eliminated manual errors through automated interlocking.
* **Enhanced Maintainability:** Utilized standard components for faster replacement and troubleshooting.
* **Real-Time Monitoring:** Enabled live status tracking of UV lamps, inputs, and outputs directly via the HMI screen.

## ⚙️ Core System Features & Workflow

### 1. Food Safety Interlock (Raw vs. Cooked Zone)
A critical feature implemented to prevent cross-contamination. The PLC logic enforces a strict safety interlock between the **Raw Zone** and **Cooked Zone**, physically preventing simultaneous door openings and ensuring hygienic transfer of materials.

### 2. Automated Sterilization Workflow
The system strictly dictates the operational sequence to ensure standard UV exposure time:
`Unlock Door` ➔ `Insert Cart` ➔ `Close Door` ➔ `Check Limit Switch` ➔ `Start UV (Active 60 sec)` ➔ `Alarm/Buzzer` ➔ `Unlock Door` ➔ `Take Cart out`

### 3. Smart Alarm Monitoring
Integrated an intelligent alarm system that detects UV lamp faults or breaker trips in real-time. The HMI provides operators with exact error descriptions and timestamps, drastically reducing diagnostic time.

## 🛠️ Hardware & Technology Stack
* **Controller:** Programmable Logic Controller (PLC)
* **Interface:** Human-Machine Interface (HMI) Touchscreen
* **Panel Design:** Full integration of the Electrical Control Panel (Internal & External layout)
* **Sensors & Safeties:** Door limit switches, emergency stops, and warning buzzers.