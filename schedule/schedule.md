---
layout: course
title: Biostat 257
---

## Course Schedule

BIOSTAT 257 tentative schedule and handouts (expect frequent updates)

Zoom link: <https://ucla.zoom.us/j/97491444804>, for call in dial +1-213-338-8477 and enter meeting ID 974 9144 4804.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main)

[CCLE Site](https://ccle.ucla.edu/course/view/21S-BIOSTAT257-1)

Readings:  

* [_50 years of data sicence_](../readings/Donoho15FiftyYearsDataScience.pdf) by David Donoho (2015)  
* [_Julia: a fresh approach to numerical computing_](../readings/BezansonEdelmanKarpinskiShah17Julia.pdf) by Bezanson, Edelman, Karpinski, and Shah (2017)  
* [_What every computer scientist should know about floating-point arithmetic_](../readings/Goldberg91FloatingPoint.pdf) by David Goldberg  
* Top 10 algorithms in the 20th century  
[Metropolis](../readings/metropolis.pdf), [Simplex](../readings/simplex.pdf), [Krylov](../readings/krylov.pdf), [Matrix decomposition](../readings/decomp.pdf), [Fortran](../readings/fortran.pdf), [QR algorithm](../readings/qr.pdf), [Quicksort](../readings/qsort.pdf), [FFT](../readings/fft.pdf), [Integer relation](../readings/integer.pdf), [FMM](../readings/fmm.pdf)  

| Week | Tuesday | Thursday | Homework |
|:-----------|:-----------|:------------|:------------|
| 1 | [3/30](https://ucla-biostat-257-2021spring.github.io/biostat257spring2021/2021/03/30/week1-day1.html) course introduction and logistics \[slides: [html](../slides/01-intro/intro.html)\] | 4/1 computer languages \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F02-langs%2Flangs.ipynb), [html](../slides/02-langs/langs.html)\], Julia intro. \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F03-juliaintro%2Fjuliaintro.ipynb), [html](../slides/03-juliaintro/juliaintro.html)\] | HW1 \[[ipynb](https://raw.githubusercontent.com/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main/hw/hw1/hw01.ipynb), [html](../hw/hw1/hw01.html)\] |
| 2 | 4/6 plotting in Julia \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F04-juliaplot%2Fjuliaplots.ipynb), [html](../slides/04-juliaplot/juliaplots.html)\], Jupyter Notebook \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F05-jupyter%2Fjupyter.ipynb), [html](../slides/05-jupyter/jupyter.html)\] | 4/8 computer arithmetic \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F06-arith%2Farith.ipynb), [html](../slides/06-arith/arith.html)\], algo. intro. \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F07-algo%2Falgo.ipynb), [html](../slides/07-algo/algo.html)\] | |
| 3 | 4/13 BLAS \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F08-numalgintro%2Fnumalgintro.ipynb), [html](../slides/08-numalgintro/numalgintro.html)\], NLA on GPU \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F09-juliagpu%2Fjuliagpu.ipynb), [html](../slides/09-juliagpu/juliagpu.html)\] | 4/15 triangular systems \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F10-trisys%2Ftrisys.ipynb), [html](../slides/10-trisys/trisys.html)\], GE/LU \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F11-gelu%2Fgelu.ipynb), [html](../slides/11-gelu/gelu.html)\] | HW2 \[[ipynb](https://raw.githubusercontent.com/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main/hw/hw2/hw02.ipynb), [html](../hw/hw2/hw02.html)\] |
| 4 | 4/20 Cholesky \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F12-chol%2Fchol.ipynb), [html](../slides/12-chol/chol.html)\], QR (GS, Householder, Givens) \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F13-qr%2Fqr.ipynb), [html](../slides/13-qr/qr.html)\] | 4/22 Sweep operator \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F14-sweep%2Fsweep.ipynb), [html](../slides/14-sweep/sweep.html)\], summary of linear regression \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F15-linreg%2Flinreg.ipynb), [html](../slides/15-linreg/linreg.html)\] | |
| 5 | 4/27 condition number \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F16-cond%2Fcond.ipynb), [html](../slides/16-cond/cond.html)\], iterative methods intro \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F17-iterative%iterative.ipynb), [html](../slides/17-iterative/iterative.html)\] | 4/29 conjugate gradient  \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F18-cg%cg.ipynb), [html](../slides/18-cg/cg.html)\] | HW3 |
| 6 | 5/4 easy linear system \[slides: [Binder](https://mybinder.org/v2/gh/ucla-biostat-257-2021spring/ucla-biostat-257-2021spring.github.io/main?filepath=slides%2F19-easylineq%easylineq.ipynb), [html](../slides/19-easylineq/easylineq.html)\], eigen-decomposition and SVD | 5/6 optimization intro. | | 
| 7 | 5/11 optimization in Julia | 5/13 Newton-Raphson, Fisher scoring, GLM, nonlinear regression (Gauss-Newton), quasi-Newton | HW4 |  
| 8 | 5/18 KKT, constrained optimization | 5/20 EM algorithm | HW5 |  
| 9 | 5/25 MM algorithm | 5/27 LP, QP | HW6 |  
| 10 | 6/1 SOCP, SDP, GP | 6/3 concluding remarks | |  
