# 2D_data_classification_with_KNN_Kmeans_MeanShift
KNN, Kmeans and MeansShift are applied to the same data separately. The performance of each method is evaluated and analyzed. The project is taught by Flare Zhao in his course, "Python 3 Intro to Artificial Intelligence".

All three methods are applied and evaluated using accuracy scores. Kmeans and mean shift results are visualized as they are unsupervised clustering methods, therefore the results have to be corrected as labels are not predefined. 

K-Means: unsupervised method. Number of clusters needs to be predefined. K center points are initially randomly picked. The K points reposition themselves to the center of the cluster.

Meanshift: unsupervised method. Initial points randomly picked. Shifting distance is equal to the average distance between the target point and all other points within the bandwidth. 

KNN: supervised method. Number of nearest neighbors needs to be defined. The label is defined by the majority X label around the target point. 
