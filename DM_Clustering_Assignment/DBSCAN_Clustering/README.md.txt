# DBSCAN Clustering Using PyCaret

## Overview
This repository contains the implementation of DBSCAN clustering using the PyCaret library. The project aims to demonstrate the application of DBSCAN, a density-based clustering algorithm, on a dataset to identify distinct clusters.

## Dataset
The dataset used in this project includes various features suitable for demonstrating DBSCAN clustering.

## Key Steps
- Importing and setting up PyCaret with the dataset.
- Creating a DBSCAN model using PyCaret.
- Analyzing clustering results and interpreting metrics.

## Parameters Explained
- `eps`: The neighborhood radius around each point. A smaller `eps` leads to the creation of more clusters.
- `min_samples`: The minimum number of points required to form a cluster. This parameter balances between forming too many small or too few large clusters.

## Results
The analysis of clustering results includes evaluating metrics like Silhouette Score, Calinski-Harabasz Index, and Davies-Bouldin Index.


