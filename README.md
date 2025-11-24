# Telco Customer Churn Analysis 📉

A complete end-to-end data analysis project focused on understanding customer churn, identifying risk factors, and generating actionable insights for Customer Success and Product teams.

This project uses the **Telco Customer Churn dataset** (Kaggle) and includes:
- data cleaning & preparation  
- exploratory data analysis (EDA)  
- churn segmentation  
- creation of actionable insights  
- Tableau dashboard (forthcoming)

---

## 📂 Project Structure

telco-churn-analysis/
│
├── data/
│   ├── raw/                 # original dataset (Kaggle CSV)
│   └── processed/           # cleaned dataset used for analysis
│
├── notebooks/
│   ├── 01_data_preparation.ipynb
│   └── 02_eda.ipynb
│
├── dashboard/
│   └── (Tableau dashboard will be placed here)
│
├── README.md
└── .gitignore
---

## 🧹 1. Data Preparation

Notebook: `notebooks/01_data_preparation.ipynb`

Steps:
- load raw dataset  
- convert `TotalCharges` to numeric  
- impute missing values  
- engineer `ServicesCount`  
- export cleaned dataset into `data/processed/`  

---

## 🔍 2. Exploratory Data Analysis (EDA)

Notebook: `notebooks/02_eda.ipynb`

Key topics:
- churn rate analysis  
- churn by contract type  
- effect of monthly charges  
- service usage patterns  
- early churn indicators  

### 🧠 Key Insights  
- **Month-to-month contracts have the highest churn (~43%)**  
- **High-charge customers are more churn-sensitive**  
- **Early-tenure customers (0–6 months) are most likely to churn**  
- **Longer contracts (12/24 months) = very strong retention**  

---

## 📊 3. Tableau Dashboard (Coming Soon)

Planned dashboard views:
- Overview KPIs  
- Churn segmentation  
- Tenure buckets  
- Monthly charges vs churn  
- Service usage & risk indicators  

Will be hosted via **Tableau Public** and linked here.

---

## 🚀 Technologies Used
- Python (pandas, numpy, seaborn, matplotlib)  
- Jupyter Notebook  
- Tableau Public  
- Git + GitHub  

