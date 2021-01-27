## Hi my name's Christian <img src="https://user-images.githubusercontent.com/1303154/88677602-1635ba80-d120-11ea-84d8-d263ba5fc3c0.gif" width="28px" alt="hi">

I'm passionate about my work as a Data Scientist because I'm a systems thinker who loves answering questions that begin with 'why'.

📫 Contact Info:

[![Twitter Badge](https://img.shields.io/badge/-Twitter-1ca0f1?style=flat&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/TheDataFunnel)](https://twitter.com/TheDataFunnel)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-0e76a8?style=flat&labelColor=0e76a8&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/christianvgarrett/)
[![Mail Badge](https://img.shields.io/badge/-Email-c0392b?style=flat&labelColor=c0392b&logo=gmail&logoColor=white)](mailto:christian@providentialmarketing.com)

### Background

1 in 8 women will develop breast cancer in their lifetime. Breast cancer is the second leading cause of cancer death among women in the US and the first leading cause of cancer death among women globally. However, with early detection (at the localized stage) the survival rate is 99%. Therefore, this research will be useful to any private or public interests that are concerned with optimizing the tools for timely diagnosis and intervention.

### Data

The data was obtained from the 'Breast Cancer Wisconsin' case study. It contains 569 observations, each with 32 attributes corresponding to features derived from digitized images of breast mass fine needle aspirations (FNA). The mean, standard error, and 'largest' values were recorded for each of 10 real-valued features recorded from the specimen cell nuclei.

### Features

This analysis compared the results of four popular unsuperivised learning techniques including K-Means, DBSCAN, Gaussian Mixture Modeland Agglomerative Hierarchical Clustering. Three dimensionality reduction techniques (PCA, tSNE, UMAP) were considered for each model providing a useful tool for 2D visualizations and a basis for potential feature engineering. Hyperparameter tuning was measured using the Adjusted Rand Index (ARI) and silhouette scores in order to determine the best fit and the selected settings were evaluated for overall accuracy, precision, recall and f1 scores for each of the classification outcomes.

### Technologies

The code is written in Python 3.0 and incorporates various popular libraries such as Pandas, Numpy, Sklearn, SciPy and StatsModels and MatPlotlib.

### Results

The Gaussian Mixture Model was selected as the most effective algorithm for this dataset because it identified over 88% of the malignant cases in this dataset and over 98% of the malignant diagnoses were accurate. In addition, this model generated a .81 ARI score indicating a high degree of similarity between the data clusterings when adjusted for the element of chance.

### Future Goals

Anaysis of the agglomerative hierarchical model revealed that some of the included features may be insignificant. Additional time to increase domain knowledge could facilitate feature aggregation which could potentially improve efficacy. Further experimentation with multicollinearity reduction, continuous feature discretization and/or elimination of variables that are least consistent with a Gaussian distribution could also improve model performance.