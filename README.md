# EXPLOARTY-DATA-ANALYSIS
 # Customer Churn Data Analysis

This project explores the **Telco Customer Churn dataset** to identify factors that influence customer churn and retention.  
The analysis focuses on data cleaning, feature engineering, and exploratory data analysis (EDA) using Python.  

---

##  Table of Contents
- [About](#about)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Installation](#installation)
- [Usage](#usage)
- [Key Insights](#key-insights)
- [Technologies](#technologies)
- [Results](#results)
- [Future Work](#future-work)
- [License](#license)

---

##  About
Customer churn (the percentage of customers who stop using a company’s services) is a critical metric in industries like telecom.  
This project analyzes churn patterns based on demographics, services, and account information to help businesses **improve retention strategies**.  

---

##  Dataset
The dataset contains customer-level information such as:
- **Demographics** (Gender, SeniorCitizen, Partner, Dependents)  
- **Account Information** (Tenure, Contract Type, Payment Method, Charges)  
- **Services** (Phone, Internet, Streaming, Tech Support, etc.)  
- **Target Variable** → `Churn` (Yes/No)  

---

## Project Workflow
1. **Data Cleaning & Preprocessing**
   - Converted `TotalCharges` to numeric
   - Fixed categorical variables (`SeniorCitizen`)
   - Handled missing values and imbalance in target variable

2. **Feature Engineering**
   - Created **dummy variables** (one-hot encoding for categorical features)  
   - Applied **feature binning** (grouped tenure into intervals)  

3. **Exploratory Data Analysis (EDA)**
   - **Univariate Analysis** → distribution of individual features  
   - **Bivariate Analysis** → relationship between churn and single features  
   - **Multivariate Analysis** → combined effect of multiple features on churn  

4. **Visualization**
   - Countplots, histograms, bar charts, and trend visualizations  
   - Clear storytelling with Seaborn & Matplotlib  

---

## ⚙️ Installation
Clone the repo and install dependencies:
```bash
git clone https://github.com/your-username/churn-analysis.git
cd churn-analysis
pip install -r requirements.txt
