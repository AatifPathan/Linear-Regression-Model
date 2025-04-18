# 📊 Simple Linear Regression: Salary Predictor

This project demonstrates a basic **Simple Linear Regression** model to predict an employee's **salary** based on their **years of experience** using Python and `scikit-learn`.

---

## 📌 Project Overview

- **Goal**: Predict the salary of an employee using years of experience as input.
- **Dataset Source**: [YBI Foundation GitHub - Salary Data](https://github.com/ybifoundation/Dataset/raw/main/Salary%20Data.csv)

---

## 📁 Files

- `Salary Experience Predictor.ipynb`: Jupyter notebook containing the full implementation.
- `README.md`: Project documentation (you are here!).

---

## 🛠️ Tools & Libraries Used

- Python
- Pandas
- Scikit-learn

---

## 🔄 Workflow

1. Load dataset using `pandas`
2. Define features (`Experience Years`) and target (`Salary`)
3. Split data into training and testing sets (70/30)
4. Train the `LinearRegression` model
5. Predict salary values on test data
6. Evaluate using:
   - Mean Absolute Error (MAE)
   - Mean Absolute Percentage Error (MAPE)
   - Mean Squared Error (MSE)

---

## 📈 Model Summary

- **Intercept (b₀)**: Derived after training the model
- **Coefficient (b₁)**: Shows the increase in salary per additional year of experience
- **Prediction**: Model outputs salary predictions for test data

---
