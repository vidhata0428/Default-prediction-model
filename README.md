# Loan Default Prediction – Give Me Some Credit Dataset

This project focuses on building a machine learning model to predict the likelihood of loan default using the "Give Me Some Credit" dataset.

## 📁 Dataset
- Source: [Give Me Some Credit – Public Dataset](https://raw.githubusercontent.com/venkatareddykonasani/Datasets/master/Give%20me%20some%20Credit/cs-training.csv)
- Key features include:
  - SeriousDlqin2yrs (Target)
  - RevolvingUtilizationOfUnsecuredLines
  - age
  - NumberOfTime30-59DaysPastDueNotWorse
  - DebtRatio
  - MonthlyIncome
  - NumberOfOpenCreditLinesAndLoans
  - NumberOfTimes90DaysLate
  - NumberRealEstateLoansOrLines
  - NumberOfTime60-89DaysPastDueNotWorse
  - NumberOfDependents

## 🔄 Data Processing & Analysis
- **Data Import:** Loaded CSV file using `pandas`.
- **Exploratory Steps:**
  - Printed shape, data types, and column names using `.info()` and `.dtypes`.
  - Investigated target variable `SeriousDlqin2yrs` with `.value_counts()`.
- **Variable Categorization:**
  - Categorical: Region, Gender, Job Type, Card Status
  - Discrete: Number of Loans, Number of Dependents, Late Payments
  - Continuous: Monthly Income, Debt Ratio

## 🔍 Feature Insights
- **Debt Ratio:** Computed as Debt ÷ Income (e.g., 25000 ÷ 100000 = 0.25)
- **Outlier Detection:** Noted outliers in `DebtRatio` above 1
- **Monthly Income:** Quantile values examined (10th, 20th, 90th, 100th percentiles)

## ⚙️ Technologies Used
- Python
- Pandas

## 🚧 Project Status
- Currently focused on data exploration and variable analysis
- Model training steps are not included in the current version of the notebook

---

## 👤 Author
**Vidhata Tiwari**  
B.Tech in Information Technology  

