---
title: "Two improved Gauss-Seidel projection methods for Landau-Lifshitz-Gilbert equation"
collection: publications
permalink: /publications/TWOIMPROVED
venue: "Journal of Computational Physics"
date: 2019-05-26
citation: 'Panchi Li, <b>Changjian Xie</b>, Rui Du, Jingrun Chen and Xiaoping Wang. <i>Journal of Computational Physics.</i> <b>2019.</b>'
---  
[[ArXiv: 1907.11853]](https://arxiv.org/pdf/1907.11853.pdf), [[doi: 10.1016/j.jcp.2019.109046]](https://doi.org/10.1016/j.jcp.2019.109046)


## Abstract
Micromagnetic simulation is an important tool to study various dynamic behaviors of
magnetic order in ferromagnetic materials. The underlying model is the Landau-LifshitzGilbert equation, where the magnetization dynamics is driven by the gyromagnetic torque
term and the Gilbert damping term. Numerically, considerable progress has been made in
the past decades. One of the most popular methods is the Gauss-Seidel projection method
developed by Xiao-Ping Wang, Carlos Garc´ıa-Cervera, and Weinan E in 2001. It first solves
a set of heat equations with constant coefficients and updates the gyromagnetic term in the
Gauss-Seidel manner, and then solves another set of heat equations with constant coefficients
for the damping term. Afterwards, a projection step is applied to preserve the length constraint in the pointwise sense. This method has been verified to be unconditionally stable
numerically and successfully applied to study magnetization dynamics under various controls.

In this paper, we present two improved Gauss-Seidel projection methods with unconditional stability. The first method updates the gyromagnetic term and the damping term
simultaneously and follows by a projection step. The second method introduces two sets of
approximate solutions, where we update the gyromagnetic term and the damping term simultaneously for one set of approximate solutions and apply the projection step to the other set
of approximate solutions in an alternating manner. Compared to the original Gauss-Seidel
projection method which has to solve heat equations 7 times at each time step, the improved
methods solve heat equations 5 times and 3 times, respectively. First-order accuracy in time
and second-order accuracy in space are verified by examples in both 1D and 3D. In addition, unconditional stability with respect to both the grid size and the damping parameter is
confirmed numerically. Application of both methods to a realistic material is also presented
with hysteresis loops and magnetization profiles. Compared with the original method, the
recorded running times suggest that savings of both methods are about 2/7 and 4/7 for the
same accuracy requirement, respectively.

