# 10-Test-Functions-for-benchmarking-optimisation-algorithms
10 Test Functions for benchmarking optimisation algorithms



In computational and applied mathematics, test functions also known as artificial landscapes, are useful to evaluate characteristics of optimization algorithms in terms of i.e. the convergence rate, precision, performance and robustness.
The included test functions are:
1. Easom 2D
f(x) = -cos(x1) cos(x2) * exp ( – ( x1 – π )² – ( x2 – π )² )
2. Becker and Lago
f(x) = ( |x1| − 5 )² + ( |x2| − 5 )²

3. Bohachevsky
f(x) = x1 ² + 2*x2² – 0.3 * cos(3πx1) – 0.4*cos(4πx2) + 0.7

4. Eggerate
f(x) = x1² + x2² + 25*( (sin(x1))² + (sin(x2))² )

5. Periodic
f(x) = 1 + (sin(x1))² + (sin(x2))² – 0.1*exp ( -x1² – x2² )

and several other functions i.e. the commonly used Sphere, Rosenbrock, Rastrigin, Schwefel, and Griewank functions.

Important note:
Since these functions are looking for minimum of f(x) by optimizing both x1 and x2, a minus sign is added in each expression.

More details can be found at this page: https://kyleongmachinelearning.wordpress.com/2016/09/25/test-functions-for-optimization/
