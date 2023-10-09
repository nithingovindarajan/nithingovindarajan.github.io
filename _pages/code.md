---
layout: page
permalink: /code/
title: Code
description: Code written by me for various research projects.
nav: true
nav_order: 3
---

<!-- ### PyTensorlab (Python)
A huge undertaking to translate the [Tensorlab](https://www.tensorlab.net/) software package in Matlab to Python. I am one of the main contributing developers to this project. (IN DEVELOPMENT) -->

### Fast null space computation of Macaulay matrices (Julia)
An efficient algorithm to compute null spaces of Macaulay matrices of bivariate polynomial systems. The null space of the matrix is obtained by converting the Macaulay matrix into a Cauchy-like matrix and then using the Schur algorithm with approximate total pivoting to compute a rank-revealing factorization. ([Link to Repository](https://github.com/nithingovindarajan/Fast-Macaulay-Nullspace/tree/main))

### Spline-based separable expansions (Matlab)
An implementation of a supervised learning framework that employs splines in combination with sums of separable functions to perform both regression and classification tasks. The discretization of the approximant by both a B-spline and a low rank polyadic decomposition result in a highly effective procedure for approximating functions in many variables. ([Download link Tensorlab+ website](https://www.tensorlabplus.net/papers/govindarajan2022cpdspline.html))

### CSS and SSS matrices (Julia)
Code to solve linear systems for matrices in Cycle Semi-Separable (CSS) and Sequentially Semi- Separable (CSS) form. The code base also includes routines to convert a dense matrix into a CSS or SSS representation. In the case of CSS matrices, this involves solving a minimum rank completion problem of overlapping Hankel blocks. ([Link to Repository](https://gitlab.com/nithin.govindarajn/sss-and-css-solvers/))

### Periodic Approximation Toolbox (Matlab)
An implementation of the periodic approximation technique for computing spectra of the Koopman operator for measure-preserving dynamical systems. The code base caters both to the discrete-time and continuous-time case, but is limited to systems that only preserve the Lebesgue measure. ([Link to Repository](https://gitlab.com/nithin.govindarajn/koopman-periodic-approximation))