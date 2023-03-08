# Basic Ml Models coded from scratch

## k-means clustering

- takes k elements at start and then clusters the rest according to the shortest distance
- adjusts the cluster means after 1st iteration
- each iteration puts the points into the cluster with closest means
- iterations continue until no changes are made

## k-medoid clustering

* take k elements from the array of data and consider them as medoids of the k clusters
* calculate the distance of the rest from the k medoids and assign them to the respective clusters with minimum distance
* calculate the total cost of the assignments
* now, for each non medoid point swap them with one of the medoids and calculate the distance and cost again
* take the least cost clustering as the optimal cluster
