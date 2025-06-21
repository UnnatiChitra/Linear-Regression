# Linear-Regression
Before diving into linear regression, it's helpful to have:

* **Basic Coding Skills** (Python)
* **Basic Math Understanding** (algebra, slope, intercept)
* **Python OOPs Concepts** (classes, methods, attributes)

This repository includes **three different implementations** of Linear Regression to help you understand the concept from scratch to library-level efficiency:

### 1. Linear Regression from scratch

> **Description:**
> Builds Linear Regression **completely from scratch** using Python. No external libraries are used for modeling — just pure math and code.

**What you’ll learn:**

* The math behind Linear Regression
* How predictions are made using `y = mx + c`
* Manual calculation of **Regression Metrics**
* Fundamentals of model fitting

### 2. Linear Regression using Sk-learn library

> **Description:**
> Applies Linear Regression using **scikit-learn**, a powerful and widely used ML library in Python.

**What you’ll learn:**

* How to use `LinearRegression` from `sklearn.linear_model`
* How to prepare and reshape data (`X`, `y`)
* Evaluating model performance using `.score()` and `.predict()`
* Comparing results with your scratch implementation

### 3. Linear Regression using Gradient Descent

> **Description:**
> Implements Linear Regression using **Gradient Descent** for optimization.

**What you’ll learn:**

* How gradient descent updates weights (`m` and `c`) to minimize loss
* How to tune **learning rate** and **epochs**
* Challenges like overflow, underfitting, and convergence
* How performance compares with `sklearn` and scratch methods

### Bonus Tips:

* If your R² is low: try **scaling your features** and adjusting learning rate
* Use plotting libraries like `matplotlib` to visualize regression lines and residuals
* Always compare manual models with sklearn to validate your logic
