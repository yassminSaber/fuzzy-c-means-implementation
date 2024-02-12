# fuzzy-c-means-implementation
 This task calrify the difference in clustering before and after applying pca.

## what is Fuzzy C-Means?

- Clustering technique used in pattern recognition and data analysis. It is an extension of the traditional K-means algorithm, incorporating the concept of fuzziness into the assignment of data points to clusters. In FCM, each data point has a degree of membership to every cluster, expressed as a probability distribution. This allows for a more flexible representation of data points that may belong to multiple clusters simultaneously.

- The algorithm iteratively updates cluster centroids and membership degrees until convergence. The membership degrees are adjusted based on the distances between data points and cluster centroids, with a parameter known as the fuzzifier controlling the degree of fuzziness in the clustering. FCM is particularly useful when dealing with data that exhibits overlap or uncertainty in cluster assignments. It has applications in image segmentation, pattern recognition, and various fields where traditional clustering methods may be too rigid.

## Result of clustering before applying pca 

<img src='https://github.com/yassminSaber/fuzzy-c-means-implementation/blob/main/Result-before-pca.png' width=700 hight= 200 />

## Result of clustering after applying pca 

<img src='https://github.com/yassminSaber/fuzzy-c-means-implementation/blob/main/Result-after-pca.png' width=700 hight= 200 />
