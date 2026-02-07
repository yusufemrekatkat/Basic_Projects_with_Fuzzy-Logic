  # 🚀 Project 1: Fuzzy Churn Prediction Engine

### 📌 Overview
This project is part of a series of 4 data science projects designed to solve real-world problems using **Fuzzy Logic**. 

Instead of traditional binary classification (Churn or Not Churn), this model treats customer behavior as a continuous spectrum. It models the uncertainty of human decision-making using mathematical membership functions.

### 🧠 The Mathematical Approach
Traditional machine learning models often act as "black boxes." In this project, I implemented a **Mamdani Inference System** to make the decision process transparent and explainable.

**Key Concepts:**
* **Fuzzification:** Transforming crisp values like $120 Monthly Charges into linguistic variables like "High."
* **Rule Base:** 7 custom-defined rules that balance customer loyalty (Tenure) against price sensitivity.
* **Defuzzification:** Using the **Centroid Method** to calculate a precise probability score.

$$z^* = \frac{\int \mu_C(z) \cdot z \, dz}{\int \mu_C(z) \, dz}$$

### 📊 Visualization
The model generates a **3D Decision Surface** that shows how the interaction between Tenure and Charges affects Churn. This allows business units to identify "Danger Zones" immediately.

### 🛠️ Tech Stack
* **Python** (Google Colab)
* **Scikit-Fuzzy** (Inference Engine)
* **Matplotlib & Numpy** (Mathematical Visualization)

### 📈 Results
The model successfully identifies high-risk customers who are in their "transition period" (Medium Tenure), where small price changes can trigger a churn decision.
