# MA301 — Numerical Methods — PLAN

**Semester:** 3 · **Credits:** 3 · **Level:** Intermediate
**Theory:** 30 hrs · **Lab:** 30 hrs · **Tools:** Python (NumPy, SciPy), C (optional)

## Syllabus

### Unit 1 — Errors, Root Finding (9 lectures)
1. Sources of error — rounding, truncation, modelling
2. Absolute and relative error
3. Machine epsilon and floating-point limits
4. Condition number and numerical stability
5. Bisection method — algorithm and convergence
6. False position (regula falsi)
7. Newton-Raphson method
8. Secant method
9. Fixed-point iteration and convergence criteria

### Unit 2 — Linear Systems (9 lectures)
1. Direct methods — Gaussian elimination
2. Pivoting — partial and full
3. LU decomposition
4. Cholesky decomposition
5. Iterative methods — Jacobi
6. Gauss-Seidel
7. Convergence of iterative methods
8. Condition number of a matrix
9. Sparse systems — an introduction

### Unit 3 — Interpolation and Curve Fitting (9 lectures)
1. Lagrange interpolation
2. Newton divided-difference interpolation
3. Spline interpolation — linear and cubic
4. Least-squares regression — linear
5. Polynomial regression
6. Non-linear regression (overview)
7. Runge's phenomenon
8. Chebyshev nodes
9. Choosing a method — stability and accuracy

### Unit 4 — Numerical Integration and Differentiation (9 lectures)
1. Trapezoidal rule
2. Simpson's 1/3 and 3/8 rules
3. Romberg integration
4. Gaussian quadrature
5. Adaptive integration
6. Newton-Cotes formulas and error terms
7. Numerical differentiation — forward, backward, central
8. Richardson extrapolation
9. Applications in engineering and science

### Unit 5 — Ordinary Differential Equations (9 lectures)
1. Initial value problems — setup
2. Euler's method and its error
3. Improved Euler (Heun's) method
4. Runge-Kutta methods — RK2 and RK4
5. Multistep methods — Adams-Bashforth (overview)
6. Stability of ODE solvers
7. Boundary value problems — finite difference
8. Systems of ODEs
9. Applications — simulation of physical systems

## Practical Labs (15)

1. Machine epsilon and floating-point error exploration
2. Root finding — bisection, Newton, secant on the same function
3. Compare convergence rates of root-finding methods
4. Gaussian elimination with and without pivoting
5. LU decomposition and solving multiple right-hand sides
6. Iterative solvers — Jacobi vs Gauss-Seidel comparison
7. Lagrange interpolation on sampled points
8. Cubic spline interpolation of a real dataset
9. Least-squares regression on a dataset
10. Trapezoidal vs Simpson — error comparison
11. Adaptive integration on a difficult function
12. Numerical differentiation — forward vs central — error plot
13. Euler vs RK4 on the same ODE
14. Solve a system of ODEs — predator-prey
15. Compare with SciPy's `solve_ivp` and analyse accuracy

## Assignments

1. Error analysis — compute truncation vs rounding errors
2. Root-finding — implement two methods with convergence analysis
3. Linear systems — solve a given system four different ways
4. Interpolation exercise on a real dataset
5. ODE solver implementation and comparison with reference
