# K-means Clustering

Hooray! Another $k$ based technique (so you know I'm going to like it :))! 

Similar to k-nearest neighbors, the k of k-means clustering is a user-chosen number, but most of the similarities end there. 

K-means clustering is a unsupervised learning technique, meaning the data we are analyzing is unlabeled. To sort through all of this data, k-means clustering tries to find clusters in the data. We choose 'k' distinct centroids to make k distinct, non-overlapping clusters. 

This technique works iteratively until centroids are "stable", and we have effectively pre-processed our data such that supervised learning can be performed on it!

In this notebook, we will implement k-means clustering on the mushrooms dataset to attempt to classify types of mushrooms!