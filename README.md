# Customer Churn Analysis – Power BI Dashboard

## Overview
This project provides an in-depth analysis of customer churn patterns in the telecom industry using Power BI.  
The dashboard highlights **customer demographics, account details, subscriptions, and key behavioral drivers** influencing churn, enabling data-driven retention strategies.

---

## Tools & Technologies 🛠️
- **Power BI** – Interactive dashboard & visualizations  
- **Excel** – Data preprocessing & cleaning  
- **Dataset** – Customer churn dataset (`02 Churn-Dataset.xlsx`)  

---

## Dataset Description
The dataset contains detailed customer information covering demographics, account details, services, and churn status.  

| Column Name      | Datatype | Description |
| :---             | :---     | :--- |
| CustomerID       | Str      | Unique identifier for each customer |
| Gender           | Str      | Gender (Male/Female) |
| SeniorCitizen    | Int      | Indicates senior citizen (1 = Yes, 0 = No) |
| Partner          | Str      | Whether the customer has a partner (Yes/No) |
| Dependents       | Str      | Whether the customer has dependents (Yes/No) |
| Tenure           | Int      | Number of months the customer has stayed |
| PhoneService     | Str      | Whether the customer has phone service (Yes/No) |
| MultipleLines    | Str      | Whether the customer has multiple lines |
| InternetService  | Str      | Internet type (DSL/Fiber optic/None) |
| OnlineSecurity   | Str      | Subscription to online security (Yes/No) |
| OnlineBackup     | Str      | Subscription to online backup (Yes/No) |
| DeviceProtection | Str      | Subscription to device protection (Yes/No) |
| TechSupport      | Str      | Subscription to tech support (Yes/No) |
| StreamingTV      | Str      | Subscription to streaming TV (Yes/No) |
| StreamingMovies  | Str      | Subscription to streaming movies (Yes/No) |
| Contract         | Str      | Contract type (Month-to-month/One year/Two year) |
| PaperlessBilling | Str      | Whether billing is paperless |
| PaymentMethod    | Str      | Customer’s payment method |
| MonthlyCharges   | Float    | Amount billed monthly |
| TotalCharges     | Float    | Total billed charges |
| Churn            | Str      | Churn status (Yes/No) |

---

## Key Metrics
- **Total Customers**: 7,043  
- **Churned Customers**: 1,869  
- **Churn Rate**: 26.54%  
- **Monthly Revenue**: 456K  
- **Monthly Loss**: 139K  

---

## Dashboard Overview

### Dashboard 1 – Customer Demographics  
![Dashboard 1](/Image_assets/Churn_Dashboard_page-0001.jpg)  

### Dashboard 2 – Account Details (Tenure & Tickets)  
![Dashboard 2](/Image_assets/Churn_Dashboard_page-0002.jpg)  

### Dashboard 3 – Subscriptions & Services  
![Dashboard 3](/Image_assets/Churn_Dashboard_page-0003.jpg)  

---

## Key Insights
- Female churn rate (26.92%) is slightly higher than male churn rate (26.12%).  
- Dependents churn less (15.45%) compared to non-dependents (32.96%).  
- Customers with partners churn at 19.66%, while those without partners churn at 32.96%.  
- Senior citizens churn more (41.68%) than younger customers (23.61%).  
- Month-to-month contracts show the highest churn (42.71%), while two-year contracts have the lowest churn (2.83%).  
- Churned customers raise more **technical tickets (2,173)** and incur higher monthly charges (~$74) compared to retained customers (~$61).  
- Fiber optic internet users churn more compared to DSL users.  
- Customers without add-on services (backup, security, device protection, streaming) are more likely to churn.  

---

## Recommendations
- Offer **discounts or incentives** for long-term contracts.  
- Focus on **improving fiber optic service quality**.  
- **Bundle add-on services** (security, streaming, device protection) to improve retention.  
- Enhance **technical support resolution speed** to reduce dissatisfaction.  
- Launch **targeted retention programs** for senior citizens and high-charge customers.  

---
