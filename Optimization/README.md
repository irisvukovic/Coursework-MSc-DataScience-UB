# Optimization
This course introduced fundamental and advanced concepts in mathematical optimization. The assignments focused on both theoretical understanding and practical behavior of algorithms, which strengthened my understanding of optimization theory and gave me hands-on experience with real algorithmic behaviors.

---

## Assignments/Projects

### 1. [Gradient Descent Methods](./gradient_descent.ipynb)
The main goals were to apply basic gradient descent using different starting points, visualize the optimization path and observe which minimum the algorithm converges to. We also implemented backtracking line search to adapt the step size at each iteration and compared the performance of constant step-size gradient descent versus backtracking gradient descent.

This project highlighted how sensitive gradient descent can be to both initialization and learning rate choice.

### 2. [Robust Linear Regression](./robust_linear_regression.ipynb)

In this practical, we used gradient descent to find the optimal values of the regression parameters \( a \) and \( b \) by minimizing different loss functions:

- Least Squares Method (LSM)
- Cauchy loss function (robust to outliers)

This assignment introduced me to the concept of robust optimization.

### 3. [Constrained Optimization](./constrained_optimization.ipynb)

This project focused on constrained problems using Sequential Quadratic Optimization (SQO). We implemented SQO with step size control, experimented with starting points farther from the optimum and tested a merit function with classical gradient descent

This exercise provided practical insight into handling real-world constraints in optimization problems.

### 4. [Stochastic Gradient Descent for SVM](./stochastic_gradient_descent.ipynb)

In this practical, we solved the Support Vector Machine (SVM) optimization problem in the primal form using Stochastic Gradient Descent (SGD). We compared the convergence and stability of classical SGD and mini-batch SGD.

This project demonstrated why stochastic methods are often preferred for large-scale learning problems.
