# Tesla Stock Price Prediction with Linear Regression

This project uses **historical stock data** for Tesla (TSLA) and applies a **Linear Regression model** to predict closing stock prices based on Open and High prices. It also evaluates model performance and visualizes prediction accuracy.

---

## Tools and Libraries Used

- Python
- pandas
- numpy
- matplotlib / seaborn
- scikit-learn (LinearRegression, train_test_split, mean_squared_error, r2_score)
- yfinance (for live stock data)

---

## Project Workflow

1. **Data Collection**  
   Collected Tesla stock data using the `yfinance` library from January 2015 to July 2025.

2. **Data Preparation**  
   - Cleaned the dataset  
   - Selected relevant features: `Open` and `High` to predict `Close`

3. **Modeling**  
   - Split the dataset into training and testing sets (80/20)  
   - Trained a Linear Regression model

4. **Evaluation**  
   - Calculated Mean Squared Error (MSE)  
   - Measured R² Score to assess accuracy

5. **Visualization**  
   - [Tesla Stock Closing Price, 2019 - 2024](https://github.com/tyohannes2/Tesla_Stock_Analysis/blob/main/Tesla%20Stock%20Closing%20Price%2C%202019-2024.png)
   - [Tesla Stock Price with Moving Averages](https://github.com/tyohannes2/Tesla_Stock_Analysis/blob/main/Tesla%20Stock%20Price%20with%20Moving%20Averages.png)
   - [Plotted actual vs. predicted closing prices](https://github.com/tyohannes2/Tesla_Stock_Analysis/blob/main/Actual%20versus%20Predicted%20Tesla%20Stock%20Prices.png)

---

## Results

- **Mean Squared Error**: `1024.37`  
- **R² Score**: `0.699`  
  _Shows a moderate correlation between predicted and actual values_

---
## Author

**Thomas Yohannes**  
- Master’s in Epidemiology  
- Data science enthusiast with interest in sports, healthcare, and finance analytics  
- [LinkedIn](https://www.linkedin.com/in/thomas-yohannes-mph-b55940135/)
