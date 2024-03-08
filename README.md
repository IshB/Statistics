# This folder contains the following projects:
Language used: MATLAB 

A: (Problems 2-4 in in pdf:"SFF_A")
  1. Program that computes the student’s T distribution with a given DOF by the inversion formula
  2. Use the integral convolution formula to compute the joint density of two independent random
variables

B: (Problem 2: Parts 1-4 in pdf:"SFF_B")
The conditional distribution of a bivariate Student t
Parts:
  1. We make a program that inputs the parameters of a bivariate Student t (2 location terms, and a 2X2
dispersion matrix, and the df parameter), and computes the parameters of the conditional distribution of
X2 given X1. The computation is done according to Ding’s paper. (Found in folder)
  3. We code a program to simulate a bivariate Student T.
     a. make a bivariate 3D plot of this estimate. 
  4.  We define a function that inputs the n X 2 matrix of simulated bivariate Student t values, as
well as a parameter, a scalar, called x2. There is a small value eps defined inside the function
  5. Now we combine all of these defined functions. We Make plots to compare our estimated density with
Ding’s predicted density. A notable observation is that as we increase the DOF; The graphs start to look
more like each other 
   
