---
title: "A machine-learning method for time-dependent wave equations over unbounded domains"
collection: publications
permalink: /publications/ABC_wave
venue: "ArXiv:2101.05807"
date: 2021-01-14
citation: '<b>Changjian Xie</b>, Xiantao Li and Jingrun Chen.'
---
[[ArXiv]](https://arxiv.org/abs/2101.05807)


## Abstract
Time-dependent wave equations represent an important class of partial differential equations (PDE) 
for describing wave propagation phenomena, which are often formulated over unbounded domains. 
Given a compactly supported initial condition, classical numerical methods reduce such problems 
to bounded domains using artificial boundary condition (ABC). In this work, we present a machine-learning method 
to solve this type of equations as an alternative to ABCs. Specifically, the mapping from the initial conditions to 
the PDE solution is represented by a neural network, trained using wave packets that are parameterized by their band width 
and wave numbers. The accuracy is tested for both the second-order wave equation and the Schrodinger equation, 
including the nonlinear Schrodinger equation. We examine the accuracy from both interpolations and extrapolations. 
For initial conditions lying in the training set, the learned map has good interpolation accuracy, 
due to the approximation property of deep neural networks. The learned map also exhibits some good extrapolation accuracy. 
We also demonstrate the effectiveness of the method for problems in irregular domains. 
Overall, the proposed method provides an interesting alternative for finite-time simulation of wave propagation.