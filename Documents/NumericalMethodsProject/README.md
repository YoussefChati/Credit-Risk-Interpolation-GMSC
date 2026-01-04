# Credit Risk Modeling Using Numerical Methods  
### Probability of Default (PD) Proxy and Industry Implications

## 📌 Project Overview

This project explores **credit risk modeling** through the lens of **numerical methods**, treating the **Probability of Default (PD)** as a continuous risk index derived from a small set of financial variables.

Instead of starting directly with machine learning, the project focuses on **numerical interpolation techniques** to understand how risk can be approximated, interpreted, and validated. This approach reflects an academic foundation while remaining closely connected to **real-world banking, insurance, and FinTech practices**.

The project serves as a **bridge between numerical analysis and industrial credit risk systems**.

---

## 🎯 Objectives

- Construct a **continuous credit risk index** as a proxy for PD  
- Apply and compare multiple **numerical interpolation methods**  
- Analyze the stability and limitations of each method  
- Evaluate numerical risk estimates against real default outcomes  
- Connect academic modeling choices to **industry credit decision systems**

---

## 📊 Dataset

### Give Me Some Credit (GMSC)

The dataset used is the **Give Me Some Credit (GMSC)** dataset, a well-known benchmark in credit risk research.

**Why this dataset was chosen:**
- Contains real-world consumer credit data  
- Includes a binary default indicator  
- Widely used in academic and professional credit risk analysis  
- Suitable for controlled experiments with limited variables  

---

## 🧮 Selected Variables

To remain aligned with a **Numerical Methods** framework, the model intentionally uses a **small and interpretable subset of variables**, such as:

- Credit utilization ratio  
- Number of severe past-due payments (e.g., 90+ days late)  
- Debt ratio  

These variables are commonly used in real credit scoring systems and allow meaningful risk interpretation without unnecessary complexity.

---

## 🧠 Methodology

### 1. Data Preprocessing
- Normalization of all input variables  
- Ensuring comparable scales for numerical computation  

### 2. Risk Index Construction
- Aggregation of normalized variables into a single continuous risk measure  
- Higher values correspond to higher estimated default risk  

### 3. Numerical Interpolation Methods
The following numerical techniques were implemented and compared:

#### • Linear Interpolation
- Simple and stable
- Easy to interpret
- Limited in capturing non-linear risk behavior

#### • Polynomial (Lagrange) Interpolation
- Captures non-linear patterns
- More flexible but sensitive to outliers
- Can introduce numerical instability

---

## 🔍 Evaluation and Comparison

The numerical risk indices were evaluated against the actual default indicator in the dataset to assess:

- Risk separation between defaulters and non-defaulters  
- Sensitivity of each method to extreme values  
- Stability and interpretability of risk estimates  

### Key Observations
- Increased mathematical complexity does not guarantee better risk estimation  
- Linear methods offer stability but lack expressiveness  
- Polynomial methods capture non-linearity but may overfit  

These trade-offs mirror challenges faced in **industrial credit risk modeling**.

---

## 🏦 Industry Perspective

### Numerical Methods vs Real-World PD Models

In real banking and FinTech environments:

- Credit risk is expressed as a **probability**, not only as a score  
- Models must be stable, explainable, and regulator-compliant  
- Decision thresholds are chosen based on risk appetite and business impact  

While numerical methods provide strong interpretability and transparency, they lack the probabilistic calibration required for operational credit decisions.

---

## ✅ Why Numerical Methods Still Matter

Despite their limitations, numerical approaches are valuable because they:

- Provide transparent and explainable risk estimates  
- Serve as educational and conceptual foundations  
- Act as baseline models for comparison and validation  
- Help build intuition before deploying statistical or ML-based models  

---

## 📈 Key Takeaways

- Credit risk can be meaningfully explored as a **numerical problem**  
- Model simplicity and stability often outweigh mathematical complexity  
- Numerical risk indices are useful as **baselines**, not final decision tools  
- Industrial credit systems require probabilistic PD models built on top of such foundations  

---

## 🔮 Future Work

This project lays the groundwork for industry-level extensions, including:

- Logistic regression–based PD modeling  
- Model validation and stability analysis  
- Decision threshold optimization  
- Business impact simulation  
- Credit scorecard and loan decision systems  

These extensions represent the transition from academic modeling to **real-world banking and FinTech applications**.

---

## 🧑‍💻 Author Notes

This project was developed as part of a **Numerical Methods** course and later refined to align with **industry credit risk practices**.  
It reflects a deliberate progression from mathematical modeling to applied financial analytics.

---

## ⭐ Why This Project Matters

This repository demonstrates:
- Strong numerical and analytical foundations  
- Clear understanding of credit risk concepts  
- Ability to connect academic methods with industry use cases  
- Readiness to extend models toward real decision systems  

