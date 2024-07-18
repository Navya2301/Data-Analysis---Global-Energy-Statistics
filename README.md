# Data-Analysis---Global-Energy-Statistics
Data Analysis of a dataset that has comprehensive statistics on global energy production, consumption, and trade.

Here we are using a simple statistical method to segment continents based on their energy consumption patterns and then refine the segmentation using a more advanced method. This will illustrate the importance of choosing the right statistical techniques to achieve better results.

## Dataset
The dataset used in this project is Global Energy Statistics from Kaggle, which includes energy consumption data for various countries. Key columns include:
Continent: The continent of the country.
Country: The name of the country.
1980 to 2021: Energy consumption data for the year 1980 to 2021.

## Data Loading and Preprocessing
1. Load data using pandas library
2. Handle missing values by dropping rows with missing dates
3. We scale numerical features using StandardScaler and Categorical features are encoded using one-hot encoding.

## Initial Segmentation: K-Means Clustering
We perform K-Means clustering to segment the countries and evaluate the clusters using silhouette score and inertia

### Improved Segmentation: Hierarchical Clustering
We use Hierarchical Clustering to further segment the countries and visualize the results using a dendrogram

### Analyze and Visualize the Clusters
We analyze the characteristics of each cluster and visualize the cluster centers for numerical features.

Insights: This project demonstrates the process of segmenting countries based on energy consumption data using both K-Means and Hierarchical Clustering methods. The insights gained from the clustering analysis can help in understanding global energy consumption patterns and guiding policy-making decisions.

## Getting started
1. Download the dataset from Kaggle - Global Energy Statistics (https://www.kaggle.com/datasets/akhiljethwa/world-energy-statistics)
2. Use google colab [Easier for python libraries]
3. Install Pandas

