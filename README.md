# 📈 Gold Price Prediction using Machine Learning  

This project predicts **Gold Prices (GLD index)** using **Machine Learning** techniques.  
By analyzing financial indicators, we train a **Random Forest Regressor** to forecast gold prices with high accuracy.  

---

## 🚀 Features
- Preprocesses and cleans dataset (`gld_price_data.csv`)  
- Splits data into **train (80%)** and **test (20%)** sets  
- Trains a **Random Forest Regressor (100 trees)**  
- Evaluates performance using **R² Score**  
- Visualizes **Actual vs Predicted Gold Prices**  

---

## 📂 Dataset
- File: `gld_price_data.csv`  
- Contains financial features + **GLD (Gold Price)** column  
- **Target Variable**: `GLD`  
- **Date column** is dropped since it does not affect prediction  

---

## ⚙️ Workflow
1. **Data Collection & Cleaning** → Load dataset, remove missing values  
2. **Feature Engineering** → Separate features (`X`) and target (`Y`)  
3. **Train-Test Split** → 80% training data, 20% testing data  
4. **Model Training** → Apply **Random Forest Regressor (n_estimators=100)**  
5. **Evaluation** → Calculate **R² Score**  
6. **Visualization** → Plot **Actual vs Predicted Prices**  

---

## 🧠 Machine Learning Model
- **Algorithm**: Random Forest Regressor  
- **Why Random Forest?**  
  - Handles non-linear data well  
  - Reduces overfitting compared to single decision trees  
  - Provides strong accuracy for regression tasks  

---

## 📊 Results
- **Metric Used**: R² Score  
- Achieved **~0.98 R²** → Excellent performance 🎯  
- Visualization shows predicted values closely follow actual gold prices  

---

## 🔧 Technologies Used
- Python  
- Pandas, NumPy → Data handling  
- Matplotlib, Seaborn → Visualization  
- scikit-learn → Machine Learning  
