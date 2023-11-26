# Gaussian Mixture Models Clustering Project

## Overview
This repository contains the analysis and implementation of a Gaussian Mixture Models (GMM) clustering on a dataset related to poverty-level wages. The project explores the application of GMM, a probabilistic model that assumes all the data points are generated from a mixture of several Gaussian distributions with unknown parameters.

## Objectives
- To apply Gaussian Mixture Models for clustering.
- To understand the choice of the number of components in GMM.
- To compare the GMM approach with K-Means clustering.

## Key Steps
1. **Choosing the Number of Components**: We utilize the Akaike Information Criterion (AIC) and the Bayesian Information Criterion (BIC) to determine the optimal number of Gaussian distributions (components) for our model.

2. **Fitting the GMM to the Data**: After scaling the data, a GMM with the optimal number of components is fitted.

3. **Assigning Clusters to Data Points**: Using the fitted model, each data point in the dataset is assigned to a cluster.

## Dataset
The dataset `poverty_level_wages.csv` includes various metrics related to annual and hourly poverty-level wages, and their distribution across different years and demographics.

### Selected Features for Clustering
- Annual Poverty-Level Wage
- Hourly Poverty-Level Wage
- Share Below Poverty Wages

## Files in the Repository
- `poverty_level_wages.csv`: The dataset used for the analysis.
- `GMM_Clustering.ipynb`: Jupyter notebook containing the analysis and clustering implementation.

## Analysis Results and Insights
- Clusters were identified that represent different economic conditions and time periods.
- The GMM's flexible approach allowed for more nuanced cluster shapes compared to K-Means.

## Comparison with K-Means
- GMM, unlike K-Means, allows for elliptical clusters and accommodates mixed membership.
- The model selection criteria (AIC and BIC) used in GMM provide a more informed approach for choosing the number of components compared to the often arbitrary selection in K-Means.

## Requirements
- Python 3.x
- Libraries: pandas, sklearn, matplotlib, numpy

## How to Run
To run the analysis, execute the Jupyter notebook `GMM_Clustering.ipynb` in an environment where the required libraries are installed.

## Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your proposed changes.

## License
[MIT License](LICENSE)

## Contact
For any queries or discussions, feel free to open an issue in this repository.
