---
title: "Robust Principal Component Analysis (RPCA) Code"
excerpt: "RPCA using a facial reduction model"
collection: portfolio
---

This is the matlab code for doing Robust Principal Component Analysis (RPCA) associated with the paper [Robust principal component analysis using facial reduction](https://doi.org/10.1007/s11081-019-09476-9). The aim is to recover the data matrix as a sum of a low-rank matrix and a sparse matrix so as to eliminate erratic noise (outliers). We propose a novel nonconvex and nonsmooth reformulation of the original NP-hard RPCA model. The new model adds a redundant semidefinite cone constraint and solves small subproblems using a PALM algorithm. Each subproblem results in an exposing vector for a facial reduction technique that is able to reduce the size significantly. This makes the problem amenable to efficient algorithms in order to obtain high-level accuracy.

======

[Down the zip file](https://feiwang-carrot.github.io/files/RPCAcode.zip)
