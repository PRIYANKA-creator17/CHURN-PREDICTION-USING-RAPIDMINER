# CHURN-PREDICTION-USING-RAPIDMINER  
**#Case Study:**
Leveraging Machine Learning to Predict and Reduce Customer Churn for a Telecom Company
Executive Summary:
The telecommunications industry is highly competitive, and customer churn poses a significant challenge to profitability and growth. Losing a customer not only means lost revenue but also increased costs in acquiring new customers to replace them. This case study focuses on how a telecom company can leverage machine learning models to predict customer churn, analyze the causes behind it, and implement data-driven strategies to retain customers, thus mitigating revenue losses and enhancing overall customer satisfaction.


**Current Business Challenge**

**Problem Statement:**
The company is facing elevated customer churn rates, but without a structured and data-driven strategy, they are unable to proactively address the issue. This has led to:

**Revenue Declines:** A high churn rate negatively affects the company's revenue, necessitating higher customer acquisition costs.
**Inconsistent Customer Retention Efforts:** The absence of targeted strategies results in inefficient marketing campaigns and unfocused retention efforts.
**Unclear Customer Insights:** Without analytics, the company lacks a clear understanding of why certain customers leave and others stay. This makes it difficult to develop tailored offers or engagement programs to retain high-risk customers.

**Data Overview**

**Dataset Features:**
The dataset contains demographic, service usage, contract, and payment information for telecom customers, as well as whether or not they churned. Key features include:

**Customer Demographics:** Gender, Senior Citizen status, Dependents, etc.
**Service Details:** Internet service type, phone service, and any value-added services like streaming or online security.
**Contract & Payment:** Type of contract (month-to-month, one year, two years), payment methods, monthly and total charges.
**Churn Label:** The target variable indicating whether the customer churned (Yes/No).


**Data Preprocessing**

To build a robust machine learning model, we first need to ensure the data is clean, well-structured, and ready for analysis:

Handling Missing Data: Some missing values were found in TotalCharges, primarily for customers with very short tenures. These were imputed by calculating the product of MonthlyCharges and tenure.

**Encoding Categorical Variables:** Features such as gender, Contract, and PaymentMethod were one-hot encoded, converting them into numerical form while preserving their categorical nature.

**Feature Scaling:** Continuous variables such as MonthlyCharges and TotalCharges were normalized to ensure fair weight across all model features, as some algorithms (e.g., logistic regression) are sensitive to the scale of the input data.

**Model Selection and Evaluation**
![image](https://github.com/user-attachments/assets/686947a6-e700-4514-89f5-fcbad2ddee79)

**Business Impact of this case study:**

**Proactive Customer Retention:**
By using predictive models, the company can identify customers who are at high risk of churning based on their contract types, payment methods, and service usage patterns. These insights allow for timely interventions, such as offering tailored discounts, enhancing customer service, or extending contracts.

**Resource Optimization:**
Instead of treating all customers equally in retention efforts, the company can focus its marketing and engagement strategies specifically on high-risk segments, improving retention ROI and reducing marketing waste.

**Data-Driven Decision Making:**
The models provide a structured framework to understand which variables (e.g., short-term contracts, month-to-month billing) are most associated with churn, enabling the company to develop data-driven policies that better align with customer needs.


