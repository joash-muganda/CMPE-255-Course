# UCF50 Video Action Recognition Analysis

An end-to-end deep dive into the UCF50 video action recognition dataset. This project showcases preprocessing, feature extraction, clustering, anomaly detection, and model building using various techniques and tools.

## Table of Contents
- [Dataset Overview](#dataset-overview)
- [Preprocessing Steps](#preprocessing-steps)
- [Clustering and Visualization](#clustering-and-visualization)
- [Anomaly Detection](#anomaly-detection)
- [Model Building](#model-building)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Dataset Overview
UCF50 is a widely used dataset for evaluating action recognition models. It contains 50 categories of actions and provides a diverse set of challenges. The dataset can be accessed and downloaded from Kaggle using the following command: 
kaggle datasets download -d vineethakkinapalli/ucf50-action-recognition-dataset

[Direct link to the dataset on Kaggle](https://www.kaggle.com/vineethakkinapalli/ucf50-action-recognition-dataset)

## Preprocessing Steps
- **Normalization**: Ensuring each video has a consistent number of frames.
- **Resizing**: Adjusting each frame to a consistent size.
- **Feature Extraction**: Using ResNet50 to extract features from each frame.

## Clustering and Visualization
KMeans clustering was applied to group similar video actions. A t-SNE visualization provides a 2D representation of the clustered videos.

## Anomaly Detection
Isolation Forest was used to identify potential outlier videos that don't conform to typical action patterns.

## Model Building
Random Forest was trained on the extracted features to categorize videos into one of the 50 action categories.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Acknowledgments
- UCF for the dataset
- OpenAI's GPT-4 for assistance in analysis
