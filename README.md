Retail Banking Customer Churn & Deposit Loss Analysis
![Power BI Churn Dashboard](![Power BI Churn Dashboard](Screenshot%202026-11-16%20192341.png)
## 📌 Project Overview
An end-to-end data analytics project identifying the root causes of customer attrition and deposit outflow in retail banking. Raw customer records were audited, cleaned, and analyzed in **Python (Pandas, Seaborn)** before building an interactive executive dashboard in **Power BI (DAX)**.

## 💰 Key Business Findings
* **Overall Churn & Financial Impact:** Out of **8,715** verified customers, **20.22%** churned—resulting in **$157.91M in lost deposits** (24.1% of total bank balances).
* **Regional Vulnerability:** **Germany** suffers a **32.32%** churn rate—more than double that of **Spain (16.42%)** and **France (16.20%)**.
* **Product Penetration ("2-Product Sweet Spot"):** Customers holding **2 products** achieve the lowest churn (**7.26%**), whereas single-product users churn at **27.75%** and over-sold **3–4 product** holders churn at **82.63%–100%**.
* **Age & Engagement Risk:** Customers in their **50s (56.12% churn)** and **60s (36.11% churn)** represent the highest-risk age brackets, while inactive members leave at nearly double the rate of active members.

## 🛠️ Tools & Technical Workflow
1. **Data Cleaning & Validation (`Python` / `Pandas`):** Handled missing values, removed duplicate accounts, enforced banking domain rules (`age`, `balance`, `credit_score`), standardized mixed `DD/MM/YYYY` and `YYYY-MM-DD` birth dates, and normalized categorical text.
2. **Exploratory Data Analysis (`Seaborn` / `Matplotlib`):** Segmented churn rates across demographics, product counts, and deposit balances.
3. **Executive Dashboarding (`Power BI` / `DAX`):** Built interactive slicers (`Country`, `Active-member`, `Gender`) and custom DAX measures (`Churn Rate`, `Lost Deposit`, `Total Customers`).

## 💡 Strategic Recommendations
1. **Germany Retention Audit:** Investigate regional fee structures, competitor savings rates, and branch service quality in Germany.
2. **Guided Cross-Selling:** Encourage 1-product customers to adopt a second core product (e.g., savings or credit card) while halting aggressive cross-selling beyond 2 products.
3. **Early Inactivity Alerts:** Trigger automated retention outreach when high-balance customers aged 45–65 show 60 days of account inactivity.
