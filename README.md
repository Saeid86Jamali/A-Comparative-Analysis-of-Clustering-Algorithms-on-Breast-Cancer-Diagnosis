## A Comparative Analysis of Clustering Algorithms on Breast Cancer Diagnosis
This code compares the performance of three clustering algorithms - K-means, Hierarchical Clustering, and DBSCAN - on the Breast Cancer Wisconsin (Diagnostic) dataset. The code first loads the dataset and splits it into training and testing sets. Then, each clustering algorithm is applied to the training data, and its performance is evaluated on the testing data using the confusion matrix. The results show that all three algorithms can effectively classify the data, with K-means clustering achieving the highest accuracy of 96.42%. Below, see a detailed explanation of this process.

Initialization:
The first part of the code imports the necessary libraries and loads the data from the Breast Cancer Wisconsin (Diagnostic) dataset. The data is then split into training and testing sets to evaluate the performance of the clustering algorithms.

Modeling - Kmeans clustering:
The Kmeans clustering algorithm is applied to the training data. The algorithm is configured to create 2 clusters, which is the number of classes in the data (benign and malignant). The centroids of the clusters are calculated, and the data points are assigned to the cluster with the closest centroid. The performance of the model is evaluated using the confusion matrix.

Modeling - Hierarchical Clustering:
The Hierarchical Clustering algorithm is applied to the training data. The algorithm is configured to use the agglomerative method, which starts by assigning each data point to its cluster. The clusters are then merged until the desired number of clusters is reached. The performance of the model is evaluated using the confusion matrix.

Modeling - DBSCAN:
The DBSCAN algorithm is applied to the training data. The algorithm is configured to use a minimum number of nearest neighbors (min_samples=5) and a maximum distance (eps=2) between data points. Points that are not within the epsilon distance of at least min_samples other points are labeled as noise. The performance of the model is evaluated using the confusion matrix.

Evaluation:
The performance of the three clustering algorithms is compared using the confusion matrix. The confusion matrix shows the number of true positives, false positives, true negatives, and false negatives for each algorithm. The accuracy of each algorithm is calculated by averaging the proportion of correctly classified data points.

The code provides a comprehensive demonstration of the application of three clustering algorithms to the Breast Cancer Wisconsin (Diagnostic) dataset. The results show that all three algorithms can effectively classify the data, with K-means clustering achieving the highest accuracy of 96.42%.
