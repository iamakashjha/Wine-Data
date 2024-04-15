# Wine-Data
Performed PCA and clustering techniques to uncover underlying structures of Wine characteristics.


In this data science project, I embarked on a comprehensive analysis utilizing Principal Component Analysis (PCA) and clustering techniques to uncover underlying structures within a dataset of wine characteristics. By performing PCA, followed by hierarchical and K-means clustering using the first three principal component scores, I aimed to identify optimal clusters and compare them with the original clustering of the data. Here's an overview of the project:
 
Problem Statement:
 
The primary objective of the project was to explore a dataset of wine attributes and identify inherent patterns and groupings using PCA and clustering algorithms. The dataset, named "wine.csv," contained various attributes describing the chemical composition of wines. The goal was to reduce the dimensionality of the dataset using PCA and then perform clustering using the reduced dimensions to uncover meaningful clusters of wine samples based on their chemical properties.
 
Approach:
 
The project followed a systematic approach to PCA and clustering analysis, encompassing the following key steps:
 
1. Data Exploration and Preprocessing:
  - Exploring the dataset to understand the distributions and relationships among wine attributes.
  - Handling missing values, outliers, and data inconsistencies, if any.
  - Scaling or normalizing features to ensure consistent scaling across attributes.
 
2. Principal Component Analysis (PCA):
  - Performing PCA to reduce the dimensionality of the dataset while preserving the most important information.
  - Identifying the principal components (PCs) that capture the maximum variance in the data.
  - Selecting the first three principal components for subsequent clustering analysis.
 
3. Clustering Techniques:
  - Utilizing hierarchical clustering to group wine samples based on similarities in their first three principal component scores.
  - Employing K-means clustering and assessing the appropriate number of clusters using techniques such as the scree plot or elbow curve.
  - Comparing the clusters obtained from PCA with the original clustering based on the ignored "class" column to evaluate consistency.
 
4. Optimal Number of Clusters:
  - Determining the optimal number of clusters for hierarchical and K-means clustering based on evaluation metrics and visualizations.
  - Assessing the agreement between the clusters obtained from PCA and the original clustering to validate the effectiveness of the dimensionality reduction technique.
 
By leveraging Python programming language along with libraries such as Pandas, NumPy, Matplotlib, scikit-learn, and scipy, the project aimed to provide insights into the underlying structure of the wine dataset and validate the utility of PCA in reducing dimensionality for subsequent clustering analysis.
