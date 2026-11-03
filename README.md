![](assets/i10955129377.gif)

# Hyunseo Jang

**Multimodal robot perception · Vision-language spatial understanding · Robot learning**

[Portfolio](https://home.hyunseo.kr/) · [Google Scholar](https://scholar.google.com/citations?user=4UTN6xYAAAAJ) · [ORCID](https://orcid.org/0009-0007-1284-4330) · [Email](mailto:hsjang@kaist.ac.kr)

I am an **M.S. student at Korea University** and a **research intern at AVE Lab, KAIST**. I will join KAIST's Cho Chun Shik Graduate School of Mobility as a **Ph.D. student in March 2027**.

My current research investigates camera–LiDAR scene representations and vision-language models for mobile robots. My earlier work includes autonomous mobile-robot integration, reinforcement learning, and simulation-based design optimization.

## Current research

**[ROMO-S: Multimodal Spatial Understanding](https://home.hyunseo.kr/projects/romo-s/)** — I study whether generated surround views help a vision-language model understand space beyond a forward-facing camera. The study compares generated-view-assisted and bird's-eye-view representations under matched front-camera and 360-degree LiDAR inputs, including missing objects and unsupported descriptions. Model development and comparative evaluation are ongoing.

**[ROMO-B: Robot Navigation and Integration](https://github.com/kelvin926/ROMO-B)** — Public ROS 2 Humble workspace for a mobile-robot platform: serial communication, Livox Mid-360 mapping/localization, Nav2/Autoware waypoint navigation, and operator tools. Software validation and hardware acceptance are documented separately in the repository.

## Selected research

### [KALO: Kangaroo-LocoManipulation](https://home.hyunseo.kr/projects/kalo/)

<a href="https://home.hyunseo.kr/projects/kalo/"><img src="https://raw.githubusercontent.com/kelvin926/kelvin926.github.io/main/assets/img/projects/kalo_arm_swing_proposed.webp" alt="Arm-motion-assisted launch on a Go2W–OpenArm platform in simulation" width="480"></a>

**IEEE/ASME AIM 2026 · Published** · [Paper](https://doi.org/10.1109/AIM65483.2026.11658017)

### [Lift-Equipped Mobile Manipulator](https://home.hyunseo.kr/projects/lift-mobile-manipulator/)

<a href="https://home.hyunseo.kr/projects/lift-mobile-manipulator/"><img src="https://raw.githubusercontent.com/kelvin926/kelvin926.github.io/main/assets/img/projects/lift_mobile_manipulator_platform.webp" alt="Shelf-transfer platform in Isaac Lab simulation" width="480"></a>

**IEEE/ASME AIM 2026 · Published**

### [CEBO-Based Stair-Climbing Wheel Design](https://home.hyunseo.kr/projects/cebo-stair-climbing-wheel/)

<a href="https://home.hyunseo.kr/projects/cebo-stair-climbing-wheel/"><img src="https://raw.githubusercontent.com/kelvin926/kelvin926.github.io/main/assets/img/projects/cebo_physical_stair_guided.webp" alt="Physical T-pedal robot climbing stairs with manual guidance" width="480"></a>

**Advanced Engineering Informatics 76, Part C, 105096 · November 2026** · [Paper](https://doi.org/10.1016/j.aei.2026.105096)

## Publications

| Year | Work                                                                                                                 | Venue / status                                                                                   |
| ---- | -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| 2026 | **KALO: Kangaroo-LocoManipulation for Early Launch Acceleration in a Wheel-Legged Robot**                            | IEEE/ASME AIM · Published · [DOI](https://doi.org/10.1109/AIM65483.2026.11658017)                |
| 2026 | **A Lift-Equipped Mobile Manipulator Platform for Shelf Transfer in Multi-Level Rack Environments**                  | IEEE/ASME AIM · Published · [Project](https://home.hyunseo.kr/projects/lift-mobile-manipulator/) |
| 2026 | **Design and Implementation of a Local Delivery Robot System: A Reinforcement Learning Approach**                    | IEEE CASE · Accepted                                                                             |
| 2026 | **Clustering-enhanced Bayesian optimization (CEBO): A case study on T-pedal wheel design of a stair-climbing robot** | Advanced Engineering Informatics · Published · [DOI](https://doi.org/10.1016/j.aei.2026.105096)  |
| 2025 | **Efficient Graph-Based Multi-Story Path Planning with Optimized Elevator Selection for Indoor Delivery Robots**     | Electronics · [DOI](https://doi.org/10.3390/electronics14050982)                                 |
| 2025 | **Time-Interval-Based Collision Detection for 4WIS Mobile Robots in Human-Shared Indoor Environments**               | Sensors · [DOI](https://doi.org/10.3390/s25030890)                                               |

[Full publication list and presentations](https://home.hyunseo.kr/#publications) · [Citation record on Google Scholar](https://scholar.google.com/citations?user=4UTN6xYAAAAJ)

## Public robotics repositories

| Repository                                                            | Scope                                                                                     |
| --------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| [ROMO-B](https://github.com/kelvin926/ROMO-B)                         | ROS 2 platform integration, mapping/localization, waypoint navigation, and operator tools |
| [leg-loco-isaac-lab](https://github.com/kelvin926/leg-loco-isaac-lab) | Go2W–OpenArm experiments and training/evaluation utilities built on Isaac Lab             |
| [isaac_wheel](https://github.com/kelvin926/isaac_wheel)               | KETI AMR rough-terrain velocity tracking and chassis-leveling environment                 |
| [Frbot_Lift](https://github.com/kelvin926/Frbot_Lift)                 | Full-lift inventory-inspection robot suspension tasks and stability evaluation            |
| [pick-and-place](https://github.com/kelvin926/pick-and-place)         | Go2W–OpenArm mobile-manipulation prototype                                                |
| [Harim_AMR](https://github.com/kelvin926/Harim_AMR)                   | Isaac Sim palletizing and AMR pallet-transfer demo                                        |

These repositories include research workspaces and prototypes; their READMEs describe setup, validation, and release scope. Historical projects include [LiDAR human detection](https://github.com/kelvin926/lidar_human_detection) and [campus AMR integration](https://github.com/kelvin926/FieldRobot_Project_Semester), both archived.

## Technical background

- **Perception:** camera–LiDAR fusion, vision-language models, BEV representations, LiDAR mapping, object detection/tracking.
- **Robot learning:** Isaac Lab / Isaac Sim, RSL-RL, PyTorch, PPO, task/reward design, curriculum design, and policy evaluation.
- **Integration:** ROS 2 / ROS, Autoware, Python, C++, Linux, CAN, and field-system validation.
- **Optimization:** Bayesian optimization, CoppeliaSim, CAD, and simulation evaluation automation.

<details>
<summary>Other software projects</summary>

- [KU Regulation Searcher](https://github.com/kelvin926/KU_Regulation_Searcher): local university-regulation search with source-grounded AI answers.
- [Codex Composer HUD](https://github.com/kelvin926/CodexComposerHUD): an unofficial desktop tool for inspecting Codex context and usage estimates.
- [PetPresence](https://github.com/kelvin926/PetPresence): a Windows desktop pet and friend-presence application.

</details>

[CV and background](https://home.hyunseo.kr/#cv) · [All public repositories](https://github.com/kelvin926?tab=repositories) · [Korea University email](mailto:kelvin926@korea.ac.kr)
