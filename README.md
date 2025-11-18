# 🤖 Optimization Project
This project aims to study the behavior and convergence properties of several optimization algorithms when applied to a **Ridge Regression** problem.
The goal is to compare algorithms in terms of convergence speed, computational cost stability, and accuracy, using the **Diamonds dataset**.

## 📌 Objectives
- Implement **Ridge Regression** as a convex optimization problem.
- Derive and analyze all mathematical properties of the objective function:
  - Convexity.  
  - Strong convexity.  
  - Differentiability / smoothness.  
  - Lipschitz continuity of the gradient.

- Apply and compare different optimization algorithms on **Diamonds dataset**, in order to predict diamond price:
  - Gradient Descent.
  - Gradient Descent with optimal step-size (1/L).
  - Stochastic Gradient Descent.
  - Mini-batch SGD.
  - Nesterov Accelerated Gradient (AGD).
  - Newton’s Method.

## 📈 Results & Analysis
The project compares:
- Convergence curves (loss vs iterations).  
- Time to convergence.  
- Distance from the closed-form solution.  
- Stability of each algorithm.  
- Effect of λ on performance and conditioning. 

