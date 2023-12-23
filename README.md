# A Comparative Analysis of Clustering Algorithms on Breast Cancer Diagnosis
This repository contains a Jupyter notebook that demonstrates the application of three clustering algorithms: K-means, Hierarchical Clustering, and DBSCAN. The code loads the Breast Cancer Wisconsin (Diagnostic) dataset, preprocesses the data and then applies the three clustering algorithms to the data. The performance of each algorithm is evaluated using the confusion matrix.

K-means clustering is a non-hierarchical clustering algorithm that partitions the data into a predefined number of clusters. The algorithm iteratively assigns data points to the cluster with the closest mean, and updates the cluster means.

Hierarchical clustering is a hierarchical clustering algorithm that builds a tree-structured representation of the data. The algorithm starts by assigning each data point to its cluster and then repeatedly merges or splits clusters until the desired number of clusters is reached.

DBSCAN is a density-based clustering algorithm that groups data points that are closely spaced in a high-dimensional space. The algorithm defines a minimum number of nearest neighbors (min_samples) and a maximum distance (eps) between data points. Points that are not within the epsilon distance of at least min_samples other points are labeled as noise.

The code in this repository demonstrates the application of these three clustering algorithms to a real-world dataset and provides a comparison of their performance.
