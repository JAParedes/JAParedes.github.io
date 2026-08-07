---
title: "Adaptive Model Predictive Control for Unmanned Aerial Vehicles"
excerpt: "Adaptive Model Predictive Control for Unmanned Aerial Vehicles, including Fixed-Wing Aircraft and Multicopters (in progress...)"
collection: projects
---

The aim of the project is to develop Predictive Cost Adaptive Control (PCAC) for aimplementation in Unmanned Aerial Vehicles. PCAC is an adapive model predictive control technique in which a model is identified online by performing closed-loop linear model identification, which is then leveraged by Generalized Predictive Control (GPC) to obtain the next input. PCAC is implemented into the control architecture of UAVs, including fixed-wing aircraft and multicopters, to enable control without requiring a prior model. For this application, the embedded system implementing PCAC is interfaced with an autopilot system running custom Ardupilot firmware.

The main tasks performed in this project so far are the following:

- Implemented diagnostics for PCAC, which included creating an interactive Matlab program to visualize the poles and zeros of the SISO transfer functions corresponding to the MIMO systems identified by PCAC.
- Implementation of features for PCAC in C++, including identification warm-start, adding variables for logging, creating a command preview interface to enable better tracking within the inner-loops controllers of the architecture.
- Debugging C++, ROS2, Ardupilot and Mavlink code to enable the correct interaction within the implemented frameworks.