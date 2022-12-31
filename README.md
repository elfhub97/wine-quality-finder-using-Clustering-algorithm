# wine-quality-finder-using-Clustering-algorithm
Abstract: Using chemical analysis determine the origin of wines

**Data Set Characteristics:**

Multivariate

Number of Instances: 178

Attribute Characteristics: Integer, Real

Number of Attributes: 13

**Source:**
  Kaggle

**Original Owners:**

Forina, M. et al, PARVUS - An Extendible Package for Data Exploration, Classification and Correlation. Institute of Pharmaceutical and Food Analysis and Technologies, Via Brigata Salerno, 16147 Genoa, Italy.

**Data Set Information:**

These data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines.

The attributes are (dontated by Riccardo Leardi, riclea '@' anchem.unige.it )

1) Alcohol
2) Malic acid
3) Ash
4) Alcalinity of ash
5) Magnesium
6) Total phenols
7) Flavanoids
8) Nonflavanoid phenols
9) Proanthocyanins
10) Color intensity
11) Hue
12) OD280/OD315 of diluted wines
13) Proline

Because there are so many attributes contributing to the wine quality, It is dificult to process these data. So for that I seeked help of PCA.
 ## So what is PCA?
 Principal Component Analysis (PCA) is a data analysis technique that provides a way of looking at and understanding data which is very high dimensional. In other words, PCA can be applied to data that has a large number of variables. There is a common misconception that PCA can only be used on data that is in a certain form.
 
 **After learning about ins and outs of data. I have come up with following Assumptions.**
 
* Kmeans clustring and Agglomerative Clustering was ideal to predict the wine quality.
* There are 3 quality of wine are found in dataset.
* colour intensity and alcohol is highly correlated with wine quality.
