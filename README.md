SmartCart Customer Clustering (Unsupervised ML)

Project Overview
This project focuses on customer segmentation using unsupervised machine learning.
The goal is to identify meaningful customer groups based on purchasing behavior to enable data-driven marketing and business decisions.

Problem Statement
Businesses often lack clear insights into different types of customers.
This project solves that by grouping customers into clusters without using labeled data.

Techniques & Algorithms Used
K-Means Clustering (primary algorithm)
Elbow Method – to determine the optimal number of clusters
Silhouette Analysis – to validate clustering quality
Feature Scaling (StandardScaler) – to improve distance-based clustering

Results
Successfully identified 4 distinct customer clusters
Each cluster represents a unique purchasing pattern
Clusters were visually validated using graphs

Visualizations
Elbow Curve (Optimal K selection)
Cluster Scatter Plot
Cluster-wise customer distribution

Dataset
Structured customer data (numerical features)
No target variable (pure unsupervised learning)

Tools & Libraries
Python
Pandas
NumPy
Scikit-learn
Matplotlib / Seaborn
Jupyter Notebook
