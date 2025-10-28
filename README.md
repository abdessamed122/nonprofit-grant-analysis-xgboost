# 🎯 Nonprofit Grant Success Predictor

> **AI-powered analysis using XGBoost to identify the most important factors influencing how nonprofits win grants.**

---

## 🧠 Overview

This project analyzes synthetic nonprofit and grant data to uncover what drives **grant success and impact efficiency** among nonprofits.  
By training an **XGBoost regression model**, we identify the most influential organizational and financial characteristics that correlate with high impact efficiency — a proxy for effective grant utilization.

---

## 🚀 Key Features

- 🧩 **Comprehensive Data Integration:** Combines multiple nonprofit datasets (quality, anomalies, grants).
- 📊 **Machine Learning Insights:** Trains an XGBoost model to predict `impact_efficiency`.
- 🔍 **Feature Importance Analysis:** Identifies the top features that determine how nonprofits succeed in winning and using grants.
- ⚙️ **Data Preprocessing:** Handles missing values and encodes categorical variables automatically.
- 📈 **Visual Analytics:** Generates feature importance charts and performance metrics.

---

## 🧰 Tech Stack

- **Python 3.10+**
- **XGBoost**
- **Scikit-learn**
- **Pandas / NumPy**
- **Matplotlib**
- **Google Colab / Jupyter Notebook**

---

## 📂 Dataset

The dataset used is from Kaggle:

> [Nonprofit Organizations and Grants (Synthetic Data)](https://www.kaggle.com/datasets/poojayakkala/nonprofit-organizations-and-grants-synthetic-data)

**Contains:**
- 240,585 nonprofits  
- 37 columns (organizational, financial, impact, and risk indicators)  
- Key fields:  
  - `impact_efficiency` → target variable  
  - `confidence_score`, `data_quality`, `has_financial`, `has_mission`, `risk_level`, etc.

---

## ⚙️ How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/nonprofit-grant-success-predictor.git
   cd nonprofit-grant-success-predictor
