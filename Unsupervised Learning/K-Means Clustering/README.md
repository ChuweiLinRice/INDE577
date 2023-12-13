# K-means clustering

K-means clustering is a popular unsupervised machine learning algorithm used for partitioning a dataset into distinct, non-overlapping subgroups (clusters). The algorithm's primary objective is to minimize the sum of squared distances between data points and the centroid of their assigned cluster.

1. Initialization: Choose the number of clusters k that you want to identify in your data. Randomly initialize 
k centroids, one for each cluster. The centroids are the initial representative points for each cluster.

2. Assignment: Assign each data point to the cluster whose centroid is closest. The distance metric used is typically Euclidean distance, but other metrics can be employed.

3. Update Centroids: Recalculate the centroid of each cluster by taking the mean of all the data points assigned to that cluster.

4. Repeat: Repeat the assignment and centroid update steps until convergence. Convergence occurs when the assignments no longer change or change very minimally.

The purpose of K-means algorithm is to minimize the sum of squared distances within each cluster, making the clusters as internally homogeneous as possible. However, the algorithm does not guarantee a global minimum; different initializations might lead to different final cluster assignments.

Assumes Spherical Clusters: K-means assumes that clusters are spherical and equally sized, which may not be the case in all datasets. For non-spherical or unevenly sized clusters, other clustering algorithms like DBSCAN or Gaussian Mixture Models might be more appropriate.

Scale Sensitivity: The algorithm is sensitive to the scale of the features, so it's often a good practice to standardize or normalize the data before applying K-means.
