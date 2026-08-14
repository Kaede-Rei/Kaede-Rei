# 👋 你好，我是 Kaede Rei

**中文** | [English](README.md)

> 华南农业大学本科生 | 机器人与嵌入式系统开发者 | AgroTech-SCAU 负责人

> 从 **MCU 底层控制** 到 **机器人操作**、**ROS 集成** 与 **真实机器人部署**，构建可复用的机器人系统

我目前就读于华南农业大学，主要围绕农业机器人与真实场景机器人系统开展学习、研究与工程实践

目前的工作重点包括：

* 嵌入式控制与机器人硬件接口
* 串联机械臂控制、运动学与动力学
* ROS 与 MoveIt 机器人操作系统
* 机器人标定与 RGB-D 感知集成
* 遥操作与真实机器人数据采集
* 农业移动操作机器人

同时，我也是 [AgroTech-SCAU](https://github.com/AgroTech-SCAU) 的主要负责人之一，主要负责嵌入式控制、机械臂系统、机器人系统集成、工程规范与项目组织

我的目标是构建不仅能够完成 Demo，同时具备可复用、可测试、可维护并能够部署到真实硬件上的机器人软件系统

---

## 🔬 当前工作

我目前的工作主要围绕真实机器人系统的四个相互关联的层级展开

### ⚙️ 嵌入式控制与机器人硬件

开发面向移动机器人、机械臂和执行机构的 MCU 实时控制系统与硬件接口，包括：

* 电机与执行机构控制
* CAN 与串口通信
* IMU 与轮式里程计数据处理
* MCU 端局部位姿估计
* 基于 IMU + 里程计的空白地图简易导航
* 层级状态机
* 手动 / 自主控制权仲裁
* 急停、超时与故障保护
* MCU–Linux 通信

### 🦾 串联机械臂控制

面向自研串联机械臂构建可复用的控制基础设施，包括：

* 机器人模型抽象
* 关节与执行器映射
* 正运动学与逆运动学
* 刚体动力学
* 重力补偿
* 硬件抽象
* CAN / 串口通信链路
* 安全与指令校验
* ROS 2 / ros2_control 集成
* MoveIt 2 集成

目前这一方向的主要平台是 [SerialArm-Core](https://github.com/Kaede-Rei/SerialArm-Core)

### 🍅 机器人操作与农业机器人

在机器人控制基础设施之上，我进一步开展真实机器人操作任务，包括：

* 番茄采摘
* 末端执行器控制
* RGB-D 感知集成
* Planning Scene 构建
* 手眼标定与多相机标定
* 机械臂运动规划
* 底盘与机械臂系统集成
* 柔顺拨叶实验

目前 ROS 2 应用层主要在 [Tomato-Picker-ROS2](https://github.com/Kaede-Rei/Tomato-Picker-ROS2) 中开发

### 🧠 遥操作与学习型机器人操作

同时探索基于学习的机器人操作方法，包括：

* 主从遥操作
* 双臂遥操作
* 真实机器人数据采集
* LeRobot
* 模仿学习
* 仿真实验
* 学习型机器人操作策略

这一方向目前仍以实验与探索为主，用于补充而不是替代传统机器人控制系统

> **关于移动导航的贡献边界：**
> 
> 我个人在移动导航方向的工作主要集中于 MCU 端 IMU / 轮式里程计处理、局部位姿估计以及基于 IMU + 里程计的空白地图简易导航
> 
> 团队平台中的 SLAM、全局定位以及 ROS 2 / Nav2 导航系统主要由其他成员负责，不作为我的个人实现进行展示

---

## 📌 项目地图

我的仓库主要分为两部分：个人机器人项目，以及我在 [AgroTech-SCAU](https://github.com/AgroTech-SCAU) 中开发或负责的机器人系统

### 🚀 主要个人项目

| 项目                                                                                | 方向        | 当前定位                                                                 |
| --------------------------------------------------------------------------------- | --------- | -------------------------------------------------------------------- |
| [SerialArm-Core](https://github.com/Kaede-Rei/SerialArm-Core)                     | 机器人控制基础设施 | 面向自研串联机械臂的 C++17 控制、动力学、安全、硬件抽象、通信与框架适配核心                            |
| [Tomato-Picker-ROS2](https://github.com/Kaede-Rei/Tomato-Picker-ROS2)             | 农业机器人操作   | 基于 SerialArm-Core 构建的 ROS 2 + MoveIt 2 番茄采摘应用栈，覆盖运动、末端执行器、感知、任务与整机部署 |
| [Dual-DM-Arm-LeRobot](https://github.com/Kaede-Rei/Dual-DM-Arm-LeRobot)           | 具身机器人操作   | 双臂遥操作、真实机器人数据采集、LeRobot 集成、模仿学习与策略部署实验                               |
| [Hand-Eye-GUI-Tools](https://github.com/Kaede-Rei/Hand-Eye-GUI-Tools)             | 机器人标定     | 面向眼在手上、眼在手外以及相机间外参标定的 GUI 工具                                         |
| [Tomato-Push-Aside-Leaves](https://github.com/Kaede-Rei/Tomato-Push-Aside-Leaves) | 农业机器人操作   | 柔顺拨叶、主动感知以及遮挡条件下机器人操作研究                                              |

### 🌱 AgroTech-SCAU 项目

以下仓库是我在 [AgroTech-SCAU](https://github.com/AgroTech-SCAU) 中开发或负责的项目，覆盖移动机器人、双臂机器人、嵌入式基础设施以及可复用机器人软件工程规范

| 项目                                                                                                            | 方向        | 我的工作                                                                    |
| ------------------------------------------------------------------------------------------------------------- | --------- | ----------------------------------------------------------------------- |
| [Steering-Wheel-Chassis](https://github.com/AgroTech-SCAU/Steering-Wheel-Chassis)                             | 移动机器人     | MCU 底盘控制、电机控制、IMU 与轮式里程计处理、局部位姿估计、空白地图简易导航、状态机、安全机制、MCU–Linux 通信与整车系统集成 |
| [Tea-Picking-Dual-Arm](https://github.com/AgroTech-SCAU/Tea-Picking-Dual-Arm)                                 | 双臂机器人     | 双臂茶叶采摘平台、主从遥操作、机械臂通信与控制集成、双臂协同以及真机演示 / 数据采集基础设施                         |
| [Wheel-Rail-Integrated-Chassis](https://github.com/AgroTech-SCAU/Wheel-Rail-Integrated-Chassis)               | 移动机器人     | 轮轨复合移动平台、嵌入式运动控制、执行机构集成、通信与整机控制原型                                       |
| [Embedded-Electronic-Control-Standard](https://github.com/AgroTech-SCAU/Embedded-Electronic-Control-Standard) | 嵌入式基础设施   | 可复用嵌入式架构、驱动 / SDK 组织、通信接口、安全机制、代码规范与机器人项目工程标准                           |
| [Robotic-Arm-Motion-Control-Standard](https://github.com/AgroTech-SCAU/Robotic-Arm-Motion-Control-Standard)   | 机器人软件基础设施 | 可复用机械臂软件架构，包括硬件接口、运动控制组织、ROS 集成、项目结构与工程规范                               |

> **移动导航贡献边界**
>
> 我在 `Steering-Wheel-Chassis` 中的工作主要集中于嵌入式控制与系统集成层，包括 IMU / 里程计处理、局部位姿估计以及 MCU 端空白地图简易导航
>
> 完整团队平台中的 LiDAR SLAM、全局定位、路径规划以及 ROS 2 / Nav2 导航模块由其他团队成员开发，不作为我的个人实现进行展示

### 🔧 支撑项目与历史项目

<details>
<summary><strong>展开支撑项目与历史项目</strong></summary>

<br>

| 项目                                                                              | 参考价值                                    |
| ------------------------------------------------------------------------------- | --------------------------------------- |
| [DM-Arm-MoveIt2](https://github.com/Kaede-Rei/DM-Arm-MoveIt2)                   | 早期 MoveIt 2 集成、可达位姿评价与机械臂运动规划实验         |
| [Renesas-DM-Arm](https://github.com/Kaede-Rei/Renesas-DM-Arm)                   | MCU 端机械臂运动学、CAN 电机控制、通信与 HFSM 实现        |
| [Multi-Arm-Controller](https://github.com/Kaede-Rei/Multi-Arm-Controller)       | 多机械臂规划接口与可达位姿搜索原型                       |
| [Lift-Gripper-Controller](https://github.com/Kaede-Rei/Lift-Gripper-Controller) | 包含电机控制、PID、CAN 通信与 HFSM 的嵌入式升降与夹爪控制器    |
| [Tomato-Picker-PiPER](https://github.com/Kaede-Rei/Tomato-Picker-PiPER)         | 早期基于 ROS 1、MoveIt、RGB-D、点云与 GUI 的番茄采摘系统 |
| [Tomato-Picker-DM](https://github.com/Kaede-Rei/Tomato-Picker-DM)               | 早期达妙机械臂番茄采摘系统与 ROS 1 → ROS 2 迁移参考       |
| [Visial-Robotic-Arm-Car](https://github.com/Kaede-Rei/Visial-Robotic-Arm-Car)   | 早期视觉移动操作机器人综合原型                         |
| [Embedded-About](https://github.com/Kaede-Rei/Embedded-About)                   | 早期嵌入式系统项目索引与归档                          |

</details>

### 🛠️ 个人基础设施

<details>
<summary><strong>展开个人基础设施</strong></summary>

<br>

| 项目                                                                      | 定位        |
| ----------------------------------------------------------------------- | --------- |
| [kaede-rei.github.io](https://github.com/Kaede-Rei/kaede-rei.github.io) | 个人网站与技术笔记 |
| [Resume-Template](https://github.com/Kaede-Rei/Resume-Template)         | 个人简历与文档模板 |

</details>

---

## 🧰 技术栈

### 💻 编程语言

![C](https://img.shields.io/badge/-C-000000?style=flat-square\&logo=c\&logoColor=white)
![C++](https://img.shields.io/badge/-C++-5C3EE8?style=flat-square\&logo=cplusplus\&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square\&logo=rust)

### ⚙️ 嵌入式系统

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square\&logo=stmicroelectronics\&logoColor=white)
![Renesas](https://img.shields.io/badge/-Renesas-CC0000?style=flat-square)
![ESP32](https://img.shields.io/badge/-ESP32-E7352C?style=flat-square)
![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=flat-square)
![CAN](https://img.shields.io/badge/-CAN%20Bus-00599C?style=flat-square)
![RTOS](https://img.shields.io/badge/-RTOS-5C3EE8?style=flat-square)
![LVGL](https://img.shields.io/badge/-LVGL-FF6F00?style=flat-square)
![Vision](https://img.shields.io/badge/-Embedded%20Vision-5C3EE8?style=flat-square)
![PCB](https://img.shields.io/badge/-PCB%20Design-00599C?style=flat-square)

### 🤖 机器人与控制

![ROS](https://img.shields.io/badge/ROS-Noetic%20%7C%20Humble-22314E?style=flat-square\&logo=ros\&logoColor=white)
![MoveIt](https://img.shields.io/badge/MoveIt-Motion_Planning-blueviolet?style=flat-square)
![ros2\_control](https://img.shields.io/badge/ros2__control-Hardware_Interface-blue?style=flat-square)
![Pinocchio](https://img.shields.io/badge/Pinocchio-Dynamics-green?style=flat-square)
![RViz](https://img.shields.io/badge/-RViz-22314E?style=flat-square)
![Gazebo](https://img.shields.io/badge/-Gazebo-2C3E50?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer_Vision-5C3EE8?style=flat-square\&logo=opencv\&logoColor=white)
![LeRobot](https://img.shields.io/badge/-🤗%20LeRobot-E7352C?style=flat-square)

### 🧪 工具与平台

![Linux](https://img.shields.io/badge/Linux-Ubuntu-E95420?style=flat-square\&logo=ubuntu\&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-Build-064F8C?style=flat-square\&logo=cmake\&logoColor=white)
![Colcon](https://img.shields.io/badge/colcon-ROS2_Build-blue?style=flat-square)
![Git](https://img.shields.io/badge/Git-Version_Control-F05032?style=flat-square\&logo=git\&logoColor=white)
![Qt](https://img.shields.io/badge/Qt-GUI-41CD52?style=flat-square\&logo=qt\&logoColor=white)

### ⏳ 仍在学习

![Isaac](https://img.shields.io/badge/-NVIDIA%20Isaac-76B900?style=flat-square\&logo=nvidia\&logoColor=white)

---

## 🌱 AgroTech-SCAU

我是 [AgroTech-SCAU](https://github.com/AgroTech-SCAU) 的主要负责人之一

目前主要负责：

* 嵌入式控制架构
* MCU 固件与机器人硬件接口
* 机械臂运动控制系统
* CAN / 串口通信架构
* 机器人系统集成
* 工程规范与可复用基础设施
* 项目架构与技术指导

在移动机器人平台中，我的工作主要集中于底层控制与系统集成：

```text
电机 / 编码器 / IMU
        ↓
MCU 实时控制
        ↓
IMU + 里程计处理
        ↓
局部位姿 / 空白地图导航
        ↓
通信桥接
        ↓
上层机器人系统
```

完整的团队机器人平台还可能包含 LiDAR SLAM、定位、全局规划、Nav2 等导航组件

这些部分由团队成员协作开发，并非我的个人实现

---

## 📊 GitHub 统计

<div align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats">
      <img alt="Kaede-Rei 的 GitHub 统计" src="https://github-readme-stats-flame-gamma-74.vercel.app/api/?username=Kaede-Rei&show_icons=true&count_private=true&theme=default&hide_border=true&bg_color=fff&title_color=00E676&icon_color=00E676" height="192px"/>
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats">
        <img alt="Kaede-Rei 常用语言" src="https://github-readme-stats-flame-gamma-74.vercel.app/api/top-langs/?username=Kaede-Rei&langs_count=8&layout=compact&theme=default&hide_border=true&bg_color=fff&title_color=000" height="192px"/>
    </a>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Kaede-Rei&theme=react-dark&hide_border=true" alt="贡献活动图" style="width: 100%;"/>
</div>

---

## 📫 联系方式

* GitHub：[Kaede-Rei](https://github.com/Kaede-Rei)
* 博客：[kaede-rei.github.io](https://kaede-rei.github.io/)
* 邮箱：[kaerei86@gmail.com](mailto:kaerei86@gmail.com)
* 邮箱：[kaerei@foxmail.com](mailto:kaerei@foxmail.com)

---
