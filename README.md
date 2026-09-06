# Applications of Mathematics in Econometrics

An AMS 510 project from Fall 2020 connects multiple linear regression in econometrics with least-squares optimization, multivariable calculus, and orthogonal projection.

## Overview

Econometric models use economic theory and data to describe relationships, test hypotheses, and support forecasting. The paper focuses on the multiple linear regression model

$$
Y_i = \beta_0 + \beta_1 x_{i1} + \cdots + \beta_k x_{ik} + \varepsilon_i
$$

and explains how ordinary least squares chooses the coefficients that minimize the sum of squared residuals.

## Mathematical connections

The paper develops three complementary views of least squares:

1. **Optimization:** the fitted coefficients minimize the residual sum of squares.
2. **Multivariable calculus:** setting the partial derivatives of the objective function equal to zero produces the normal equations; convexity identifies the resulting stationary point as a global minimum.
3. **Linear algebra:** the fitted response is the orthogonal projection of the observed response vector onto the column space of the design matrix. When $X^\mathsf{T}X$ is invertible, the coefficient estimator is

$$
\widehat{\beta} = (X^\mathsf{T}X)^{-1}X^\mathsf{T}y.
$$

Together, these perspectives show why least squares provides the best linear approximation in the Euclidean-distance sense and prepares the model for later inference and prediction.

## Repository contents

- `Term Project.pdf` — final two-page paper
- `README.md` — project overview

## Author

Kai Li.
