# Supervised Machine Learning

## Regression

Predict a value of feature for a certain point in an infinite range.

- Linear Regression:
  - Gradient Descent: get less cost function parameters (w,b).

  - Single Variable regression: Regression for only one feature.

  - Multiple variable regression: Single prediction (element by element) or (vectorization), Gradient Descent with multiple variables.

  - Learning Rate: choosing alpha

  - Feature Scaling: Rescaling of dataset so features have similiar ranges

    - (x-min)/(max-min)

    - mean normalization: (M - mean)/(max-min)

    - Z-score normalization: (M - mean)/sd

- Feature Engineering: Transforming a feature to design new features.

- Polynomial Regression: one feature but polinomially distributed (1 + x + x**2 + x**3).

## Classification

small range of values for one feature (0,1) (yes, no), (man, woman, child)

- Sigmoid or Logistic function: for representing the range: g(z) = 1/(1+exp(-z)).

- Logistic Regression: Applying the sigmoid function to the linear model.: f = g(w.x(i) + b).

  - Loss function.

  - Cost function.

  - Gradient Descent.
