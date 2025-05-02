# 📘 What is Training Set Error?

**Training set error** refers to the **error a machine learning model makes on the data it was trained on**. It shows **how well the model has learned to fit the training data**, but **not necessarily how well it will perform on new, unseen data**.

---

## 📌 In Simple Terms:

- **Low training error** means the model is doing well on the data it has already seen.
- **High training error** means the model hasn’t even learned the training data properly (i.e., it’s underfitting).

---

## 🔢 Example

### 🎯 Task:

Predict house price based on square footage.

### 🧮 Training Data (X = size in sq.ft, y = price in $1000s):

| X (sq.ft) | y (Price) |
| --------- | --------- |
| 1000      | 200       |
| 1500      | 300       |
| 2000      | 400       |

Now you train a **Linear Regression model** on this data.

Suppose after training, your model predicts:

| X (sq.ft) | Actual y | Predicted y | Error (y - predicted y) |
| --------- | -------- | ----------- | ----------------------- |
| 1000      | 200      | 210         | -10                     |
| 1500      | 300      | 290         | +10                     |
| 2000      | 400      | 395         | +5                      |

### 🧮 Training Set Error Calculation:

If we use **Mean Squared Error (MSE)**:

\[
\text{MSE} = \frac{(-10)^2 + (10)^2 + (5)^2}{3} = \frac{100 + 100 + 25}{3} = \frac{225}{3} = 75
\]

---

## 💡 Key Points:

- A **low training error** (e.g., MSE = 5) could mean the model is fitting the data well.
- But **only looking at training error is misleading**, because it says nothing about performance on unseen data (that's where **validation/test error** comes in).
