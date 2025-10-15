---
title: "Optimization for controller synthesis"
excerpt: "Controller Learning and Synthesis based on Control and Trajectory Optimization <br/><img src='/images/videos/uav_trajectory_thumbnail.png'>"
collection: projects
---

The aim of the project is the development of a technique to learn and synthesize controllers based on training data obtained from solving control and trajectory optimization problems. The main idea is to train computationally inexpensive controllers using data from closed-loop simulations which either implement optimal control feedback or a complex controller to follow an optimal trajectory, with the objective of obtaining a controller that emulates an optimal behavior without requiring a computationally expensive controller. For this purpose, multiple linear controllers are trained such that each controller emulates a desired behavior; fuzzy logic is then used to interpolate the outputs of all linear controllers to better emulate the optimal behavior.

The main tasks performed in this project were the following:

-  Set up the optimization problems and numerical solvers using CasADi to implement optimization-based controllers, such as Model Predictive Control (MPC), and obtain optimal trajectories via nonlinear optimization.
- Apply least-squares optimization to train linear controllers from data obtain from the optimization procedures described above; the data sets were chosen based on desired behaviors observed in the optimization results.
- Implement Takagi-Sugeno-based fuzzy logic to interpolate the outputs of the trained linear controllers to better emulate the optimal behaviors displayed by the optimization results.
