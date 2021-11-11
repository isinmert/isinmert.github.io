---
title: "Constrained Covariance Steering Based Tube-MPPI"
collection: publications
permalink: /publications/ACC1
venue: "Submitted to American Control Conference 2022"
date: 2021-09-23
citation: '<b>Balci, I. M.</b>, Bakolas, E., Vlahov, B., & Theodorou, E. (2021). Constrained Covariance Steering Based Tube-MPPI. arXiv preprint arXiv:2110.07744.'


---

<!-- Insert Paper Link -->
[[PDF]](https://arxiv.org/pdf/2110.07744)

## Abstract
<!-- Insert Abstract -->
In this paper, we present a new trajectory optimization algorithm for stochastic linear systems which combines Model Predictive Path Integral (MPPI) control with Constrained Covariance Steering (CSS) to achieve high performance with safety guarantees (robustness). Although MPPI can be used to solve complex nonlinear trajectory optimization problems, it may not always handle constraints effectively and its performance may degrade in the presence of unmodeled disturbances. By contrast, CCS can handle probabilistic state and / or input constraints (e.g., chance constraints) and also steer the state covariance of the system to a desired positive definite matrix (control of uncertainty) which both imply that CCS can provide robustness against stochastic disturbances. CCS, however, suffers from scalability issues and cannot handle complex cost functions in general. We argue that the combination of the two methods yields a class of trajectory optimization algorithms that can achieve high performance (a feature of MPPI) while ensuring safety with high probability (a feature of CCS). The efficacy of our algorithm is demonstrated in an obstacle avoidance problem and a circular track path generation problem.
