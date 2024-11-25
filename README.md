# OASIS-INFOBYTES-DATASCIENCE-TASK3

# **Sales Prediction Using Machine Learning**
This project demonstrates a machine learning model for predicting product sales based on advertising spend across TV, Radio, and Newspaper platforms. 
The model helps businesses estimate future sales and optimize their advertising strategies.

# **Introduction**
Sales prediction involves forecasting the number of products sold based on factors like advertising spend, target audience, and market trends. 
This project:
Uses Python and machine learning techniques.
Employs a linear regression model for sales prediction.

# **Dataset**
The dataset contains advertising budgets for three platforms and corresponding sales data. Key columns include:
TV: Advertising budget spent on TV.
Radio: Advertising budget spent on Radio.
Newspaper: Advertising budget spent on Newspaper.
Sales: Units of product sold.

# **Technologies Used**
Programming Language: Python
Libraries:
Data Analysis: pandas, numpy
Visualization: matplotlib, seaborn
Machine Learning: scikit-learn
Workflow
# **Data Preprocessing**
Load the dataset.
Clean data (handle missing values, remove duplicates).
Exploratory Data Analysis (EDA):
Understand relationships between variables using visualizations.
Feature Selection:
Selected TV, Radio, and Newspaper as features.
Model Training:
Split data into training and testing sets.
Trained a Linear Regression model.
# **Evaluation**:
Assessed model performance using MAE, MSE, RMSE, and R² Score.
Visualization:
Plotted actual vs predicted sales.

# **Visualizations**
1. Actual vs Predicted Sales (Scatter Plot)


#**Results**
The model achieved the following performance metrics:

Mean Absolute Error (MAE): 1.25
Mean Squared Error (MSE): 2.80
Root Mean Squared Error (RMSE): 1.67
R² Score: 0.91

Future Work
Integrate more advanced models like Random Forest or Gradient Boosting.
Include time-series analysis for seasonal sales trends.
Explore additional features such as region, competition, and product category
