# 👋 Hi, I'm Kaede Rei

[中文](README_zh.md) | **English**

> SCAU Undergraduate | Agri-Robotics Developer | AgroTech-SCAU Lead

> Focusing on **Embedded Control**, **Robotic Arm Motion Control**, and **Agricultural Robot System Integration**.

I am an undergraduate student at South China Agricultural University, working on agricultural robotics systems that connect embedded control, robotic arms, perception, ROS, and real-world deployment.

Currently, I am one of the main leads of [AgroTech-SCAU](https://github.com/AgroTech-SCAU), mainly responsible for:

* electronic control architecture
* robotic arm motion control
* system integration
* engineering standards and project organization

---

## 🔬 Current Research

My current work focuses on greenhouse mobile manipulation through three connected directions:

### 🦾 Robotic Arm Motion Control

Building a self-developed DM robotic arm platform with:

- ROS 2 control and hardware interfaces
- kinematics and dynamics
- gravity compensation
- impedance and admittance control
- MoveIt 2 integration
- safety and fault recovery

### 🍅 Agricultural Manipulation

Studying manipulation tasks in greenhouse environments, including:

- tomato harvesting
- compliant leaf manipulation
- active perception
- base–arm coordination
- RGB-D perception and hand–eye calibration

### 🧠 Embodied Manipulation

Exploring learning-based robot manipulation through:

- dual-arm teleoperation
- real-robot dataset collection
- LeRobot and imitation learning
- Isaac Sim and sim-to-real experiments
- autonomous leaf manipulation

---

## 📌 Project Map

My repositories are organized by their current role in research, engineering development, and knowledge reuse.

### Active Research & Main Platforms

| Project                                                                                                       | Area                      | Current Role                                                                                                     |
| ------------------------------------------------------------------------------------------------------------- | ------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| [DM-Arm-Hardware-Interface](https://github.com/Kaede-Rei/DM-Arm-Hardware-Interface)                           | Robotic Arm Control       | Main ROS 2 platform for DM robotic-arm hardware interfaces, dynamics, and compliant control                      |
| [Tomato-Push-Aside-Leaves](https://github.com/Kaede-Rei/Tomato-Push-Aside-Leaves)                             | Agricultural Manipulation | Leaf-manipulation and active-perception research for greenhouse harvesting                                       |
| [Dual-DM-Arm-LeRobot](https://github.com/Kaede-Rei/Dual-DM-Arm-LeRobot)                                       | Embodied AI               | Dual-arm teleoperation, real-robot datasets, imitation learning, and policy deployment                           |
| [DM-Arm-MoveIt2](https://github.com/Kaede-Rei/DM-Arm-MoveIt2)                                                 | Motion Planning           | MoveIt 2 integration, reachable-pose evaluation, and manipulation task-planning experiments                      |
| [AgroTech-SCAU/Steering-Wheel-Chassis](https://github.com/AgroTech-SCAU/Steering-Wheel-Chassis)               | Mobile Robot              | Main Atlas chassis repository covering embedded control, MCU–Linux integration, navigation, and autonomous tasks |
| [AgroTech-SCAU/Wheel-Rail-Integrated-Chassis](https://github.com/AgroTech-SCAU/Wheel-Rail-Integrated-Chassis) | Mobile Robot              | Wheel–rail integrated chassis platform and control prototype                                                     |

### Tools, Standards & Supporting Repositories

| Project                                                                                                                           | Role                                                                                  |
| --------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| [Hand-Eye-GUI-Tools](https://github.com/Kaede-Rei/Hand-Eye-GUI-Tools)                                                             | Hand–eye, eye-to-hand, and multi-camera calibration tools                             |
| [AgroTech-SCAU/Steering-Wheel-Chassis-Model-Collection](https://github.com/AgroTech-SCAU/Steering-Wheel-Chassis-Model-Collection) | Mechanical models and design assets for steering-wheel chassis platforms              |
| [AgroTech-SCAU/Embedded-Electronic-Control-Standard](https://github.com/AgroTech-SCAU/Embedded-Electronic-Control-Standard)       | Embedded architecture, reusable SDK, communication, safety, and development standards |
| [AgroTech-SCAU/Robotic-Arm-Motion-Control-Standard](https://github.com/AgroTech-SCAU/Robotic-Arm-Motion-Control-Standard)         | Reusable ROS and robotic-arm motion-control architecture                              |

<details>
<summary><strong>Legacy & Engineering References</strong></summary>

<br>

These repositories are retained as historical implementations, migration sources, or engineering references.

| Project                                                                         | Reference Value                                                                                            |
| ------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| [Tomato-Picker-PiPER](https://github.com/Kaede-Rei/Tomato-Picker-PiPER)         | Complete ROS1 tomato-harvesting workflow with MoveIt, RGB-D perception, point clouds, and GUI task control |
| [Tomato-Picker-DM](https://github.com/Kaede-Rei/Tomato-Picker-DM)               | ROS1 DM robotic-arm harvesting implementation and ROS 2 migration reference                                |
| [Renesas-DM-Arm](https://github.com/Kaede-Rei/Renesas-DM-Arm)                   | MCU-side robotic-arm kinematics, CAN motor control, communication, and HFSM reference                      |
| [Multi-Arm-Controller](https://github.com/Kaede-Rei/Multi-Arm-Controller)       | Multi-arm planning interfaces and reachable-pose search prototype                                          |
| [Lift-Gripper-Controller](https://github.com/Kaede-Rei/Lift-Gripper-Controller) | Embedded lift and gripper controller with PID, CAN communication, and HFSM                                 |
| [Steering-Wheel-Chassis](https://github.com/Kaede-Rei/Steering-Wheel-Chassis)   | Earlier personal version of the chassis project; current development has moved to AgroTech-SCAU            |
| [Visial-Robotic-Arm-Car](https://github.com/Kaede-Rei/Visial-Robotic-Arm-Car)   | Early visual robotic-arm mobile manipulation prototype                                                     |
| [Embedded-About](https://github.com/Kaede-Rei/Embedded-About)                   | Index and archive of early embedded-system projects                                                        |

</details>

<details>
<summary><strong>Personal Infrastructure & Other Repositories</strong></summary>

<br>

| Project                                                                 | Role                                                                    |
| ----------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| [Kaede-Rei](https://github.com/Kaede-Rei/Kaede-Rei)                     | GitHub profile README                                                   |
| [kaede-rei.github.io](https://github.com/Kaede-Rei/kaede-rei.github.io) | Personal website and technical blog                                     |
| [Resume-Template](https://github.com/Kaede-Rei/Resume-Template)         | Personal résumé and document template                                   |

</details>

---

## 🧰 Tech Stack

### 💻 Programming Languages

![C](https://img.shields.io/badge/-C-000000?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/-C++-5C3EE8?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust)

### ⚙️ Embedded Systems

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square\&logo=stmicroelectronics\&logoColor=white)
![Renesas](https://img.shields.io/badge/-Renesas-CC0000?style=flat-square)
![ESP32](https://img.shields.io/badge/-ESP32-E7352C?style=flat-square)
![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=flat-square)
![CAN](https://img.shields.io/badge/-CAN%20Bus-00599C?style=flat-square)
![RTOS](https://img.shields.io/badge/-RTOS-5C3EE8?style=flat-square)
![LVGL](https://img.shields.io/badge/-LVGL-FF6F00?style=flat-square)
![Vision](https://img.shields.io/badge/-Embedded%20Vision-5C3EE8?style=flat-square)
![PCB](https://img.shields.io/badge/-PCB%20Design-00599C?style=flat-square)

### 🤖 Robotics & Control

![ROS](https://img.shields.io/badge/ROS-Noetic%20%7C%20Humble-22314E?style=flat-square\&logo=ros\&logoColor=white)
![MoveIt](https://img.shields.io/badge/MoveIt-Motion_Planning-blueviolet?style=flat-square)
![ros2\_control](https://img.shields.io/badge/ros2__control-Hardware_Interface-blue?style=flat-square)
![Pinocchio](https://img.shields.io/badge/Pinocchio-Dynamics-green?style=flat-square)
![RViz](https://img.shields.io/badge/-RViz-22314E?style=flat-square)
![Gazebo](https://img.shields.io/badge/-Gazebo-2C3E50?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-5C3EE8?style=flat-square\&logo=opencv\&logoColor=white)
![LeRobot](https://img.shields.io/badge/-🤗%20LeRobot-E7352C?style=flat-square)

### 🧪 Tools & Platforms

![Linux](https://img.shields.io/badge/Linux-Ubuntu-E95420?style=flat-square\&logo=ubuntu\&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-Build-064F8C?style=flat-square\&logo=cmake\&logoColor=white)
![Colcon](https://img.shields.io/badge/colcon-ROS2_Build-blue?style=flat-square)
![Git](https://img.shields.io/badge/Git-Version_Control-F05032?style=flat-square\&logo=git\&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-GUI-41CD52?style=flat-square\&logo=qt\&logoColor=white)

### ⏳ Still Learning...
![Isaac](https://img.shields.io/badge/-NVIDIA%20Isaac-76B900?style=flat-square&logo=nvidia&logoColor=white)

---

## 🧩 Engineering Philosophy

I care more about complete and reusable robot systems than isolated demonstrations.

```text
real task
    ↓
hardware and sensor constraints
    ↓
embedded control and safety
    ↓
motion control and ROS integration
    ↓
perception and task coordination
    ↓
experiments, documentation and deployment
```

I prefer systems that are:

- safe before powerful
- modular before complex
- reproducible before flashy
- maintainable before temporary
- verified on real hardware

---

## 🌱 AgroTech-SCAU

At [AgroTech-SCAU](https://github.com/AgroTech-SCAU), I contribute to:

- embedded control architecture
- robotic arm motion control
- mobile robot system integration
- project architecture and engineering standards
- technical mentoring and knowledge transfer

Representative team projects include:

- [Steering-Wheel-Chassis](https://github.com/AgroTech-SCAU/Steering-Wheel-Chassis)
- [Wheel-Rail-Integrated-Chassis](https://github.com/AgroTech-SCAU/Wheel-Rail-Integrated-Chassis)
- [Embedded-Electronic-Control-Standard](https://github.com/AgroTech-SCAU/Embedded-Electronic-Control-Standard)
- [Robotic-Arm-Motion-Control-Standard](https://github.com/AgroTech-SCAU/Robotic-Arm-Motion-Control-Standard)

---

## 📊 GitHub Stats

<div align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats">
      <img alt="Kaede-Rei's Github Stats" src="https://github-readme-stats-flame-gamma-74.vercel.app/api/?username=Kaede-Rei&show_icons=true&count_private=true&theme=default&hide_border=true&bg_color=fff&title_color=00E676&icon_color=00E676" height="192px"/>
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats">
        <img alt="Kaede-Rei's Top Languages" src="https://github-readme-stats-flame-gamma-74.vercel.app/api/top-langs/?username=Kaede-Rei&langs_count=8&layout=compact&theme=default&hide_border=true&bg_color=fff&title_color=000" height="192px"/>
    </a>
</div>
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Kaede-Rei&theme=react-dark&hide_border=true" alt="Contribution Graph" style="width: 100%;"/>
</div>

---

## 📫 Contact

* GitHub: [Kaede-Rei](https://github.com/Kaede-Rei)
* Blog: [kaede-rei.github.io](https://kaede-rei.github.io/)
* Email: [kaerei86@gmail.com](mailto:kaerei86@gmail.com)

---
