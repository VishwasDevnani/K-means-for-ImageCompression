# K-means-for-ImageCompression

Kmeans algorithm is an iterative algorithm that tries to partition the dataset into Kpre-defined distinct non-overlapping subgroups (clusters) where each data point belongs to only one group. It tries to make the intra-cluster data points as similar as possible while also keeping the clusters as different (far) as possible. It assigns data points to a cluster such that the sum of the squared distance between the data points and the cluster’s centroid (arithmetic mean of all the data points that belong to that cluster) is at the minimum. The less variation we have within clusters, the more homogeneous (similar) the data points are within the same cluster.
The way kmeans algorithm works is as follows:
1. Specify number of clusters K.


2. Initialize centroids and then randomly selecting K data points for the centroids without replacement.


3. Keep iterating until there is no change to the centroids. i.e assignment of data points to clusters isn’t changing.
* Compute the sum of the squared distance between data points and all centroids.
* Assign each data point to the closest cluster (centroid).
* Compute the centroids for the clusters by taking the average of the all data points that belong to each cluster.

# Results:

| Original Image | Compressed Image | Reconstructed Image |
| :---:         |     :---:      |          :---: |
| ![](https://github.com/VishwasDevnani/K-means-for-ImageCompression/blob/main/Images/luffy.png)   | ![](https://github.com/VishwasDevnani/K-means-for-ImageCompression/blob/main/Images/compressed_luffy.png)     | ![](https://github.com/VishwasDevnani/K-means-for-ImageCompression/blob/main/Images/reconstructed_luffy.png)    |
| size: 288 KB     | size: 52.2 KB       | size: 112 KB       |
