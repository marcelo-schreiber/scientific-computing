# Scientific computing

## Other languages
- [README em português](https://github.com/marcelo-schreiber/scientific-computing/blob/master/README.pt.md)

## Introduction

This repository contains the code for the scientific computing course at the Federal University of Paraná (UFPR). The course is taught in C and covers the following topics:

- Floating Point Arithmetic IEEE 754 in Intervals
- Linear systems
- Polynomial Interpolation
- Matrix and Vector Multiplication
- Numerical Integration
- Polynomial Approximation

## Projects

The projects are divided into the following folders:

- `ep1`: Floating Point Arithmetic IEEE 754 in Intervals;
- `ep2`: Solving Linear systems by Gaussian Elimination in 3 strategies;
- `ep3`: Polynomial Interpolation by Lagrange and Newton methods;
- `ep4`: Matrix and Vector Multiplication with UNROLL & JAM and LOOP BLOCKING optimizations;
- `ep5`: Numerical Integration of the Styblinski-Tang function using Monte Carlo and rectangle methods;
- `t1`: Polynomial Approximation by Minimization of the Least Squares Method using Floating Point intervals;
- `t2`: t1 with optimizations;

All projects have a `Makefile` to compile the code. To compile the code, just run `make` in the project folder and remember to read the `README.md` file in each folder to understand how to run the code. Also some submodules have a `REPORT.pdf` file, read it to understand the code and the likwid results in charts.
Most of them also require Likwid to be installed. To install it, follow the instructions in the [official repository](https://github.com/RRZE-HPC/likwid).

## Authors

- [Marcelo Schreiber](https://github.com/marcelo-schreiber)
- [Felipe Vieira](https://github.com/felipeqvieira)
