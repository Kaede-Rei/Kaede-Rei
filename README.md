# 👋 Hi, I'm Kaede Rei

[中文](README_zh.md) | **English**

> SCAU Undergraduate | Robotics & Embedded Systems Developer | AgroTech-SCAU Lead

> Building reusable robot systems from **MCU-level control** to **robot manipulation**, **ROS integration**, and **real-world deployment**

I am an undergraduate student at South China Agricultural University, working on robotics systems for agricultural and real-world applications

My current work focuses on:

- embedded control and robot hardware interfaces
- serial manipulator control, kinematics, and dynamics
- ROS and MoveIt manipulation systems
- robot calibration and RGB-D perception integration
- teleoperation and real-robot data collection
- agricultural mobile manipulation

I am also one of the main leads of [AgroTech-SCAU](https://github.com/AgroTech-SCAU), where I mainly work on embedded control, robotic-arm systems, robot integration, engineering standards, and project organization

My goal is to build robot software that is not only demonstrable, but also reusable, testable, and deployable on real hardware

---

## 🔬 Current Work

My current work is organized around four connected layers of a real robot system

### ⚙️ Embedded Control & Robot Hardware

I develop MCU-side control systems and hardware interfaces for mobile robots, robotic arms, and actuators, including:

- motor and actuator control
- CAN and serial communication
- IMU and wheel-odometry processing
- MCU-side local pose estimation
- simple IMU + odometry based navigation on blank maps
- hierarchical state machines
- manual / autonomous control arbitration
- emergency stop, timeout, and fault protection
- MCU–Linux communication

### 🦾 Serial Manipulator Control

I am developing reusable control infrastructure for custom serial manipulators, including:

- robot model abstraction
- joint and actuator mapping
- forward and inverse kinematics
- rigid-body dynamics
- gravity compensation
- hardware abstraction
- CAN / serial transport
- safety and command validation
- ROS 2 / ros2_control integration
- MoveIt 2 integration

My current main platform for this work is [SerialArm-Core](https://github.com/Kaede-Rei/SerialArm-Core)

### 🍅 Robot Manipulation & Agricultural Robotics

On top of the robot-control layer, I work on real manipulation applications such as:

- tomato harvesting
- end-effector control
- RGB-D perception integration
- Planning Scene construction
- hand–eye and multi-camera calibration
- robotic-arm motion planning
- base–arm system integration
- compliant leaf manipulation experiments

The current ROS 2 application stack is being developed in [Tomato-Picker-ROS2](https://github.com/Kaede-Rei/Tomato-Picker-ROS2)

### 🧠 Teleoperation & Learning-Based Manipulation

I am also exploring learning-based robot manipulation through:

- leader–follower teleoperation
- dual-arm teleoperation
- real-robot dataset collection
- LeRobot
- imitation learning
- simulation experiments
- learned manipulation policies

This direction is currently experimental and complements, rather than replaces, the classical robot-control stack

> **Scope note on mobile navigation:**  
> My personal work on mobile navigation has mainly been MCU-side IMU / wheel-odometry processing, local pose estimation, and simple blank-map navigation
> SLAM, global localization, and the ROS 2 / Nav2 navigation stack used in team platforms are primarily developed by other team members and are not presented here as my personal implementation

---

## 📌 Project Map

My repositories are organized around two parts: my personal robotics projects and the systems I develop or lead within [AgroTech-SCAU](https://github.com/AgroTech-SCAU)

### 🚀 Main Personal Projects

| Project                                                                           | Area                         | Current Role                                                                                                                                      |
| --------------------------------------------------------------------------------- | ---------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| [SerialArm-Core](https://github.com/Kaede-Rei/SerialArm-Core)                     | Robot Control Infrastructure | Portable C++17 control, dynamics, safety, hardware abstraction, communication, and framework-adapter core for custom serial manipulators          |
| [Tomato-Picker-ROS2](https://github.com/Kaede-Rei/Tomato-Picker-ROS2)             | Agricultural Manipulation    | ROS 2 + MoveIt 2 tomato-picking application stack built on SerialArm-Core, covering motion, end-effector, perception, task, and deployment layers |
| [Dual-DM-Arm-LeRobot](https://github.com/Kaede-Rei/Dual-DM-Arm-LeRobot)           | Embodied Manipulation        | Dual-arm teleoperation, real-robot dataset collection, LeRobot integration, imitation learning, and policy deployment experiments                 |
| [Hand-Eye-GUI-Tools](https://github.com/Kaede-Rei/Hand-Eye-GUI-Tools)             | Robot Calibration            | GUI tools for eye-in-hand, eye-to-hand, and camera-to-camera calibration                                                                          |
| [Tomato-Push-Aside-Leaves](https://github.com/Kaede-Rei/Tomato-Push-Aside-Leaves) | Agricultural Manipulation    | Ongoing research on compliant leaf manipulation, active perception, and manipulation under occlusion                                              |

### 🌱 AgroTech-SCAU Projects

These repositories are developed or led by me as part of [AgroTech-SCAU](https://github.com/AgroTech-SCAU), covering mobile robots, dual-arm systems, embedded infrastructure, and reusable robotics engineering standards

| Project                                                                                                       | Area                          | My Work                                                                                                                                                                                                                 |
| ------------------------------------------------------------------------------------------------------------- | ----------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Steering-Wheel-Chassis](https://github.com/AgroTech-SCAU/Steering-Wheel-Chassis)                             | Mobile Robot                  | MCU-side chassis control, motor control, IMU and wheel-odometry processing, local pose estimation, simple blank-map navigation, state machines, safety logic, MCU–Linux communication, and complete vehicle integration |
| [Tea-Picking-Dual-Arm](https://github.com/AgroTech-SCAU/Tea-Picking-Dual-Arm)                                 | Dual-Arm Robotics             | Dual-arm tea-picking platform, leader–follower teleoperation, arm communication and control integration, dual-arm coordination, and real-robot demonstration / data-collection infrastructure                           |
| [Wheel-Rail-Integrated-Chassis](https://github.com/AgroTech-SCAU/Wheel-Rail-Integrated-Chassis)               | Mobile Robot                  | Wheel–rail integrated mobile platform, embedded motion control, actuator integration, communication, and system-level control prototype                                                                                 |
| [Embedded-Electronic-Control-Standard](https://github.com/AgroTech-SCAU/Embedded-Electronic-Control-Standard) | Embedded Infrastructure       | Reusable embedded architecture, driver / SDK organization, communication interfaces, safety mechanisms, coding conventions, and engineering standards for robot projects                                                |
| [Robotic-Arm-Motion-Control-Standard](https://github.com/AgroTech-SCAU/Robotic-Arm-Motion-Control-Standard)   | Robot Software Infrastructure | Reusable robotic-arm software architecture covering hardware interfaces, motion-control organization, ROS integration, project structure, and engineering conventions                                                   |

> **Contribution boundary for mobile navigation**
>
> My work on `Steering-Wheel-Chassis` focuses on the embedded and system-integration layers, including IMU / odometry processing, local pose estimation, and simple MCU-side blank-map navigation
>
> The LiDAR SLAM, global localization, path planning, and ROS 2 / Nav2 navigation components contained in the complete team platform are developed by other team members and are not presented as my personal implementation

### 🔧 Supporting & Previous Projects

<details>
<summary><strong>Show supporting and previous projects</strong></summary>

<br>

| Project                                                                         | Reference Value                                                                                          |
| ------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| [DM-Arm-MoveIt2](https://github.com/Kaede-Rei/DM-Arm-MoveIt2)                   | Earlier MoveIt 2 integration, reachable-pose evaluation, and robotic-arm motion-planning experiments     |
| [Renesas-DM-Arm](https://github.com/Kaede-Rei/Renesas-DM-Arm)                   | MCU-side robotic-arm kinematics, CAN motor control, communication, and HFSM implementation               |
| [Multi-Arm-Controller](https://github.com/Kaede-Rei/Multi-Arm-Controller)       | Multi-arm planning interfaces and reachable-pose search prototype                                        |
| [Lift-Gripper-Controller](https://github.com/Kaede-Rei/Lift-Gripper-Controller) | Embedded lift and gripper controller with motor control, PID, CAN communication, and HFSM                |
| [Tomato-Picker-PiPER](https://github.com/Kaede-Rei/Tomato-Picker-PiPER)         | Earlier ROS 1 tomato-harvesting system with MoveIt, RGB-D perception, point clouds, and GUI task control |
| [Tomato-Picker-DM](https://github.com/Kaede-Rei/Tomato-Picker-DM)               | Earlier DM robotic-arm tomato-picking system and ROS 1 → ROS 2 migration reference                       |
| [Visial-Robotic-Arm-Car](https://github.com/Kaede-Rei/Visial-Robotic-Arm-Car)   | Early integrated visual mobile-manipulation prototype                                                    |
| [Embedded-About](https://github.com/Kaede-Rei/Embedded-About)                   | Archive and index of earlier embedded-system projects                                                    |

</details>

### 🛠️ Personal Infrastructure

<details>
<summary><strong>Show personal infrastructure</strong></summary>

<br>

| Project                                                                 | Role                                 |
| ----------------------------------------------------------------------- | ------------------------------------ |
| [kaede-rei.github.io](https://github.com/Kaede-Rei/kaede-rei.github.io) | Personal website and technical notes |
| [Resume-Template](https://github.com/Kaede-Rei/Resume-Template)         | Résumé and document templates        |

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

## 🌱 AgroTech-SCAU

I am one of the main leads of [AgroTech-SCAU](https://github.com/AgroTech-SCAU)

My main responsibilities include:

- embedded control architecture
- MCU firmware and robot hardware interfaces
- robotic-arm motion-control systems
- CAN / serial communication architecture
- robot system integration
- engineering standards and reusable infrastructure
- project architecture and technical mentoring

For mobile robot platforms, my work is mainly concentrated on the lower control and integration layers:

```text
motors / encoders / IMU
        ↓
MCU real-time control
        ↓
IMU + odometry processing
        ↓
local pose / blank-map navigation
        ↓
communication bridge
        ↓
upper-level robot system
```

The complete team platforms may also contain LiDAR SLAM, localization, global planning, Nav2, and other navigation components

Those components are developed collaboratively within the team and not my personal implementation

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
* Email: [kaerei@foxmail.com](mailto:kaerei@foxmail.com)

---
