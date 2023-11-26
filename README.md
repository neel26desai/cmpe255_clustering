# cmpe255_clustering
This repository contains the code and demonstraction of various clustering methods on differen types of data.

The repo consists of the following files:

a. KMeansFrom_Scrath.ipynb: 
  - This file contains the implementation of KMeans from scratch without the use of sklearn.
    
b. HierarchicalClusteringipynb.ipynb:
  - This file contains the implementation of various Hiearchihcal Clustering techniques on iris data set.

c. GaussianMixtures.ipynb:-
  - This file contains the implementation of GMM on circular and elongated data.
    
d. DBScanPycaret.ipynb
  - This file contains DBSCAn implementation using pycaret (automl library) on the jewellery dataset.
    
e. AnomalyDetectionPyOD.ipynb
  - This notebook illustrated the use of PyOD for outlier/anomaly detection for univariant and multivariant use cases. The dataset used is historical Amazon share prices.
    
f. TimeSeriesClustering.ipynb
 - This notebook illustrates how can we perform clustering on time series data (with exogenous variables), the use of seasonality and trend in clustering and the use of the pre-trained model for predicting clusters on unssen data. The dataset used is last 1 years Alphabet's stock price

g. DocumentClustering.ipynb
  - This notebook illustrated how we can perform clustering on text documents, it uses cutting-edge LLM's embeddings for embedding text. In this demonstration, we have used the Bert LLM's encoder.
    
h. ImageClustering.ipynb
 - This notebook demonstrates how we can generate image embeddings using ImageBind LLM, and how can use these embeddings for clustering the data. The dataset ia a flower daatsets which contains images of 10 different species of flowers, the link can be found inside the notebook. (Note: a good GPU is a must for running this)

i. AudioClustering.ipynb
 - This notebook demonstrates how we can generate audio embeddings using ImageBind LLM, and how can use these embeddings for clustering the data. The dataset which we have used consists of 300 audio files containing speeches in English, Spanish and French.
