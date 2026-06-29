# 💼 Employee Salary Prediction
### VeloxCode Agency Internship | ML Project 1

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat&logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?style=flat&logo=scikit-learn)
![Google Colab](https://img.shields.io/badge/Google-Colab-yellow?style=flat&logo=googlecolab)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

---

## 🎯 What is this project?

Ever wondered how companies decide how much to pay their employees?  
This project builds an **ML-powered Salary Prediction System** that estimates employee salaries based on their **experience**, **education level**, and **job role** — just like real HR analytics tools used in top companies.

---

## 📊 Dataset Overview

| Feature | Description |
|---------|-------------|
| `Experience_Years` | Total years of work experience |
| `Education` | High School / Bachelor / Master / PhD |
| `Job_Role` | Intern / Analyst / Engineer / Manager / Director |
| `Salary` | Target variable (in USD) |

- **500 employee records** (synthetic, realistic distribution)
- No missing values
- Balanced across roles and education levels

---

## 🔍 Project Workflow

```
Raw Data → EDA → Feature Engineering → Model Training → Evaluation → Prediction
```

### 1️⃣ Exploratory Data Analysis
- Salary distribution histogram
- Experience vs Salary scatter plot
- Average salary by Education & Job Role
- Boxplots for outlier detection

### 2️⃣ Feature Engineering
- Label Encoding for categorical variables
- StandardScaler for numerical normalization
- 80/20 Train-Test Split

### 3️⃣ Models Trained & Compared

| Model | Key Strength |
|-------|-------------|
| 🔵 Linear Regression | Simple baseline, interpretable |
| 🟠 Ridge Regression | Handles multicollinearity, regularized |
| 🟢 Decision Tree | Captures non-linear patterns |

### 4️⃣ Evaluation Metrics
- **MAE** — Mean Absolute Error
- **RMSE** — Root Mean Squared Error
- **R² Score** — Goodness of fit

---

## 🏆 Results

> **Ridge Regression** achieved the best performance with the highest R² Score and lowest error — proving that regularization helps in salary prediction tasks.

---

## 🛠️ Tech Stack

- **Language:** Python 3.8+
- **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Google Colab

---

## 💡 Key Learnings

- Real-world HR data always has categorical features that need encoding
- Ridge Regression outperforms plain Linear Regression when features are correlated
- Visualizing data before modeling reveals patterns that numbers alone can't show
- Experience is the single strongest predictor of salary

---

## 👩‍💻 Author

**Maryam** — AI/ML Engineer  
🔗 [GitHub](https://github.com/saifmaryam) | 🤗 [HuggingFace](https://huggingface.co/spaces/maryam-cheema-ai)

*Completed as part of VeloxCode Agency Internship Program*
