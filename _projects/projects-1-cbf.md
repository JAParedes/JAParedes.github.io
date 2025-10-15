---
title: "Control barrier functions"
excerpt: "Control barrier functions for discrete-time systems with applications to robotics and aerospace systems <br/><img src='/images/videos/PDTE-MCBF_thumbnail_v2.png'>"
collection: projects
---

Control barrier functions (CBFs) have emerged as a powerful framework for enforcing safety in control systems by guaranteeing the forward invariance of a prescribed safe set. Most CBF formulations are developed in continuous-time, which requires discretization for practical implementation, which implies that the guarantees provided by the continuous-time theorems do not necessarily hold. This motivates the implementation of CBFs based on discrete-time systems, which take the discretization and sampling effects into account. The aim of the project is to develop discrete-time CBFs that can be easily implemented in robotics and aerospace systems for safe operation. In particular, the multicopter lateral flight system is considered.

The main tasks performed in this project so far are the following:

- Developed a discrete-time, predictive CBF formulation for systems with unmodeled delays and input dynamics. This setup simplifies the implementation of CBFs on outer-loop controllers within an inner-loop, outer-loop architecture, which is adopted in several robotics and aerospace systems.
- Developed a simulation environment to test a projection-based CBF formulation to address the feasibility and computational issues that nonconvex constraints cause in discrete-time CBF formulations; a comparison against nonconvex CBFs was established to highlight the advantages of the proposed method. 

