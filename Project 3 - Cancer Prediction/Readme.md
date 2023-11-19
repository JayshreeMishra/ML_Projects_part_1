# Breast Cancer Diagnosis Prediction Model

This is a machine-learning project that aims to predict the diagnosis of breast cancer (Malignant or Benign) using ten computed features from cell nucleus images.

## Dataset Information:
The dataset includes ten features (X) for each cell nucleus, such as radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension. These features are accompanied by three measures: mean, standard error, and largest/worst.

## Objective:
The goal is to develop a predictive model using machine learning algorithms to accurately classify breast tumors as malignant or benign based on these features.

### Model Development:
1. Data Preprocessing: The dataset is cleaned, missing values are handled, and feature scaling is applied.
2. Model Selection: Various classification algorithms, such as Logistic Regression, Support Vector Machines, Random Forest, etc., are evaluated to find the best-performing model.
3. Model Training: The selected model is trained using the mean values of features as inputs and the diagnosis as the target variable.
4. Model Evaluation: The trained model is evaluated on a separate test set to measure its accuracy, precision, recall, and F1-score for cancer prediction.

The project aims to provide an effective cancer prediction model that can contribute to early detection and better patient outcomes.
