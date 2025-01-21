# ML_Assignment_3-Regression
A machine learning assignment analyzing the California Housing Dataset using regression models. Includes data preprocessing, model implementation, and performance evaluation to predict housing prices.
# Regression Analysis - Machine Learning Assignment 3

## Overview

This project involves implementing and evaluating various regression algorithms using the **California Housing Dataset** from Scikit-learn. The analysis focuses on preprocessing the data, building regression models, and comparing their performance to identify the most effective approach for predicting housing prices.

---

## Project Details

### 1. Dataset Selection and Preprocessing
- **Dataset:** California Housing Dataset from Scikit-learn.  
- **Preprocessing Steps:**
  - Converted the dataset into a pandas DataFrame for easier handling.
  - Scaled features using `StandardScaler` to standardize input values.
  - Split the dataset into training and testing sets for model evaluation.

### 2. Regression Algorithms Implemented
The following regression models were applied:
- **Linear Regression**  
- **Decision Tree Regressor**  
- **Random Forest Regressor**  
- **Gradient Boosting Regressor**  
- **Support Vector Regressor (SVR)**  

For each algorithm:
- Models were trained on the training set.
- Predictions were made on the testing set.

### 3. Model Evaluation
Performance was assessed using:
- **Mean Squared Error (MSE):** Measures average squared difference between predicted and actual values.
- **Mean Absolute Error (MAE):** Measures average absolute difference between predicted and actual values.
- **R² Score:** Indicates the proportion of variance explained by the model.

### 4. Results and Comparison
- **Best Performing Model: Random Forest Regressor**  
  - **R² Score:** 0.805  
  - **MSE:** 0.2555  
  - **MAE:** 0.3276  
  - *Reason:* Demonstrated superior ability to capture complex relationships in the dataset.  

- **Worst Performing Model: Linear Regression**  
  - **R² Score:** 0.576  
  - **MSE:** 0.5559  
  - **MAE:** 0.5332  
  - *Reason:* Struggled with non-linear relationships in the data, leading to poor predictions.

### 5. Insights and Conclusion
- Non-linear models like **Random Forest** and **Gradient Boosting** outperformed **Linear Regression**, highlighting the importance of capturing complex patterns in the data.  
- Feature scaling was critical for models like SVR, which are sensitive to the magnitude of input features.

---

## Repository Name
`Regression-Analysis-ML-Assignment`

## Short Description
A machine learning assignment analyzing the California Housing Dataset using regression models. Includes data preprocessing, model implementation, and performance evaluation to predict housing prices.
