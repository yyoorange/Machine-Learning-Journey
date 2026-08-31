# Course 3: Unsupervised Learning, Recommenders, Reinforcement Learning

This folder documents my progress through Course 3 of the Machine Learning Specialization by DeepLearning.AI and Stanford Online.

## Topics Covered

### Unsupervised Learning

- K-means Clustering
- Cluster Assignment
- Centroid Optimization
- K-means Cost Function
- Random Initialization
- Multiple Random Initializations

### Recommender Systems

- Collaborative Filtering
- User and Item Parameters
- Movie Rating Prediction
- Collaborative Filtering Cost Function
- Regularization
- Mean Normalization
- Vectorized Cost Computation
- TensorFlow GradientTape
- Adam Optimization
- Personalized Movie Recommendations

## Assignments

### 01 — K-Means Clustering

Implemented the core components of the K-means clustering algorithm, including:

- Finding the closest centroid for each training example
- Recomputing cluster centroids
- Iteratively optimizing cluster assignments
- Understanding the K-means objective function

**Notebook:** `01_KMeans_Clustering.ipynb`

### 02 — Collaborative Filtering Recommender System

Implemented a collaborative filtering model for movie recommendations.

Key tasks included:

- Implementing the collaborative filtering cost function
- Computing predictions from user and movie feature vectors
- Applying L2 regularization to model parameters
- Using a rating indicator matrix to train only on observed ratings
- Normalizing movie ratings
- Using a vectorized TensorFlow implementation of the cost function
- Training user and movie parameters with TensorFlow GradientTape and Adam
- Generating personalized movie rating predictions and recommendations

**Notebook:** `02_Collaborative_Filtering_Recommender_System.ipynb`

## Tools and Technologies

- Python
- NumPy
- TensorFlow / Keras
- Pandas
- Jupyter Notebook

## Key Concepts

The exercises in this course extend machine learning beyond supervised prediction to discovering structure in unlabeled data and building personalized recommendation systems.

For collaborative filtering, the main workflow explored is:

**User Ratings → Latent Features → Cost Function → Regularization → Optimization → Rating Prediction → Recommendations**

More assignments will be added as I continue through the course.
