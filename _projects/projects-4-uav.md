---
title: "Adaptive Autopilot for UAVs"
excerpt: "Adaptive Digital Autopilot Development for Unmanned Aerial Vehicles (UAVs) <br/><img src='/images/videos/uav_MC_thumbnail.png' width='752' height='423'>"
collection: projects
---

<b>Source of Funding:</b> Office of Naval Research (ONR) under grant N00014-19-1-2273.

The aim of the project is to develop an adaptive digital autopilot for UAVs to address unknown or unanticipated changes in flight conditions and prevent nominal flight performance degradation. For this purpose, the PX4 autopilot firmware is modified to enable the implementation of the adaptive autopilot solution. Tests were performed using multicopter, fixed-wing and vertical take-off and landing (VTOL) aircraft.

The main tasks performed in this project were the following:

- Implemented an adaptive control algorithm in the PX4 autopilot firmware for simulation and physical testing.
- Designed and developed a wireless communication setup to allow the transmission of Motion Capture (MOCAP) measurements for state estimation.

**Papers**

- Single-Shot Learning of Multirotor Controller Gains: A Data-Driven Approach with Experimental Validation (<a href = "https://japaredes.github.io/publication/2025-09-09-mirtaba-UAV-rcac">More details</a>)
- A Hammerstein-Weiner Modification of Adaptive Autopilot for Parameter Drift Mitigation with Experimental Results (<a href = "https://japaredes.github.io/publication/2024-09-09-UAV-drift">More details</a>) (<a href = "https://github.com/JAParedes/PX4-Autopilot/tree/RCAC_MC_FW_dev_mavlink"> Code </a>)
- Data-Driven Retrospective-Cost-Based Adaptive Digital PID Control (<a href = "https://japaredes.github.io/publication/2024-07-07-ddrcac-uav">More details</a>)
- Performance Comparison of Adaptive Autopilot Architectures for Multicopter Stabilization and Trajectory Tracking (<a href = "https://japaredes.github.io/publication/2024-04-04-autopilot-architectures">More details</a>)
- Experimental Flight Testing of a Fault-Tolerant Adaptive Autopilot for Fixed-Wing Aircraft (<a href = "https://japaredes.github.io/publication/2023-07-07-lee-FW-autopilot">More details</a>) (<a href = "https://github.com/JAParedes/PX4-Autopilot/tree/RCAC_FW_UM"> Code </a>)
- An adaptive PID autotuner for multicopters with experimental results (<a href = "https://japaredes.github.io/publication/2022-06-06-spencer-MC-A-PID">More details</a>) (<a href = "https://github.com/JAParedes/PX4-Autopilot/tree/RCAC_MC_AutoTuner"> Code </a>)
- Experimental Implementation of an Adaptive Digital Autopilot (<a href = "https://japaredes.github.io/publication/2021-08-08-goel-adaptive-autopilot">More details</a>)

**Videos**

- An Adaptive PID Autotuner for Multicopters with Experimental Results: Flight tests with GPS data (<a href = "https://japaredes.github.io/videos/videos-7-UAV_MC/">Link</a>)
- An adaptive digital autopilot for fixed-wing aircraft (<a href = "https://japaredes.github.io/videos/videos-6-UAV_FW/">Link</a>)

**Code**


- PX4 Autopilot: Hammerstein-Weiner Modification for Parameter Drift Mitigation (<a href = "https://github.com/JAParedes/PX4-Autopilot/tree/RCAC_MC_FW_dev_mavlink">Link</a>)
- PX4 Autopilot: RCAC implementation for Fixed-Wing Aircraft (<a href = "https://github.com/JAParedes/PX4-Autopilot/tree/RCAC_FW_UM">Link</a>)
- PX4 Autopilot: RCAC implementation for Multicopter (<a href = "https://github.com/JAParedes/PX4-Autopilot/tree/RCAC_MC_AutoTuner">Link</a>)
- mavros: Implementation of guidance law and PX4 interface with position and attitude data stream from MOCAP cameras (<a href = "https://github.com/JAParedes/mavros/tree/mavros-mocap-guidance">Link</a>)

<img src="/images/videos/uav_MC_thumbnail.png">
