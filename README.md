<div align="center">

<a href="#about">About</a> &nbsp; | &nbsp; <a href="#experience">Experience</a> &nbsp; | &nbsp; <a href="#additional-work">Additional Work</a> &nbsp; | &nbsp; <a href="#projects">Projects</a> &nbsp; | &nbsp; <a href="#competitions">Competitions &amp; Mentoring</a> &nbsp; | &nbsp; <a href="#tools">Tools</a> &nbsp; | &nbsp; <a href="#contact">Contact</a>

<br>

<img src="assets/bhirabhat/profile.jpg" width="120" style="border-radius:50%;" alt="Bhirabhat Klomjit"/>

<h1 align="center">Bhirabhat Klomjit (Pae , PaYae)</h1>
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

#### FIBO — Pile Monitoring & Industrial Station Integration

*Apr 2026 — Present · R&D prototype for an industrial wood-handling site*

A LiDAR-based system for tracking wood piles so a wheel loader can handle them with less manual work. Processed LiDAR data and the decision algorithm come from other teams; I worked on the station-side layer that connects them to the robot and the operators.

- Designed the database and state logic (PostgreSQL) that turn processed LiDAR output into pile and storage-slot state.
- Defined and documented a read-only interface for the decision-algorithm team to read that state, and wrote an example client.
- Connected the system to the robot's status messages over MQTT, read-only.
- Developed a read-only validation dashboard (FastAPI, React) for checking pile, slot and robot data on a map, and deployed the stack on the station's Windows system with a health check and a verified deployment script.
- Proposed and deployed a Station Monitor that brings station, LiDAR, network and robot health into one view; used Aruba controller data and field tests for network diagnostics and supported the vendor's final tuning.

Deployed on the station and used in on-site tests with the real robot; still an R&D prototype.

<p align="center">
  <img src="assets/bhirabhat/station-data-flow.png" width="600" alt="System data flow across sensing, station services, storage, decision outputs, and the validation interface"/>
</p>

<p align="center">
  <img src="assets/bhirabhat/station-operations-screen.png" height="250" alt="Operations screen for validating pile, storage-slot, furnace and robot data on a warehouse map (read-only)"/>
  <img src="assets/bhirabhat/station-pose-cross-check.png" height="250" alt="Cross-checking the robot pose drawn on our validation screen against the robot's own 3D viewer"/>
</p>

<p align="center"><sub>Left: operations screen. Right: cross-checking the robot pose on our validation screen against the robot's own 3D viewer during field testing.</sub></p>

#### FACOBOT AMR — Operator Interface & ROS 2 Integration

*Dec 2025 — May 2026*

- Developed the robot-interface web application for a warehouse AMR, covering manual control, mission execution, robot status, error and status handling, and operator workflows.
- Built a ROS 2 action bridge between the web application and ROS 2, since the action workflow could not be handled through direct WebSocket alone, and integrated ROS 2 actions, topics, services, feedback, and robot state.
- Implemented safety behavior including dead-man control, a connection watchdog, stopping commands on disconnect, state-based command gating, and emergency-stop handling.
- Tested and debugged the system on the real robot, including state mismatches, disconnections, and safety edge cases.

Core navigation, QR, Pure Pursuit, and docking algorithms were primarily developed by other team members; I helped test, debug, and integrate those features.

<p align="center">
  <img src="assets/bhirabhat/facobot-robot.jpg" height="260" alt="FACOBOT AMR"/>
  <img src="assets/bhirabhat/facobot-manual-ui.jpg" height="260" alt="FACOBOT manual control interface"/>
</p>

#### Carver — ROS 2 Migration & SLAM / Localization

*Jun 2026 — Jul 2026*

- Developed and integrated the SLAM/localization subsystem using SLAM Toolbox, including ROS 2 launch/configuration, topic remapping, LiDAR/TF integration, and map generation.
- Tested and debugged the subsystem in Gazebo/RViz, addressing TF, mapping, localization, and LiDAR integration issues; real-robot tuning remains for the hardware-integration stage.

<p align="center"><img src="assets/bhirabhat/carver-slam-map.png" width="600" alt="Carver SLAM map and ROS 2 visualization"/></p>

---

<a id="additional-work"></a>

### Additional Technical Work

#### Peplink — GPS–Odometry Alignment

*Jan 2026 — Mar 2026*

Owned the GPS-to-robot-odometry alignment task and tested it with real hardware and data to align outdoor positioning with the robot's local odometry frame.

- Worked on coordinate conversion, frame alignment, covariance handling, and integration of the alignment logic.

---

<a id="projects"></a>

### Coursework & Robotics Projects

#### LiftEase — Patient Transfer Bed

*Year 1 · Semester 1*

- Designed the prototype concept and mechanical structure in SolidWorks, including the conveyor-based transfer mechanism and motor integration.
- Selected and integrated the motors, electrical controls, and basic firmware, and worked with teammates on mechanical assembly and prototype testing.
- Built as an early functional prototype to demonstrate the transfer concept; usability and safety were not yet developed to a practical product level.

<p align="center">
  <img src="assets/bhirabhat/liftease-cad-design.png" height="205" alt="LiftEase CAD design views"/>
  <img src="assets/bhirabhat/liftease-prototype.jpg" height="205" alt="LiftEase transfer bed prototype"/>
</p>

#### Squash Ball Hitting Machine

*Year 1 · Semester 2*

- Designed the machine's control electronics in EasyEDA, including 555-timer timing and PWM circuits, motor-control stages, PCB layouts, and a custom power supply.
- Selected components, sized the power supply, assembled and wired the electronics, then tuned and tested the whole machine.

<p align="center"><img src="assets/bhirabhat/squash-ball-main-board-schematic.png" width="480" alt="Squash ball machine main-board schematic"/></p>

<p align="center">
  <img src="assets/bhirabhat/squash-ball-joystick.jpg" height="205" alt="Squash ball machine joystick"/>
  <img src="assets/bhirabhat/squash-ball-logic-control.png" height="205" alt="Logic-control prototype and circuit schematic"/>
  <img src="assets/bhirabhat/squash-ball-machine.jpg" height="205" alt="Squash ball machine"/>
</p>

#### Drum Oil Skimmer for CNC Machine Coolant Tank

*Year 2 · Semester 1*

- Developed the Raspberry Pi Pico control system, including the circuit and PCB, wiring, power, pH sensing, LCD, motor control, and firmware.
- Tested the prototype under real operating conditions, including pH sensor noise observed while the motor was running.

<p align="center">
  <img src="assets/bhirabhat/oil-skimmer-prototype.jpg" height="380" alt="Drum oil skimmer prototype"/>
  <img src="assets/bhirabhat/oil-skimmer-scraper.jpg" height="380" alt="Drum oil skimmer scraper"/>
</p>

#### 1-DOF Pick-and-Place Arm

*Year 2 · Semester 2*

- Designed the complete electrical/control system around an STM32G474RE, from component selection and EasyEDA schematics to control-box layout, wiring, assembly, and hardware testing.
- Integrated 24 V sensors, encoder feedback, opto-isolated inputs, relay and pneumatic outputs, the motor drive, and emergency-stop circuitry.
- Developed the firmware for sensor handling, homing, safety behavior, and command handling, and debugged the complete system on hardware.
- My contribution focused on electrical/control and integration; the mechanical arm structure was developed by other team members.

<p align="center"><img src="assets/bhirabhat/1dof-arm-control-box-schematic.png" width="480" alt="1-DOF arm control-box schematic"/></p>

<p align="center">
  <img src="assets/bhirabhat/1dof-arm-electrical-box.jpg" height="245" alt="1-DOF arm electrical control box"/>
  <img src="assets/bhirabhat/1dof-arm-after-test.jpg" height="245" alt="1-DOF arm after hardware testing"/>
  <img src="assets/bhirabhat/1dof-arm-assembly.jpg" height="245" alt="1-DOF pick-and-place assembly"/>
</p>

---

<a id="competitions"></a>

### Competitions & Mentoring

#### ABU Robocon — Meihua

- Handled the main mobile-base software integration using ROS 2 and micro-ROS, connecting high-level commands, low-level control, robot feedback, and interfaces contributed by multiple team members.
- Tested and tuned the real robot in workshop and field conditions, focusing on straight-line motion, yaw response, motor behavior, encoder reliability, and ROS integration.
- Supported debugging of low-level behavior and communication issues while integrating the mobile-base software.

<p align="center">
  <img src="assets/bhirabhat/abu-robocon-field-test.jpg" height="360" alt="ABU Robocon robot field test"/>
  <img src="assets/bhirabhat/abu-robocon-team-testing.jpg" height="360" alt="ABU Robocon team testing"/>
</p>

#### Junior Botball Challenge — Robotics Competition Trainer

*Jul 2026 — Aug 2026*

- Trained and prepared a student robotics team in match strategy, route planning, teamwork, communication, and problem-solving under competition conditions.
- Designed competition-style training problems, ran mock competitions, and supported robot debugging and strategy adjustments.
- The team received a Gold Award at the JBC Global Final 2026 in Beijing, China.

<p align="center">
  <img src="assets/bhirabhat/jbc-global-final-award.jpg" height="230" alt="Junior Botball Challenge Global Final 2026 award stage"/>
  <img src="assets/bhirabhat/jbc-training-mock-field.png" height="230" alt="Training a student team with a mock competition field"/>
</p>

---

<a id="tools"></a>

### Technologies & Tools I’ve Worked With

<sub>Practical exposure across projects; not a proficiency ranking.</sub>

| Area | Technologies & Tools |
|---|---|
| **Robotics & Integration** | ![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=flat&logo=ros&logoColor=white) `micro-ROS` `TF2` `Nav2` `SLAM Toolbox / Localization` `LiDAR Integration` |
| **Backend & Data** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) `Supabase` `MQTT` `WebSocket` `REST API` |
| **Embedded & Control** | ![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white) ![Raspberry Pi Pico](https://img.shields.io/badge/Raspberry%20Pi%20Pico-C51A4A?style=flat&logo=raspberrypi&logoColor=white) `C / C++` `Microcontroller Firmware` `555 / Relay Logic` `PWM Motor Control` |
| **Electrical & Hardware** | `Circuit Design` `PCB Design & Assembly` `Power-Supply Design` `Control-Box Design & Wiring` `Component Selection` `Sensors / Encoders` `Relays / Motor Drivers` `Hardware Testing & Debugging` |
| **CAD & Design Tools** | `SolidWorks` `EasyEDA` |
| **Interfaces & Field Tools** | ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black) `Windows` `PowerShell` |

---

<a id="contact"></a>

### Contact

<p align="center">
  <a href="mailto:bhirabhat.klom@mail.kmutt.ac.th"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/Peaxtt"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

<!-- TODO: Add Resume PDF and LinkedIn links when available. -->
