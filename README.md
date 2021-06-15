# Cluster-flowers-into-Categories-using-KMeans

Problem statement : From the given ‘Iris’ dataset, predict the optimum number of clusters and represent it visually. 
      
Using an unsupervised machine learning algorithm K-Means, we find clusters in the Iris dataset. Each entry of the Iris dataset specifies a flower's Sepal length, Sepal width, Petal length, and Petal width.

Here we use the Elbow Method, to find the optimum number of clusters
![The Elbow Curve](https://user-images.githubusercontent.com/55353267/122058712-85d09900-ce09-11eb-908e-6bfb6cc2069e.jpg)
 Note: The drop in the parameter WCSS( Within Cluster Sum of Squares of Diatance of Centroid ) is negligible after K = 3 is the optimum number of clusters.
 
 # Without using Principal Component Analysis

By using Kmeans to find the clusters and avoid Random Initialization trap. Here we have plotted PetalLength against PetalWidth.
 
 ![Analysis](https://user-images.githubusercontent.com/55353267/122074462-dbf80900-ce16-11eb-9809-73ead250a09d.jpg)


