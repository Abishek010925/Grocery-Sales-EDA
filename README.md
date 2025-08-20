🛒 Supermart Grocery Sales Analysis (Python Project)
📌 Project Overview
This project analyzes Supermart Grocery Sales data using Python.
The notebook covers data preprocessing, exploratory data analysis (EDA), sales trend visualization, and predictive modeling to understand key sales drivers and evaluate forecasting models.

🔑 Key Objectives:
Clean and preprocess the sales dataset.
Explore sales patterns across regions, cities, categories, and subcategories.
Identify sales trends over months, years, and weekdays.
Build and evaluate predictive models (Linear Regression, Random Forest) for sales forecasting.

📊 Exploratory Data Analysis (EDA)

Key visualizations include:
  Sales by Region (East, West, South, etc.)
  Sales by City (top and bottom performers)
  Sales by Category & Sub-Category (e.g., Beverages, Household, etc.)
  Sales trends over time:
  By month, year, weekday
  Combined year-month trends

🔬 Feature Engineering
  Extracted day, month, year from order date.
  Created Quarter and Months_Since_Start features.
  One-hot encoded categorical variables (Region, City, Category, Sub Category).

🤖 Machine Learning Models
1. Linear Regression
Split data into train/test (80-20).
Results:
Mean Squared Error (MSE): ~582
R² Score: -0.006 (poor performance, model underfits).

2. Random Forest Regressor
Pipeline with preprocessing + Random Forest.
Results:
Mean Squared Error (MSE): ~599
R² Score: -0.07 (also underperforming).

📌 Insight: Simple regression models don’t capture the complexity of the dataset. Future work could include Gradient Boosting, XGBoost, or time-series forecasting approaches.

🛠️ Tech Stack

Language: Python
Libraries:
numpy, pandas → Data manipulation
matplotlib, seaborn → Visualization
scikit-learn → Machine learning
Pipeline, OneHotEncoder, RandomForestRegressor, LinearRegression

📌 Future Improvements
  Apply time series forecasting models (ARIMA, Prophet, LSTM).
  Perform hyperparameter tuning for Random Forest.
  Incorporate external data (seasonality, holidays, promotions).
  
👤 Author

Abishek Chaudhari
GitHub: @Abishek010925
LinkedIn: linkedin.com/in/abishek-chaudhari/
