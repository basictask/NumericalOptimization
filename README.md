# Numerical Methods for Optimization and Control Theory
Numerical optimization and multivariate analysis implemented by me for Numerical Optimization for System and Control Theory in ELTE university. 
These are MATLAB live scripts that contain full task descriptions and implementations of solutions. 

## 1_2
We want to place n = 3 charged particles along a circle centered at the origin. Suppose that
the particles carry c1 = 1, c2 = 2 and c3 = 3 units of charge, respectively. The particles shall
be placed in such a way that the total potential of the system is minimized.
Formalize this optimization problem. Which known algorithm would you recommend to solve
the problem with? Demonstrate an approximate solution to the problem.

## 1_5
Modify the implementation of the Armijo Gradient descent method, such that the plots also
include the further points examined by the line search method underneath, and also the
examined line should be visualised at each iteration.

## 1_7
Implement the unimodal Fibonacci line search algorithm, an improvement over the zero-order unimodal line search algorithm (zero_unimodal.m).

## 1_13
Implement the Polak–Ribiere conjugate gradient method. You may use the code for the
Fletcher–Reeves conjugate gradient algorithm (FR_conj_grad.m) as reference. Use a first-order unimodal line search method to find the directional minimizer at each step.

## 2_1
Implement the Broyden–Fletcher–Goldfarb–Shanno quasi-Newton method using exact line
search (i.e. each linesearch terminates in a directional local minimizer). You may use the
code for the Davidon–Fletcher–Powell method (QN_DFP.m) as reference.

## 2_5
Implement a constrained barrier method with logarithmic barrier. Make it able to explicitly
compute the gradients and Hessians of the modified fρ objectives based on the exact gradients
and Hessians of the gi contraint functions, given in the input. Use Newton’s method as the
unconstrained subroutine. You may use the code for the Carrol barrier (barrier_path.m)
as reference. You may implement the method with approximated Hessians for partial score.

## 2_10
Implement a function for fitting a three dimensional paraboloid z(x, y) = a·x^2+b·xy+c·y2^+dx+ey+f to a sample of m points (xi, yi, zi) ∈ R3, (i = 1, . . . , m) using linear least squares. Your method should find and return the optimal parameter values for a, b, c, d, e and f. You may use our SVD-based linear least squares solver (linear_LSq.m) after contstructing the coefficient matrix and the vector of expected values. Create a 3D plot of the input points and the returned paraboloid.

## 2_12
Implement a function to visualize the Carrol barrier’s effect used in inequality constrained
optimization problems for functions of two variables. The input should be the objective
function f, the constraints g, and the parameter ϱ. The function should create a 3D plot of
the original and the scaled objective functions. Provide some samples with bounded feasible
regions (e.g. triangle, rectangle, circle or some other nice region of your choice).
