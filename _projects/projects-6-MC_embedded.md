---
title: "Multicopter Controllers for Embedded Systems"
excerpt: "Development and Evaluation of Multicopter Controllers for Computationally Limited Embedded Systems <br/><img src='/images/videos/embedded_thumbnail.png' width='752' height='423'>"
collection: projects
---

<b>Source of Funding:</b> National Science Foundation (NSF) under grant CMMI 1634709.

The aim of the project is the evaluation of digital controllers for multicopter systems, suitable for real-time implementation in low power embedded systems. For this purpose, PID, LQR and explicit MPC (EMPC) techniques are implemented in a quadcopter system, which is flown in an outdoor testing facility and made to track an inclined, circular path at different tangential velocities under ambient wind conditions.

The main tasks performed in this project were the following:

- Developed simulation environment that implemented continuous-time quadcopter nonlinear dynamics and discrete-time controller capabilities for preliminary testing.
- Performed closed-loop simulation tests to tune the hyperparameters of PID, LQR and EMPC for suitable position tracking performance.
- Implemented the control and trajectory generation algorithms in C code for compilation and execution in the target embedded system.
- Performed closed-loop physical tests to determine trajectory following performance of the tuned digital controllers.

<img src="/images/videos/embedded_thumbnail.png">
