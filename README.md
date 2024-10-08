# Supervised Machine Learning Algorithms

## Regression

- Linear Regression:
  
  - Single Variable regression: Regression for only one feature.
    - Gradient Descent: get less prediction function parameters $(w,b)$ to minimize the cost function.

  - Multiple variable regression: Single prediction (element by element) or (vectorization)
    - Gradient Descent with multiple variables.

  - Learning Rate: choosing alpha

  - Feature Scaling: Rescaling of dataset so features have similiar ranges
    - Usual Normalization
    - Mean Normalization
    - Z-Score Normalization


- Feature Engineering: Transforming a feature to design new features.

- Polynomial Regression: one feature but polinomially distributed ( $1 + x + x^{2} + x^{3}$ ).

## Classification

small range of values for one feature (0,1) (yes, no), (man, woman, child)

- Sigmoid or Logistic function: for representing the range.

- Logistic Regression: Applying the sigmoid function to the linear model.: $f = g(w.x(i) + b)$ .

  - Loss function.

  - Cost function.

  - Gradient Descent.
  
### Overfitting

- Regularization for Linear and Logistic Regression.
