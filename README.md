# machine-learning-with-r
Code for the book Machine Learning with R by Brett Lantz

## Chapter 3 kNN
Basic classification based on k nearest neighbors.

## Chapter 9 k-means
Classification based on k-means method. The number of clusters (k) is predetermined. First the positions 
of the k centroids (center of mass) are randomly chosen. Then each point is assigned to the cluster depending 
on its distance to the centroid. Next the new position for the centroid is calculated based on the posistions
of the points within the cluster. Once the new positions of the centroids are determined, the algorithm tries
to update the assignment of the points to the clusters. If no further changes can be made, the algorithm stops.
