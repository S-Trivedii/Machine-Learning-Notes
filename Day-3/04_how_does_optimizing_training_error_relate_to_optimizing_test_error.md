# 📘 How Does Optimizing Training Error Relate to Optimizing Test Error?

This document explains the relationship between minimizing training error and the effect it has on test error, with a focus on generalization in machine learning.

---

## ✅ Optimizing Training Error vs Optimizing Test Error

| Aspect             | Training Error                               | Test Error                               |
| ------------------ | -------------------------------------------- | ---------------------------------------- |
| **What is it?**    | Error on the **training data**               | Error on **unseen/test data**            |
| **Goal**           | Make the model learn from given data         | Ensure the model generalizes to new data |
| **How it’s used?** | Directly minimized by the learning algorithm | Evaluated to measure model performance   |

---

## 🎯 The Key Relationship

> **Optimizing training error helps reduce test error — but only up to a point.**

- In the beginning, as training error decreases, **test error also decreases**.
- But if you reduce training error **too much**, the model may **overfit** — meaning it memorizes the training data and fails on test data.

---

## 📈 Typical Error Curve

When you plot training and test error over time (or complexity), you often see:

- 🔽 **Training Error**: Keeps decreasing.
- 🔽➡️🔼 **Test Error**: Decreases at first, then increases (due to overfitting).

```text
     Test Error
         ^
         |\
         | \
         |  \       <- overfitting zone
         |   \_____
         |         \_____
         |____________________> Model Complexity

---

## 🧠 Key Insight

> **Good models aim for low test error, not just low training error.**

So while you **optimize training error using optimization techniques**, you should always:

- Use **cross-validation**
- Monitor **validation/test error**
- Apply **regularization** or **early stopping** if overfitting occurs
```
