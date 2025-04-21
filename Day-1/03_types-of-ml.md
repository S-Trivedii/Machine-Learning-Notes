### Types of Machine Learning

✅ Types of Machine Learning (based on learning setup):

- Supervised Learning (you get both input X and output Y)

- Unsupervised Learning (you only get X, and must find patterns or structure)

- Reinforcement Learning (learning through trial and error using rewards)

- Semi-supervised Learning (a mix of labeled and unlabeled data)

- Self-supervised Learning (using data to generate its own labels)

---

## Supervised Learning

You give the model:

- **Inputs** (x) – like a photo or person info

- **Correct outputs** (y) – like a label (cat/dog) or a value (age)

The model learns the connection between **x** and **y**. So the main idea for supervised learning is learn some sort of relationship between input and output

```bash
Dn = {(x(1),y(1)),…,(x(n),y(n))}
```

where Dn is data, and x represent input and y represent output

---

### 🔍 Supervised Learning Subtypes

1. 🎯 **Classification:**
   - The goal is to **put things into categories.**
   - Example: Given an email (x), decide if it’s spam or not (y)
   - You train it using data like:
   ```bash
   {(email1, spam), (email2, not spam), ...}
   { email ∈ spam/not-spam }
   ```

🟢 **Binary classification:**

- Only **two options** for y (like yes/no)

🔵 **Multi-class classification:**

- **More than two options** (like classifying animals as dog, cat, bird)

2. **Regression**
   - **Output:** Continuous (real-valued numbers)
   - **Goal:** Predict a numeric value
   - **Examples:**
     - Predicting house prices
     - Estimating someone's age
     - Forecasting temperature

More on regression later

## Final Goal of Supervised Learning:

Once trained, the model should be able to look at **a new x and predict the correct y** — even if it hasn’t seen that exact example before.
