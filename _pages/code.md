---
layout: page
permalink: /code/
title: Code
description: Code written by me for various research projects.
nav: true
nav_order: 3
---

### PyTensorlab (Python)
A huge undertaking to translate the [Tensorlab](https://www.tensorlab.net/) software package in Matlab to Python. I am one of the main contributing developers to this project. (IN DEVELOPMENT)

### Fast null space computation of Macaulay matrices (Julia)
Julia code written by me and [Raphaël Widdershoven](https://www.kuleuven.be/wieiswie/nl/person/00147347) to efficiently compute null spaces of Macaulay matrices of bivariate polynomial systems. The null space of the matrix is computed by converting the Macaulay matrix into a Cauchy-like matrix and then employing the Schur algorithm with approximate total pivoting to compute a rank-revealing factorization. ([Link to Repository](https://github.com/nithingovindarajan/Fast-Macaulay-Nullspace/tree/main))

### Spline-based separable expansions (Matlab)
Matlab code written by me and [Nico Vervliet](https://www.kuleuven.be/wieiswie/nl/person/00092556) that implements regression and classification techniques using splines in combination with sums of separable functions. ([Download link Tensorlab+ website](https://www.tensorlabplus.net/papers/govindarajan2022cpdspline.html))

### CSS and SSS matrices (Julia)
Julia code to solve linear systems for matrices in Cycle Semi-Separable (CSS) and Sequentially Semi- Separable (CSS) form. The codebase also includes routines to convert a dense matrix into a CSS or SSS representation. In the case of CSS matrices, this involves solving a minimum rank completion problem of overlapping Hankel blocks. ([Link to Repository](https://gitlab.com/nithin.govindarajn/sss-and-css-solvers/))

### Periodic Approximation Toolbox (Matlab)
Matlab code written by me to compute spectra of the Koopman operator for measure-preserving systems using the technique of periodic approximation. ([Link to Repository](https://gitlab.com/nithin.govindarajn/koopman-periodic-approximation))