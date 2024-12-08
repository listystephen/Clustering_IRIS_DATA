# Clustering_IRIS_DATA
Clustering Algorithm Implementation: KMeans and Hierarchical Clustering

**(A). KMeans Clustering**
1. Description of KMeans Clustering KMeans clustering is a centroid-based algorithm that partitions the dataset into 
k clusters. The algorithm works as follows:
Randomly initializes k cluster centroids.
Assigns each data point to the nearest centroid.
Updates centroids as the mean of the assigned points.
Repeats the process until convergence (when centroids stop changing significantly).

Why KMeans is suitable for the Iris dataset?

The Iris dataset contains continuous numerical features that are well-suited for distance-based clustering.
It is known to have natural groupings (species), making it ideal for exploratory clustering like KMeans.

**(B) Hierarchical Clustering**
1. Description of Hierarchical Clustering Hierarchical clustering builds a tree (dendrogram) of clusters:

Agglomerative approach: Starts with each data point as its own cluster and merges them step by step based on proximity.
Divisive approach: Starts with all points in one cluster and splits them iteratively.

Why Hierarchical Clustering is suitable for the Iris dataset?

It provides a visual representation (dendrogram) of how clusters are formed.
It helps explore the natural groupings in the Iris dataset without assuming the number of clusters upfront.
