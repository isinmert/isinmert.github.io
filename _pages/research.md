---
title: Research Overview
permalink: /research/
author_profile: true
---
My research can be mainly classified into two main categories. So far, I have
worked on the Covariance Steering Theory and its application in safe and robust
trajectory optimization.
## Covariance Steering Theory
In this project, we extend the Covariance Steering Theory.
Covariance Steering problems are a class of stochastic optimal control problems
where the goal is steer a distribution to a desired one while minimizing some
cost index.

We solved soft constrained version of this problem in which the condition on
the terminal distribution is encoded in the objective function by utilizing
squared Wasserstein Distance. We also proposed a new parametrization to these
problems to make them more tractable.[[1]](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9306841)
[[2]](https://arxiv.org/pdf/2103.14428)


In our recent work, we showed that under certain conditions the Covariance
Steering with Wasserstein distance problem is convex and convex concave
procedure converges to the unique global minimizer.
[[3]](https://arxiv.org/pdf/2103.13579)

## Covariance Steering in Robust Trajectory Optimization
One implication of covariance control problems is to control the distribution
of the state of the agent. We use this interpretation of covariance steering
to make model predictive path integral control algorithm more robust against
unmodeled disturbances. Furthermore, our approach provides additional safety
against bad tuning of running cost functions and algorithm parameters.
[[4]](https://arxiv.org/pdf/2110.07744)
