# Unsupervised Machine Learning and Crypto Currency
## Objective
###  The purpose of this exercise was to use unsupervised machine learning to interpret a data set of various cryptocurrencies trading on the market to see what clusters would make sense to offer as a packaged investement for potential clients. Unsupervised machine learning was used since there is not a known output for what the various data clusters might look like using K-Means. Principal Component Analysus was used to speed up the efficency of the machine learning algorithyms in order to reduce the number of imput features to a more manageable size to reduce overfitting. The scikit-learn and hvplot libraries were used for this excercise.
## Results
###![kmeans.png](/resources/kmeans.png)
###
###![clusters.png](/resources/clusters.png)
###
###![plot.png](/resources/plot.png)
## Summary
### After the K-Means analysis, the optimal amount of clusters for this data set seem to be 4 by looking at the elbow graph above in the results section. However, there is an outlier of one cluster with exactly 1 coin: BitTorrent. After further investigation to see why the BitTorrent coin is so unique in the world of crypto and what seperates it from more popular and well-known cryptos like Bitcoin and Ethereum, it seems that it is used as an incentive for BitTorrents normal peer-to-peer sharing service as a "bonus" in order to incentive people to help host seeds for various files. This opens further investigation to the utility of cryptocurrency as not just another blockchain node, but as a catalyst in an existing ecosystem to help software companies evolve and develop further.

### Another noteable coin that was not an outlier for clustering purposes is TurtleCoin in the Class 0 cluster due to total coin supply is at 100% like BitTorrents coin. According to its team, Turtlecoin is “perhaps the best way to introduce your kids to a Proof-of-Work cryptocurrency ”, a hybrid of a "joke" coin like dogecoin and an educational tool used to educated the public on cryptocurrency. 
