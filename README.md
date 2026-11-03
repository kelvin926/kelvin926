# Hyunseo Jang

<img align="right" src="https://raw.githubusercontent.com/kelvin926/kelvin926.github.io/main/assets/img/hyunseo_jang.jpg" alt="Portrait of Hyunseo Jang" width="130" height="182">

**Multimodal robot perception · Generated surround views · Terrain-aware robotics**

[Portfolio](https://home.hyunseo.kr/) · [Google Scholar](https://scholar.google.com/citations?user=4UTN6xYAAAAJ) · [ORCID](https://orcid.org/0009-0007-1284-4330) · [Email](mailto:hsjang@kaist.ac.kr)

I am an **M.S. student at Korea University** and a **research intern at AVE Lab, KAIST**. I will join KAIST's Cho Chun Shik Graduate School of Mobility as a **Ph.D. student in March 2027**.

My current research investigates generated panoramas and camera–LiDAR fusion for surround-view terrain perception and terrain-aware mobile robotics. My earlier work includes autonomous mobile-robot integration, reinforcement learning, and simulation-based design optimization.

<br clear="all">

## Current research

### [ROMO-S: Surround-View Terrain Perception](https://home.hyunseo.kr/projects/romo-s/)

<a href="https://home.hyunseo.kr/projects/romo-s/"><img src="https://raw.githubusercontent.com/kelvin926/kelvin926.github.io/a88442aa072c724a2f721256101e946ee23b370b/assets/img/projects/romo_s_sensor_observations.jpg" alt="ROMO-S front-camera and LiDAR observations with a five-camera reference panorama from ShanghaiTech Mapping Robot data" width="480"></a>

_Recorded sensor observations and multi-camera reference imagery; the reference panorama is not an inference input._

I study whether a panorama generated from one front camera and current 360-degree LiDAR improves surrounding terrain perception. Image-space segmentation is pooled at measured LiDAR points and fused with sensor features. Terrain-sensitive driving settings are evaluated in simulation. This is master's thesis research; generated appearance is inferred context and does not establish safe traversability.

### [ROMO-B: Robot Navigation and Integration](https://home.hyunseo.kr/projects/romo-b/)

<a href="https://home.hyunseo.kr/projects/romo-b/"><img src="https://raw.githubusercontent.com/kelvin926/kelvin926.github.io/a88442aa072c724a2f721256101e946ee23b370b/assets/img/projects/romo_b_platform.jpg" alt="Physical blue ROMO-B bimanual mobile robot" width="260"></a>
<a href="https://raw.githubusercontent.com/kelvin926/kelvin926.github.io/a88442aa072c724a2f721256101e946ee23b370b/assets/img/projects/romo_b_rviz.png"><img src="https://raw.githubusercontent.com/kelvin926/kelvin926.github.io/a88442aa072c724a2f721256101e946ee23b370b/assets/img/projects/romo_b_rviz.png" alt="ROMO-B RViz development screenshot showing LiDAR mapping and route layers" width="480"></a>

_ROMO-B hardware photograph and RViz development screenshot. Open the map image at full size for detail._

Public ROS 2 Humble workspace for a mobile-robot platform: serial communication, Livox Mid-360 mapping/localization, Nav2/Autoware waypoint navigation, and operator tools. Software validation and hardware acceptance are documented separately in the repository.

## Selected research

### [KALO: Kangaroo-LocoManipulation](https://home.hyunseo.kr/projects/kalo/)

<a href="https://home.hyunseo.kr/projects/kalo/"><img src="https://raw.githubusercontent.com/kelvin926/kelvin926.github.io/main/assets/img/projects/kalo_arm_swing_proposed.webp" alt="Arm-motion-assisted launch on a Go2W–OpenArm platform in simulation" width="480"></a>

**IEEE/ASME AIM 2026 · Published** · [Paper](https://doi.org/10.1109/AIM65483.2026.11658017)

- **Contribution:** launch-assist concept, Go2W–OpenArm setup, evaluation metrics, and Isaac Lab/RSL-RL experiments.
- **Simulation result:** forward-velocity AUC over the first 1.5 s increased **15.1% relative to the fixed carrying-pose baseline** (0.726 → 0.835); time to 90% target speed decreased from 1.703 s to 1.067 s.
- **Related code:** [leg-loco-isaac-lab](https://github.com/kelvin926/leg-loco-isaac-lab) contains the public experimental workspace. The complete paper-reproduction package is not publicly released.

### [Lift-Equipped Mobile Manipulator](https://home.hyunseo.kr/projects/lift-mobile-manipulator/)

<a href="https://home.hyunseo.kr/projects/lift-mobile-manipulator/"><img src="https://raw.githubusercontent.com/kelvin926/kelvin926.github.io/main/assets/img/projects/lift_mobile_manipulator_platform.webp" alt="Shelf-transfer task for the lift-equipped mobile manipulator in simulation" width="480"></a>

_Simulation demo of the shelf-transfer platform._

**IEEE/ASME AIM 2026 · Published**

- **Contribution:** platform design, a 9-D action / 41-D observation PPO environment, and shelf-transfer evaluation.
- **Simulation result:** **41/50 successful trials (82%)** with ±3 cm source-object position randomization; failures included 3 grasp failures and 6 object drops.
- [Project and evaluation details](https://home.hyunseo.kr/projects/lift-mobile-manipulator/)

### [CEBO-Based Stair-Climbing Wheel Design](https://home.hyunseo.kr/projects/cebo-stair-climbing-wheel/)

<a href="https://home.hyunseo.kr/projects/cebo-stair-climbing-wheel/"><img src="https://raw.githubusercontent.com/kelvin926/kelvin926.github.io/main/assets/img/projects/cebo_physical_stair_guided.webp" alt="Physical T-pedal robot climbing stairs with manual guidance" width="480"></a>

_Physical stair test with manual guidance; separate from the optimization's simulation evaluation._

**Advanced Engineering Informatics 76, Part C, 105096 · November 2026** · [Paper](https://doi.org/10.1016/j.aei.2026.105096)

- **Contribution:** T-pedal wheel search-space design, optimization experiments, and CoppeliaSim evaluation-loop automation.
- **Focus:** clustering-enhanced Bayesian optimization for wheel design, with traversal-time and body-pitch evaluation.

<details>
<summary>More hardware and robotics work</summary>

<a href="https://home.hyunseo.kr/projects/inventory-inspection-adaptive-suspension/"><img src="https://raw.githubusercontent.com/kelvin926/kelvin926.github.io/main/assets/img/projects/lift_integrated_platform_photo.jpg" alt="Physical inventory-inspection robot beside warehouse racks" width="180"></a>
<a href="https://home.hyunseo.kr/projects/amr-integration/"><img src="https://raw.githubusercontent.com/kelvin926/kelvin926.github.io/main/assets/img/projects/amr_ranger_mini_platform_closeup.jpg" alt="Ranger Mini research platform with a LiDAR and camera" width="240"></a>

Physical platforms for [inventory-robot stabilization](https://home.hyunseo.kr/projects/inventory-inspection-adaptive-suspension/) and [campus AMR integration](https://home.hyunseo.kr/projects/amr-integration/). Project pages separate hardware context, simulation studies, and field work.

</details>

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

- **Perception:** camera–LiDAR fusion, generated panoramas, semantic segmentation, terrain perception, BEV representations, LiDAR mapping, object detection/tracking.
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
