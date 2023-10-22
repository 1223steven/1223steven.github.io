---
title: "Error analysis of a linear numerical scheme for the Landau-Lifshitz equation with large damping parameters"
collection: publications
permalink: /publications/MAAIRL
venue: "Mathematical Methods in the Applied Sciences"
date: 2023
citation: 'Yongyong Cai, Jingrun Chen, Cheng Wang, <b>Changjian Xie</b>.'
---
[[ArXiv]](https://arxiv.org/pdf/1902.09740.pdf)
[[doi]]( https://doi.org/10.1002/mma.9601)


## Abstract
A second-order accurate, linear numerical method is analyzed for the Landau–Lifshitz equation with large damping parameters. 
This equation describes the dynamics of magnetization, with a non-convexity constraint of unit length of the magnetization. 
The numerical method is based on the second-order backward differentiation formula in time, combined with an implicit treatment for 
the linear diffusion term from the harmonic mapping part and explicit extrapolation for the nonlinear terms. Afterward, a projection 
step is applied to normalize the numerical solution at a point-wise level. This numerical scheme has shown extensive advantages in the 
practical computations for the physical model with large damping parameters, which comes from the fact that only a linear system with 
constant coefficients (independent of both time and the updated magnetization) needs to be solved at each time step, and has greatly
improved the numerical efficiency. Meanwhile, a theoretical analysis for this linear numerical scheme has not been available. 
In this paper, we provide a rigorous error estimate of the numerical scheme, in the discrete $\ell^{\infty}(0,T;\ell^2)\cap\ell^2(0,T;H^1_h)$ 
norm, under suitable regularity assumptions and reasonable ratio between the time step size and the spatial mesh size. 
In particular, the projection operation is nonlinear, and a stability estimate for the projection step turns out to be highly challenging. 
Such a stability estimate is derived in details, which will play an essential role in the convergence analysis for the numerical scheme, 
if the damping parameter is greater than $3$.