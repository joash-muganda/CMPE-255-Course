# Audio Clustering Project

## Overview
This project focuses on the unsupervised clustering of audio files. The initial objective was to use ImageBind LLM embeddings, but due to accessibility issues, we opted for an alternative approach using MFCCs (Mel-frequency cepstral coefficients) as audio embeddings.

## Methodology
- **Feature Extraction:** Extracted MFCCs using the `librosa` library.
- **Clustering:** Applied K-Means algorithm to group audio files based on their MFCCs.
- **Analysis:** Evaluated clusters through qualitative analysis and by examining the Elbow Method for optimal K determination.

## Results
The clustering results are documented in the [project documentation](Documentation-link). The results include the number of clusters determined, sample files from each cluster, and insights into the characteristics that might influence the grouping of audio files.

## Data Source
The audio files used for this project are sourced from a [Kaggle dataset](https://www.kaggle.com/datasets/joachipo/darksound).

## Note
This project was adapted to an alternative method instead of ImageBind LLM due to constraints in accessing the tool. The methodology and results, however, remain robust and demonstrate the potential of MFCCs for audio analysis.

## Usage
To replicate this project or to perform further analysis, please refer to the code and documentation provided in this repository.

## Contribution
Contributions to this project are welcome. You can suggest improvements, report issues, or contribute to the code by creating a pull request or opening an issue.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE-file-link) file for details.
