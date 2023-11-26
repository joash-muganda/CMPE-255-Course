# Hierarchical Clustering Analysis

## Project Overview
This project involves the implementation of hierarchical clustering on a dataset of credit card customers. The goal is to segment customers based on various banking behaviors and credit usage patterns.

## Dataset
The dataset includes information about credit card customers such as average credit limit, total number of credit cards, bank visits, online visits, and calls made.

## Methodology
1. **Data Preprocessing**:
   - Selected features relevant to customer behavior: average credit limit, total credit cards, bank visits, online visits, and calls made.
   - Scaled the features using `StandardScaler` for equal contribution in clustering.

2. **Hierarchical Clustering**:
   - Implemented using Ward's method which minimizes the total within-cluster variance.
   - Visualized the clustering structure using a dendrogram.

3. **Cluster Analysis**:
   - Determined an optimal threshold for cutting the dendrogram to form distinct clusters.
   - Analyzed each cluster to understand the defining characteristics and behaviors of customers in each group.

## Key Findings
- Identified distinct customer segments ranging from digital-savvy users to traditional banking customers.
- Insights into varying levels of credit usage, banking engagement, and preferences for banking channels.

## Technologies Used
- Python
- Libraries: Pandas, Scipy, Matplotlib, and Scikit-learn

## How to Run
(Include instructions on how to run the project in a local environment.)

## Author
(Your Name)

## License
(Include license information if applicable.)
