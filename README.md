# Machine Learning Journey

This repository documents my progress through the Machine Learning Specialization by DeepLearning.AI and Stanford Online.

It contains my implementations, exercises, and notes on fundamental machine learning concepts, including supervised learning, neural networks, model evaluation, regularization, and unsupervised learning.

## Course 1: Supervised Machine Learning — Regression and Classification

Topics covered:

- Linear Regression
- Cost Functions
- Gradient Descent
- Multiple Linear Regression
- Feature Scaling
- Feature Engineering
- Polynomial Regression
- Logistic Regression
- Decision Boundaries
- Overfitting
- Regularization

## Course 2: Advanced Learning Algorithms

### Neural Networks

Topics covered:

- Neural Network Architecture
- Dense Layers
- Forward Propagation
- TensorFlow Sequential Models
- Activation Functions
- Multiclass Classification
- Softmax Regression
- Sparse Categorical Cross-Entropy

### Model Evaluation and Selection

Topics covered:

- Training, Cross-Validation, and Test Sets
- Mean Squared Error (MSE)
- Classification Error
- Bias and Variance
- Diagnosing Underfitting and Overfitting
- Model Complexity
- Model Selection using Cross-Validation

### Regularization

Topics covered:

- L2 Regularization
- Regularized Neural Networks
- Controlling Model Complexity
- Comparing Training and Cross-Validation Error
- Selecting the Regularization Parameter (Lambda)

## Course 3: Unsupervised Learning, Recommenders, Reinforcement Learning

### Unsupervised Learning

Topics covered:

- Unsupervised Learning
- Clustering
- K-means Clustering
- Cluster Assignment
- Computing Cluster Centroids
- K-means Optimization Objective
- Random Initialization
- Selecting the Number of Clusters
- Image Compression with K-means

### K-means Clustering Programming Assignment

In this assignment, I implemented the K-means clustering algorithm and applied it to image compression.

The main tasks included:

- Implementing K-means clustering using NumPy
- Computing the closest centroid for each training example
- Assigning data points to clusters based on Euclidean distance
- Recomputing cluster centroids from assigned data points
- Iteratively updating cluster assignments and centroid positions
- Exploring random initialization of cluster centroids
- Applying K-means clustering to image pixels
- Compressing an image by reducing the number of colors represented in the image

## Recent Assignments

### Model Evaluation and Regularization

In this assignment, I explored techniques for evaluating machine learning models and improving their ability to generalize to unseen data.

The main tasks included:

- Implementing mean squared error for regression model evaluation
- Implementing classification error for categorical predictions
- Splitting data into training, cross-validation, and test sets
- Comparing training and cross-validation performance
- Diagnosing high bias and high variance
- Building simple and complex neural network architectures
- Investigating the effect of model complexity on overfitting
- Applying L2 regularization to neural networks
- Comparing regularized and unregularized models
- Exploring different regularization strengths to improve generalization

### K-means Clustering

In this assignment, I implemented the core components of the K-means clustering algorithm from scratch and used the algorithm for image compression.

The implementation included:

- Finding the closest centroid for each data point
- Computing updated centroid means
- Iteratively refining cluster assignments
- Initializing centroids
- Applying K-means to RGB image data
- Reconstructing an image using a reduced color palette

## Tools and Technologies

- Python
- NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Key Concepts

Through these exercises, I am developing a practical understanding of both supervised and unsupervised machine learning workflows.

For supervised learning:

**Data → Model → Training → Validation → Model Selection → Regularization → Testing**

For unsupervised learning:

**Data → Initialization → Cluster Assignment → Centroid Update → Iteration → Evaluation / Application**

A key focus is understanding not only how machine learning algorithms work, but also how to implement their core components, evaluate their performance, diagnose potential problems, and apply them to practical tasks.

## Repository Purpose

This repository serves as a record of my machine learning studies and practical implementations. It will continue to be updated as I progress through the Machine Learning Specialization and explore additional topics in machine learning.
