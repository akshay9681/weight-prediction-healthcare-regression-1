# weight-prediction-healthcare-regression-1
Assessment Final  
# Reflection on the Problem and Solution

This project focused on predicting an individual's sleep duration (Sleep_Hours) using clinical and lifestyle factors like age, gender, BMI, smoking, exercise, diet, alcohol use, chronic diseases, and stress.

The dataset was extracted from a ZIP file and loaded into a pandas DataFrame. Missing values in categorical features (Exercise_Freq and Alcohol_Consumption) were imputed using the mode. Categorical variables were one-hot encoded to prepare the data for modeling.

A Linear Regression model was chosen for its simplicity and interpretability. The data was split into training (80%) and testing (20%) sets. The model achieved a Mean Squared Error (MSE) of about 2.23, indicating moderate predictive performance.

Challenges included handling missing data and feature representation. Future improvements could involve testing more advanced regression models, feature engineering, cross-validation, and hyperparameter tuning to improve accuracy and robustness.
