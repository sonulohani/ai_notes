## Where KNN fails

1. If the data is a jumble of all different classes then knn will fail because it will try to find k nearest neighbours but all points are random.
2. Whenever the the data is imbalanced. If one class if 85% of the data and remaining classes belongs to 15% of the data. The predicting the class of a point always give the majority class.
3. outliers points - Let's say you have two clusters of different classes. Then if you have a outlier point as query, knn will assign one of the classes even though the query point is far away from both clusters.
4. Nearest neighbor depends greatly on distances between points. As you increase the number of dimensions, your distances are going to be less representative, this is called curse of dimensionality. Whenever your query point is far away from rest of the data points in your data-set. Unless you modify your data, KNN is very bad for high dimensional data. 

