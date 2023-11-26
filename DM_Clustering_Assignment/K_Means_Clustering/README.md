# K-Means Clustering from Scratch

## Project Overview
This project demonstrates the implementation of the K-Means clustering algorithm from scratch in Python. We applied the algorithm to the 'Mall_Customers' dataset to segment customers based on their annual income and spending behavior.

## Key Features
- Custom implementation of K-Means without using built-in libraries.
- Analysis of the 'Mall_Customers' dataset for practical insights.
- Visualization of clustering results for easy interpretation.

## Dataset
The 'Mall_Customers' dataset contains the following features:
- `CustomerID`: A unique identifier for each customer.
- `Gender`: The customer's gender (Male/Female).
- `Age`: The age of the customer.
- `Annual Income (k$)`: The annual income of the customer in thousands of dollars.
- `Spending Score (1-100)`: A score based on the customer's spending behavior.

## Implementation Steps
1. **Data Exploration and Preprocessing**:
   - Visualization of the distributions of 'Age', 'Annual Income', and 'Spending Score'.
   - Selection of relevant features for clustering.
2. **K-Means Algorithm**:
   - Random initialization of centroids.
   - Assignment of data points to the nearest centroid.
   - Recomputation of centroids as the mean of assigned points.
   - Iteration until convergence of centroids.
3. **Cluster Analysis**:
   - Use of the Elbow Method to determine the optimal number of clusters.
   - Detailed analysis and interpretation of each cluster.

## Results
The K-Means algorithm successfully segmented customers into distinct groups, revealing various spending patterns across different income levels and age groups.

## Technologies Used
- Python
- Matplotlib and Seaborn for visualizations
- NumPy for numerical computations

## How to Run
(Provide instructions on how to run the project in a local environment.)

## Author
(Your Name)

## License
(Include license information if applicable.)
