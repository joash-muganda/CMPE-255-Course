# Audio Classification Study: Cats vs. Dogs

In this project, we aim to classify audio files into two categories: cat sounds and dog sounds. The study was conducted using a popular Kaggle dataset, which required significant preprocessing and cleaning. 

## Table of Contents

1. [Introduction](#introduction)
2. [Exploratory Data Analysis](#exploratory-data-analysis)
3. [Data Cleaning and Preprocessing](#data-cleaning-and-preprocessing)
4. [Modeling](#modeling)
5. [Results and Observations](#results-and-observations)
6. [Acknowledgments](#acknowledgments)

## Introduction

The primary dataset consists of various audio files of cats and dogs. Our objective was to extract meaningful features from these audio files and use them to train a machine learning model to classify unseen audio files.

## Exploratory Data Analysis

We started with a detailed exploratory data analysis to understand the nature of our data:
- **Visualizations**: Distribution plots of MFCC (Mel-frequency cepstral coefficients) features were generated.
    - ![Data Distribution](./Data_Distribution_image.jpg)

- **Anomaly Detection**: We utilized DBSCAN to identify and handle anomalies in the dataset.

- **Clustering**: KMeans clustering was employed to understand the inherent groupings in the data.
    - ![Clustering Visualization](./Clustering_Visual_image.jpg)

## Data Cleaning and Preprocessing

- **Data Imputation**: Missing values were addressed using KNN imputation.
- **Feature Engineering**: MFCCs were extracted from the audio files, which served as our primary features for modeling.
- **Normalization**: Features were scaled to ensure model efficiency.

## Modeling

The study employed AutoML, specifically TPOT, to generate the best model pipeline. This approach allowed for automated hyperparameter tuning and model selection.

- **Best Model**: The best model turned out to be the GradientBoostingClassifier with specific hyperparameters.

## Results and Observations

The classifier achieved an internal CV score of approximately 0.9123, showcasing its potential in distinguishing between cat and dog sounds effectively.

## Acknowledgments

Special acknowledgment to ChatGPT-4 for assisting in the data analysis, cleaning, and processing steps, providing code insights, and overall guidance throughout the study.
