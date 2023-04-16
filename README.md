# numericalProject-falsePosition
Numerical Computing : False Position Solver 
The false position method is a numerical root-finding algorithm that is used to find the roots of a given nonlinear equation. The method is also known as the linear interpolation method, and it works by iteratively approximating the root of the equation using linear interpolation between two initial guesses.

In the false position method, we start with two initial guesses, which are used to define an interval in which the root of the equation is known to exist. The method then computes the values of the function at the two endpoints of the interval and uses linear interpolation to estimate the location of the root.

The estimate is then compared with the actual root of the equation, and the interval is updated accordingly. The process is repeated until the estimated root converges to the actual root within a specified tolerance.

The false position method is a relatively simple and efficient algorithm for finding the roots of a nonlinear equation. However, it can be sensitive to the choice of initial guesses, and it may not converge for certain types of functions or intervals. Therefore, it is important to carefully choose the initial guesses and to check the convergence of the method for a given problem.
