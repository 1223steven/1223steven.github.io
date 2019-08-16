---
title: "Convergence analysis of a second-order semi-implicit projection method for Landau-Lifshitz equation"
collection: publications
permalink: /publications/MAAIRL
venue: "Submitted to  (ICML-19)"
date: 2018-4-12
citation: 'Jingrun Chen, Cheng Wang, <b>Changjian Xie</b>. <i>submitted to Applied Numerical Mathematics</i>. <b>2019</b>.'
---
[[PDF]](https://arxiv.org/pdf/1902.09740.pdf)


## Abstract
The numerical approximation for the Landau-Lifshitz equation,
the dynamics of magnetization in a ferromagnetic material, is taken into consideration. This highly nonlinear equation, with a non-convex constraint, has
several equivalent forms, and involves solving an auxiliary problem in the infinite domain. All these features have posed interesting challenges in developing
numerical methods. In this paper, we first present a fully discrete semi-implicit
method for solving the Landau-Lifshitz equation based on the second-order
backward differentiation formula and the one-sided extrapolation (using previous time-step numerical values). A projection step is further used to preserve
the length of the magnetization. Subsequently, we provide a rigorous convergence analysis for the fully discrete numerical solution by introducing two sets
of approximated solutions to preceed estimation alternatively, with unconditional stability and second-order accuracy in both time and space, provided
that the spatial step-size is the same order as the temporal step-size, which
remarkably relax restrictions of temporal step-size compared to the implicit
schemes. And also, the unique solvability of the numerical solution without
any assumptions for the step size in both time and space is theoretically justified, which turns out to be the first such result for the micromagnetics model.
All these theoretical properties are verified by numerical examples in both oneand three- dimensional spaces.
