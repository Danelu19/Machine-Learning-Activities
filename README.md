# Machine-Learning-Activities
Welcome to the Machine Learning Activities Repository! This repository serves as a centralized hub for various machine learning projects, experiments, and educational materials. Whether you're a beginner looking to explore the basics of machine learning or an experienced practitioner seeking inspiration, you'll find a variety of resources here.

# K-Means Lab
This lab was developed as a class laboratory.

### Description:
This Python script demonstrates the application of K-Means clustering on a dataset containing information about age and annual income. The dataset is visualized using a scatter plot, and the Elbow method is employed to determine the optimal number of clusters (k). The script then performs K-Means clustering and visualizes the resulting clusters.

### Dependencies:
- Python 3.x
- Libraries: pandas, numpy, sklearn, matplotlib

### Usage:
1. Install the required libraries using:
   ```
   pip install pandas numpy scikit-learn matplotlib
   ```

2. Run the script by executing:
   ```
   python kmeans_clustering.py
   ```

### Output:
The script generates a scatter plot of the dataset, an Elbow plot to determine the optimal k value, and a final scatter plot with clusters identified.

### Additional Notes:
- The dataset is loaded from a CSV file hosted on GitHub, and the script contains comments to guide you through each step.
- Normalization using MinMaxScaler is applied to the dataset before clustering.
- The Elbow method is used to find the optimal k value for clustering.

## Hierarchical Clustering

### Description:
This Python script demonstrates the application of Hierarchical Clustering on a randomly generated dataset. The script includes the creation of a distance matrix, visualization of the dendrogram, and the use of different linkage methods (average, complete, and single) for clustering.

### Dependencies:
- Python 3.x
- Libraries: numpy, scipy, matplotlib, sklearn

### Usage:
1. Install the required libraries using:
   ```
   pip install numpy scipy matplotlib scikit-learn
   ```

2. Run the script by executing:
   ```
   python hierarchical_clustering.py
   ```

### Output:
The script generates a scatter plot of the randomly generated dataset, a distance matrix, and dendrograms for average, complete, and single linkage methods.

### Additional Notes:
- The dataset is randomly generated using the `make_blobs` function from scikit-learn.
- Different linkage methods are applied to observe their impact on cluster formation.
- The script includes comments to guide you through each step.

## Data Clustering with K-Means and Hierarchical Clustering

### Overview
This repository contains Python scripts for performing data clustering using K-Means and Hierarchical Clustering techniques. The scripts are designed to analyze a dataset and identify underlying patterns or clusters based on specified features.

### Scripts
1. **KMeans_Clustering.ipynb**: This Jupyter Notebook script demonstrates the application of K-Means clustering on a dataset containing information about age and annual income. The script covers steps such as data visualization, choosing the optimal number of clusters (K), and visualizing the resulting clusters. Additionally, it explores the impact of normalizing the dataset before clustering.

2. **Hierarchical_Clustering.ipynb**: This Jupyter Notebook script illustrates the application of Hierarchical Clustering on a synthetic dataset generated using the `make_blobs` function. The script includes the generation of random blobs, visualization of the blobs, calculation of the distance matrix, and the creation of a dendrogram using different linkage methods.

### Dataset
The K-Means clustering script uses a dataset containing age and annual income information. You can find the dataset [here](https://raw.githubusercontent.com/erickedu85/dataset/master/age_income.csv).


# LSTM Project
This project was developed in collaboration with a team passionate about ML.  

Team Members:

- First Member Name: Jonathan Loor

- Second Member Name: Ariana Jiménez

- Third Member Name: Dánely Sánchez
