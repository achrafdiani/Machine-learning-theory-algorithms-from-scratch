# Machine Learning Algorithms from Scratch

This repository contains implementations of several core machine learning algorithms from scratch using Python. The goal is to understand the internal workings of popular machine learning methods by coding them without relying on external libraries for the algorithm logic.

## Contents

Each Jupyter notebook covers a different topic in machine learning, including:

 **Multiclass Classification (OvO, OvA, ECOC)**
   - Logistic regression models implemented with One-vs-One (OvO) and One-vs-All (OvA) strategies.
   - Error-Correcting Output Codes (ECOC) framework applied with the Pocket algorithm for improved classification accuracy.
   - Gradient descent implemented for training, with decision boundary visualizations.
   - Performance evaluation and plotting of binary classifiers in the ECOC framework.


**Covering Number**
   - Detailed exploration of covering numbers and their role in controlling model complexity.
   - Visualizations and examples demonstrating the mathematical properties and how they apply to generalization in machine learning.

 **Cross-Validation**
   - Implementation of K-fold cross-validation from scratch.
   - Demonstrates the importance of cross-validation in model performance evaluation.
   - Visualizes accuracy fluctuations across folds and explains how cross-validation helps in stable model selection.

 **Elimination Methods with VC Dimension**
   - Discusses the concept of Vapnik-Chervonenkis (VC) dimension.
   - Implements elimination methods using VC dimension to evaluate and compare model capacities.
   - Theoretical insights on how VC dimension affects generalization, coupled with practical examples.

 **Linear and Logistic Regression**
   - Implementation of linear regression with gradient descent.
   - Logistic regression for binary classification, including visualization of decision boundaries.
   - Comparison of regularized and non-regularized models to prevent overfitting using Lasso and Ridge regression techniques.


 **Polynomial Regression**
   - Demonstrates the transition from linear to polynomial regression for non-linear data (pressure vs. temperature).
   - Implements polynomial regression for different degrees (Q=2, 3, 4) and visualizes the impact of model complexity.
   - Compares the accuracy and empirical loss for each polynomial degree and linear regression.
   - Concludes that higher-order polynomials provide better fits for non-linear relationships.

 **Regularization (Lasso and Ridge)**
   - Introduces regularization techniques to control overfitting in logistic regression models.
   - Implements L1 (Lasso) and L2 (Ridge) regularization and compares their effects on model performance.
   - Provides insights into the trade-off between bias and variance, visualized through the empirical loss and penalty terms.
   - Demonstrates the benefits of regularization in improving model generalization by penalizing large weights.

