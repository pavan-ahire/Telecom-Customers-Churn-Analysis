# 📊 Telecom Customer Churn Analysis using Power BI

## 📘 Project Overview  
This project analyzes telecom customer data to identify key factors contributing to customer churn.  
Using **Microsoft Power BI**, an interactive dashboard was developed to visualize churn trends, customer behavior, and revenue impact.  
The dataset includes information on **7,042 customers**, covering demographics, services, contracts, and billing details.

---

## 🎯 Business Objective  
To analyze and identify the factors leading to customer churn and to provide actionable insights that help improve retention, customer satisfaction, and overall business performance.

---

## 🧩 Problem Statement  
Customer churn is a critical challenge for telecom companies, directly impacting revenue and customer base growth.  
The objective of this project is to understand **why customers leave**, determine which segments are most affected, and provide data-driven recommendations to reduce churn.

---

## 🗂️ Dataset Information  
The dataset includes the following key features:

| Column Name | Description |
|--------------|-------------|
| customerID | Unique identifier for each customer |
| gender | Male / Female |
| SeniorCitizen | Indicates if the customer is a senior citizen (1 = Yes, 0 = No) |
| Partner | Whether the customer has a partner (Yes / No) |
| Dependents | Whether the customer has dependents (Yes / No) |
| tenure | Number of months the customer has stayed with the company |
| PhoneService | Whether the customer has phone service (Yes / No) |
| MultipleLines | Indicates if the customer has multiple phone lines |
| InternetService | Type of internet connection (DSL / Fiber optic / No internet) |
| OnlineSecurity | Subscribed to online security service |
| OnlineBackup | Subscribed to online backup service |
| DeviceProtection | Subscribed to device protection service |
| TechSupport | Subscribed to technical support |
| StreamingTV | Subscribed to TV streaming service |
| StreamingMovies | Subscribed to movie streaming service |
| Contract | Type of contract (Month-to-month / One year / Two year) |
| PaperlessBilling | Whether billing is paperless (Yes / No) |
| PaymentMethod | Method of payment used |
| MonthlyCharges | Monthly amount charged to the customer |
| TotalCharges | Total amount charged to date |
| Churn | Indicates if the customer has churned (Yes / No) |

---

## 🧹 Data Preparation Steps  
1. Removed duplicate and missing entries.  
2. Converted `TotalCharges` column to numeric format.  
3. Created calculated columns like **Churn Rate**, **Tenure Groups**, and **Number of Services**.  
4. Cleaned and formatted the dataset for Power BI visualization.  

---

## 📊 Key Insights  
- Customers with **month-to-month contracts** have the highest churn rate.  
- **Higher monthly charges** are linked with greater churn probability.  
- **Fiber optic users** tend to churn more compared to DSL users.  
- **Senior citizens** and customers **without dependents or partners** are more likely to leave.  
- Customers with **longer tenure** show higher loyalty.  

---

## 💡 Recommendations  
- Offer **discounts and loyalty rewards** to long-term customers.  
- Improve **technical support** and **service quality** for fiber optic users.  
- Encourage **long-term contracts** with promotional benefits.  
- Provide **customized plans** for senior citizens and low-tenure customers.  
- Use **predictive analytics** to identify at-risk customers early.  

---

## 🧭 Tools and Technologies Used  
- **Microsoft Power BI** – Data visualization and analysis  
- **Microsoft Excel / CSV** – Data cleaning and preprocessing  
- **DAX (Data Analysis Expressions)** – Calculations and KPI creation  

---

## 📈 Dashboard Highlights  
- Overview of total customers and churn percentage  
- Churn distribution by gender, senior citizens, and contract type  
- Analysis of monthly charges vs. tenure  
- Comparison of churn behavior by internet and phone services  
- Revenue impact of retained vs. lost customers  


![Dashboard Preview](https://github.com/pavan-ahire/Telecom-Customers-Churn-Analysis/blob/main/telecom%20customer%20churn%20analysis/Asset/tele%20customer%20churn_page-0005.jpg)

---

## 📘 Conclusion  
The analysis reveals that customer churn is mainly influenced by **contract type, service quality, and monthly charges**.  
Focusing on improving customer experience, providing flexible plans, and targeting high-risk segments can significantly reduce churn and improve business sustainability.

---

## 👤 Author  
**Pavan Ahire**  
Data Analyst | Power BI Enthusiast  
📧 *[Add your email or LinkedIn profile]*  

---

