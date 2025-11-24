# 🤖 Project COMMAND CENTER  
### AI-Driven Autonomous AMR Path Optimization for Proactive Material Supply

---

## 📌 1. Project Overview  

**Project COMMAND CENTER** is an AI-driven autonomous AMR path optimization system designed for smart factories aiming for **zero-downtime production**.  
By integrating predictive analytics and autonomous logistics, the system minimizes human intervention and prevents production delays through **proactive material supply orchestration**.

---

## ✨ 2. Key Features  

- **Real-Time Inventory Detection & Prediction**  
  The central AI control tower continuously monitors production line inventory and applies analytics to **predict material depletion before it occurs**.

- **Proactive Task Allocation**  
  Based on predictive results, the system autonomously **assigns optimal supply missions to AMRs**, ensuring uninterrupted material flow.

- **Reliable Autonomous Navigation**  
  Equipped with **LiDAR** and **IMU** sensors, AMRs perform real-time obstacle avoidance and route correction using a pre-built digital map.

- **Automated Material Handling**  
  Integrated **self-lifting mechanisms** enable pallet pickup and delivery without operator input.

- **Interconnected Control Architecture**  
  Each unit communicates bidirectionally with the AI control server, forming a **decentralized yet coordinated fleet system** that scales with production.

---

## 📐 3. System Architecture  

The COMMAND CENTER operates on a three-layer hierarchical structure:

1. **Perception Layer**  
   Converts environmental and operational data into digital signals.  
   - **Module:** AI Vision Server

2. **Cognition & Decision Layer**  
   Performs decision-making and path optimization using real-time data.  
   - **Module:** Onboard Raspberry Pi (AMR Controller)

3. **Actuation Layer**  
   Executes control signals as physical movement and mechanical operations.  
   - **Module:** STM32-Based Motor Controller

---

## 🛠️ 4. Technology Stack  

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Hardware** | STM32, Raspberry Pi, LiDAR, IMU | Motor control, localization, environmental perception |
| **Software** | Python (AI/ML), ROS 2, C/C++ | AI-based control, path optimization, real-time control |
| **Development Tools** | Git, GitHub, Visual Studio Code | Version management and collaborative development |

*Additional integration options include ROS 2 packages, MQTT messaging, and real-time telemetry pipelines for AI inference feedback.*

---

## 👥 5. Team Roles  

- **Member A:** AI monitoring and predictive algorithm development  
- **Member B:** Autonomous navigation and path optimization (Raspberry Pi)  
- **Member C:** Motor control and lift mechanism hardware (STM32)

---

## 🎬 6. Demonstration  

[Demo Video Link — To Be Added]

---

## 🌐 Reference Materials  

- [Watch Project Demo](https://www.youtube.com/watch?v=your_video_id)  
- [Technical Specification Document](https://example.com/spec)  
- [Detailed Design Documentation](docs/Design.md)
