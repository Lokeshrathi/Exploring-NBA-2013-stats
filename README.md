# Exploring-NBA-2013-Dataset with Machine Learning

### Goal:
- The objective of this Notebook is to:
 - Cluster players with the same features as present in the dataset.
 - Predict the Points of Player using Linear Regression.
 
 ### Data Exploration
 - Find out data variables and their mean points.
 - Find out relation between different feautures.
 - Get the numeric data and remove the nan values.
 ![](/IMAGES/corr.png)
 
### Clustering
 - Cluster players using KMeans clustering.
 - Created 5 clusters.
 - Plot the players by Cluster using PCA(Principal Component Analysis, it is dimensionaluty reducing algorithm), we have     plotted 2 dimensional clusters here.
 
 ![](/IMAGES/clus.png)
 
 **Results of Clustering**
 - We found out the clusters in which players like LeBron James and Kevin Durant belong to.
 - Created a data frame which grouped labels(cluster number)against each player.
 
 ### Predicting points of players.
   - We predict the points by each player based on Free throws attempted, field goals attempted and 3 point shots attempted.
   ![](/IMAGES/LBkd.png)
   
 ### Credits:-
 - Data was imported from [Link](https://raw.githubusercontent.com/Yorko/mlcourse.ai/master/data/nba_2013.csv)
 - Kmeans clustering [Link](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
 
  
  
