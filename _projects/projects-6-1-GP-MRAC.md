---
title: "Gaussian Processes for Model Reference Adaptive Control"
excerpt: "Implementation of Gaussian Processes (GPs) to estimate adaptive elements in model reference adaptive control (MRAC) <br/><img src='/images/videos/GP_MRAC_thumbnail.png' width='752' height='423'>"
collection: projects
---

The aim of the project is to implement a model reference adaptive control (MRAC) scheme in which Gaussian Processes (GPs) are employed to estimate the adaptive elements that MRAC features. The MRAC algorithm relies on a reference model with an adaptive term to mitigate errors caused by model uncertainty. For this project, it is assumed that the uncertainty term  can be described by a time-varying prior mean and covariance and that GPs can be used to learn continuous functions that best describe the mean and the covariance. Therefore the GP-MRAC scheme aims to model uncertainty using a GP-based adaptive element.  The GP-MRAC algorithm is tested by tracking a trajectory in the presence of the wing-rock dynamics.

This project was developed as part of the final project for a Parameter Inference and State Estimation graduate class and is based on the paper <b>Bayesian Nonparametric Adaptive Control Using Gaussian Processes</b>, which can be obtained using the following links: <a href = "https://dspace.mit.edu/bitstream/handle/1721.1/77931/TNN12.pdf">Preprint</a>, <a href = "https://ieeexplore.ieee.org/document/6823109">Full Paper</a>

The project report, results, and code can be found at the link below.


**Code**

- GP_MRAC_Code (<a href = "https://github.com/JAParedes/GP_MRAC_Code">Link</a>)

<img src="/images/videos/GP_MRAC_thumbnail.png">