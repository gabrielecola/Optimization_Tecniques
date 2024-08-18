# Optimization Tecnicques

This project contains a series of Jupyter notebooks that explore various concepts in optimization. Each notebook covers a different topic, ranging from optimization methods to neural network-based digit recognition. Below is an overview of the contents of each notebook:

## Notebooks Overview

### 1. **First Homework: Comparison of First Order and Second Order Methods on an Optimization Test Function**

This notebook is dedicated to exploring and comparing first-order and second-order optimization methods using a test function. The key aspects covered in this notebook include:

- **First-Order Methods:** We examine methods such as Gradient Descent, which rely on the first derivative (gradient) of the function to guide the optimization process.
  
- **Second-Order Methods:** We also explore methods like Newton's method, which utilize second derivatives (Hessian matrix) to accelerate convergence, especially in convex optimization problems.

- **Test Function:** A test function is used to compare the convergence properties, computational efficiency, and accuracy of the first-order and second-order methods.


### 2. **Comparison of Deterministic vs. Stochastic Methods & Unregularized vs. Regularized Formulations in a Linear Regression Problem**

In this notebook, we delve into the field of linear regression, focusing on the following comparisons:

- **Deterministic vs. Stochastic Methods:**
  - **Deterministic Methods:** These include techniques like Ordinary Least Squares (OLS), where the entire dataset is used to compute the gradients and update the model parameters.
  - **Stochastic Methods:** Methods such as Stochastic Gradient Descent (SGD) are explored, where only a subset of the data (a mini-batch) is used in each iteration, making the method more scalable for large datasets.

- **Unregularized vs. Regularized Formulations:**
  - **Unregularized:** Standard linear regression without any penalties on the model parameters.
  - **Regularized:** Techniques like Ridge Regression (L2 regularization) and Lasso (L1 regularization) are discussed, which help in mitigating overfitting by adding penalties to the model complexity.


### 3. **Digit Recognition via Neural Networks**

This notebook focuses on building and training neural networks for the task of digit recognition. Key topics include:

- **Data Preprocessing:** Preparation of the dataset (e.g., MNIST) for training, including normalization and reshaping.
  
- **Neural Network Architecture:** Design and implementation of a multi-layer neural network, including input, hidden, and output layers.
  
- **Training and Evaluation:** The model is trained using backpropagation and evaluated on a test set to assess its performance.

- **Performance Metrics:** Metrics such as accuracy, precision, and recall are computed to evaluate the effectiveness of the neural network in recognizing handwritten digits.


