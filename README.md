# Unsupervised Machine Learning and Crypto Currency
## Objective
### The purpose of this exercise was to use unsupervised machine learning to interpret a data set of various cryptocurrencies trading on the market to see what clusters would make sense to offer as a packaged investment for potential clients. Unsupervised machine learning was used since there is not a known output for what the various data clusters might look like using K-Means. Principal Component Analysis was used to speed up the efficiency of the machine learning algorithms in order to reduce the number of input features to a more manageable size to reduce over fitting. The scikit-learn and hvplot libraries were used for this exercise.
## Results
![kmeans.png](/resources/kmeans.png)
### After the K-Means analysis, looking at the elbow curve produced it seems clear that at 4 clusters most of the data set is utilized before diminishing returns increase significantly, so 4 clusters seem to be the optimal number for this analysis
![clusters.png](/resources/clusters.png)
### The 4 clusters are visualized here in a 3d graph to show which specific cryptocurrencies are grouped together 
![plot.png](/resources/plot.png)
### The plot here shows the same information of the cluster groups in a 2D setting with the total coin supply and the total mined coins as the variables in this visualization.
## Summary
### After the K-Means analysis, the optimal amount of clusters for this data set seem to be 4 by looking at the elbow graph above in the results section. However, there is an outlier of one cluster with exactly 1 coin: BitTorrent. After further investigation to see why the BitTorrent coin is so unique in the world of crypto and what separates it from more popular and well-known crypts like Bitcoin and Ethereal, it seems that it is used as an incentive for BitTorrents normal peer-to-peer sharing service as a "bonus" in order to incentive people to help host seeds for various files. This opens further investigation to the utility of cryptocurrency as not just another blockchain node, but as a catalyst in an existing ecosystem to help software companies evolve and develop further.

### Another notable coin that was not an outlier for clustering purposes is Turtledove in the Class 0 clusters due to total coin supply is at 100% like BitTorrents coin. According to its team, Turtle coin is “perhaps the best way to introduce your kids to a Proof-of-Work cryptocurrency ”, a hybrid of a "joke" coin like doge coin and an educational tool used to educate the public on cryptocurrency. 
