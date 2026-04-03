# Customer Credit Risk & Financial Behavior Analysis

## **Project Overview**

This project presents a **data-driven analysis of customer credit risk and financial behavior**, simulating real-world banking and investment decision-making.

By combining **customer demographics** with **transaction-level financial activity**, the project identifies the key drivers of credit risk, uncovers patterns in financial behavior, and provides actionable insights for **risk assessment, customer segmentation, and loan decision support**.

---

## **Objectives**

* Identify the primary factors influencing credit risk.
* Analyze customer financial behavior and spending patterns.
* Develop risk-based customer segmentation.
* Simulate data-driven loan decision support.
* Build interactive dashboards for business stakeholders.

---

## **Datasets**

This project integrates **two datasets** with 1,000 customers each:

**1. German Credit Data**

* Demographics: Age, Sex, Job
* Financial attributes: Credit Amount, Duration
* Account info: Savings, Checking
* Target variable: Risk Level

**2. Bank Transaction Data**

* Transaction activity: Total Transactions, Avg Transaction
* Financial flows: Total Credit, Total Debit
* Account balance behavior: Min/Max Balance
* Channel usage: ATM, Branch, Online

---

## **Data Preparation**

* The German Credit Data had 1,000 entries, while the Bank Transaction Data had 50,000 entries, so the datasets were not directly compatible.
* Used Excel formulas to aggregate and summarize transaction-level data (e.g., total transactions, total spent, average transaction) per customer.
* Added a CustomerID row to both datasets to create a common key for joining.
* Performed an inner join in Tableau on CustomerID to combine demographic, credit, and transaction-level financial data.
* Ensured the merged dataset contained 1,000 customer-level records, ready for analysis.

---

## **Feature Engineering**

Several calculated fields were created to enhance analytical depth:

* **Net Cash Flow:** Total Received – Total Spent
* **Transaction Volatility:** Variability in transaction patterns
* **Credit Intensity:** Loan burden relative to financial activity
* **Customer Risk Score:** Composite risk indicator
* **Risk Flag:** Binary classification for high-risk customers

---

## **Dashboards**

### **Dashboard 1: Credit Risk Drivers**

**Purpose:** Identify core factors influencing customer credit risk.

**Key Visuals & Insights:**

1. **Risk Distribution Overview:** Shows overall portfolio risk; X% of customers are high risk.
2. **Credit Amount vs Loan Duration:** Longer, larger loans cluster in high risk.
3. **Loan Intensity vs Risk:** High-intensity loans indicate repayment pressure.
4. **Credit Risk by Job Category:** Lower employment stability correlates with higher risk.

**Filters:** Age Group, Housing Status, Sex
**Colors:** Red = High Risk, Green = Low Risk

**Caption Example:**

> “This dashboard highlights the key drivers of credit risk, combining loan characteristics and customer demographics to provide actionable insights for portfolio monitoring.”

---

### **Dashboard 2: Customer Financial Behavior**

**Purpose:** Analyze how transaction patterns and financial activity relate to risk.

**Key Visuals & Insights:**

1. **Spending vs Income Behavior:** Customers spending near or above income show elevated risk.
2. **Net Cash Flow Distribution Across Risk Levels:** Negative net cash flow correlates with high risk.
3. **Transaction Volatility vs Credit Amount:** High volatility and large loans indicate repayment stress.
4. **Net Cash Flow vs Transaction Volatility:** Highlights high-risk customers with unstable cash flow.
5. **Customer Segmentation:** Clusters customers by financial behavior and risk profile.
6. **Loan Decision Support – Risk Score vs Credit Intensity:** Shows high-risk customers under repayment pressure.

**Filters:** Age Group, Housing Status, Sex
**Colors:** Red = High Risk, Green = Low Risk

**Caption Example:**

> “This dashboard provides a detailed view of customer financial behavior and highlights high-risk segments based on cash flow, transaction patterns, and credit intensity.”

---

## Dashboard Preview
<img width="958" height="634" alt="image" src="https://github.com/user-attachments/assets/c289323e-21a0-41a3-8b00-c0e2c2a9490f" />

---

## **Technical Skills Demonstrated**

* **Data Cleaning & Preprocessing:** Handling missing values, categorical encoding, dataset merging.
* **Feature Engineering:** Created financial metrics (Credit Intensity, Transaction Volatility, Customer Risk Score).
* **Data Visualization:** Built interactive Tableau dashboards with filters, KPIs, and tooltips.
* **Banking & Financial Analytics:** Identified risk drivers, portfolio exposure, and customer segmentation.
* **Business Storytelling:** Presented insights clearly for decision-making.

---

## **Key Takeaways / Business Impact**

* Portfolio health and risk exposure can be quickly assessed via **high-level KPIs**.
* Loan size, duration, and intensity are strong predictors of default risk.
* Employment and housing status provide demographic context for risk assessment.
* Transaction behavior and net cash flow reveal hidden high-risk customers.
* Interactive dashboards allow stakeholders to explore segments and make informed decisions.

---

## **Future Work / Extensions**

* Integrate more granular behavioral features (e.g., payment delays, overdrafts).
* Build predictive models for loan default probability.
* Extend segmentation to identify high-value, low-risk customers.
* Simulate a **Loan Decision Support System** using risk scores and credit intensity.

---
## **Dashboard link**

https://g-baloyi.github.io/Customer-Credit-Risk-and-Financial-Behavior-Analysis/








