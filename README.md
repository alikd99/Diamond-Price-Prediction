Diamond Price Prediction
This project aims to predict the price of diamonds based on their characteristics using various regression models. The dataset is sourced from the popular diamonds dataset available in Seaborn, which contains prices and attributes like carat, cut, color, clarity, and dimensions.

📊 Project Overview
Goal: Build and evaluate machine learning models that accurately predict diamond prices.

Dataset: Seaborn diamonds dataset (~54,000 rows).

Target Variable: price

Features Used:

Numeric: carat, depth, table, x, y, z

Categorical: cut, color, clarity

📁 Project Structure
bash
Copy
Edit
.
├── DiamondPricePrediction.ipynb  # Jupyter notebook with full analysis and modeling
└── README.md                     # Project documentation
⚙️ Methods and Workflow
Data Cleaning & Exploration:

Removed duplicates

Checked for missing values

Visualized feature distributions

Feature Engineering:

Encoded categorical features using OrdinalEncoder

Scaled numeric features using StandardScaler

Modeling:

Trained multiple regression models:

Linear Regression

Ridge & Lasso Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Evaluation:

Metrics: R² Score, MAE, MSE, RMSE

Selected the best-performing model based on test set performance

🧠 Key Findings
Carat has the strongest positive correlation with price.

Cut, color, and clarity significantly influence the price.

Random Forest Regressor yielded the best performance with high accuracy on the test set.
