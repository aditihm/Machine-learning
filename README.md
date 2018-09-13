### Machine-learning
This repository deals with machine learning and it's algorithms.

## Regression:

# 1.Linear regression
Linear regression is an attractive model because the representation is so simple.

The representation is a linear equation that combines a specific set of input values (x) the solution to which is the predicted output for that set of input values (y). As such, both the input values (x) and the output value are numeric.

The linear equation assigns one scale factor to each input value or column, called a coefficient and represented by the capital Greek letter Beta (B). One additional coefficient is also added, giving the line an additional degree of freedom (e.g. moving up and down on a two-dimensional plot) and is often called the intercept or the bias coefficient.

For example, in a simple regression problem (a single x and a single y), the form of the model would be:

y = B0 + B1*x

In higher dimensions when we have more than one input (x), the line is called a plane or a hyper-plane. The representation therefore is the form of the equation and the specific values used for the coefficients (e.g. B0 and B1 in the above example).

It is common to talk about the complexity of a regression model like linear regression. This refers to the number of coefficients used in the model.

When a coefficient becomes zero, it effectively removes the influence of the input variable on the model and therefore from the prediction made from the model (0 * x = 0). This becomes  relevant if you look at regularization methods that change the learning algorithm to reduce the complexity of regression models by putting pressure on the absolute size of the coefficients, driving some to zero.

# 2.Polynomial Regression
The goal of regression analysis is to model the expected value of a dependent variable y in terms of the value of an independent variable (or vector of independent variables) x. In simple linear regression, the model

{\displaystyle y=\beta _{0}+\beta _{1}x+\varepsilon ,\,} {\displaystyle y=\beta _{0}+\beta _{1}x+\varepsilon ,\,}
is used, where ε is an unobserved random error with mean zero conditioned on a scalar variable x. In this model, for each unit increase in the value of x, the conditional expectation of y increases by β1 units.

In many settings, such a linear relationship may not hold. For example, if we are modeling the yield of a chemical synthesis in terms of the temperature at which the synthesis takes place, we may find that the yield improves by increasing amounts for each unit increase in temperature. In this case, we might propose a quadratic model of the form

{\displaystyle y=\beta _{0}+\beta _{1}x+\beta _{2}x^{2}+\varepsilon .\,} {\displaystyle y=\beta _{0}+\beta _{1}x+\beta _{2}x^{2}+\varepsilon .\,}
In this model, when the temperature is increased from x to x + 1 units, the expected yield changes by {\displaystyle \beta _{1}+\beta _{2}(2x+1).} {\displaystyle \beta _{1}+\beta _{2}(2x+1).} (This can be seen by replacing x in this equation with x+1 and subtracting the equation in x from the equation in x+1.) For infinitesimal changes in x, the effect on y is given by the total derivative with respect to x: {\displaystyle \beta _{1}+2\beta _{2}x.} {\displaystyle \beta _{1}+2\beta _{2}x.} The fact that the change in yield depends on x is what makes the relationship between x and y nonlinear even though the model is linear in the parameters to be estimated.
