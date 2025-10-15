---
title: "Experimental Application of Predictive Cost Adaptive Control to Thermoacoustic Oscillations in a Rijke Tube with Unknown Input Delay"
collection: publications
category: conferences
permalink: /publication/2025-08-08-paredes-rijke-pcac
excerpt: 'The present paper uses predictive cost adaptive control (PCAC) for sampled-data control of an experimental Rijke-tube setup. PCAC is applied to the Rijke-tube setup under various experimental scenarios to test its performance under unknown and parameter-dependent dynamics, and its robustness to input delay.'
date: 2025-08-08
venue: 'Proceedings of the American Control Conference'
citation: 'J. A. Paredes Salazar and D. S. Bernstein, &quot;Experimental Application of Predictive Cost Adaptive Control to Thermoacoustic Oscillations in a Rijke Tube with Unknown Input Delay,&quot; in <i>Proc. Amer. Contr. Conf. (ACC),</i> IEEE, 2025, pp. 1864–1869.'
---

Model predictive control (MPC) has been used successfully in diverse applications. As its name suggests, MPC requires a model for predictive optimization. The present paper focuses on the application of MPC to a Rijke tube, in which a heating source and acoustic dynamics interact to produce self-excited oscillations. Since the dynamics of a Rijke tube are difficult to model to a high level of accuracy, the implementation of MPC requires leveraging data from the laboratory setup as well as knowledge about thermoacoustics, which is labor intensive and requires domain expertise. This is exacerbated by the presence of unknown input delays, which are caused by wave propagation properties, dependent on the placement of the heating source along the tube, and hard to accurately determine. With this motivation, the present paper uses predictive cost adaptive control (PCAC) for sampled-data control of an experimental Rijke-tube setup. PCAC performs online closed-loop linear model identification for receding-horizon optimization based on the backward propagating Riccati equation. In place of analytical modeling, open-loop experiments are used to create a simple emulation model, which is used to choose PCAC hyperparameters. PCAC is applied to the Rijke-tube setup under various experimental scenarios to test its performance under unknown and parameter-dependent dynamics, and its robustness to input delay.

Paper: <a href = "https://ieeexplore.ieee.org/abstract/document/11107843"> Link </a>

Preprint: <a href = "https://arxiv.org/pdf/2402.00346"> Link </a>