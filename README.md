# NOETRONYX-Robot-Dog-Journey
End-to-end portfolio project for an AI-powered quadruped robot (Robot Dog). Integrating Python, ESP32, OpenCV, YOLOv8, ROS2, Jetson Orin Nano, 2D LiDAR, and LLM for human-robot interaction. This repository documents the complete 12-month R&amp;D journey, from bare-metal sensor reading to autonomous navigation and edge-AI inference.

## 🚀 Project Overview
**Start Date:** 2026.08.01  
**Target Completion:** 2027.08.01  
**Core Objective:** Build a fully functional, AI-enabled quadruped robot from scratch, emphasizing **system integration** over isolated algorithm development.

This repository serves as the central hub for my senior-year entry portfolio, targeting:
- **PolyU ESE** – Electronic Systems & IoT Engineering
- **CityU CDE** – Computer and Data Engineering

---

## 🧠 Technical Stack Roadmap
The development follows a strictly incremental hardware-software co-design workflow:

| Phase | Tech Stack | Deliverable |
| :---: | :--- | :--- |
| **Phase 1** | Python, Git, VS Code | CLI tools, data processing scripts |
| **Phase 2** | ESP32, I2C/SPI/UART, MQTT | Sensor data acquisition & IoT pipeline |
| **Phase 3** | OpenCV, YOLOv8 | Real-time object detection (people, cups, phones) |
| **Phase 4** | ROS2, Gazebo | System architecture simulation & module planning |
| **Phase 5** | Jetson Orin Nano, 2D LiDAR | Edge-AI inference, SLAM, and obstacle avoidance |
| **Phase 6** | Quadruped Kit, High-torque Servos | Inverse kinematics & gait control |
| **Phase 7** | LLM (Llama 3 / GPT-API), TTS | Voice-interactive autonomous agent |

---

## 📁 Portfolio Projects (6 Milestones)
Each milestone is a standalone GitHub repository linked to this main project. They are designed to demonstrate progressive competency in **Embedded Systems**, **Computer Vision**, **Robotics**, and **Edge AI**.

| # | Project Name | Key Features | Status |
| :-: | :--- | :--- | :--- |
| **P1** | **Robot Sees the World** | YOLO object detection via USB camera | 🔜 Planned |
| **P2** | **Robot Remembers You** | ByteTrack implementation for person re-identification | 🔜 Planned |
| **P3** | **Robot Follows You** | PID control + Serial communication for chassis tracking | 🔜 Planned |
| **P4** | **Robot Avoids Obstacles** | 2D LiDAR + ROS2 navigation stack | 🔜 Planned |
| **P5** | **Robot Starts Thinking** | Multi-sensor fusion & decision-making nodes | 🔜 Planned |
| **P6** | **Robot Interacts** | LLM integration + Speech synthesis for HRI | 🔜 Planned |

---

## 🛠️ Hardware Procurement Strategy (Phased)
To avoid financial overhead and reduce cognitive load, hardware is acquired strictly upon milestone completion.

| Phase | Budget (HKD) | Components | Trigger Condition |
| :---: | :---: | :--- | :--- |
| **Phase 1** | ~$1,000 | USB Camera, basic sensors (MPU6050, DHT11) | Start of P1 |
| **Phase 2** | ~$3,000 - $5,000 | Jetson Orin Nano (8GB+), Cooling Kit | Completion of P2 |
| **Phase 3** | ~$5,000+ | Quadruped Metal Frame, 12x Servos, 2D LiDAR, BMS | Completion of P4 |

---

## 📈 Current Progress Log
> *Daily development logs are maintained in the `/docs` directory. This section updates weekly.*

- **Week 0 (Aug 1, 2026):** Repository initialized. Development environment set up (Python 3.12 + VS Code + ESP-IDF).
- **Next Step (Week 1):** Complete Python core syntax (Ch. 1-3 of "Zero to One Python") and basic Git workflows.

---

## 📚 Reference Texts
- *Zero to One: Python Quick Start* – Foundation for scripting and data handling.
- *AI at the Edge : A Practical Guide* – Reference for DSP, model deployment, and end-to-end edge architectures.

---

## 👤 Author
**Ivan Wong**  
*Aspirant Embedded Systems & Robotics Engineer*  
Targeting 2027/2028 Senior Year Entry (PolyU / CityU)

---

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
