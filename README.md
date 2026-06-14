# Numerical Analysis Project 2023

This repository contains a Jupyter Notebook implementing fundamental computational methods studied in Numerical Analysis. 

## Authors
* **Panagiotis-Polydoros Vogiatzis** (AEM: 10855)
* **Christos Gounaris** (AEM: 10638)

## Features & Contents

### 1. Matrix Factorization
* **LU Decomposition (`LUmine`):** Custom implementation for decomposing a square matrix into lower and upper triangular matrices.
* **QR Decomposition (`QRmine`):** Custom implementation utilizing the Gram-Schmidt process to factorize matrices into orthogonal and upper triangular matrices.

### 2. Hilbert Matrix Stability Analysis
* Generation of $N \times N$ Hilbert matrices.
* System solving ($Hx = b$) utilizing the custom LU algorithm.
* Error sensitivity and condition testing via computational perturbations ($10^{-15}$).
* Plotting and visualization of numerical instability metrics (Maximum Absolute Difference and 2-Norm differences) across scaling matrix dimensions.

### 3. Least Squares Function Approximation
* Generating target datasets using a predefined mathematical function corrupted with random Gaussian noise ($y = \cos(4t) + 0.1 \cdot \mathcal{N}(0,1)$).
* Constructing a Vandermonde design matrix for $4^{\text{th}}$-degree polynomial fitting.
* Computing optimal coefficient vectors by solving normal equations through custom LU and QR factorizations.
* Evaluation of the Residual Sum of Squares (RSS) and plotting the optimal regression curve against the noisy data points.

## Requirements & Dependencies
* Python 3.x
* Jupyter Notebook
* NumPy
* Matplotlib
