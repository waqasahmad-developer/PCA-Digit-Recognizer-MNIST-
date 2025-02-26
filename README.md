PCA on Digit Recognizer Dataset (MNIST) with KNN
This repository explores the impact of Principal Component Analysis (PCA) on the classification performance of a K-Nearest Neighbors (KNN) model using the Digit Recognizer (MNIST) dataset. The project evaluates how dimensionality reduction affects accuracy and computational efficiency.

Workflow
Train KNN on Full Dataset

Train a KNN model using all features (784 pixels).
Measure and record the training time and accuracy.
Train KNN with 200 Principal Components

Apply PCA to reduce the dataset to 200 components.
Train KNN on the transformed dataset and measure performance.
Iterative PCA Analysis

Loop through values of n_components from 1 to 784.
Train KNN for each value and record accuracy.
Analyze how the number of components affects model performance.
Visualization

Plot accuracy vs. number of principal components.
Visualize the dataset in 2D and 3D using PCA-transformed features.
Results & Insights
Comparison of accuracy and computation time with and without PCA.
Identification of the optimal number of components for efficient classification.
Visualization of feature space transformation through PCA.
This project demonstrates the trade-off between dimensionality reduction and model performance, providing insights into how PCA can optimize machine learning workflows.
