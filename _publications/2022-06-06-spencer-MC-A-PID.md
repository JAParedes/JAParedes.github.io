---
title: "An adaptive PID autotuner for multicopters with experimental results"
collection: publications
category: conferences
permalink: /publication/2022-06-06-spencer-MC-A-PID
excerpt: 'This paper develops an adaptive PID autotuner for multicopters, and presents simulation and experimental results.'
date: 2022-06-06
venue: 'Proceedings of the International Conference on Robotics and Automation'
citation: "J. Spencer, J. Lee, J. A. Paredes, A. Goel, and D. Bernstein, &quot;An adaptive PID autotuner for multicopters with experimental results,&quot; in <i>Proc. Int. Conf. Robot. Autom. (ICRA),</i> IEEE, 2022, pp. 7846–7853."
---

This paper develops an adaptive PID autotuner for multicopters, and presents simulation and experimental results. The autotuner consists of adaptive digital control laws based on retrospective cost adaptive control implemented in the PX4 flight stack. A learning trajectory is used to optimize the autopilot during a single flight. The autotuned autopilot is then compared with the default PX4 autopilot by flying a test trajectory constructed using the second-order Hilbert curve. In order to investigate the sensitivity of the autotuner to the quadcopter dynamics, the mass of the quadcopter is varied, and the performance of the autotuned and default autopilot is compared. It is observed that the autotuned autopilot outperforms the default autopilot.

Paper: <a href = "https://dsbaero.engin.umich.edu/wp-content/uploads/sites/441/2022/10/An_Adaptive_PID_Autotuner_for_Multicopters_with_Experimental_Results.pdf"> Link </a>

Code: <a href = "https://github.com/JAParedes/PX4-Autopilot/tree/RCAC_MC_AutoTuner"> Link </a>