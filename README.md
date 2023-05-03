# CryptoClustering

For cluster number 3, positive  24 hours price change can lead to positive 7 day price change. 

For cluster number 2, positive or negative 24 hours price change mostly leads to negative 7 day price change but for some instances it can lead to positive 7 day price change. 

Celsius-degree-token and Ethland move differently than other coins.  A positive 24 hour price change for Celsius-degree-token can lead to a negative 7 day price change and a negative 24 hour price change for Ethland can lead to no change in the 7 day price change.

After running the PCA, we see similar results for the two features of 24 hour and 7 day price change. However, these are not the only features that we should consider. Other features like 14 day, 30 day, 60 day, 200 day, and 1 year can also be important. Therefore, I have run a PCA analysis and plot the clusters against the first 2 principal components. Still Celsius-degree-token and Ethland have their own clusters, and the same clusters of coins like before. 

My conclusion is that the 24 hour and 7 day price change are the most important features of this data.