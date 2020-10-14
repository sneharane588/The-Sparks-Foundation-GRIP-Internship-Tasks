# Prediction using Unsupervised ML
## K- Means Clustering

From the given ‘Iris’ dataset, predict the optimum number of clusters and
represent it visually.

## Dataset Information : 
The Iris Dataset contains samples of three species of Iris : 

- Iris setosa
- Iris virginica
- Iris versicolor.

![species.png](https://miro.medium.com/max/2550/1*7bnLKsChXq94QjtAiRn40w.png)

#### The Iris Dataset contains four features (length and width of sepals and petals) of 50 samples of each  species.

![iris.png](https://www.integratedots.com/wp-content/uploads/2019/06/iris_petal-sepal-e1560211020463.png)

 These measures were used to create a linear discriminant model to classify the species.
 The dataset is often used in data mining, classification and clustering examples and to test algorithms.

## Elbow Method

The elbow method is used to determine the optimal number of clusters in k-means clustering. The elbow method plots the value of the cost function produced by different values of k. As you know, if k increases, average distortion will decrease, each cluster will have fewer constituent instances, and the instances will be closer to their respective centroids. However, the improvements in average distortion will decline as k increases. The value of k at which improvement in distortion declines the most is called the elbow, at which we should stop dividing the data into further clusters.

![elbow.png](https://www.oreilly.com/library/view/statistics-for-machine/9781788295758/assets/995b8b58-06f1-4884-a2a1-f3648428e947.png)
