java c
Department of Electrical and Computer Engineering 
EECE-7204 
Applied Probability  Stochstic Processes 
FALL-2024 
Homework-6 Problem Set 
Due on November 16, 2024
P6.1 A random sequence Xn is defined by Xn = Asin(Ωn), n ≥ 0, in which A and Ω are discrete random variables described by their joint probability mass function (pmf)

Determine:
(a)  the marginal density fX3 (x),
(b)  the joint density fX1,X5 (x, y),
(c)  the mean sequence μX ( n),
(d)  the auto-correlation bi-sequence R X( m, n), and
(e)  whether the sequence Xn is
• a strict-sense stationary,
• a wide-sense stationary,
• an independent random sequence,
•  an uncorrelated random sequence, and
• an orthogonal random sequence.
P6.2 Stark/Woods Text Problem 8.10 (Page 528).
For a better clarity, this problem is modified as follows.
(a)  The components,  of the random-10 vector X satisy “non-causal” recursive equa-
tions, given by
with “initial” and “final” equations, respectively, given by
Using (1) and (2), arrange the above 10 scalar equations in the vector form. asX = BX + CW  (3)
where B and C are 10 × 10 matrices of numbers, derived from (1) and (2), and W = { Wi} is a random-10 vector. Now solve for the vector X and arrange the solution as
By carefully examining the numbers in matrix A, verify that the scalar equations for Xi are given by
You will need equation (5) to solve the following parts. What is the value of ρ in (5)?
(b)  Determine the mean vector μX .
(c)  Determine the ACVM KX .
(d)  Write an expression for the multidimensional pdf, fX (x), of the random vector X.
P6.3 Stark/Woods Text Problem 8.21 (Page 531). 
P6.4 Stark/Woods Text Problem 8.29 (Page 534).
P6.5 Let X [ n] be an indep代 写EECE-7204 Applied Probability & Stochstic Processes FALL-2024 Homework-6 Problem SetMatlab
代做程序编程语言endent and identically distributed (IID) random sequence with PDF, at each n, given by fX (x; n) = 2x[ u (x) − u(x − 1)]. Another random sequence Y [ n] is defined as

(a)  Determine μX [ n] of X [ n].
(b)  Determine R X [ n 1, n2] of X [ n].
(c)  Determine the mean sequence μY [ n], n ≥ 1 of Y [ n].
(d)  Determine the variance sequence σY(2) [ n], n ≥ 1 of Y [ n].
(e)  Let W = Y [ n 1] − Y [ n2], n 1 , n2 ≥ 1 be a random variable. Determine the variance σW(2) of the random variable W.
P6.6 Stark/Woods Text Problem 8.48. (Page 539).
P6.7 Stark/Woods Text Problem 8.51. (Page 539-540).
P6.8 [MATLAB Problem] 
In this problem you will generate M = 100 sample sequences of length N = 1000 of the random- walk process with step-size S = 1 and analyze its statistical properties.
(a)  First generate M independent sequences W [ n] of length N + 1 in which each sample takes value equal to +S or −S with probability 1/2.   Now perform. cumulative sum  (i.e., use the MATLAB function cumsum) on each sample sequence to obtain M realizations of the random-walk process X [ n] of length N. Plot all sample sequences in one figure. Submit a printout of your script. and a printout of your plot.
(b)  Estimate and plot the mean sequence μX [ n] by averaging over M realizations. How does it compare with the actual mean sequence given in the lecture notes? Submit a printout of your script. and a printout of your plot.
(c)  Estimate and plot the variance σX(2)[ n] by averaging over M realizations. How does it com- pare with the actual variance sequence given in the lecture notes?  Submit a printout of your script. and a printout of your plot.
(d)  Comment on the stationarity of the random-walk process.

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
