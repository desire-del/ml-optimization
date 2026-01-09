![Python](https://img.shields.io/badge/python-3.11-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green)
![NumPy](https://img.shields.io/badge/numpy-yes-brightgreen)

# Regularized Regression and Gradient-Based Optimization in Python

## Overview

This repository provides implementations and experiments for **linear regression** with **regularization**, focusing on **Ridge (ℓ2)** and **Lasso (ℓ1)** penalties. It demonstrates classical and advanced **gradient-based optimization techniques**, including:

- **Gradient Descent** with fixed step size  
- **Backtracking Line Search**  
- **Momentum Method**  
- **Proximal Gradient Method** for sparse models  
 

The project is designed for **educational purposes**, showing convergence, sparsity, and generalization performance.

---

## Features

- **Least Squares Regression**: Standard solution and evaluation on training/test sets  
- **Ridge Regression (ℓ2)**: Gradient descent with optional line search and momentum  
- **Lasso Regression (ℓ1)**: Sparse solutions using proximal gradient methods  
- **Visualization**: Evolution of objective functions, gradient norms, and sparsity patterns  
- **Configurable Regularization**: Easily modify λ for Ridge and Lasso  
- **Reproducible Experiments**: Python + NumPy + Matplotlib

