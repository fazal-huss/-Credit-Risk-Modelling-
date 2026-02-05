# Credit Risk Modelling – PD & Expected Loss Framework

## 📌 Project Overview
This project presents an **end-to-end Credit Risk Analytics framework** designed to
estimate borrower default risk and portfolio-level credit losses using real-world
retail banking data.

The project simulates how **banks and financial institutions** assess credit risk
using Probability of Default (PD), risk segmentation, and Expected Loss (EL).

---

## 🎯 Business Problem
Financial institutions need to:
- Identify high-risk borrowers
- Quantify potential credit losses
- Support risk-based pricing and credit approval decisions

This project addresses these needs by building a **data-driven, interpretable credit
risk model** aligned with industry practices.

---

## 🧠 Key Concepts Used
- Probability of Default (PD)
- Risk Segmentation (PD-based cut-offs)
- Expected Loss (EL = PD × LGD × EAD)
- Logistic Regression (interpretable risk modeling)

---

## 🗂 Dataset
- **German Credit Risk Dataset**
- Contains demographic, financial, and behavioral attributes of borrowers
- Public dataset commonly used in credit risk research

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook
- Logistic Regression
- Git & GitHub

---

## 🔍 Project Workflow

### 1️⃣ Data Understanding
- Examined dataset structure and variable meanings
- Identified target variable for default risk

### 2️⃣ Exploratory Data Analysis (EDA)
- Analyzed borrower characteristics vs default behavior
- Identified key risk drivers such as loan duration, account balances, and housing status

### 3️⃣ Feature Engineering
- Handled missing values using risk-aware strategies
- Encoded categorical variables
- Standardized numerical features

### 4️⃣ Probability of Default (PD) Modeling
- Built Logistic Regression model
- Achieved **AUC ≈ 0.76** on test data
- Ensured interpretability and stability

### 5️⃣ Risk Segmentation & Business Validation
- Segmented borrowers into PD-based risk bands
- Validated monotonic increase in default rates across bands
- Proposed credit policy actions

### 6️⃣ Expected Loss (EL) Estimation
- Estimated Expected Loss using **PD × LGD × EAD**
- Identified high-risk borrowers contributing disproportionately to portfolio loss
- Demonstrated portfolio-level risk insights

---

<img width="2752" height="1536" alt="unnamed (1)" src="https://github.com/user-attachments/assets/1d47370f-ba65-4ddb-acbd-e7500bcf0c5a" />


## 📊 Key Results
- Strong model discrimination with **AUC ≈ 0.76**
- Clear separation of default risk across risk bands
- High-risk segments contribute the majority of Expected Loss
- Outputs aligned with real-world credit risk decision-making

---

## 💼 Business Applications
- Risk-based loan approval
- Differential pricing strategies
- Portfolio risk monitoring
- Credit policy formulation

---

## 📁 Project Files
- `notebooks/` → Step-by-step analysis and modeling
- `data/` → Raw and processed datasets
- `requirements.txt` → Python dependencies

---

## 👤 Author
**Mohd Fazal Hussain**  
MSc Banking & Financial Analytics  
Aspiring Data / Risk Analyst
