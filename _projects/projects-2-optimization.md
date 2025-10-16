---
title: "Optimization for controller synthesis"
excerpt: "Controller Learning and Synthesis based on Control and Trajectory Optimization <br/><img src='/images/videos/uav_trajectory_thumbnail.png' width='752' height='423'>"
collection: projects
---

The aim of the project is the development of a technique to learn and synthesize controllers based on training data obtained from solving control and trajectory optimization problems. The main idea is to train computationally inexpensive controllers using data from closed-loop simulations which either implement optimal control feedback or a complex controller to follow an optimal trajectory, with the objective of obtaining a controller that emulates an optimal behavior without requiring a computationally expensive controller. For this purpose, multiple linear controllers are trained such that each controller emulates a desired behavior; fuzzy logic is then used to interpolate the outputs of all linear controllers to better emulate the optimal behavior.

The main tasks performed in this project were the following:

-  Set up the optimization problems and numerical solvers using CasADi to implement optimization-based controllers, such as Model Predictive Control (MPC), and obtain optimal trajectories via nonlinear optimization.
- Apply least-squares optimization to train linear controllers from data obtain from the optimization procedures described above; the data sets were chosen based on desired behaviors observed in the optimization results.
- Implement Takagi-Sugeno-based fuzzy logic to interpolate the outputs of the trained linear controllers to better emulate the optimal behaviors displayed by the optimization results.

**Papers**

- Data-driven Fuzzy Control for Time-Optimal, Aggressive Trajectory Tracking (<a href = "https://japaredes.github.io/publication/2025-10-10-phelps_time-optimal">More details</a>)
- MPC-guided, data-driven fuzzy controller synthesis (<a href = "https://japaredes.github.io/publication/2025-07-07-paredes-mpc">More details</a>)

**Videos**

- Time-optimal trajectory planning for multicopter UAV lateral flight (<a href = "https://japaredes.github.io/videos/videos-4-uav-trajectory/">Link</a>)
- Inverted Pendulum on a Cart system stabilization via MPC control schemes (<a href = "https://japaredes.github.io/videos/videos-5-inv_pend/">Link</a>)

**Code**

- Trajectory Optimization for Multicopter UAV Lateral Flight (<a href = "https://github.com/JAParedes/Trajectory_Optimization_for_Multicopter_UAV_Lateral_Flight">Link</a>)
- MPC for Inverted Pendulum on a Cart Stabilization (<a href = "https://github.com/JAParedes/MPC_for_inverted_pendulum_on_a_cart_stabilization">Link</a>)


<img src="/images/videos/uav_trajectory_thumbnail.png">
