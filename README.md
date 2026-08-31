# Machine Learning Journey

This repository documents my progress through the **Machine Learning Specialization** by DeepLearning.AI and Stanford Online.

It contains my implementations, programming assignments, and notes on fundamental machine learning concepts, including supervised learning, neural networks, model evaluation, decision trees, unsupervised learning, and clustering.

---

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

Through these exercises, I developed an understanding of the foundations of supervised machine learning and the optimization techniques used to train regression and classification models.

---

## Course 2: Advanced Learning Algorithms

### Neural Networks

Topics covered:

- Neural Network Architecture
- Dense Layers
- Forward Propagation
- TensorFlow Sequential Models
- Activation Functions
- Binary Classification
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

### Decision Trees

Topics covered:

- Entropy
- Dataset Splitting
- Information Gain
- Selecting the Best Feature for a Split
- Recursive Tree Construction
- Decision Tree Learning

In the Decision Trees assignment, I implemented the core components of a decision tree algorithm, including entropy calculation, dataset splitting, information gain computation, and best-feature selection.

---

## Course 3: Unsupervised Learning, Recommenders, Reinforcement Learning

### Unsupervised Learning

Topics covered so far:

- Unsupervised Learning
- Clustering
- K-means Clustering
- Cluster Assignment
- Centroid Updates
- K-means Cost Function
- Random Initialization
- Choosing the Number of Clusters
- Image Compression with K-means

### K-means Clustering Assignment

Implemented the K-means clustering algorithm from its core components and applied it to image compression.

Main tasks included:

- Finding the closest centroid for each training example
- Assigning examples to clusters
- Recomputing cluster centroids
- Iteratively updating cluster assignments and centroid positions
- Understanding the effect of random initialization
- Applying K-means clustering to image pixels
- Compressing an image by reducing the number of colors

This assignment provided practical experience with unsupervised learning and demonstrated how clustering can be used beyond conventional data analysis tasks.

---

## Tools and Technologies

- Python
- NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Git / GitHub

---

## Key Concepts

Through these exercises, I am developing practical understanding of the machine learning workflow across both supervised and unsupervised learning.

### Supervised Learning

**Data → Model → Training → Validation → Model Selection → Regularization → Testing**

### Decision Trees

**Dataset → Entropy → Information Gain → Best Split → Decision Tree**

### K-means Clustering

**Data → Initialize Centroids → Cluster Assignment → Centroid Update → Repeat Until Convergence**

A key focus of this repository is understanding not only how machine learning algorithms are used, but also how their underlying components can be implemented and interpreted.

---

## Repository Structure

```text
Machine-Learning-Journey/
│
├── course-1-supervised-machine-learning/
│
├── course-2-advanced-learning-algorithms/
│   ├── 01_Neural_Network_Binary_Classification.ipynb
│   ├── 02_Neural_Network_Multiclass_Classification.ipynb
│   ├── 03_Model_Evaluation_and_Regularization.ipynb
│   ├── 04_Decision_Trees.ipynb
│   └── README.md
│
├── course-3-unsupervised-learning/
│   └── 01_KMeans_Clustering.ipynb
│
└── README.md
