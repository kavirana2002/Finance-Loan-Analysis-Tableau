# 💰 Finance Loan Analysis | Tableau

A data analytics dashboard project built using **Tableau** to analyze and visualize finance loan data. This project covers 9 in-depth analysis questions, an interactive dashboard, and a complete data story — all built as a personal learning exercise.

---

## 📌 Project Overview

This project provides a comprehensive view of loan performance metrics, helping users understand loan distribution, repayment trends, default rates, customer risk, and branch performance through interactive Tableau visuals.

---

## 🎯 Objective

To analyze finance loan data using Tableau and answer key business questions through charts, KPI cards, calculated fields, an interactive dashboard, and a data story.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Tableau** | Data visualization & dashboard creation |
| **Excel / CSV** | Data source |
| **Calculated Fields** | Custom metrics & KPIs |
| **Tableau Story** | Data storytelling across 9 questions |

---

## ❓ 9 Analysis Questions Solved

| # | Question | Visual Used |
|---|----------|------------|
| Q1 | Total customers, total loan amount, total EMI collected & total remaining balance | KPI Cards |
| Q2 | Which loan type has the highest loan amount? | Bar Chart |
| Q3 | Monthly loan approval trend | Line Chart |
| Q4 | Top 10 customers based on loan amount | Horizontal Bar Chart |
| Q5 | Which state has the highest loan amount? | Map / Bar Chart |
| Q6 | Which payment mode collects the highest EMI amount? | Pie / Bar Chart |
| Q7 | Branches with the highest default loans | Bar Chart |
| Q8 | Customer risk categories (High / Medium / Low Risk) using credit score, remaining balance, loan status & late fee | Color-coded Table |
| Q9 | Branches with low recovery percentage using `SUM(payment_amount) / SUM(loan_amount) × 100` | Bar Chart |

---

## 📊 Dashboard Features

- 📈 **Charts & Graphs** — Bar charts, line graphs, and pie charts showing loan trends, repayment patterns, and default rates
- 🔢 **KPIs & Cards** — Total customers, total loan amount, total EMI collected, and total remaining balance
- 📋 **Tables & Filters** — Detailed data tables with filters to drill down by loan type, branch, state, or customer
- 🧮 **Calculated Fields** — Custom formulas like recovery percentage and customer risk categories
- 📖 **Story Sheet** — Complete data storytelling covering all 9 questions in sequence

---

## 📁 Project Structure

```
finance-loan-analysis-tableau/
│
├── FinanceLoanAnalysis.twbx         # Main Tableau workbook (all 11 sheets)
├── README.md                        # Project documentation
├── data/
│   └── loan_data.csv               # Dataset used in the project
└── screenshots/
    ├── 01_dashboard.png            # Main Dashboard
    ├── 02_story.png                # Story Sheet
    ├── 03_kpi_overview.png         # Q1 - KPI Cards
    ├── 04_loan_type.png            # Q2 - Loan Type Analysis
    └── 05_branch_recovery.png      # Q9 - Branch Recovery
```

---

## 🚀 How to Use

1. **Clone or download** this repository
2. Open the `.twbx` file in **Tableau Desktop** or **Tableau Public**
   - Download Tableau Public for free from [here](https://public.tableau.com/)
3. If needed, update the **data source path** to point to the dataset on your machine
4. Explore all **9 analysis sheets**, the **main dashboard**, and the **story sheet**!

---

## 📷 Dashboard Preview



---

## 📚 Key Learnings

Through this project, I learned:
- How to connect and clean data using **Tableau's data source editor**
- How to create custom metrics using **Calculated Fields** (e.g. recovery %)
- How to build **customer risk categories** using multiple conditions
- How to design an intuitive and interactive **dashboard** in Tableau
- How to present data insights using **Tableau Story**
- How to analyze financial data to derive meaningful business insights

---

## 🙋‍♂️ About

This project was created as part of my personal learning journey into **data analytics and visualization**. I am exploring Business Intelligence (BI) tools like Tableau to build real-world dashboards.

---

## 📬 Contact

Feel free to connect with me or share feedback!

- GitHub: 
- LinkedIn: https://www.linkedin.com/in/kanak-rana-b0630631a
---

⭐ If you found this project helpful or interesting, feel free to **star** the repository!
