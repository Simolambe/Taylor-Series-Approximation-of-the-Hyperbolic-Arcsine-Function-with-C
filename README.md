Project Overview
The goal of this project is to develop a program that evaluates the hyperbolic arcsine function (asinh) using a Taylor series expansion. The program uses at least four terms of the Taylor series and compares the results with the C standard library's implementation of the function over the interval 0<x<4 with a step size of 0.01 or finer. Additionally, the project includes visualizations comparing the Taylor series approximation to the actual function and plots the difference between the two.

Function Analyzed
The function chosen for this project is the hyperbolic arcsine (asinh).

Key Observations
Taylor Series Convergence: The Taylor series for asinh(x) converges accurately only for values of x between −1 and 1. For 𝑥>1, the series diverges, leading to increasingly inaccurate estimates. In the range 0<x<1, the approximation is reasonably accurate, with a maximum error of around 0.01. However, for values of x>1, the approximation begins to deviate significantly from the true function.

Oscillations in the Taylor Series: The terms in the Taylor series alternate in sign and increase in magnitude as x increases. This results in the approximation becoming worse as more terms are added, especially for values of x>1. When the number of terms is even (as in this case with 4 terms), the final term tends to dominate, which can cause the approximation to become negative, particularly for higher values of x.

Maximum Error: The program's results show that the maximum difference between the Taylor series approximation and the actual function can reach up to 663 for values of x>1. The graph of the function begins to dip into negative values as the Taylor series estimate becomes increasingly inaccurate.
