---
title: "Application of Root-Finding Methods to Iterative Model Predictive Control of Pseudo-Linear Systems"
collection: publications
category: conferences
permalink: /publication/2025-06-06-alhazmi-iter-MPC
excerpt: 'This paper explores the effectiveness of four root-finding methods for iterative model predictive control applied to nonlinear systems that can be written in pseudo-linear form.'
date: 2025-06-06
venue: 'Proceedings of the American Control Conference'
citation: 'R. A. Alhazmi, J. A. Paredes Salazar, S. A. U. Islam, and D. S. Bernstein, &quot;Application of Root-Finding Methods to Iterative Model Predictive Control of Pseudo-Linear Systems,&quot; in <i>Proc. Amer. Contr. Conf. (ACC),</i> IEEE, 2025, pp. 3385–3390.'
---

For nonlinear systems that can be written in pseudo-linear form, we use iterative model predictive control (IMPC) for receding-horizon optimization. Pseudo-linear models, which are written in terms of state-dependent-coefficients (SDC’s), are widely used with the state-dependent Riccati equation. IMPC iterates over the horizon by updating the future control and state sequences until the future control sequence converges. To facilitate convergence, this paper explores the effectiveness of four root-finding methods and compares their performance with fixed-point iteration. At each iteration, a quadratic programming problem is solved using the current SDC’s to obtain a full-state-feedback controller. To assess the effectiveness of the root-finding methods, each technique is used to stabilize a collection of benchmark nonlinear systems.

Paper: <a href = "https://dsbaero.engin.umich.edu/wp-content/uploads/sites/441/2025/08/RamiACC2025_IMPC4PLS.pdf"> Link </a>