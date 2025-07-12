# Proj_08B_Kmeans_IRIS

This project applies K-Means clustering to the classic Iris dataset, which contains measurements of three iris flower species (Setosa, Versicolor, Virginica). The goal is to group the data into clusters without using the species labels and to analyze the clustering results using visualization and evaluation metrics.

Purpose
To demonstrate unsupervised learning by clustering the Iris dataset without using labels.

To visualize the original data and clustering results.

To determine the optimal number of clusters using the Elbow Method and Silhouette Score.

Features
Data Loading: Loads the Iris dataset from scikit-learn.

Visualization: Plots the original data and the clustering results using Matplotlib.

K-Means Clustering: Applies K-Means to group the data into clusters.

Elbow Method: Plots the Sum of Squared Errors (SSE) for different cluster counts to help identify the optimal number of clusters.

Silhouette Score: Calculates and plots the silhouette score for different values of k to evaluate clustering quality.

Usage Instructions
Install Dependencies:

pip install scikit-learn matplotlib

Run the Code:

Copy the Python code into your IDE or a Jupyter notebook.

Execute the code to see the visualizations and clustering results.

Workflow Overview:

Load the Iris dataset.

Visualize the original data (colored by true species).

Apply K-Means clustering and visualize the predicted clusters.

Use the Elbow Method (SSE plot) to suggest the optimal number of clusters.

Use the Silhouette Score plot to further validate the best cluster count.

Example Output
Elbow Method Plot: Shows how SSE changes with different numbers of clusters, helping to identify the "elbow point" (commonly k=3 for Iris).

Silhouette Score Plot: Indicates clustering quality for different k values.

Scatter Plots:

Original data colored by true labels.

Clustered data colored by predicted cluster assignments.
