
# Heart Disease Prediction - Problem Statement

## Overview
Heart disease is recognized as the leading cause of death in the developed world. The objective of this project is to employ a dataset for predicting the likelihood of patients suffering from heart disease in the near future based on various features.

## Dataset
The dataset utilized for this prediction is available [here](https://github.com/mimran-khan/HeartAttackPrediction/blob/main/heart.csv).

## Data Exploration and Cleaning

- **Dataset Features**: Includes age, sex, chest pain type, resting blood pressure, cholesterol levels, fasting blood sugar, and more.
- **Cleaning Process**: No null values were found after the initial cleaning. Data anomalies were corrected to ensure quality analysis.

## Statistical Analysis and Visualization

- **Techniques Used**:
  - Distribution plots and box plots to explore individual variables.
  - Heatmaps and correlation matrices to examine relationships between variables.
- **Key Visualizations**: Included to identify outliers and understand data distributions.

## Data Preprocessing

- **Standardization**:
  - Applied MinMax scaling to standardize features, enhancing model comparability and performance.
- **Feature Selection**:
  - Dropped 'fasting blood sugar' due to its low correlation with the target variable, optimizing the feature set for model training.

## Model Building

- **Models Trained**:
  - A random forest classifier was employed due to its effectiveness in handling various data types and robustness against overfitting.
- **Data Splits**:
  - Examined model performance with different training-testing splits (80-20 and 10-90), analyzing the impact of training data volume on model accuracy.

## Evaluation Metrics

- **Metrics Used**:
  - Accuracy, precision, recall, and F1-score to assess the model's predictive power.
- **Performance**:
  - Detailed metrics provided insights into the model's ability to predict heart disease accurately.

## Insights and Recommendations

- **Key Predictors**:
  - 'Chest pain type' and 'max heart rate achieved' were significant predictors of heart disease.
- **Recommendations**:
  - Focus on significant predictors for early screening and targeted prevention strategies to combat heart disease effectively.

---

This analysis utilizes advanced data science techniques to provide a thorough understanding of factors influencing heart disease, aiding in better prediction and prevention strategies.

