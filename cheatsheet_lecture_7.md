# Cheatsheet for Class 7
Class: ECSE 305
Date: October 16, 2018

## Continuous Random Variable

  > Continuous RVs are variable that are not discrete. Meaning they can be part of a non-countable set or an infinite set.

  > There are 2 contition that a random RV must respect:
		
	1. We express possible values a continuous RV can take with an interval. For instance: a <= x <= b <br/>for a,b,x E Real Numbers
	
	2. P(X = c) = 0 for any number that is a possible value of X.

## Probability Distribution Function

  > We now introduce Continuous Probability Distributions. Just like before, they allow us to determine what are the probabilities that X equal to c. The main differencehere is that the intervals are infinite (since x can take any values).

  > Since this is a continuous fucntion, x can take any values.

  > If we now require the density function [ P(a <= X <= b) ] we can take the integral of the function where the boundaries are a (lower) and b (upper). Since we use continuous RV, P(a < X < b) == P(a <= X <= b).

  > The total are under a pdf is equal to 1. This mean that the integral of the Probability Distribution Function from -inf to +inf is equal to 1.


## Cumulative distribution Function

  > We now introduce Continuous Cumulative Distributions. CDFs will now be function that lies in a range of values. For instance, if x < a then F(x) = 0. If a<x<b, then F(x) = "some function". If b<x then f(x) = 1.

  > We write F(x) the cdf and f(x) the pdf. With continuous values, F'(x) = f(x).


## Expected Value and Variance

  > The expected value of a Continuous RV is denoted as E(X).

  > E(X) is equal to the integral of f(x) (the pdf) times x.

  > The variance of a Continuous RV is denoted as V(X) or sigma<sup>2</sup><sub>X</sub>.

  > V(X) is equal to E(X<sup>2</sup>) - [E(X)]<sup>2</sup>.

  > The stardard variation of X is equal to the square root of V(X).








