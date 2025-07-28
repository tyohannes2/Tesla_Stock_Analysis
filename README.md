📈 Tesla Stock Price Prediction with Linear Regression
This project uses historical stock data for Tesla (TSLA) and applies a Linear Regression model to predict closing stock prices based on Open and High prices. It also evaluates model performance and visualizes prediction accuracy.

🔧 Tools and Libraries Used
Python

pandas

numpy

matplotlib / seaborn

scikit-learn (LinearRegression, train_test_split, mean_squared_error, r2_score)

yfinance (for live stock data)

📊 Project Workflow
Data Collection
Collected Tesla stock data using the yfinance library from January 2015 to July 2025.

Data Preparation

Cleaned the dataset

Selected relevant features: Open and High to predict Close

Modeling

Split the dataset into training and testing sets (80/20)

Trained a Linear Regression model

Evaluation

Calculated Mean Squared Error (MSE)

Measured R² Score to assess accuracy

Visualization

Tesla Stock Price, 2019-2024
Tesla Stock Price with Moving Prices
Plotted actual vs. predicted closing prices

🧪 Results
Mean Squared Error: 1024.37

R² Score: 0.699
(Shows a moderate correlation between predicted and actual values)
