# ML-Gold-Price-Prediction
This project focuses on predicting the price of Gold (GLD index) using Machine Learning techniques. By analyzing financial indicators, we use a Random Forest Regressor to model and forecast gold prices.

🚀 Features

Preprocessing of financial dataset (gld_price_data.csv)

Train-Test Split (80-20)

Random Forest Regressor model for prediction

Evaluation using R² Score

Visualization of Actual vs Predicted Gold Prices

📂 Dataset

File used: gld_price_data.csv

Contains multiple financial features along with the GLD (Gold Price) column.

Target variable: GLD (Gold Price).

The Date column is dropped since it does not contribute to prediction.

⚙️ Workflow

Data Collection & Cleaning

Load dataset and remove missing values.

Feature Engineering

Separate features (X) and target (Y).

Train-Test Split

80% training data, 20% testing data.

Model Training

Apply Random Forest Regressor (100 trees).

Evaluation

Evaluate using R² Score.

Visualization

Plot Actual vs Predicted Gold Prices.

🧠 Machine Learning Model

Algorithm: Random Forest Regressor

Why Random Forest?

Handles non-linear data well

Reduces overfitting compared to single decision trees

Provides high accuracy for regression tasks

📊 Results

Evaluation Metric: R² Score

A high R² Score (~0.98+) indicates excellent performance.

Visualization clearly shows predicted values closely following actual gold prices.

🔧 Technologies Used

Python

Pandas, NumPy → Data handling

Matplotlib, Seaborn → Visualization

scikit-learn → Machine Learning
