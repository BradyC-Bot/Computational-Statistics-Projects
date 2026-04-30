# Computational Statistics & Algorithmic Optimization

This repository contains a collection of projects focused on implementing machine learning foundations, stochastic modeling, and custom optimization algorithms from scratch. Each project emphasizes the mathematical theory behind data science and its practical application using **R**.

## 🚀 Featured Projects

### 1. Robust Regression via Custom Gradient Descent

Implemented a robust estimation model to handle outliers by moving beyond standard Ordinary Least Squares (OLS).

-   **The Problem:** Standard squared error loss is highly sensitive to outliers.
    
-   **The Solution:** Derived the gradient $\nabla\rho(\theta)$ for a **Log-cosh loss function** and built a **Gradient Descent** optimizer from scratch to find the global minimum.
    
-   **Key Results:** Compared manual implementation against R’s `optim()` and `nlm()` functions to validate convergence accuracy and computational efficiency.
    

### 2. Discrete Optimization: Simulated Annealing

Explored metaheuristic search patterns to solve high-dimensional discrete optimization problems.

-   **The Problem:** Finding the optimal starting configuration for **Conway’s Game of Life** to maximize "alive" cells after a set duration.
    
-   **The Solution:** Developed a **Simulated Annealing** algorithm to navigate a 25-dimensional binary search space.
    
-   **Technical Highlight:** Implemented a cooling schedule to balance exploration of the state space with exploitation of local optima.
    

### 3. Predictive Modeling with Markov Chains

Applied stochastic processes to model and predict outcomes in a competitive environment (Tennis Match simulation).

-   **The Problem:** Estimating the probability of victory based on varying player skill levels and game states.
    
-   **The Solution:** Constructed **Transition Matrices** to represent game flow and utilized **Monte Carlo simulations** to verify theoretical probabilities.
    
-   **Key Insight:** Used matrix powers ($A^n$) to calculate state-transition probabilities for long-term match outcomes.
    

### 4. Mode Discovery via Kernel Density Estimation (KDE)

Used optimization techniques to identify underlying patterns in continuous data distributions.

-   **The Task:** Developed a script to find the **Global Mode** (the highest peak) of a KDE.
    
-   **The Approach:** Calculated the derivative of the kernel density function and applied gradient-based optimization to navigate the density surface.
    
-   **ML Relevance:** Essential for cluster analysis and understanding unsupervised data structures.
    

### 5. Evaluating the Bias-Variance Trade-off

Analyzed model complexity to ensure generalization on unseen datasets.

-   **The Experiment:** Fitted polynomial models of varying degrees to time-series data and evaluated their performance.
    
-   **Metric:** Used **Average Predictive Squared Error (APSE)** to determine the optimal balance between model flexibility and predictive stability.
    
-   **Outcome:** Identified the "sweet spot" in model complexity that minimized overfitting while maintaining accuracy.
    

----------

## 🛠️ Tools & Technologies

-   **Language:** R
    
-   **Mathematical Frameworks:** Stochastic Processes, Calculus-based Optimization, Linear Algebra.
    
-   **Key Concepts:** Gradient Descent, Monte Carlo Simulation, Markov Chains, Bias-Variance Trade-off.
    

## 📈 How to Use

Each folder contains the `.R` or `.Rmd` source code and a rendered `PDF/HTML` report showing the final analysis and visualizations.
