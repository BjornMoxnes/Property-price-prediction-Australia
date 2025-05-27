# Predicting Property Price Outcomes in Australia

## Overview
This project uses machine learning to predict whether Australian homes (Feb 2022–Feb 2023) sell above or below their listing price. The dataset includes 4,937 properties with structured and text features from real estate listings.

## Methods
- **Data Preparation:** Cleaning, encoding, and feature engineering.
- **Models:** Decision Tree, Random Forest, and SVM, with hyperparameter tuning.
- **Evaluation:** 5-fold cross-validation, F1-score as the main metric.

## Results
- **Random Forest** performed best (F1: 84.7%), leveraging both structured and text features.
- Text features (emotional intensity, readability, keywords) improved prediction accuracy.

## Key Takeaway
Random Forest with advanced text features is recommended for accurate, interpretable property price predictions in Australian real estate.
