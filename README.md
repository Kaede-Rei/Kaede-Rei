<!-- visual-profile-v2 -->
<p align="right"><a href="README_zh.md">中文</a> · <strong>English</strong></p>
<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0%3A0F172A%2C55%3A6D28D9%2C100%3A0D9488&amp;height=190&amp;section=header&amp;text=Kaede%20Rei&amp;fontSize=48&amp;fontColor=FFFFFF&amp;fontAlignY=37&amp;desc=Robotics%20Developer&amp;descSize=18&amp;descAlignY=59&amp;animation=fadeIn" alt="Kaede Rei — Robotics Developer" width="100%" /></p>
<p align="center">
  <img src="https://img.shields.io/badge/Robotic%20Arms-7C3AED?style=for-the-badge" alt="Robotic Arms" />
  <img src="https://img.shields.io/badge/Embedded%20Software-0D9488?style=for-the-badge" alt="Embedded Software" />
  <img src="https://img.shields.io/badge/System%20Integration-2563EB?style=for-the-badge" alt="System Integration" />
</p>
<p align="center"><strong>🤖 Robotics Developer</strong><br />🎓 SCAU Undergraduate &nbsp; · &nbsp; 🌱 AgroTech-SCAU Lead</p>
<p align="center">
  <a href="https://kaede-rei.github.io/"><img src="https://img.shields.io/badge/Website-6366F1?style=flat-square&amp;logo=githubpages&amp;logoColor=white" alt="Website" /></a>
  <a href="mailto:kaerei86@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Gmail" /></a>
  <a href="https://github.com/AgroTech-SCAU"><img src="https://img.shields.io/badge/AgroTech%20SCAU-0D9488?style=flat-square&amp;logo=github&amp;logoColor=white" alt="AgroTech SCAU" /></a>
</p>

## 👋 About Me

I develop robotic-arm software, embedded control systems, and robot integration frameworks, with hands-on work in agricultural robotics and real hardware. My work spans models, drivers, and control through calibration, task orchestration, and deployment.

I aim to turn implementations for individual robots into general-purpose cores, portable modules, and reusable interfaces that future projects can build on.

## 🚀 Featured Work

These projects pursue **general-purpose architectures, portability, and reuse across robot projects**. They span my personal and AgroTech-SCAU repositories, where I lead development or contribute as a primary code author.

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/Kaede-Rei/SerialArm-Core">🦾 SerialArm-Core</a></h3>
<p><img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square" alt="C++17" /> <img src="https://img.shields.io/badge/Dynamics%20Core-7C3AED?style=flat-square" alt="Dynamics Core" /></p>
<p>Building a general-purpose, extensible C++17 dynamics core for serial manipulators, separating rigid-body dynamics, gravity compensation, and calibration from specific robot models, actuator backends, and upper-level frameworks.</p>
<p>Robot profiles and shared hardware interfaces support adaptation to different arms, with impedance/admittance control, Python bindings, and ROS 2 / ros2_control / MoveIt 2 integration. SerialArm Studio provides model, calibration, control, and diagnostic workflows. Linux packages are available in <a href="https://github.com/Kaede-Rei/SerialArm-Core/releases">Releases</a>.</p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/AgroTech-SCAU/Competition-Robot-2026-Atlas">🤖 Atlas</a></h3>
<p><img src="https://img.shields.io/badge/STM32-03234B?style=flat-square" alt="STM32" /> <img src="https://img.shields.io/badge/Swerve%20%2B%205--DOF%20Arm-0D9488?style=flat-square" alt="Swerve + 5-DOF Arm" /></p>
<p>An embedded software baseline already iterated and reused across multiple wheeled competition robots, with continued work on portability and adaptation through configuration. It covers <strong>swerve-drive chassis control, five-axis arm motion control, RC receiver integration, and leader–follower teleoperation</strong>.</p>
<p>My work refines reusable boundaries around MCU drivers, communication, kinematics, scheduling, state machines, control authority, and faults to support different robot configurations. I also implemented the YASMIN mission state machine.</p>
<p>Atlas is retained as an archived baseline, with code carried forward into <a href="https://github.com/AgroTech-SCAU/Competition-Robot-2026-Longinus">Longinus</a> and related Competition-Robot-2026 projects.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/AgroTech-SCAU/Embedded-Electronic-Control-Standard">⚙️ Embedded Control SDK</a></h3>
<p><img src="https://img.shields.io/badge/MCU%20SDK-0D9488?style=flat-square" alt="MCU SDK" /> <img src="https://img.shields.io/badge/Drivers%20%26%20Architecture-334155?style=flat-square" alt="Drivers &amp; Architecture" /></p>
<p>A shared MCU SDK developed with portability across projects and MCU platforms as a design goal, separating drivers, utilities, and kinematics from specific HALs, boards, and application logic.</p>
<p>Platform interfaces, project-side assembly, and layered boundaries let new devices and boards connect through adapters, while shared conventions cover timeouts, stops, and fault handling.</p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/AgroTech-SCAU/AT-System-Integration">🧩 AT-System-Integration</a></h3>
<p><img src="https://img.shields.io/badge/HSM%20%2B%20Behavior%20Tree-2563EB?style=flat-square" alt="HSM + Behavior Tree" /> <img src="https://img.shields.io/badge/Developing-B45309?style=flat-square" alt="Developing" /></p>
<p>Building a general-purpose integration framework for different robots and tasks. Shared capability interfaces and adapters connect manipulation, vision, navigation, and embedded backends, reducing task logic's dependence on any single project's implementation.</p>
<p>ATIL Robot Studio provides visual state orchestration, behavior-tree task design, and runtime diagnostics. Under active development, with capability-level mocks and an existing behavior-tree execution path; hardware integration progresses through project-specific validation.</p>
</td>
</tr>
</table>

## 🖥️ Tools in Action

<table>
<tr><th width="50%"><a href="https://github.com/Kaede-Rei/SerialArm-Core">🦾 SerialArm Studio</a></th><th width="50%"><a href="https://github.com/AgroTech-SCAU/AT-System-Integration">🧩 ATIL Robot Studio</a></th></tr>
<tr><td><a href="assets/serialarm-studio-dynamics.png"><img src="assets/serialarm-studio-dynamics.png" alt="Calibration and validation workbench for the dynamics core" width="100%" /></a></td><td><a href="assets/atil-robot-studio-orchestration.png"><img src="assets/atil-robot-studio-orchestration.png" alt="AT-System-Integration · Visual state and task orchestration" width="100%" /></a></td></tr>
<tr><td align="center"><sub>Calibration and validation workbench for the dynamics core</sub></td><td align="center"><sub>AT-System-Integration · Visual state and task orchestration</sub></td></tr>
</table>

<details>
<summary>📐 Handeye Calibration Workbench</summary>

<p align="center"><a href="https://raw.githubusercontent.com/AgroTech-SCAU/Handeye-Calibration-App/main/docs/images/launcher-connect.png"><img src="https://raw.githubusercontent.com/AgroTech-SCAU/Handeye-Calibration-App/main/docs/images/launcher-connect.png" alt="Handeye Calibration — camera and robot data inputs" width="100%" /></a></p>

</details>

## 🗺️ Project Map

Other representative projects where I lead development or contribute as a primary code author.

| Project | Focus & Main Contributions |
| --- | --- |
| 📐 [Handeye-Calibration-App](https://github.com/AgroTech-SCAU/Handeye-Calibration-App) | Visual hand–eye calibration: camera/robot inputs, synchronized sampling, solver diagnostics, and independent geometric validation |
| 🍅 [Tomato-Manipulation](https://github.com/AgroTech-SCAU/Tomato-Manipulation) | Tomato-picking application built on SerialArm-Core: MoveIt 2 motion capabilities, end-effector control, RGB-D / Planning Scene integration, and picking tasks |
| 🧠 [Dual-DM-Arm-LeRobot](https://github.com/Kaede-Rei/Dual-DM-Arm-LeRobot) | Dual-arm teleoperation, demonstration collection and processing, LeRobot hardware integration, imitation learning, and policy deployment experiments |
| 🍃 [Tea-Picking-Dual-Arm](https://github.com/AgroTech-SCAU/Tea-Picking-Dual-Arm) | HX-10HM / RM65-B leader–follower systems: joint mapping, homing, gravity-compensation integration, and single-/dual-arm teleoperation |
| ⚙️ [Wheel-Rail-Integrated-Chassis](https://github.com/AgroTech-SCAU/Wheel-Rail-Integrated-Chassis) | STM32H723 chassis control: four-wheel steering kinematics, motor communication, remote-control inputs, scheduling, and fault handling |

## 🧰 Technical Stacks

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


- **🦾 Robotic arms:** kinematics and rigid-body dynamics (Pinocchio), model and dynamics calibration, joint control and gravity compensation, ROS 2 / MoveIt 2, hand–eye calibration, and RGB-D integration; exploring teleoperation, demonstrations, and imitation learning
- **⚙️ Embedded software:** STM32, CAN / UART / SPI, actuator and IMU interfaces, swerve-drive and five-axis arm control, RC inputs and teleoperation, IMU/odometry processing, local pose estimation, PID, hierarchical state machines, control authority, timeouts, and faults
- **🧩 System integration:** Linux and ROS 2, MCU–host communication, coordinate frames and interface contracts, task state machines and behavior trees, configuration, diagnostics, and deployment

## 🌱 AgroTech-SCAU

As one of the association's leads, I combine hands-on development with technical coordination: project architecture, shared infrastructure, module interfaces, integration and debugging, engineering standards, documentation, and technical guidance.

I also study mechanics, computer vision, and mobile navigation to support system-level decisions and collaboration across the team. My main development focus remains robotic arms, embedded software, and system integration.

<details>
<summary>🗃️ Earlier Work & Learning</summary>

- [Renesas-DM-Arm](https://github.com/Kaede-Rei/Renesas-DM-Arm): earlier MCU arm kinematics, CAN motor control, and state-machine work
- [DM-Arm-MoveIt2](https://github.com/Kaede-Rei/DM-Arm-MoveIt2): MoveIt 2 integration and arm motion-planning experiments
- [Hand-Eye-GUI-Tools](https://github.com/Kaede-Rei/Hand-Eye-GUI-Tools): ROS Noetic hand–eye and multi-camera extrinsic calibration tools
- [Modern-Robotics-Curriculum](https://github.com/Kaede-Rei/Modern-Robotics-Curriculum): AI-assisted personal robotics study materials and teaching experiments

</details>

## 📊 Development Activity

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

## 📫 Get in Touch

<p align="center">
  <a href="https://kaede-rei.github.io/"><img src="https://img.shields.io/badge/Website-6366F1?style=flat-square&amp;logo=githubpages&amp;logoColor=white" alt="Website" /></a>
  <a href="mailto:kaerei86@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=flat-square&amp;logo=gmail&amp;logoColor=white" alt="Gmail" /></a>
  <a href="https://github.com/AgroTech-SCAU"><img src="https://img.shields.io/badge/AgroTech%20SCAU-0D9488?style=flat-square&amp;logo=github&amp;logoColor=white" alt="AgroTech SCAU" /></a>
</p>

<p align="center"><a href="mailto:kaerei@foxmail.com">Alternative: kaerei@foxmail.com</a></p>

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0%3A0F172A%2C55%3A6D28D9%2C100%3A0D9488&amp;height=75&amp;section=footer" alt="Profile footer" width="100%" />
