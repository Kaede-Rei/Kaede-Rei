<!-- visual-profile-v2 -->
<p align="right"><strong>中文</strong> · <a href="README.md">English</a></p>
<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0%3A0F172A%2C55%3A6D28D9%2C100%3A0D9488&amp;height=190&amp;section=header&amp;text=Kaede%20Rei&amp;fontSize=48&amp;fontColor=FFFFFF&amp;fontAlignY=37&amp;desc=Robotics%20Developer&amp;descSize=18&amp;descAlignY=59&amp;animation=fadeIn" alt="Kaede Rei — Robotics Developer" width="100%" /></p>
<p align="center">
  <img src="https://img.shields.io/badge/Robotic%20Arms-7C3AED?style=for-the-badge" alt="Robotic Arms" />
  <img src="https://img.shields.io/badge/Embedded%20Software-0D9488?style=for-the-badge" alt="Embedded Software" />
  <img src="https://img.shields.io/badge/System%20Integration-2563EB?style=for-the-badge" alt="System Integration" />
</p>
<p align="center"><strong>🤖 机器人开发者</strong><br />🎓 华南农业大学本科生 &nbsp; · &nbsp; 🌱 AgroTech-SCAU 主要负责人之一</p>
<p align="center">
  <a href="https://kaede-rei.github.io/"><img src="https://img.shields.io/badge/Website-6366F1?style=flat-square&amp;logo=githubpages&amp;logoColor=white" alt="Website" /></a>
  <a href="mailto:kaerei86@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Gmail" /></a>
  <a href="https://github.com/AgroTech-SCAU"><img src="https://img.shields.io/badge/AgroTech%20SCAU-0D9488?style=flat-square&amp;logo=github&amp;logoColor=white" alt="AgroTech SCAU" /></a>
</p>

## 👋 关于我

我主要开发机械臂控制软件、机器人嵌入式系统与整机集成框架，围绕农业机器人和真实硬件开展工程实践；关注从模型、驱动与控制，到标定、任务编排和部署的完整开发过程

希望把具体机器人中的实现逐步沉淀为通用内核、可移植模块与可复用接口，让新的机器人项目能在已有能力上继续构建

## 🚀 代表工作

以下项目围绕 **通用化、可移植性与跨项目复用** 持续建设，覆盖我的个人与协会仓库；我在其中主导开发或承担主要代码贡献

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/Kaede-Rei/SerialArm-Core">🦾 SerialArm-Core</a></h3>
<p><img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square" alt="C++17" /> <img src="https://img.shields.io/badge/Dynamics%20Core-7C3AED?style=flat-square" alt="Dynamics Core" /></p>
<p>以构建通用、可扩展的 C++17 机械臂动力学内核为目标，围绕刚体动力学、重力补偿与动力学标定，将核心能力与具体机器人模型、执行器后端及上层框架解耦</p>
<p>通过 Robot Profile 与统一硬件接口适配不同机械臂，提供阻抗与导纳控制、Python Binding 及 ROS 2 / ros2_control / MoveIt 2 接入；配套 SerialArm Studio 组织模型、标定、控制与诊断流程；Linux 安装包见 <a href="https://github.com/Kaede-Rei/SerialArm-Core/releases">Releases</a></p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/AgroTech-SCAU/Competition-Robot-2026-Atlas">🤖 Atlas</a></h3>
<p><img src="https://img.shields.io/badge/STM32-03234B?style=flat-square" alt="STM32" /> <img src="https://img.shields.io/badge/Swerve%20%2B%205--DOF%20Arm-0D9488?style=flat-square" alt="Swerve + 5-DOF Arm" /></p>
<p>已在多台比赛轮式机器人上迭代与复用的嵌入式软件基线，持续面向通用化与配置化适配完善，核心覆盖 <strong>舵轮底盘控制、五轴机械臂运动控制、遥控器接入与主从遥操作</strong></p>
<p>围绕 MCU 驱动与通信、运动学与控制调度、状态机、控制权及故障处理完善复用边界，适配不同整车配置；整机层也实现了 YASMIN 任务状态机</p>
<p>Atlas 现作为归档基线保留，相关代码迁移至 <a href="https://github.com/AgroTech-SCAU/Competition-Robot-2026-Longinus">Longinus</a> 等 Competition-Robot-2026 项目继续演进</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/AgroTech-SCAU/Embedded-Electronic-Control-Standard">⚙️ Embedded Control SDK</a></h3>
<p><img src="https://img.shields.io/badge/MCU%20SDK-0D9488?style=flat-square" alt="MCU SDK" /> <img src="https://img.shields.io/badge/Drivers%20%26%20Architecture-334155?style=flat-square" alt="Drivers &amp; Architecture" /></p>
<p>以跨项目、跨 MCU 平台复用为目标，将设备驱动、基础模块与运动学算法从具体 HAL、板卡和项目业务中分离，逐步形成公共嵌入式软件基础</p>
<p>围绕平台接口、项目侧装配与分层边界组织设备 SDK 和通信能力，使新设备、新板卡能通过适配接入；同时统一超时、停止与故障处理约定</p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/AgroTech-SCAU/AT-System-Integration">🧩 AT-System-Integration</a></h3>
<p><img src="https://img.shields.io/badge/HSM%20%2B%20Behavior%20Tree-2563EB?style=flat-square" alt="HSM + Behavior Tree" /> <img src="https://img.shields.io/badge/Developing-B45309?style=flat-square" alt="Developing" /></p>
<p>以构建面向不同机器人与作业任务的通用集成框架为目标，通过统一能力接口与适配器连接机械臂、视觉、导航和电控后端，减少任务流程对单个项目实现的依赖</p>
<p>配套 ATIL Robot Studio 提供可视化状态编排、行为树任务设计与运行诊断入口；目前持续开发中，已有能力层 Mock 与行为树执行路径，真机接入按实际验证进度推进</p>
</td>
</tr>
</table>

## 🖥️ 工具与界面

<table>
<tr><th width="50%"><a href="https://github.com/Kaede-Rei/SerialArm-Core">🦾 SerialArm Studio</a></th><th width="50%"><a href="https://github.com/AgroTech-SCAU/AT-System-Integration">🧩 ATIL Robot Studio</a></th></tr>
<tr><td><a href="assets/serialarm-studio-dynamics.png"><img src="assets/serialarm-studio-dynamics.png" alt="动力学内核的标定与验证工作台" width="100%" /></a></td><td><a href="assets/atil-robot-studio-orchestration.png"><img src="assets/atil-robot-studio-orchestration.png" alt="AT-System-Integration · 可视化状态与任务编排" width="100%" /></a></td></tr>
<tr><td align="center"><sub>动力学内核的标定与验证工作台</sub></td><td align="center"><sub>AT-System-Integration · 可视化状态与任务编排</sub></td></tr>
</table>

<details>
<summary>📐 手眼标定工作台</summary>

<p align="center"><a href="https://raw.githubusercontent.com/AgroTech-SCAU/Handeye-Calibration-App/main/docs/images/launcher-connect.png"><img src="https://raw.githubusercontent.com/AgroTech-SCAU/Handeye-Calibration-App/main/docs/images/launcher-connect.png" alt="Handeye Calibration — camera and robot data inputs" width="100%" /></a></p>

</details>

## 🗺️ 项目地图

其他由我主导开发或承担主要代码贡献的代表项目

| 项目 | 方向与主要工作 |
| --- | --- |
| 📐 [Handeye-Calibration-App](https://github.com/AgroTech-SCAU/Handeye-Calibration-App) | 可视化手眼标定；相机与机器人数据接入、同步采样、求解诊断与独立几何验证 |
| 🍅 [Tomato-Manipulation](https://github.com/AgroTech-SCAU/Tomato-Manipulation) | 基于 SerialArm-Core 的番茄采摘应用；MoveIt 2 运动能力、末端执行器、RGB-D / Planning Scene 与采摘任务 |
| 🧠 [Dual-DM-Arm-LeRobot](https://github.com/Kaede-Rei/Dual-DM-Arm-LeRobot) | 双臂遥操作、示范数据采集与处理、LeRobot 硬件适配，以及模仿学习训练与策略部署实验 |
| 🍃 [Tea-Picking-Dual-Arm](https://github.com/AgroTech-SCAU/Tea-Picking-Dual-Arm) | HX-10HM 与 RM65-B 主从系统；关节映射、归零、重力补偿接入与单 / 双臂遥操作 |
| ⚙️ [Wheel-Rail-Integrated-Chassis](https://github.com/AgroTech-SCAU/Wheel-Rail-Integrated-Chassis) | STM32H723 底盘电控；四舵轮运动学、电机通信、遥控输入、控制调度与故障处理 |

## 🧰 技术栈

<p>
  <img src="https://img.shields.io/badge/C-555555?style=flat-square&amp;logo=c&amp;logoColor=white" alt="C" />
  <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&amp;logo=cplusplus&amp;logoColor=white" alt="C++17" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python" />
</p>
<p>
  <img src="https://img.shields.io/badge/ROS%202-22314E?style=flat-square&amp;logo=ros&amp;logoColor=white" alt="ROS 2" />
  <img src="https://img.shields.io/badge/MoveIt%202-7C3AED?style=flat-square" alt="MoveIt 2" />
  <img src="https://img.shields.io/badge/ros2__control-2563EB?style=flat-square" alt="ros2_control" />
  <img src="https://img.shields.io/badge/Pinocchio-059669?style=flat-square" alt="Pinocchio" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&amp;logo=opencv&amp;logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/LeRobot-B45309?style=flat-square&amp;logo=huggingface&amp;logoColor=white" alt="LeRobot" />
</p>
<p>
  <img src="https://img.shields.io/badge/STM32-03234B?style=flat-square&amp;logo=stmicroelectronics&amp;logoColor=white" alt="STM32" />
  <img src="https://img.shields.io/badge/CAN%20Bus-0D9488?style=flat-square" alt="CAN Bus" />
  <img src="https://img.shields.io/badge/Linux-334155?style=flat-square&amp;logo=linux&amp;logoColor=white" alt="Linux" />
  <img src="https://img.shields.io/badge/CMake-064F8C?style=flat-square&amp;logo=cmake&amp;logoColor=white" alt="CMake" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&amp;logo=git&amp;logoColor=white" alt="Git" />
</p>


- **🦾 机械臂**：运动学与刚体动力学（Pinocchio）、模型与动力学标定、关节控制与重力补偿、ROS 2 / MoveIt 2、手眼标定与 RGB-D 集成；进一步探索遥操作、示范采集与模仿学习
- **⚙️ 电控 / 嵌入式软件**：STM32、CAN / UART / SPI、执行器与 IMU 接口、舵轮底盘与五轴机械臂运控、遥控器与遥操作、IMU 与里程计处理、局部位姿估计、PID 与层级状态机，以及控制权、超时与故障管理
- **🧩 系统集成**：Linux 与 ROS 2、MCU–主机通信、坐标系与接口契约、任务状态机与行为树、配置管理、运行诊断与整机部署

## 🌱 AgroTech-SCAU

作为协会主要负责人之一，我同时参与具体代码开发与技术组织，包括项目架构、公共基础设施、模块接口协调、系统联调、工程规范、文档与成员技术指导

也为整机方案讨论和跨方向协作补充机械、视觉与移动导航方面的理论知识；主要开发方向仍是机械臂、电控与系统集成

<details>
<summary>🗃️ 历史项目与学习探索</summary>

- [Renesas-DM-Arm](https://github.com/Kaede-Rei/Renesas-DM-Arm)：早期 MCU 机械臂运动学、CAN 电机控制与状态机实践
- [DM-Arm-MoveIt2](https://github.com/Kaede-Rei/DM-Arm-MoveIt2)：MoveIt 2 接入与机械臂运动规划实验
- [Hand-Eye-GUI-Tools](https://github.com/Kaede-Rei/Hand-Eye-GUI-Tools)：基于 ROS Noetic 的手眼与多相机外参标定工具
- [Modern-Robotics-Curriculum](https://github.com/Kaede-Rei/Modern-Robotics-Curriculum)：AI 辅助整理的个人机器人学学习资料与教学实验

</details>

## 📊 开发活动

<table width="100%">
<tr>
<td width="50%" valign="top">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api?username=Kaede-Rei&amp;show_icons=true&amp;rank_icon=github&amp;role=OWNER%2CORGANIZATION_MEMBER%2CCOLLABORATOR&amp;include_all_commits=true&amp;hide=contribs&amp;show=contributions&amp;line_height=20&amp;card_width=450&amp;custom_title=Development%20Stats&amp;bg_color=0D1117&amp;title_color=C4B5FD&amp;text_color=C9D1D9&amp;icon_color=2DD4BF&amp;border_color=30363D" />
  <img src="https://github-stats-extended.vercel.app/api?username=Kaede-Rei&amp;show_icons=true&amp;rank_icon=github&amp;role=OWNER%2CORGANIZATION_MEMBER%2CCOLLABORATOR&amp;include_all_commits=true&amp;hide=contribs&amp;show=contributions&amp;line_height=20&amp;card_width=450&amp;custom_title=Development%20Stats&amp;bg_color=F8FAFC&amp;title_color=6D28D9&amp;text_color=334155&amp;icon_color=0D9488&amp;border_color=E2E8F0" alt="GitHub development statistics" width="100%" />
</picture>
</td>
<td width="50%" valign="top">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=Kaede-Rei&amp;layout=compact&amp;langs_count=6&amp;card_width=450&amp;custom_title=Public%20Repo%20Languages&amp;bg_color=0D1117&amp;title_color=C4B5FD&amp;text_color=C9D1D9&amp;icon_color=2DD4BF&amp;border_color=30363D" />
  <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=Kaede-Rei&amp;layout=compact&amp;langs_count=6&amp;card_width=450&amp;custom_title=Public%20Repo%20Languages&amp;bg_color=F8FAFC&amp;title_color=6D28D9&amp;text_color=334155&amp;icon_color=0D9488&amp;border_color=E2E8F0" alt="Public repository language distribution" width="100%" />
</picture>
</td>
</tr>
</table>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Kaede-Rei&amp;theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Kaede-Rei&amp;theme=github" alt="GitHub profile and contribution summary" width="100%" />
</picture>
</p>

## 📫 联系我

<p align="center">
  <a href="https://kaede-rei.github.io/"><img src="https://img.shields.io/badge/Website-6366F1?style=flat-square&amp;logo=githubpages&amp;logoColor=white" alt="Website" /></a>
  <a href="mailto:kaerei86@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Gmail" /></a>
  <a href="https://github.com/AgroTech-SCAU"><img src="https://img.shields.io/badge/AgroTech%20SCAU-0D9488?style=flat-square&amp;logo=github&amp;logoColor=white" alt="AgroTech SCAU" /></a>
</p>

<p align="center"><a href="mailto:kaerei@foxmail.com">备用邮箱：kaerei@foxmail.com</a></p>

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0%3A0F172A%2C55%3A6D28D9%2C100%3A0D9488&amp;height=75&amp;section=footer" alt="Profile footer" width="100%" />
