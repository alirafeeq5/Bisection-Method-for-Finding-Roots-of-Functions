# Bisection-Method-for-Finding-Roots-of-Functions
Python script implements the bisection method, a simple numerical technique used to find the roots of a continuous function within a specified interval. The bisection method is effective for functions where the sign of the function changes over the interval, indicating a root exists.


Method Overview

The bisection method works by iteratively narrowing down the interval where a root exists:

1.	Input:
   
      •	Enter a function 𝑓(𝑥)f(x).
  	
      •	Specify the interval [𝑎,𝑏][a,b] where the root is expected to lie.
  	
      •	Define the desired precision of the root (number of decimal places).
  	
2.	Validation:
   
      •	Checks for the continuity of the function 𝑓(𝑥)f(x) on the interval [𝑎,𝑏][a,b].
  	
      •	Verifies that 𝑓(𝑎)f(a) and 𝑓(𝑏)f(b) have opposite signs, ensuring a root exists within the interval.
  	
3.	Algorithm Execution:
	
      •	Iteratively divides the interval [𝑎,𝑏][a,b] into halves (c = (a + b) / 2).
  	
      •	Determines the sign of 𝑓(𝑐)f(c) to decide which sub-interval to continue with.
  	
      •	Repeats until the desired precision is achieved or until convergence.
  	
4.	Output:
	
      •	Displays a table summarizing each iteration:
  	
      •	Iteration number.
  	
      •	Interval [𝑎,𝑏][a,b] and midpoint 𝑐c.
  	
      •	Value of 𝑓(𝑐)f(c) (function evaluation at 𝑐c).
  	
      •	Estimated error compared to the previous iteration.
  	
5.	Results:
    
    •	Prints the last two iterations for visualization.
  	
    •	Provides the approximated root of the function within the specified precision.

