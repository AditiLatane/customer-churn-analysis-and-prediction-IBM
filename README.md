# Customer Churn Analysis Dashboard (Power BI)

## Project Overview

This project focuses on analyzing **customer churn behavior** using Power BI to help businesses identify high-risk customers and design **data-driven retention strategies**. The dashboard combines descriptive analysis, churn metrics, and dynamic insights to support proactive decision-making.

The analysis highlights how **customer demographics, payment methods, contract types, and service usage** influence churn probability.

---

## Business Objective

* Identify customer segments with **high churn risk**
* Understand **key drivers of churn**
* Enable **proactive retention strategies** using interactive visuals and smart narratives
* Support management with **actionable recommendations**

---

## Key KPIs

* **Total Customers**
* **Churned Customers**
* **Churn Rate (%)**
* **High-Risk Customers Count**
* **Average Tenure**

---

## Analysis Dimensions

The dashboard allows churn analysis across multiple business dimensions:

* **Demographics**: Gender, Senior Citizen, Partner, Dependents
* **Billing & Payments**: Payment Method, Auto-pay vs Manual
* **Customer Relationship**: Tenure, Contract Type
* **Service Usage**: Number of Services, Internet Type, Tech Support

---

## Machine Learning (ML) Modeling

1) Drop Identifier (like CustomerID) & Leakage Columns
2) Define Target & Features
3) Define Column Groups
4) Train-Test Split
5) Preprocessing using ColumnTransformer
6) Pipeline Creation
7) Model Training
8) Model Evaluation
9) Random Forest Pipeline

    Accuracy of 81% | 85% precision for non-churn | 66% precision for churn

---

## Key Insights

* Churn is **highest during early tenure (0–6 months)**, indicating onboarding risk
* **Month-to-month contracts** show significantly higher churn than long-term contracts
* **Senior citizens** have the highest churn rate among demographics
* Customers using **electronic check payments** churn more compared to auto-pay users
* **Service bundling** drastically reduces churn probability

---

## Advanced Features

### Churn Probability Logic (DAX)

* Customers are classified into **High / Medium / Low risk** based on churn probability
* Risk segmentation enables targeted retention strategies

### Dynamic Smart Narratives

* Recommendations automatically update based on selected slicers such as:

  * Gender
  * Senior Citizen
  * Partner
  * Dependents
  * Payment Method
* Ensures **context-aware business insights** for decision-makers

---

## Business Recommendations

* Strengthen **early-tenure engagement** with structured onboarding
* Incentivize customers to switch to **long-term contracts**
* Promote **auto-pay payment methods** through discounts or rewards
* Provide **personalized support for senior citizens**
* Encourage **service bundling and cross-selling**
* Use churn risk scores to **prioritize retention campaigns**

---

## Tools & Technologies

* **Power BI** – Data modeling, DAX, dashboards, smart narratives
* **DAX** – Churn probability, risk segmentation, dynamic text
* **Excel / CSV** – Data preprocessing and validation

---

## Dashboard Features

* Interactive slicers for customer segmentation
* Dynamic recommendations linked to filters
* Clear visuals for churn trends and drivers
* Business-focused layout

---

## Why This Project Matters

This project demonstrates:

* Strong **business understanding of customer retention**
* Ability to translate data into **actionable insights**
* Practical use of **DAX for real-world analytics problems**
* Dashboard storytelling skills valued in **Data Analyst / Business Analyst roles**

---

## Use Cases

* Telecom & subscription-based businesses
* Customer retention teams
* Product & marketing analytics
* Executive decision support

---

<img width="694" height="395" alt="image" src="https://github.com/user-attachments/assets/4d9e76b1-ce12-4c76-888c-11d8d2051528" />

---

<img width="688" height="397" alt="image" src="https://github.com/user-attachments/assets/b0b2d2d8-a0f4-436f-b6c9-c2dff72d3680" />

---

<img width="691" height="390" alt="image" src="https://github.com/user-attachments/assets/e92e8154-bb48-40ef-96f8-6134143fe3c7" />

