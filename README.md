# Study_Datascience

## 1. Linear Regression

* SST(total) = SSR(explained) + SSE(unexplained)

* OLS (ordinary least squares) model - minimum SSE [lowest error]

* R-squared = SSR/SST (measure how much of the total variability of the dataset, ranging 0 to 1 variability)

## 2. Multiple Linear Regression

* adjusted R-squared (<R-squared) measures how well your model fits the data, but it penalizes the use of variables that are meaningless for the regression

* increases R-squared but decreases adjusted R-squared ⇒ omit the variable

## 3. Logistic Regression
-> The logistic regression predicts the probability of an event occurring

* Maximum likelihood estimation (MLE) : estimates how likely it is that the model at hand describes the real underlying relationship of the variables

* LL-null ( log likelihood-null) : the log-likelihood of a model which has no independent variables

* LLR(log likelihood ratio) : measures if our model is statistically different from LL-null


## 4. k-means clustering
* multivariate statistical technique that groups observations on the basis some of their features or variables they are described by

* → maximize the similarity of observations within a cluster and maximize the dissimilarity between clusters

    1. choose the num of clusters [The elbow method]
      * minimize the distance between points in a cluster (low WCSS within-cluster sum of squares)
    2. specify the cluster seeds
    3. assign each point to a centroid
    4. adjust the centroids
    
## 5. Hierarchical clustering
`pros and cons of dendrogram`

* Pros

1. Hierarchical clustering shows all the possible linkages between clusters

2. No need to preset the number of clusters like K-means

3. Many methods to perform hierarchical clustering

* Cons

1. Scaleability

2. Computational expensive
    
