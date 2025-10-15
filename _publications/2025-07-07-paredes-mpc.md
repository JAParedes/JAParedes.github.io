---
title: "MPC-guided, data-driven fuzzy controller synthesis"
collection: publications
category: conferences
permalink: /publication/2025-07-07-paredes-mpc
excerpt: 'This paper presents a fuzzy controller synthesis framework guided by MPC. In the proposed framework, training data is obtained from MPC closed-loop simulations and is used to optimize a low computational complexity controller to emulate the response of MPC.'
date: 2025-07-07
venue: 'Proceedings of the American Control Conference'
citation: 'J. A. Paredes Salazar and A. Goel, &quot;MPC-guided, data-driven fuzzy controller synthesis,&quot; in <i>Proc. Amer. Contr. Conf. (ACC),</i> IEEE, 2025, pp. 46–51.'
---

Model predictive control (MPC) is a powerful control technique for online optimization using system model-based predictions over a finite time horizon. However, the computational cost MPC requires can be prohibitive in resource-constrained computer systems. This paper presents a fuzzy controller synthesis framework guided by MPC. In the proposed framework, training data is obtained from MPC closed-loop simulations and is used to optimize a low computational complexity controller to emulate the response of MPC. In particular, autoregressive moving average (ARMA) controllers are trained using data obtained from MPC closed-loop simulations, such that each ARMA controller emulates the response of the MPC controller under particular desired conditions. Using a Takagi-Sugeno (T-S) fuzzy system, the responses of all the trained ARMA controllers are then weighted depending on the measured system conditions, resulting in the Fuzzy-Autoregressive Moving Average (F-ARMA) controller. The effectiveness of the trained F-ARMA controllers is illustrated via numerical examples.

Paper: <a href = "https://ieeexplore.ieee.org/document/11107503"> Link </a>

Preprint: <a href = "https://arxiv.org/pdf/2410.06556"> Link </a>