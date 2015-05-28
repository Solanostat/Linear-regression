In statistics, linear regression is an approach for modeling the relationship between a scalar dependent variable y and one or more explanatory variables (or independent variable) denoted X. The case of one explanatory variable is called simple linear regression. For more than one explanatory variable, the process is called multiple linear regression.
(This term should be distinguished from multivariate linear regression, where multiple correlated dependent variables are predicted, rather than a single scalar variable.)

Linear regression analysis is the most widely used of all statistical techniques: it is the study of linear, additive relationships between variables.   Let Y denote the “dependent” variable whose values you wish to predict, and let X1, …,Xk denote the “independent” variables from which you wish to predict it, with the value of variable Xi in period t (or in row t of the data set) denoted by Xit.  Then the equation for computing the predicted value of Yt is:



This formula has the property that the prediction for Y is a straight-line function of each of the X variables, holding the others fixed, and the contributions of different X variables to the predictions are additive.  The slopes of their individual straight-line relationships with Y are the constants b1, b2, …, bk, the so-called coefficients of the variables.   That is, bi is the change in the predicted value of Y per unit of change in Xi, other things being equal.  The additional constant b0, the so-called intercept, is the prediction that the model would make if all the X’s were zero (if that is possible).   The coefficients and intercept are estimated by least squares, i.e., setting them equal to the unique values that minimize the sum of squared errors within the sample of data to which the model is fitted. And the model's prediction errors are typically assumed to be independently and identically normally distributed.
Linear Regression Implementation in Python

This is an implementation of linear regression using a gradient descent algorithim. 

lm1.py


