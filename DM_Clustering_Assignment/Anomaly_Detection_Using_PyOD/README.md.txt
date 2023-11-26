# Global Temperature Anomaly Detection Using PyOD

This repository hosts the materials and findings from the anomaly detection analysis conducted on global temperature data, utilizing the Python Outlier Detection (PyOD) library.

## Overview

The project showcases the application of the Isolation Forest algorithm, an unsupervised learning technique from PyOD, for identifying atypical annual global temperatures. The goal is to demonstrate how anomaly detection can be performed on univariate time-series data and to interpret the significance of the detected anomalies.

## Repository Contents

- `Anomaly_Detection_Global_Temperatures.ipynb`: The Jupyter notebook containing the Python code for performing the anomaly detection.
- `global_temperatures.csv`: The dataset file used in the analysis.
- `anomaly_detection_report.pdf`: A detailed report summarizing the findings of the anomaly detection analysis.

## Anomaly Detection Process

- **Model Selection**: The Isolation Forest model was chosen for its efficacy in handling datasets with no prior distribution assumptions.
- **Model Training**: The model was trained on the univariate series of average global temperatures reported annually.
- **Anomaly Identification**: The trained model identified years with significant deviations from the typical temperature range.
- **Results Visualization**: The anomalies were visualized on a line plot against the timeline of the dataset.

## Detailed Report

For a thorough explanation of the process, findings, and implications of the detected temperature anomalies, refer to the [Anomaly Detection Report](link-to-report).

## Quick Start

To run this analysis, clone the repository and ensure you have Python and the necessary packages installed. You can install all required packages using the following command:

pip install -r requirements.txt


Then, launch the Jupyter notebook to view the analysis.

## Contributing

We welcome contributions and suggestions! Please feel free to fork the repository, make changes, and submit pull requests.

## License

This project is open source and available under the [MIT License](LICENSE.md).

## Questions?

If you have any questions or comments, please feel free to open an issue in this repository.
