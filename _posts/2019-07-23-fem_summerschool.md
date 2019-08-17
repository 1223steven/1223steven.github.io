---
title: 'Minicourse--Notes for The 3rd Summer School on The Theory and Numerics of PDEs'
date: 2019-07-23
venue: 'Chengdu, Sichuan'
permalink: /posts/2019/07/fem-summer-school/
<!-- tags:
  - cool posts
  - category1
  - category2 -->
---
# Group Photo
<p align="center">
  <img src="https://1223steven.github.io/files/summer-school/PDEs.jpg?raw=true" alt="Photo" style="width: 650px;"/>
</p>

# Speaker
* [Xiaobing Feng (The University of Tennessee )](https://www.math.utk.edu/~xfeng/)
* [Chiwang Shu (Brown University)](http://www.dam.brown.edu/people/shu/)
* [Jie Shen (Purdue University)](http://www.math.purdue.edu/~shen/) 

# Links
* [Course page](https://tianyuan.scu.edu.cn/portal/article/index/id/366.html)
* [Workshop on the theory and numerics of PDEs](https://tianyuan.scu.edu.cn/portal/article/index/id/370/pid/16/cid/29.html) : [Schedule](http://1223steven.github.io/files/summer-school/schedule_chengdu.pdf)
  * LIST OF SPEAKERS:
     * [Guanghui Hu (BCSRC)](https://www.csrc.ac.cn/en/people/faculty/169.html) : Direct and inverse time-harmonic wave scattering problems
	 * [Buyang Li](http://www.mypolyuweb.hk/~bygli/LI_Buyang.htm) : A convergent evolving finite element algorithm for mean curvature flow of closed surfaces
	 * [Liang Li](http://www.math.uestc.edu.cn/plus/list.php?tid=228) : Solution of parametric electromagnetic radiation problems using a residual based POD reduced order method
	 * [Yibao Li](http://gr.xjtu.edu.cn/web/yibaoli) : Direct discretization method for t he Cahn Hilliard equation on surfaces
	 * [Junliang Lv](https://teachers.jlu.edu.cn/Lvjunliang/zh_CN/index.htm) : Numerical methods for scattering problems in unbounded domain
	 * [Qinglin Tang](https://scholar.google.com.sg/citations?user=Sx2DG9YAAAAJ&hl=en) : An efficient numerical method to compute the ground state of rotating dipolar Bose Einstein Condensates
	 * [Hao Wu](http://math.tongji.edu.cn/Data/View/4276) : Variational approach for learning Markov processes from time series data
	 * [Kuan Xu](https://math.ustc.edu.cn/new/teachersinfo1.php?id=181) : Computing convolutions, the story so far
	 * [Qinghai Zhang](https://person.zju.edu.cn/qinghai) : GePUP: A Fourth order Projec tion Method for Solving the Incompressible Navier Stokes Equations
	 * [Zhennan Zhou (BICMR)](http://bicmr.pku.edu.cn/~zhennan/) :Towards a mathematical understanding of surface hopping methods
   

# Abstract
This mini-course intends to present a holistic introduction to the finite element method (FEM), 
which is arguably the most popular and most powerful numerical method for solving partial differential equations (PDEs). 
Both boundary value problems (for elliptic PDEs) and initial–boundary value problems (for parabolic and hyperbolic PDEs) will be considered in the course. 
Following the historic development of the FEM, it will be introduced within a more general Galerkin and Petrov-Galerkin framework. 
The focuses of the course are to introduce/explain the main ideas/ingredients of the FEM and its variants/extensions (such as nonconforming methods, mixed methods, 
least squares methods) as well as the main techniques for the convergence analysis. Due to the time constraint. 
The construction of FE spaces and their interpolation theory will only be briefly covered, so is the Sobolev space theory. 
Unlike the popular presentation of the materials which assumes the coercivity of the underlying PDE problem (or bilinear form) in a Hilbert space setting, 
this mini-course adopts an approach which relies on the weak coercivity (i.e., inf-sup/LBB condition) and is formulated in a Banach space setting. If time permits, 
connection of the FEM to discontinuous Galerkin (DG) methods and mixed finite element methods will also be discussed. 
Applications of the FEM to be covered include the Stokes and Navier-Stokes equations for incompressible fluids and the Lame’s equations for linear elasticity. 
Finally, solution methods (i.e., solvers) and computer implementation of the FEM will also be briefly discussed.

# Outline
1. Big picture and sources of PDEs. 
2. Formulation and analysis of abstract Galerkin method. 
3. Formulation and examples of the finite element method. 
4. Convergence theories of the finite element method. 
5. Applications to incompressible fluids and linear elasticity. 
6. Solvers and computer implementation.

# Reference
1. “Numerical Solutions of Partial Differential Equations by Finite Element Method” by C. Johnson, Dover, 2009. 
2. “Theory and Practice of Finite Elements” by A. Ern and J.-L. Guermond, Springer, 2004. 
3. ‘The Mathematical Theory of Finite Element Methods” by S. Brenner and R. Scott, Springer, 2008. 
4. “The Finite Element Method for Elliptic Problems” by P. G. Ciarlet, SIAM, 2002. 
5. “Finite Elements: Theory, Fast Solvers, and Applications in Solid Mechanics” by D. Braess, Cambridge University Press, 2007. 
6. “Selected Topics in Finite Element Methods” by Z. Chen and H. Wu, Science Press, 2010. 
7. “Survey Lectures on the Mathematical Foundation of the Finite Element Method” by I. Babushka and A. K. Aziz; In: A. K. Aziz, Ed., The Mathematical Foundations of the Finite Element Method with Applications to Partial Differential Equations, Academic Press, New York, 1972, pp. 5-359. 
8. “From finite differences to finite elements: A short history of numerical analysis of partial differential equations” by V. Thom\’ee , Journal of Computational and Applied Mathematics, 128:1-54, 2001. 
9. “Programming of Finite Element Methods in MATLAB” by L. Chen, https://arxiv.org/abs/1804.05156/ 
10. “Discontinuous Galerkin finite element differential calculus and applications to numerical solutions of linear and nonlinear PDEs” by X. Feng, T. Lewis and M. Neilan, J. Computational and Applied Mathematics 299:68–91, 2016. A Matlab Toolbox was developed by Stefan Schnake which can be downloaded from
http://www2.math.ou.edu/~sschnake/research

