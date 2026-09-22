# 💼 Corporate Finance & Expense Analytics Dashboard

## 📌 Project Overview
This repository contains an end-to-end **Corporate Financial Analytics** project built in **Power BI**. The dashboard analyzes 10,000 financial records across **2023 and 2024**, tracking **$100M+ in gross revenue**, operational expenditure patterns, net profit margins, project budget approvals, and vendor payment flows across 15 major cities.

---

## 📊 Executive Key Performance Indicators (KPIs)
* **Gross Revenue:** $100,174,447.95
* **Total Expenses:** $50,372,366.43
* **Net Profit:** $49,802,081.52
* **Profit Margin:** 49.72%
* **Total Financial Transactions:** 10,000
* **Departments Analyzed:** 7 (IT, Sales, Marketing, Operations, HR, R&D, Finance)
* **Geographic Regions:** 5 Regions across 15 Cities

---

## 🗄️ Dataset Architecture & Key Dimensions
* **Fact Data:** Daily transaction records including expense amounts, revenue generated, payment methods, and approval statuses.
* **Dimensions:**
  * **Departments:** IT, Marketing, HR, R&D, Sales, Operations, Finance
  * **Expense Categories:** Equipment, Training, Software Licenses, Travel, Events, Consulting, Advertising
  * **Projects:** Tech Revamp, Expansion Q1, Project Alpha, Project Beta, Hiring Boost, Innovation Lab
  * **Regions & Cities:** Central, East, West, North, South (Cairo, Alexandria, Giza, Luxor, Port Said, etc.)
  * **Payment Methods:** Bank Transfer, Credit Card, Cheque, Cash
  * **Currencies Handled:** EGP, USD, EUR, GBP

---

## 💡 Analytical Insights & Features
1. **Financial Performance Overview:** High-level executive scorecards for Revenue, Expenses, Net Profit, and Operating Margin by year/quarter.
2. **Departmental Expense Breakdown:** Analysis of cost distributions across IT, Marketing, and Operations to identify high-cost centers.
3. **Approval Status & Risk Analysis:** Monitoring pending vs. rejected expense requests to streamline internal corporate governance.
4. **Vendor & Project Cost Control:** Tracking major suppliers (Vendors A–D) and cost efficiency per strategic initiative (*Tech Revamp*, *Innovation Lab*).

---

## 📂 Repository Structure
```text
├── data/
│   └── Finance_Data.xlsx     # Raw dataset (10,000 transactions)
├── pbix/
│   └── Finance_Data.pbix     # Power BI report file
├── screenshots/             # Dashboard visual preview images
└── README.md                # Project documentation
