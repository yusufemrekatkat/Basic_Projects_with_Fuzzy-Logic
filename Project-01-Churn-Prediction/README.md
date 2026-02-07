# 📡 Project 01: Customer Churn Intelligence
### *Mathematical Engineering Approach to Behavioral Uncertainty*

This project documents the development of a high-precision **Churn Prediction Engine** built on the principles of **Fuzzy Logic**. Unlike traditional binary models, this system captures the continuous nature of customer sentiment, identifying risk before it becomes an exit.




## 🛠 The Evolution: From 2D to 4D
The repository tracks the transition from basic logic to a complex, multi-dimensional decision engine, showcasing how mathematical granularity improves decision-making.

| Phase | Complexity | Inputs | Mathematical Goal |
| :--- | :--- | :--- | :--- |
| **01** | **Foundation** | Tenure, Charges | Basic price sensitivity modeling. |
| **02** | **Advanced** | + Support Calls | Capturing the "Frustration" factor. |
| **03** | **Elite (4D)** | + Satisfaction Score | Merging objective data with subjective emotion. |




## 🧠 Core Methodology
As a **Mathematical Engineer**, I designed this system to prioritize **explainability** and **mathematical continuity**.

### 1. Trapezoidal Membership Functions (Saturation)
I utilized **Trapezoidal MFs** at the boundaries to model **Saturation Points**. 
* *Insight:* Beyond a certain monthly bill or support call count, the membership reaches a maximum value of $1.0$, accurately representing that the customer’s sensitivity has plateaued.

### 2. The Centroid Defuzzification
To calculate the final crisp "Risk Score," the system finds the **Center of Gravity** of all activated rules:
$$z^* = \frac{\int \mu_C(z) \cdot z \, dz}{\int \mu_C(z) \, dz}$$





## 📊 4D Dimensionality Slicing
Visualizing a 4-input system requires **Slicing**. By holding "Emotional Satisfaction" and "Support Frequency" at their neutral states, we generate a **3D Decision Surface** to analyze the interaction between **Loyalty (Tenure)** and **Cost (Charges)**.

* **Interactive Feature:** The project includes a rotatable **Plotly** model, allowing stakeholders to visually inspect the "Risk Cliffs"—the specific thresholds where customer churn becomes critical.





## 🎯 Strategic Business Impact
* **Proactive Intervention:** Identify "Grey Zone" customers with a $60-70\%$ risk score before they officially churn.
* **Capital Efficiency:** Optimize retention budgets by focusing only on segments with high-risk peaks.
* **Explainable AI:** Every decision is tied to a human-readable rule set, making the model trustworthy for stakeholders.
