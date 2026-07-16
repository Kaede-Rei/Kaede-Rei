# 👋 你好，我是 Kaede Rei

**中文** | [English](README.md)

> 华南农业大学本科生 | 农业机器人开发者 | AgroTech-SCAU 负责人之一

> 专注于 **嵌入式控制**、**机械臂运动控制** 与 **农业机器人系统集成**。

我目前就读于华南农业大学，主要围绕农业机器人系统开展学习、研究与项目实践，关注如何将嵌入式控制、机械臂、感知系统、ROS 与真实机器人部署连接起来。

目前，我是 [AgroTech-SCAU](https://github.com/AgroTech-SCAU) 的主要负责人之一，主要负责：

* 电控系统架构
* 机械臂运动控制
* 机器人系统集成
* 工程规范与项目组织

---

## 🔬 当前研究方向

我目前的工作主要围绕温室移动操作机器人展开，覆盖四个相互关联的方向。

### ⚙️ 嵌入式控制与移动平台

开发面向移动底盘、机械臂和执行机构的 MCU 实时控制系统，主要包括：

* 电机与执行机构控制
* CAN 与串口通信
* IMU 与里程计数据处理
* 层级状态机
* 手动与自主控制权仲裁
* 急停、超时与故障保护
* MCU–Linux 通信与系统集成

### 🦾 机器人运动控制与 ROS 集成

构建可复用的 Linux 与 ROS 机器人控制系统，主要包括：

* ROS 2 control 硬件接口
* 机械臂运动学与动力学
* 重力补偿
* 阻抗与导纳控制
* MoveIt 2 运动规划
* 导航与底盘控制接口
* 异步任务编排
* 底盘与机械臂协同

### 🍅 农业移动操作

研究温室环境中的机器人作业任务，主要包括：

* 番茄采摘
* 柔顺拨叶
* 主动感知
* RGB-D 感知与手眼标定
* 温室导航
* 移动底盘与机械臂协同

### 🧠 具身智能

探索基于学习的机器人操作方法，主要包括：

* 主从遥操作
* 真实机器人数据采集
* LeRobot 与模仿学习
* 仿真与 Sim-to-Real
* 自主拨叶操作
* 学习型操作策略部署

---

## 📌 项目地图

以下仓库按照它们当前在研究、工程开发和知识复用中的作用进行分类。

### 当前研究与主要平台

| 项目                                                                                                            | 方向      | 当前定位                                     |
| ------------------------------------------------------------------------------------------------------------- | ------- | ---------------------------------------- |
| [DM-Arm-Hardware-Interface](https://github.com/Kaede-Rei/DM-Arm-Hardware-Interface)                           | 机械臂控制   | 达妙机械臂 ROS 2 主平台，包含硬件接口、动力学与柔顺控制          |
| [Tomato-Push-Aside-Leaves](https://github.com/Kaede-Rei/Tomato-Push-Aside-Leaves)                             | 农业机器人操作 | 面向温室采摘的拨叶与主动感知研究                         |
| [Dual-DM-Arm-LeRobot](https://github.com/Kaede-Rei/Dual-DM-Arm-LeRobot)                                       | 具身智能    | 双臂遥操作、真实机器人数据集、模仿学习与策略部署                 |
| [DM-Arm-MoveIt2](https://github.com/Kaede-Rei/DM-Arm-MoveIt2)                                                 | 运动规划    | MoveIt 2 集成、可达位姿评价与操作任务规划实验              |
| [AgroTech-SCAU/Steering-Wheel-Chassis](https://github.com/AgroTech-SCAU/Steering-Wheel-Chassis)               | 移动机器人   | Atlas 底盘主仓库，覆盖嵌入式控制、MCU–Linux 集成、导航与自主任务 |
| [AgroTech-SCAU/Wheel-Rail-Integrated-Chassis](https://github.com/AgroTech-SCAU/Wheel-Rail-Integrated-Chassis) | 移动机器人   | 轮轨复合底盘平台与控制原型                            |

### 工具、规范与支撑仓库

| 项目                                                                                                                                | 定位                      |
| --------------------------------------------------------------------------------------------------------------------------------- | ----------------------- |
| [Hand-Eye-GUI-Tools](https://github.com/Kaede-Rei/Hand-Eye-GUI-Tools)                                                             | 手眼、眼在手外与多相机标定工具         |
| [AgroTech-SCAU/Steering-Wheel-Chassis-Model-Collection](https://github.com/AgroTech-SCAU/Steering-Wheel-Chassis-Model-Collection) | 舵轮底盘机械模型与设计资料           |
| [AgroTech-SCAU/Embedded-Electronic-Control-Standard](https://github.com/AgroTech-SCAU/Embedded-Electronic-Control-Standard)       | 嵌入式架构、通用 SDK、通信、安全与开发规范 |
| [AgroTech-SCAU/Robotic-Arm-Motion-Control-Standard](https://github.com/AgroTech-SCAU/Robotic-Arm-Motion-Control-Standard)         | 可复用的 ROS 与机械臂运动控制架构     |

<details>
<summary><strong>历史项目与工程参考</strong></summary>

<br>

以下仓库作为历史实现、迁移来源或工程参考继续保留。

| 项目                                                                              | 参考价值                                     |
| ------------------------------------------------------------------------------- | ---------------------------------------- |
| [Tomato-Picker-PiPER](https://github.com/Kaede-Rei/Tomato-Picker-PiPER)         | 基于 ROS1、MoveIt、RGB-D、点云和 GUI 的完整番茄采摘流程参考 |
| [Tomato-Picker-DM](https://github.com/Kaede-Rei/Tomato-Picker-DM)               | 达妙机械臂 ROS1 采摘系统与 ROS 2 迁移参考              |
| [Renesas-DM-Arm](https://github.com/Kaede-Rei/Renesas-DM-Arm)                   | MCU 端机械臂运动学、CAN 电机控制、通信与 HFSM 参考         |
| [Multi-Arm-Controller](https://github.com/Kaede-Rei/Multi-Arm-Controller)       | 多机械臂规划接口与可达位姿搜索原型                        |
| [Lift-Gripper-Controller](https://github.com/Kaede-Rei/Lift-Gripper-Controller) | 包含 PID、CAN 通信和 HFSM 的升降与夹爪控制器            |
| [Steering-Wheel-Chassis](https://github.com/Kaede-Rei/Steering-Wheel-Chassis)   | 底盘项目的个人早期版本，当前开发已迁移至 AgroTech-SCAU       |
| [Visial-Robotic-Arm-Car](https://github.com/Kaede-Rei/Visial-Robotic-Arm-Car)   | 早期视觉、机械臂与移动底盘综合原型                        |
| [Embedded-About](https://github.com/Kaede-Rei/Embedded-About)                   | 早期嵌入式项目索引与归档                             |

</details>

<details>
<summary><strong>个人基础设施与其他仓库</strong></summary>

<br>

| 项目                                                                      | 定位                 |
| ----------------------------------------------------------------------- | ------------------ |
| [Kaede-Rei](https://github.com/Kaede-Rei/Kaede-Rei)                     | GitHub 个人主页 README |
| [kaede-rei.github.io](https://github.com/Kaede-Rei/kaede-rei.github.io) | 个人网站与技术博客          |
| [Resume-Template](https://github.com/Kaede-Rei/Resume-Template)         | 个人简历与文档模板          |

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

## 🧩 工程理念

相比孤立的功能演示，我更关注完整且可复用的机器人系统。

```text
真实任务
    ↓
硬件与传感器约束
    ↓
嵌入式控制与安全保护
    ↓
运动控制与 ROS 集成
    ↓
感知与任务编排
    ↓
实验、文档与真实部署
```

我更倾向于构建这样的系统：

* 安全优先于性能堆叠
* 模块化优先于复杂堆砌
* 可复现优先于表面效果
* 可维护优先于临时可用
* 在真实硬件上完成验证

---

## 🌱 AgroTech-SCAU

在 [AgroTech-SCAU](https://github.com/AgroTech-SCAU) 中，我主要参与：

* 嵌入式控制架构建设
* 机械臂运动控制
* 移动机器人系统集成
* 项目架构与工程规范
* 技术指导与知识传承

代表性的团队项目包括：

* [Steering-Wheel-Chassis](https://github.com/AgroTech-SCAU/Steering-Wheel-Chassis)
* [Wheel-Rail-Integrated-Chassis](https://github.com/AgroTech-SCAU/Wheel-Rail-Integrated-Chassis)
* [Embedded-Electronic-Control-Standard](https://github.com/AgroTech-SCAU/Embedded-Electronic-Control-Standard)
* [Robotic-Arm-Motion-Control-Standard](https://github.com/AgroTech-SCAU/Robotic-Arm-Motion-Control-Standard)

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

---
