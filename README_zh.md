# 👋 嗨，我是 Kaede Rei

**中文** | [English](README.md)

🎓 **华南农业大学 (SCAU) 本科生** | 🌾 **广东省农科院 (GAAS) 项目合作成员** </br>
有志成为 💻 嵌入式软件工程师 | 🤖 农业机器人开发人员 | 🧠 具身智能探索者

专注于 **嵌入式系统 / 六轴机械臂 / ROS / 具身智能 (IL + RL)**，
面向农业自动化场景，从「底层驱动 + 运动控制 + ROS 系统集成 + 学习型策略」构建机器人机械臂电控与具身智能控制系统

当前重点方向：

- 六轴机械臂控制系统与运动学/轨迹规划
- 嵌入式控制器与驱动链路开发
- ROS / MoveIt / 机器人系统集成
- 模仿学习（IL）与强化学习（RL）实机探索
- 农业场景下的机器人应用落地

---

## 🧩 技术栈

### 🔹 编程语言
![C](https://img.shields.io/badge/-C-000000?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/-C++-5C3EE8?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust)

### 🔹 嵌入式系统
![STM32](https://img.shields.io/badge/-STM32-03234B?style=flat-square)
![Renesas](https://img.shields.io/badge/-Renesas-CC0000?style=flat-square)
![ESP32](https://img.shields.io/badge/-ESP32-E7352C?style=flat-square)
![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=flat-square)
![CAN](https://img.shields.io/badge/-CAN%20Bus-00599C?style=flat-square)
![RTOS](https://img.shields.io/badge/-RTOS-5C3EE8?style=flat-square)
![LVGL](https://img.shields.io/badge/-LVGL-FF6F00?style=flat-square)
![Vision](https://img.shields.io/badge/-Embedded%20Vision-5C3EE8?style=flat-square)
![PCB](https://img.shields.io/badge/-PCB%20Design-00599C?style=flat-square)

### 🔹 机器人与控制
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/-CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![ROS](https://img.shields.io/badge/-ROS1/2-22314E?style=flat-square&logo=ros)
![MATLAB](https://img.shields.io/badge/-MATLAB-0076A8?style=flat-square)
![MoveIt](https://img.shields.io/badge/-MoveIt1/2-FF6F00?style=flat-square)
![Pinocchio](https://img.shields.io/badge/-Pinocchio-EE7C21?style=flat-square)
![RViz](https://img.shields.io/badge/-RViz-22314E?style=flat-square)
![Gazebo](https://img.shields.io/badge/-Gazebo-2C3E50?style=flat-square)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=flat-square&logo=opencv)
![LeRobot](https://img.shields.io/badge/-🤗%20LeRobot-E7352C?style=flat-square)


### ⏳ 持续学习中...
![Isaac](https://img.shields.io/badge/-NVIDIA%20Isaac-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Qt](https://img.shields.io/badge/-Qt-41CD52?style=flat-square&logo=qt&logoColor=white)

---

## 核心能力

- **嵌入式控制架构**  
  裸机 / RTOS 系统架构设计，BSP 分层，驱动抽象，多执行器协同

- **通信与设备集成**  
  CAN / SCI / 无线链路，通信协议实现，多机协同联动，硬件链路联调

- **机械臂建模与运动求解**  
  MDH 建模，正/逆运动学，刚体动力学（通过Pinocchio），位姿可达性处理，环境感知规划

- **控制接口与任务框架**  
  控制器抽象，命令分发，系统接口设计，末端执行器集成，任务链组织

- **具身智能 Manipulation**  
  遥操作采集，数据集构建，策略训练与推理部署，LeRobot / ACT / SmolVLA 实机流程

- **工程验证与工具链**  
  CMake / Ninja，ARM GNU Toolchain，FSP / RASC，MATLAB 验证，Python 辅助联调
  
---

## 🚧 参与项目

| 项目 | 应用场景 | 技术栈 | 描述 |
|--------|-------------|-------|------------|
| 🦾 番茄采摘机器人 | 精准农业 | STM32 + ROS + MoveIt | 机械臂底层驱动、运动学解算、ROS 控制链路，面向精准农业操作 |
| 🐦 鸽笼自动换料系统 | 畜牧自动化 | MCU + RTOS | 自动换料系统设计，从裸机重构至 RTOS，实现稳定可靠的饲料管理 |
| 🚗 舵轮轮轨一体底盘 | 农业移动平台 | 电机驱动 + SDK | 舵轮控制、底盘运动学与通信协议设计，实现复杂地形下的移动能力 |
| 🤝 双臂 IL + RL 协同系统 | 农业机械臂协作研究 | LeRobot + ROS2 | 面向真实机械臂的模仿学习与强化学习协同策略研究与部署 |

### **部分项目仓库地址**：

- [Dual-DM-Arm-LeRobot](https://github.com/Kaede-Rei/Dual-DM-Arm-LeRobot)
- [Tomato-Picker-PiPER](https://github.com/Kaede-Rei/Tomato-Picker-PiPER)
- [Renesas-DM-Arm](https://github.com/Kaede-Rei/Renesas-DM-Arm)

---

## 📌 关于我

- 我更关注**完整工程链路**，不局限于单点功能实现
- 我长期聚焦**农业机器人**，希望把机械臂控制、导航、视觉与智能策略逐步整合成可运行的平台
- 我对“**可靠、可维护、可部署**”的机器人系统比单纯 demo 更感兴趣
- 目前也在持续学习 Qt、Rust、具身智能，获得更完整的机器人软件架构能力

---

## 📊 GitHub 统计

<div align="center">
    <a href="https://github.com/anuraghazra/github-readme-stats">
      <img alt="Kaede-Rei 的 Github 统计" src="https://github-readme-stats-flame-gamma-74.vercel.app/api/?username=Kaede-Rei&show_icons=true&count_private=true&theme=default&hide_border=true&bg_color=fff&title_color=00E676&icon_color=00E676" height="192px"/>
    </a>
    <a href="https://github.com/anuraghazra/github-readme-stats">
        <img alt="Kaede-Rei 的常用语言" src="https://github-readme-stats-flame-gamma-74.vercel.app/api/top-langs/?username=Kaede-Rei&langs_count=8&layout=compact&theme=default&hide_border=true&bg_color=fff&title_color=000" height="192px"/>
    </a>
</div>
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Kaede-Rei&theme=react-dark&hide_border=true" alt="贡献图" style="width: 100%;"/>
</div>

---

## 联系方式

- Blog: https://kaede-rei.github.io/
- GitHub: https://github.com/Kaede-Rei
- EMail: kaerei86@gmail.com
