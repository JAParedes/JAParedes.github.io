---
title: "Predictive Cost Adaptive Control of Fixed-Wing Aircraft Without Prior Modeling"
collection: publications
category: conferences
permalink: /publication/2025-03-03-riley-fw-pcac
excerpt: 'The present paper investigates the performance of predictive cost adaptive control (PCAC) for fixed-wing aircraft control without using any prior aerodynamic model or offline data collection.'
date: 2025-03-03
venue: 'Proceedings of the AIAA Scitech Forum'
citation: "R. Richards, J. Paredes, and D. Bernstein, &quot;Predictive Cost Adaptive Control of Fixed-Wing Aircraft Without Prior Modeling,&quot; in <i>Proc. AIAA SciTech Forum,</i> 2025, p. 2081."
---

Autopilots for fixed-wing aircraft are typically designed based on linearized aerodynamic models consisting of stability and control derivatives obtained from wind-tunnel testing. The resulting local controllers are then pieced together using gain scheduling. For applications where the aerodynamics are unmodeled, the present paper proposes an autopilot based on predictive cost adaptive control (PCAC). As an indirect adaptive control extension of model predictive control, PCAC uses recursive least squares (RLS) with variable-rate forgetting for online, closed-loop system identification. At each time step, RLS-based system identification updates the coefficients of an input-output model whose order is specified by the user. For MPC, the receding-horizon optimization is performed by solving a quadratic program at each iteration. The present paper investigates the performance of PCAC for fixed-wing aircraft without using any prior aerodynamic model or offline data collection.

Paper: <a href = "https://arc.aiaa.org/doi/10.2514/6.2025-2081"> Link </a>

Preprint: <a href = "https://arxiv.org/abs/2402.00352"> Link </a>