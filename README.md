# Rainfall Prediction in Australia

## Introduction
Rainfall prediction is a crucial aspect of meteorology, impacting various sectors such as agriculture, transportation, and water management. This project aims to predict whether a location in Australia will experience rain tomorrow based on meteorological data. Accurate forecasting can provide valuable insights to local governments and industries, particularly in regions with low rainfall like Australia.

## Technology/Datasets
- **Python Libraries**: Pandas, Requests, Seaborn, Matplotlib, Scikit-learn, Warnings, SciPy
- **Dataset**: "Rain in Australia"
  - Features: 23
  - Observations: 145,460
  - Includes parameters like temperature, rainfall, wind speed, humidity, and pressure.

## Models Evaluated
- Logistic Regression
- K-Nearest Neighbors
- Decision Tree
- AdaBoost
- Bagging Classifier
- Support Vector Machine (SVM)
- Random Forest
- Multilayer Perceptron

## Evaluation Metrics
- **Accuracy**: Overall correctness of predictions.
- **Precision**: Proportion of true positive predictions among all positive predictions.
- **Recall**: Proportion of true positive predictions among all actual positive instances.
- **F1-score**: Harmonic mean of precision and recall.
- **AUC-ROC score**: Ability to distinguish between positive and negative instances.

## Analysis
- **Key Features**: Humidity3PM and WindGustSpeed were consistently important across models.
- **Best Model**: Logistic Regression performed best, prioritizing recall due to the high cost of false negatives in predicting rainfall.

## Conclusion
Given the importance of recall and AUC-ROC score in predicting rainfall, Logistic Regression emerges as the best model. However, further refinements like hyperparameter tuning and feature engineering could potentially enhance model performance.
