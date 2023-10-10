# House-Price-Prediction--AmeyThore-Machine_Learning
# Linear Regression House Price Predictor
This project builds a linear regression model to predict house prices based on features in the house_prices.csv dataset.

Files
house_prices.ipynb: Jupyter notebook containing the Python code to load data, train a LinearRegression model, and evaluate performance.
house_prices.csv: Input dataset containing features and labels for houses and their prices.
Usage
The main modeling steps are:

Load house_prices.csv into a Pandas DataFrame
Drop any non-numeric columns
Split data into X (features) and y (target Price)
Split data into train and test sets
Fit a LinearRegression model on the training data
Make predictions on the test data
Evaluate model performance using MSE and R-squared metrics
Key libraries used include Pandas, NumPy, sklearn for modeling, and Matplotlib for any visualization.

Notes
Make sure all features in X are numeric. Objects or strings will cause errors.
Categorical variables like neighborhood may need one-hot encoding.
Standardization/normalization may help with modeling.
Cross-validate hyperparams and try other models like Lasso, Ridge, etc.
Additional feature engineering can improve performance.
