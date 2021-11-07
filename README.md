# ML_PHW2  
Gachon Univ. SW 201735826 류창민

## cluster_model  
__cluster_model__ is function that conducts __clustering Semi-Automatically__  
input variables are __x, df, n_times__  
__x__ is a modified input data(Dataset which drop median house value)  
__df__ is Original input data  
__n_times__ is a number to try  

Score means __Silhouette score__ in this function  
In this function, using Silhoutte score, find the best models with best parameters  
In this function, __KMeans, DBSCAN, EM(GMM), CLARANS, MeanShift__ clustering algorithms are used.

As result, best model calculated by Silhoutte score will be visualized by using scatter plot  
Also, median_house_value variables are visualized according to k quantiles.
