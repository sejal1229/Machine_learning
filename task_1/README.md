# PRODIGY_ML_01

📘 Project Description: House Price Prediction using Linear Regression

🔹 Introduction

  The goal of this project is to predict house prices based on key housing features such as square footage (sqft_living), number of bedrooms, and number of bathrooms. 

  A Linear Regression model is implemented to understand the relationship between these features and the target variable (house price).

House price prediction is an important real-world problem in the real estate industry, as it helps buyers, sellers, and agents to estimate the fair value of properties.

🔹 Dataset Description

  The dataset used contains real estate data of houses, where each row represents a house and its features.

  For this project, we selected the following attributes:

-sqft_living: The total living area of the house (in square feet).

-bedrooms: Number of bedrooms in the house.

-bathrooms: Number of bathrooms in the house.

-price: The target variable – the actual price of the house.

  This dataset is suitable for regression analysis as the target variable (price) is continuous.

🔹 Project Workflow

- Importing Libraries

  Used essential Python libraries like pandas, numpy, matplotlib, seaborn, and scikit-learn.

  These libraries help in data analysis, visualization, and building the machine learning model.

- Loading the Dataset

  The dataset is read using Pandas and the first few rows are displayed to understand its structure.

- Feature Selection
  Only the required features (sqft_living, bedrooms, bathrooms) were selected along with the target (price).

- Data Preprocessing
  Checked for missing values to ensure data quality.
  
  Visualized relationships using a pair plot, which shows how the selected features correlate with price.

- Splitting Data
  The dataset was split into training (80%) and testing (20%) sets using train_test_split.

- Model Training
  A Linear Regression model from scikit-learn was trained on the training data.
  The model learns the coefficients (weights) that best fit the relationship between features and target.

- Model Evaluation
  Predictions were made on the test set.
  
  Performance was measured using:
  
  -Mean Squared Error (MSE)
  
  -Root Mean Squared Error (RMSE)

  -R² Score (goodness of fit).

  The evaluation results showed how well the model can predict unseen data.

- Visualization
  A scatter plot of Actual vs Predicted Prices was drawn to visually inspect the model’s accuracy.

- Predicting New Inputs
  
  The trained model was tested on new input values of sqft, bedrooms, and bathrooms to predict house price.

- Saving & Loading the Model
  
  The trained model was saved using joblib (house_price_model.pkl).

Later, it was reloaded and tested again to verify predictions without retraining.

🔹 Results

  The model successfully established a linear relationship between house price and the selected features.

  Square footage (sqft_living) was found to be the most significant factor in predicting price, followed by bathrooms and bedrooms.

  Although simple, the model provides a baseline prediction system for house pricing.

🔹 Conclusion

  This project demonstrates how a Linear Regression model can be applied for predicting house prices using only a few basic features.

While the accuracy could be improved by adding more variables (like location, year built, condition, etc.), the project provides a strong foundation for understanding the process of regression modeling in real estate data analysis.
