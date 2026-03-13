# Influenza Outbreak Detection using Machine Learning

This project applies supervised machine learning techniques to detect influenza outbreak periods using global influenza surveillance data.

## Models Used
- Logistic Regression (baseline model)
- Random Forest (ensemble model)

## Dataset
The dataset contains influenza surveillance indicators including:
- Influenza A cases
- Influenza B cases
- Laboratory specimens processed
- Seasonal indicators (week of year)

## Methodology
1. Data cleaning and preprocessing
2. Exploratory data analysis
3. Feature engineering
4. Model training
5. Hyperparameter tuning using GridSearchCV
6. Model evaluation

## Evaluation Metrics
Models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

Recall is prioritised because correctly detecting outbreak periods is critical for public health surveillance.

