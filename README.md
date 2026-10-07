<div align="center">

<a href="#about">About</a> &nbsp; | &nbsp; <a href="#experience">Experience</a> &nbsp; | &nbsp; <a href="#additional-work">Additional Work</a> &nbsp; | &nbsp; <a href="#projects">Projects</a> &nbsp; | &nbsp; <a href="#tools">Tools</a> &nbsp; | &nbsp; <a href="#contact">Contact</a>

<br>

<img src="assets/bhirabhat/avatar-bhirabhat.jpg" width="120" style="border-radius:50%;" alt="Bhirabhat Klomjit"/>

<h1 align="center">Bhirabhat Klomjit (Pae)</h1>
<h3 align="center">Robotics & Automation Engineering Student</h3>
<p align="center">Robotics Integration · Industrial Systems · Embedded Control</p>
<p align="center">FIBO, KMUTT · 3rd Year</p>

<p align="center">
  <a href="mailto:bhirabhat.klom@mail.kmutt.ac.th"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/Peaxtt"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

</div>

---

<a id="about"></a>

### About

Robotics & Automation Engineering student at **FIBO, KMUTT** with hands-on experience integrating robotics, industrial systems, software, and embedded hardware. I work across subsystem boundaries by translating requirements, coordinating interfaces, deploying integrated systems, and validating them through testing and troubleshooting.

| | |
|---|---|
| **Degree** | B.Eng. Robotics & Automation · FIBO, KMUTT |
| **Year** | 3rd Year |
| **Focus** | Robotics System Integration · Industrial Automation · Embedded Control |

---

<a id="experience"></a>

### Selected Engineering Experience

#### Industrial Station Integration

*Apr 2026 — Present · Flagship project*

Integrated station-side software for an industrial monitoring project, focusing on data handling, operator-facing data validation, and coordination across robotics and software subsystems.

- Defined database behavior for pile and slot data; integrated processed LiDAR output from another team into the station layer.
- Integrated and deployed the read-only data-validation dashboard on the station’s Windows system.
- Coordinated interfaces with the robot and decision-algorithm teams. The Worker exchanges robot status through MQTT and does not send commands to the robot.
- Supported system-level testing and troubleshooting, resolved issues within my scope, and coordinated follow-up with the teams responsible for other subsystems.

<p align="center">
  <img src="assets/bhirabhat/station-data-flow.png" width="520" alt="System data flow across sensing, station services, storage, decision outputs, and the validation interface"/>
  <br>
  <img src="assets/bhirabhat/operations-screen.png" width="520" alt="Operations screen for validating pile, storage-slot, furnace and robot data on a warehouse map (read-only)"/>
  <br>
  <img src="assets/bhirabhat/pose-cross-check.png" width="520" alt="Cross-checking the robot pose drawn on our validation screen against the robot's own 3D viewer"/>
</p>

<p align="center"><sub>Field test on 26 September 2026, before correction: the robot marker on our validation screen appeared too far ahead compared with the robot’s own viewer. The position was corrected the same day.</sub></p>

#### FACOBOT AMR — Operator Interface & ROS 2 Integration

*Dec 2025 — May 2026*

Worked on the operator interface and robot integration for a warehouse AMR.

- Integrated operator controls and workflows with ROS 2 actions and robot state.
- Implemented interface workflows for manual control and missions, and contributed software safety behavior.
- Helped debug and integrate navigation-related features; core navigation, QR, Pure Pursuit, and docking algorithms were primarily developed by other team members.

<p align="center">
  <img src="assets/bhirabhat/Facobot-Robot.jpg" height="150" alt="FACOBOT AMR"/>
  <img src="assets/bhirabhat/facobot-manual-ui.jpg" height="150" alt="FACOBOT manual control interface"/>
</p>

#### Carver — ROS 2 Migration & SLAM / Localization

*Jun 2026 — Jul 2026*

Contributed the SLAM/localization subsystem to a team project migrating a conventional PLC-based system toward ROS 2.

- Generated maps, tuned localization, and integrated LiDAR, TF, odometry, and ROS 2 topics.
- Integrated the subsystem with the team's simulation; the project was completed at simulation level.

<p align="center"><img src="assets/bhirabhat/Carver_SLAM.png" width="520" alt="Carver SLAM map and ROS 2 visualization"/></p>

---

<a id="additional-work"></a>

### Additional Technical Work

#### Peplink — GPS–Odometry Alignment

*Short-term task*

Owned the GPS-to-robot-odometry alignment task and tested it with real hardware and data.

- Worked on coordinate conversion, frame alignment, covariance handling, and integration of the alignment logic.

#### B2 Web RViz — Visualization Prototype

*May 2026*

Extended a browser-based visualization prototype, tested mainly with simulation, rosbag, and dummy data.

<p align="center"><img src="assets/bhirabhat/b2-pointcloud-rviz.jpg" height="150" alt="B2 point-cloud visualization"/></p>

---

<a id="projects"></a>

### Coursework & Robotics Projects

#### FRA161 — Squash Ball Hitting Machine

- Designed logic-control electronics using 555 timer and relay circuits; worked on the PCB, power supply, and joystick control.
- Soldered, wired, tuned, and tested the physical machine.

<p align="center">
  <img src="assets/bhirabhat/Shooter-Joy.jpg" height="150" alt="Squash ball machine joystick"/>
  <img src="assets/bhirabhat/Prototype-Shooter-LogicControl.png" height="150" alt="Logic-control prototype and circuit schematic"/>
  <img src="assets/bhirabhat/Shooter-Y1-2.jpg" height="150" alt="Squash ball machine"/>
</p>

#### LiftEase — Patient Transfer Bed

Team project. Contributed to the mechanical structure, conveyor and motor selection, electrical controls, firmware, and directional control interface; participated in prototype assembly and testing.

<p align="center">
  <img src="assets/bhirabhat/LiftEase-CAD-Design.png" height="150" alt="LiftEase CAD design views"/>
  <img src="assets/bhirabhat/Auto-Flip-Bed.jpg" height="150" alt="LiftEase transfer bed prototype"/>
</p>

#### 1-DOF Pick-and-Place Arm

Designed the electrical/control system, selected components, and wired the control box. Worked on STM32 firmware, safety circuits, and sensors; tested the system on hardware. My contribution was electrical and control, not the mechanical arm structure.

<p align="center">
  <img src="assets/bhirabhat/1DOF_full_electrical-box.jpg" height="150" alt="1-DOF arm electrical control box"/>
  <img src="assets/bhirabhat/1DOF_pic_final_after_test.jpg" height="150" alt="1-DOF arm after hardware testing"/>
  <img src="assets/bhirabhat/1DOF-Assembly.jpg" height="150" alt="1-DOF pick-and-place assembly"/>
</p>

#### Grease Separator / Oil Skimmer

Worked on control electronics and firmware, pH sensor integration, and display/indicator integration; tested the physical prototype.

<p align="center">
  <img src="assets/bhirabhat/Oil-Skimmer.jpg" height="150" alt="Oil skimmer prototype"/>
  <img src="assets/bhirabhat/Oil-Skimmer-Scraper.jpg" height="150" alt="Oil skimmer scraper"/>
</p>

#### ABU Robocon — Meihua

Contributed to mobile-base software using ROS 2 and micro-ROS, integrated team members' software, and supported troubleshooting, testing, and tuning on the real robot.

<p align="center">
  <img src="assets/bhirabhat/ABU_test_real_field.jpg" height="150" alt="ABU Robocon robot field test"/>
  <img src="assets/bhirabhat/ABU_working_with_team.jpg" height="150" alt="ABU Robocon team testing"/>
</p>

---

<a id="tools"></a>

### Technologies & Tools I’ve Worked With

<sub>Practical exposure across projects; not a proficiency ranking.</sub>

| Area | Technologies & Tools |
|---|---|
| **Robotics & Integration** | ![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=flat&logo=ros&logoColor=white) `micro-ROS` `TF2` `Nav2` `SLAM / Localization` `LiDAR Integration` |
| **Backend & Data** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) `Supabase` `MQTT` `WebSocket` `REST API` |
| **Embedded & Control** | ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=flat&logo=raspberrypi&logoColor=white) `555 / Relay Logic` `Sensors` `PLC Integration & Testing` |
| **Interfaces & Field Tools** | ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black) `Windows` `PowerShell` |

---

<a id="contact"></a>

### Contact

<p align="center">
  <a href="mailto:bhirabhat.klom@mail.kmutt.ac.th"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/Peaxtt"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

<!-- TODO: Add Resume PDF and LinkedIn links when available. -->
