# Customer-Churn-Project
This project focuses on predicting bank customer churn using supervised machine learning models. Customer retention is generally more cost-effective than customer acquisition. By identifying customers who are likely to leave (churn), the bank can proactively implement targeted retention strategies.

The analysis utilizes a dataset containing 10,000 customer records, including demographic information (e.g., Age, Geography, Gender) and financial details (e.g., Credit Score, Balance, Number of Products). Through exploratory data analysis, the project identifies key churn indicators, highlighting that older customers and those with higher balances may be at a greater risk of churning.

## 📊 Dataset
The dataset used in this project is the **Predicting Churn for Bank Customers** dataset, originally sourced from [Kaggle](https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers). 

It contains 10,000 customer records with 14 features, including:
* **Demographics:** Age, Geography (France, Spain, Germany), Gender.
* **Financials:** Credit Score, Balance, Estimated Salary.
* **Engagement:** Tenure, Number of Products, Has Credit Card, Is Active Member.
* **Target Variable:** `Exited` (1 = Churned, 0 = Retained).

## 🔍 Key Insights from Exploratory Data Analysis (EDA)
During the initial analysis, several key trends emerged regarding customer churn:
* **Class Imbalance:** The dataset is imbalanced, with approximately 20% of customers churning and 80% remaining.
* **Age Factor:** Age is a strong indicator of churn; older customers show a higher likelihood of leaving the bank.
* **Balance:** Interestingly, customers with higher account balances appear to be at a greater risk of churn, potentially indicating that they feel underserved.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Libraries:** * Data Manipulation: `pandas`, `numpy`
    * Data Visualization: `matplotlib`, `seaborn`
    * Machine Learning: `scikit-learn` *(Add other ML libraries here if you used them, like XGBoost or LightGBM)*

## 📝 Project Structure
customer-churn-prediction/
│
├── data/
│   └── bank.data.csv           <- The raw dataset 
│
├── notebooks/
│   └── Bank_Customer_Churn_Project.ipynb 
│
├── README.md                   <- The main documentation file
├── requirements.txt            <- List of dependencies (e.g., pandas, numpy, scikit-learn)
└── .gitignore                  
