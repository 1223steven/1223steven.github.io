---
title: "2023 $13^{th} CSCM$"
subtitle: "Second-order Semi-implicit Projection Methods And Analysis for Micromagnetics Simulations"
collection: talks
type: "Talk"
permalink: /talks/2023-07-15-nanjing-CSIAM
venue: "CSCM"
date: 2023-07-15
location: "Nanjing, China"
---

The numerical approximation for the Landau-Lifshitz equation, the dynamics of magnetization in a
ferromagnetic material, is taken into consideration. This highly nonlinear equation, with a non-convex
constraint, has several equivalent forms, and involves solving an auxiliary problem in the infinite domain.
All these features have posed interesting challenges in developing numerical methods. In this talk,
I will introduce a fully discrete semi-implicit method for solving the Landau-Lifshitz equation based on
the second-order backward differentiation formula and the one-sided extrapolation (using previous timestep
numerical values). A projection step is further used to preserve the length of the magnetization.
Subsequently, we provide a rigorous convergence analysis for the fully discrete numerical solution by
introducing two sets of approximated solutions to preceed estimation alternatively, with unconditional
stability and second-order accuracy in both time and space, provided that the spatial step-size is the same
order as the temporal step-size, which remarkably relax restrictions of temporal step-size compared to
the implicit schemes. And also, the unique solvability of the numerical solution without any assumptions
for the step size in both time and space is theoretically justified, which turns out to be the first such
result for the micromagnetics model. All these theoretical properties are verified by numerical examples
in both one- and three- dimensional spaces. <br>

[[Slide]](http://1223steven.github.io/files/xie_cscm2023.pdf)