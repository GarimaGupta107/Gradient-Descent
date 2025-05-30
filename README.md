# Gradient-Descent

## Gradient Descent is an iterative algorithm which is used to minimize the loss function by updating the value of Parameters m(Slope) and b(intercept).

# Types of Gradient Descent:

## 1.Batch Gradient Descent (BGD):
- Uses the entire training dataset to compute the gradient of the loss function.
- Updates the model parameters once per epoch.
- Can be computationally expensive for large datasets.

Batch Gradient Descent is a type of gradient descent where the entire training dataset is used to compute the gradient at each step of the update.

## 2.Stochastic Gradient Descent (SGD):
- Uses a single training example to compute the gradient of the loss function.
- Updates the model parameters after each example.
- Can be noisy and may not converge to the optimal solution.

## 3.Mini-Batch Gradient Descent (MBGD):
- Uses a small batch of training examples to compute the gradient of the loss function.
- Updates the model parameters after each mini-batch.
- Balances the trade-off between BGD and SGD.
