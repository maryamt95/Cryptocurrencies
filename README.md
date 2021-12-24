# Cryptocurrencies

## Analysis Overview

The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.
This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.
We use the following methods for the analysis:

* preprocessing the database,
* reducing the data dimension using Principal Component Analysis(PCA),
* clustering cryptocurrencies using K-Means,
* visualizing classification results with 2D and 3D scatter plots.

## Results
* Following the preprocessing and cleaning phase we have a total of 532 tradable cryptocurrencies.

### Clustering Cryptocurrencies using K-Means - Elbow Curve

We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.
We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.

![image](https://github.com/maryamt95/Cryptocurrencies/blob/main/resource/Elbow%20curve.JPG)

The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

### Visualizing Cryptocurrencies Results

![image](https://github.com/maryamt95/Cryptocurrencies/blob/main/resource/3D%20plot.JPG)

This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.

### Tradable Cryptocurrencies Table

![image](https://github.com/maryamt95/Cryptocurrencies/blob/main/resource/table1.JPG)

Most of the cryptocurrencies are part of class #0 and #3.
The snapshot above shows that BitTorrent is the only cryptocurrency in class #2.


### 2D-Scatter plot with TotalCoinMined vs TotalCoinSupply

![image](https://github.com/maryamt95/Cryptocurrencies/blob/main/resource/2d%20scatter.JPG)

Plotting the scatter plot from two cryptocurrency features directly does not efficiently segregate the different classes. Then using the PCA algorithm is the right method for better visualizations.

## Summary 

We have identified the classification of 532 cryptocurrencies based on similarities of their features.
Unique features  of each group need to be analyzed to determined their performance and potential interest for the investment bank's clients.

