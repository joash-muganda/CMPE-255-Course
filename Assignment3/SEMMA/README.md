# Machine Learning Approach to Olympic Medal Predictions

## Overview:
Venturing into the captivating chronicles of the Olympics, this project harnesses machine learning to anticipate medalists. Through the lens of data from myriad Olympic events, we unveiled patterns and key factors potentially steering an athlete toward medal triumph.

## Dataset:
- **Attributes**: Our dataset paints a picture with features like Age, Height, Weight, Nationality, specific Olympic event, and Medal attainment.
- **Magnitude**: With over 270,000 entries, our dataset is a testament to multiple Olympic epochs.

![Histogram of Age Distribution](https://github.com/joash-muganda/SJSU-FA23-CMPE-255-Data-Mining/blob/main/Assignment3/SEMMA/SEMMA_Artifacts/age_distribution.png)

## Methodology:
- **Data Dive & Refinement**: The expedition began with an intricate dissection of the dataset's anatomy. This phase was accentuated by addressing data voids and morphing the medal feature into a binary testament of victory or otherwise.

- **Data Enlightenment Phase**: Revelations included age demographics of Olympians and the pedestal prominence of certain sports.

![Bar Chart of Medal Distribution Across Sports](https://github.com/joash-muganda/SJSU-FA23-CMPE-255-Data-Mining/blob/main/Assignment3/SEMMA/SEMMA_Artifacts/distribution_across%20sports.png)

- **Modeling & Assessment**: Four contenders — Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting — were put to the test. Their prowess post fine-tuning:
   - **Logistic Regression**: 87.31%
   - **Decision Tree**: 87.53% (The Crown Bearer)
   - **Random Forest**: 86.23%
   - **Gradient Boosting**: 86.16%

![Bar Chart of Model Accuracies](https://github.com/joash-muganda/SJSU-FA23-CMPE-255-Data-Mining/blob/main/SEMMA/SEMMA_Artifacts/intial_and_tuned_model_accuracies.png)

## Key Revelations:
- The prime age window for Olympic glory seems to be 20-30.
- In the medal tally, Track & Field, Gymnastics, and Swimming often lead the parade.

## Dive Deeper:
Crave more granularity? My [Colab notebook](https://colab.research.google.com/drive/1VCBL2tVe0BoJwP6S3jFtjRloZMYu_SjA?usp=sharing) offers a riveting journey from data to insights. 

## Collaboration & Feedback:
An amalgamation of sports fervor and data science craftsmanship, this project seeks to influence athletic strategies and foster informed sponsorship choices. Your insights, queries, or collaborative zest are eagerly awaited.
