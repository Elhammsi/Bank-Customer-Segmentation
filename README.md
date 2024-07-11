# Bank Customer Segmentation
## Project Overview
This project aims to segment bank customers using clustering techniques. Customer segmentation helps in understanding the distinct groups of customers, allowing for more targeted marketing strategies and personalized services. The primary steps involved in this project include data preprocessing, exploratory data analysis (EDA), feature engineering, clustering using K-means, applying Principal Component Analysis (PCA) for dimensionality reduction, and visualizing the customer segments with radar plots.
Table of Contents

    1. Data Preprocessing
    
    2. Exploratory Data Analysis (EDA)
    
    3. Feature Engineering
    
    4. Clustering
    
        ◦ K-means Clustering
        
        ◦ Evaluation with Silhouette Coefficient and Elbow Method
        
        ◦ Principal Component Analysis (PCA)
        
    5. Visualization
    
        ◦ Radar Plot
        
    6. Conclusion

## Data Preprocessing

Data preprocessing involves cleaning the dataset to ensure it is ready for analysis. The steps include:

    • Handling missing values
    
    • Encoding categorical variables
    
    • Scaling numerical features
    
    • Removing duplicates
    
Exploratory Data Analysis (EDA)

EDA helps in understanding the underlying patterns and relationships within the data. In this project, the following techniques were used:

    • Descriptive statistics to summarize the data
    
    • Visualizations such as histograms, box plots, and pair plots to explore distributions and correlations
    
    • Identification of outliers
    
## Feature Engineering

Feature engineering transforms raw data into meaningful features that improve the performance of machine learning models. Key steps include:

    • Creating new features
    
    • Aggregating or combining existing features
    
    • Normalizing or standardizing features
    
## Clustering
K-means Clustering
K-means clustering is an unsupervised learning algorithm used to partition the dataset into K clusters. The algorithm iteratively assigns data points to the nearest cluster center and then updates the cluster centers based on the assignments.
Evaluation with Silhouette Coefficient and Elbow Method

To determine the optimal number of clusters (K), we used:

    • Silhouette Coefficient: Measures how similar a data point is to its own cluster compared to other clusters. Values range from -1 to 1, with higher values indicating better-defined clusters.
    
    • Elbow Method: Plots the sum of squared distances from each point to its assigned cluster center. The 'elbow' point indicates the optimal K, where adding more clusters does not significantly reduce the sum of squared distances.
    
## Principal Component Analysis (PCA)

Given the differing results from the silhouette coefficient and elbow method, PCA was applied for dimensionality reduction. PCA reduces the data to a lower-dimensional space while preserving most of the variance, making it easier to visualize and cluster.
Visualization

Radar Plot

Radar plots were used to visualize the customer segments. These plots help in understanding the characteristics of each segment across multiple dimensions. Each axis represents a feature, and the plot displays the average values for each cluster.
## Conclusion

This project successfully segmented bank customers into distinct groups using K-means clustering and PCA. The radar plots provided a clear visualization of the customer segments, revealing insightful patterns that can guide marketing and customer relationship strategies. The combination of clustering evaluation methods ensured robust and meaningful segmentation.

