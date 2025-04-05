# 📊 KNN Regression from Scratch with Manhattan Distance

This project is a pure Python implementation of the **K-Nearest Neighbors (KNN)** algorithm for **regression**, using the **Manhattan distance** as the metric — without relying on any machine learning libraries such as `scikit-learn`.

---

## 🧠 About the Project

The goal is to predict future values (e.g., stock closing prices) using a basic regression technique. This implementation is educational and designed to show how KNN works under the hood.

---

## 📁 Dataset Used

The dataset contains two main features:

- `Prev Close`: Previous closing price
- `Close`: Actual closing price

You can replace this dataset with any other suitable regression dataset.

---

## ⚙️ Algorithm Workflow

1. Load and preprocess the dataset
2. Split data into training and testing sets (80/20)
3. Implement KNN with:
   - **Distance de Manhattan**:
     \[
     D(x, y) = \sum |x_i - y_i|
     \]
4. Predict values for test set
5. Evaluate performance using:
   - MAE (Mean Absolute Error)
   - MSE (Mean Squared Error)
   - R² Score

---
