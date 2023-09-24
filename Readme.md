**Project Summary: Sales Prediction With Python**

**Objective:**
The objective of this project is to predict sales based on advertising expenditures in different media channels, namely TV, Radio, and Newspaper, using various regression models. The project involves data preprocessing, feature engineering, model building, and evaluation.

**Data Preprocessing:**
1. **Data Loading:** I loaded the dataset containing information about advertising expenditures and sales.
2. **Data Cleaning:** I checked for missing values and outliers, and I removed the 'Unnamed: 0' column, which appeared to be an index.
3. **Data Splitting:** I split the dataset into features (X) and the target variable (y), with 'Sales' as the target. Then, I further split the data into training and testing sets.

**Model Building:**
I built and evaluated multiple regression models to predict sales based on advertising expenditures. I considered the following models:

1. **Multiple Linear Regression:** I initially applied a basic multiple linear regression model.
2. **Polynomial Regression:** I experimented with polynomial regression by adding polynomial features to capture potential nonlinear relationships in the data.
3. **Ridge Regression:** I used Ridge Regression as a regularized linear regression model to reduce overfitting.
4. **Lasso Regression:** Lasso Regression was employed as another regularized linear regression model.
5. **Decision Tree Regressor:** I used a Decision Tree Regressor to capture complex nonlinear relationships in the data.
6. **Random Forest Regressor:** A Random Forest Regressor was applied as an ensemble method to further improve predictions.

**Model Evaluation:**
I evaluated the performance of each model using the following metrics:

- **Mean Squared Error (MSE):** A measure of the average squared difference between predicted and actual values.
- **R-squared (R2) Score:** A measure of how well the model explains the variance in the target variable.

**Results:**
After evaluating each model, I found that the Random Forest Regressor outperformed other models, achieving the lowest MSE and the highest R2 score. This suggests that the Random Forest model provides the best predictions for sales based on advertising expenditures in this dataset.

**Future Steps:**
In future iterations of this project, I can consider further hyperparameter tuning and feature engineering to improve model performance. Additionally, I may explore more advanced regression techniques and gather more data for more robust predictions. Regular model maintenance and updates are essential to ensure continued accuracy.
