# Basic Projects with Fuzzy-Logic
A collection of 3 engineering projects utilizing Fuzzy Logic to model real-world uncertainty and complex decision systems.


# 🛡️ Sentinel: AI-Powered Fraud Detection System

**Sentinel** is an intelligent security system designed to catch credit card fraud.

Unlike old systems that use rigid rules (If/Else), Sentinel uses **Fuzzy Logic** (Artificial Intelligence). It thinks like a human security guard. It understands "Context", "Trust", and "Risk".

---

## 🚀 Project Evolution: From Simple to Smart

This project evolved in **3 Phases**. Each phase added a new "dimension" of intelligence to the system.

| Phase | Code Name | Logic | Key Feature |
| :--- | :--- | :--- | :--- |
| **01** | **The Gatekeeper** | 2D (Money + Speed) | Detects **Bot Attacks**. |
| **02** | **The Trinity** | 3D (+ Location) | Detects **Impossible Travel**. |
| **03** | **The Mastermind** | 4D (+ Trust/Age) | Understands **User Context**. |

---

## 📂 Phase 01: The Gatekeeper (2-Input)
**"The Basic Guard"**

In the beginning, the system only looked at the transaction itself.
* **Inputs:**
    1.  **Amount ($):** How much money?
    2.  **Frequency:** How fast are the transactions?
* **What it does:** It catches "Velocity Attacks". If someone tries 50 small transactions in 1 minute, it blocks them.
* **Problem:** It cannot see *where* the user is.

---

## 📂 Phase 02: The Trinity (3-Input)
**"The Location Expert"**

We added a third eye: **Location**. Now the system knows where you live.
* **New Input:**
    3.  **Distance (km):** Distance from home.
* **What it does:** It catches "Impossible Travel".
    * *Example:* You buy coffee in New York, and 10 minutes later you buy a TV in Paris.
* **Problem:** It treats a loyal customer and a thief exactly the same. It has no memory of "Trust".

---

## 📂 Phase 03: The Mastermind (4-Input)
**"The Ultimate AI"**

This is the final form. We taught the AI to understand **History** and **Trust**.
* **New Input:**
    4.  **Account Age (Days):** How long have you been a customer?
* **What it does:** It balances **Risk vs. Trust**.
    * **Scenario A:** A *New User* spends $5,000 → **BLOCKED** ⛔ (Too risky).
    * **Scenario B:** A *Loyal User* (10 Years) spends $5,000 → **ALLOWED** ✅ (Trusted).
    * **Scenario C:** A *Loyal User* acts like a Bot (High Speed) → **BLOCKED** ⛔ (Hacked Account).

---

## 🧠 How It Works (The Decision Engine)

Sentinel does not say "Yes" or "No". It calculates a precise **Risk Score (0% - 100%)**.

### **The Risk Meter:**
* **🟢 0% - 35% (Safe):** Allow transaction silently.
* **🟡 35% - 75% (Suspicious):** Ask for SMS Verification (OTP).
* **🔴 75% - 100% (Dangerous):** **BLOCK** immediately.

---

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **AI Logic:** Scikit-Fuzzy (Fuzzy Control Systems)
* **Math:** NumPy
* **Visualization:** Matplotlib & Plotly (for 3D Surface Plots)

---

> *"Security is not about blocking everyone. It is about blocking the bad guys while letting the good guys pass freely."*
