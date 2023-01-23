# finalCapstone

## Unsupervised Learning on US Arrests in 1973 Data Set

This project uses unsupervised machine learning models such as PCA and clustering to analyse statistics on accounts of Murder, Assault and Rape per 100,000 arrests for all 50 US states in 1973. It also includes a column with the percentage of people living in an ubran area in that state. 

*Contents*

The first few lines of code are preprocessing of the data.  Including renaming certain columns, checking for any null values within the data as well as examining the datatype for each column to ensure we're working with continuous numerical data. 

Next, we summarise the statistical properties of each column. Looking at the mean, std deviation, min and max values for each feature.

We then plot four histograms looking at the ditribution of observations for each feature. 

The next part of the project uses correlation analysis to find any features that are strongly positively or negatively correlated. 

PCA is then carried out on the data to try and reduce the number of features.

Finally two different types of clustering techniques are carried out on the data. Namely, hierarchical clustering and K-means clustering.
