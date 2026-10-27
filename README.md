# Analyzing-Customer-Churn-Rate
This Power BI dashboard analyzes telecom churn across 6,687 customers. It reveals a 26.86% overall churn rate, driven by monthly contracts (46.29% vs 6.62% yearly). Primary attrition factors include competitor offers, service rep attitudes, and short tenure. Built with Power BI, Power Query, and DAX.
# 📉 Telecom Customer Churn Analysis & Retention Dashboard

## 📌 Project Overview
This Power BI dashboard analyzes customer attrition (churn) data across **6,687 telecom customers** to identify the key drivers behind customer loss and help design targeted retention strategies[cite: 1, 2, 5]. By evaluating demographic factors, contract terms, service usage, payment methods, and customer interactions, this project translates raw operational data into actionable business intelligence[cite: 1, 2, 5, 6].

---

## 📊 Key Insights & Highlights

* **Overall Attrition:** The baseline customer churn rate across the organization stands at **26.86%**[cite: 1, 3].
* **Contract Risk:** Contract type is the single largest predictor of churn—customers on **Month-to-Month contracts** experience a **46.29% churn rate**, compared to just **6.62%** for those on Yearly contracts[cite: 2].
* **Demographics & Age:** Churn risk increases significantly with age, with older age groups exhibiting churn rates approaching **60%**[cite: 1].
* **Primary Departure Reasons:** The leading causes of churn are competitor offers (better prices/devices) and negative experiences with customer service representative attitudes[cite: 1].
* **Tenure & Payment Methods:** Customers paying via **Paper Check** and **Direct Debit** experience the highest early-tenure drop-off, particularly within their first 20 months[cite: 5, 6].
* **Data Consumption:** Non-unlimited data users consuming less than 10 GB per month display higher churn rates (up to 35%) compared to heavy data users[cite: 3].

---

## 🛠️ Tech Stack & Methods
* **Power BI Desktop:** Dynamic visualization, interactive dashboard design, and drill-through analysis[cite: 1, 2, 5].
* **Power Query (ETL):** Data cleaning, age/tenure binning, custom grouping, and dataset transformations[cite: 1, 5].
* **DAX (Data Analysis Expressions):** Custom measures for churn percentages, average charges, customer segment counts, and cross-filter calculations[cite: 1, 2, 4, 6].

---

## 📸 Visualizations Included
* **Demographic Breakdown:** Churn rate distribution by age bins, senior status, and customer groups[cite: 1, 2].
* **Contract & Financial Trends:** Monthly vs. yearly contract comparisons paired with account length and payment methods[cite: 2, 5, 6].
* **Root Cause Analysis:** Categorized Pareto analysis of churn reasons (Competitor, Service Attitude, Price, Network Reliability)[cite: 1, 2].
* **Usage Patterns:** Churn segmentation based on international plan activity and data consumption tiers[cite: 3, 4].

---

## 💡 Strategic Business Recommendations
1. **Contract Migration:** Offer renewal incentives or discounted add-ons to convert high-risk Month-to-Month customers onto long-term annual plans[cite: 2].
2. **Support & Service Upgrades:** Improve frontline support training and address competitor pricing pressure to resolve the top two churn drivers[cite: 1].
3. **Targeted Onboarding:** Implement specialized onboarding initiatives for newly joined customers paying via manual methods to improve retention during the critical first 20 months[cite: 5, 6].

---

## 📂 Repository Structure
```text
├── data/
│   └── customer_churn_data.csv
├── screenshots/
│   ├── churn_overview.png
│   └── contract_payment_analysis.png
├── Telecom_Customer_Churn_Analysis.pbix
└── README.md
