# Customer Credit Risk & Financial Behavior Analysis

## Project Overview

This project presents a comprehensive data-driven analysis of customer credit risk and financial behavior, designed to simulate real-world banking and investment decision-making.

By combining customer demographic data with transaction-level financial activity, the project aims to uncover the key drivers of credit risk and provide actionable insights for improving lending strategies, risk assessment, and customer segmentation.

---

## Objectives

* Identify the primary factors influencing credit risk
* Analyze customer financial behavior and spending patterns
* Develop risk-based customer segmentation
* Simulate data-driven loan decision support
* Build interactive dashboards for business stakeholders

---

## Datasets Used

This project integrates two datasets:

### 1. German Credit Data

* Customer demographics (Age, Sex, Job)
* Financial attributes (Credit Amount, Duration)
* Account information (Savings, Checking)
* Target variable: **Risk Level**

### 2. Bank Transaction Data

* Transaction activity (Total Transactions, Avg Transaction)
* Financial flows (Total Credit, Total Debit)
* Account balance behavior (Min/Max Balance)
* Channel usage (ATM, Branch, Online)

---

## Data Preparation

* Cleaned missing and inconsistent values
* Standardized categorical variables
* Merged datasets using `CustomerID`
* Ensured consistency across 1000 customer records

---

## Feature Engineering

To enhance analytical depth, several calculated fields were created:

* **Net Cash Flow** = Total Received – Total Spent
* **Transaction Volatility** = Variability in transaction patterns
* **Credit Intensity** = Loan burden relative to financial activity
* **Customer Risk Score** = Composite risk indicator
* **Risk Flag** = Binary classification for high-risk customers

---

## Tableau Dashboards

### Dashboard 1: Credit Risk Drivers

This dashboard explores the core factors influencing customer credit risk.

**Key Visualizations:**

* Risk Distribution Overview
* Risk Distribution by Age Group
* Credit Amount vs Loan Duration
* Credit Risk by Job Category
* Credit Risk by Housing Status
* Loan Intensity vs Risk

 **Key Insights:**

* Younger customers exhibit higher credit risk
* Larger loans and longer durations increase risk exposure
* Lower job categories are associated with higher default likelihood
* Homeownership strongly correlates with lower risk
* High credit intensity signals financial stress

---

### Dashboard 2: Customer Financial Behavior *(In Progress)*

This dashboard will analyze how transaction patterns and financial activity relate to risk.

**Planned Focus Areas:**

* Spending vs income behavior
* Net cash flow distribution
* Transaction volatility analysis
* Channel usage patterns (ATM, Online, Branch)

---

### Dashboard 3: Customer Segmentation *(In Progress)*

This dashboard will group customers into meaningful segments based on financial and risk characteristics.

**Planned Focus Areas:**

* Risk score segmentation
* Behavioral clustering
* High-value vs high-risk customer identification

---

### Dashboard 4: Loan Decision Support System *(In Progress)*

This dashboard will simulate real-world banking decisions using risk indicators.

**Planned Features:**

* Loan approval simulation
* Risk flag monitoring
* Expected loss estimation
* High-risk customer identification

---

### Dashboard 5: Executive Summary *(In Progress)*

A high-level dashboard designed for decision-makers, summarizing key insights and business impact.

---

## Tools & Technologies

* **Tableau** – Data visualization and dashboard development
* **Python / Excel** – Data cleaning and preprocessing
* **GitHub** – Project version control and portfolio presentation

---

## Dashboard Preview

<img width="928" height="620" alt="image" src="https://github.com/user-attachments/assets/0dbf02ea-f2f4-4e97-8e03-030cf083d543" />

---

## Business Value

This project demonstrates how data can be leveraged to:

* Improve credit risk assessment
* Enhance customer segmentation strategies
* Support data-driven lending decisions
* Identify high-risk and high-value customers
* Optimize financial product offerings

---

## Future Improvements

* Build predictive models (e.g., Logistic Regression, Random Forest)
* Integrate real-time risk scoring
* Enhance segmentation using clustering algorithms
* Deploy dashboards for interactive web access

---

## Final Note

This project is actively being developed, with additional dashboards and advanced analytics currently in progress. The goal is to evolve this into a complete, production-level credit risk analytics solution.






