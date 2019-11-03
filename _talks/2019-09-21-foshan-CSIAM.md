---
title: "2019 CSIAM Contributed paper"
subtitle: "Second-order Semi-implicit Projection Methods for Landau-Lifshitz Equation"
collection: talks
type: "Talk"
permalink: /talks/2018-12-08-nanjing-JSIAM
venue: "CSIAM"
date: 2019-09-21
location: "foshan, China"
---

In ferromagnets, the intrinsic magnetic order, known as magnetization, makes these materials
ideal for information storage and manipulation. From the modeling perspective, magnetization
dynamics is described by the Landau-Lifshitz equation with pointwise length constraint. From
the numerical perspective, typically, second-order in time schemes are either explicit with strong
stability restriction on the stepsize due to the high nonlinearity or implicit with a nonlinear
system of equations to be solved at each step. In the talk, we will introduce several second-order
semi-implicit schemes based on the second-order backward-differentiation-formula and the onesided interpolation 
from former steps with a projection step. For these schemes, we are able to
prove the uniqueness of the numerical solution to the linear system of equations at each step. For
one of these schemes, we then prove its second-order accuracy under the mild condition that the
stepsize in time is proportional to the gridsize in space. Examples in 1D and 3D are given to
verify the analysis results. A benchmark problem from National Institute of Standards and
Technology is also tested to verify the applicability of these schemes. <br>

[[Slide]](http://1223steven.github.io/files/Xie_CSIAM2019.pdf)