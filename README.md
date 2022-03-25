# PCA

In this task, we investigated the differences between arrests per 100,000 residents for assault, murder, and rape in each of the 50 US states in 1973. Also given is the percent of the population living in urban areas. This was conducted using unsupervised learning methods such as Principal Component Analysis (PCA) and various clustering techniques.

PCA resulted in the dataset reducing to two principcal components (PC). 
Both the Agglomerative Clustering method and the kmeans method had a recommended cluster size of 2. However, the Agglomerative Clustering method had the higher silhouette score. 

Results showed that PC1 had a positive correlation to all the features in the dataset. Most notably, 'Rape', 'Assault' and 'Murder'. For PC2, the only significant relationship it had was with one feature, 'UrbanPop' and it was a negative correlation.

On the scatter graphs, The first cluster data points all had positive PC1 values and PC2 values which range from -1.5 to 2.5. The postive PC1 values suggests that for this cluster, the arrests are mainly attributed to 'Rape', 'Assault' and 'Murder'. 

The second cluster data points mainly had negative PC1 values and majority negative PC2 values. This suggests that for this cluster, the arrests are mainly attributed to a high percentage of the population living in urban areas.
