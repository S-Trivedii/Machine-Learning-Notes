
# Supervised Learning – Explained

## What is Supervised Learning?

**Supervised Learning** is a type of machine learning where a model is trained using **labeled data**.

Labeled data means:
- Each input has a **known correct output**
- The model learns a mapping from **input → output**

### Simple Definition
> Supervised learning is learning from examples **with answers** so the model can predict answers for new data.

---

## Basic Example

### House Price Prediction

| Size (sq ft) | Bedrooms | Price (₹) |
|-------------|----------|-----------|
| 800 | 2 | 40 lakh |
| 1200 | 3 | 65 lakh |
| 1500 | 4 | 90 lakh |

- **Input (X):** Size, Bedrooms  
- **Output (Y):** Price  

The model learns the relationship and predicts the price of a new house.

---

## Types of Supervised Learning

Supervised learning has **two main subtypes**:

1. Regression
2. Classification

---

## 1. Regression

### What is Regression?
Regression is used when the **output is a continuous numeric value**.

### Examples
- House price prediction
- Temperature prediction
- Salary prediction
- Stock price prediction

### Simple Mathematical Example

price = w × size + b

```yaml

- `w` → weight
- `b` → bias
- Output is a number
```

### Common Regression Algorithms
- Linear Regression
- Polynomial Regression
- Ridge & Lasso Regression
- Support Vector Regression (SVR)
- Decision Tree Regression

---

## 2. Classification

### What is Classification?
Classification is used when the **output is a category or class**.

### Examples
- Email → Spam / Not Spam
- Tumor → Benign / Malignant
- Loan → Approved / Rejected
- Student → Pass / Fail

### Example Dataset

| Email Text | Label |
|-----------|-------|
| "Win money now" | Spam |
| "Meeting at 10" | Not Spam |

### Common Classification Algorithms
- Logistic Regression
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

---

## Regression vs Classification

| Feature | Regression | Classification |
|-------|-----------|----------------|
| Output type | Continuous value | Category |
| Example | House price | Spam detection |
| Output | ₹50,00,000 | Spam / Not Spam |
| Loss functions | MSE, MAE | Cross-Entropy |

---

## Key Components of Supervised Learning

1. **Labeled Dataset (X, Y)**
2. **Model**
3. **Loss Function**
   - Measures how wrong the model is
4. **Optimization**
   - Adjusts parameters to minimize loss
5. **Generalization**
   - Model performs well on unseen data

---

## Real-World Analogy

**Teacher–Student Model**
- Teacher provides questions with answers
- Student practices and learns
- Student solves new questions independently

This is how supervised learning works.

---

## Summary

- Supervised learning uses **labeled data**
- Two main types:
  - **Regression** → predicts numbers
  - **Classification** → predicts categories
- Widely used in real-world applications like finance, healthcare, and search engines

---

## Next Topics (Optional)
- Supervised vs Unsupervised vs Reinforcement Learning
- Loss functions in detail
- Bias–Variance tradeoff
- Overfitting and Underfitting
  
