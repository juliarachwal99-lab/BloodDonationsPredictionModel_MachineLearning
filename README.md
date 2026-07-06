# Blood donations prediction model (Machine Learning)

## Project Overview
This repository contains a machine learning workflow to predict blood donor return behavior based on historical data from the Blood Transfusion Service Center in Hsin-Chu City, Taiwan. The project applies an adapted RFM framework to solve a binary classification problem: predicting whether a donor returned to donate blood in March.

## Used in project
* **Stack:** Python (Pandas, NumPy, Scikit-Learn, Matplotlib)
* **Workflow:** Data cleaning, 80/20 train-test split, data normalization via `StandardScaler`, and model training

## Models & Evaluation Results
Models were evaluated on the test set using the Accuracy metric:

| Model | Test Accuracy |
| :--- | :---: |
| **K-Neighbors Classifier (KNN)** | **76.67%** |
| **Logistic Regression** | **76.00%** |
| **Random Forest Classifier** | **76.00%** |

### Conclusion
All models demonstrated consistent predictive performance around the 76% accuracy threshold, with KNN achieving the highest score of 76.67%.
