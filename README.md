# 💼 LendAnalytics: Bank Loan Analysis Dashboard

This Excel-powered dashboard provides a comprehensive visual analysis of a bank's historical loan data, helping stakeholders monitor key metrics like loan disbursement, repayment patterns, interest trends, and risk profiling.

---

## 🖼️ Dashboards

### 🔷 1. Summary Dashboard

![Summary Dashboard](Summary%20Dashboard.png)

A high-level view of Good vs Bad Loans including percentages, counts, and key metrics like funded amount, interest rate, and DTI.

---

### 🔶 2. Overview Dashboard

![Overview Dashboard](Overview%20Dashboard.png)

A broader analytical perspective with visual insights on:
- Applications by Month, State, Term
- Employee-based metrics
- Home ownership segmentation

---

## 🎛️ Interactive Slicers

### 🎚️ Grade & Purpose Filters

This slicer allows users to filter loan data based on **loan grades (A to G)** and **loan purposes** like:
- Credit Card
- Car
- Education
- Small Business
- Medical, etc.

By selecting one or more grades/purposes, all dashboard visuals update accordingly to provide focused insights.

---

### 📂 Dashboard Navigation Slicer

A **toggle-style slicer** is used to **switch between dashboards** (like Summary & Overview) inside the same Excel sheet.

- When a user selects a particular dashboard from the slicer (e.g., “Summary”), only visuals related to that dashboard become visible.
- The remaining visuals are hidden using **cell linking & selection-based visibility**.
- It's a creative way to simulate multi-page navigation within a single Excel page.

---

## 📁 Project Files

- `Bank Loans Analysis.xlsx` — Main Excel Dashboard  
- `financial_loan.csv` — Source dataset

---

## 🔍 Features

- 2 Fully Functional Dashboards  
- Dynamic Slicers for Custom Filtering  
- Pivot Charts & Tables for Insights  
- Conditional Formatting  
- Interactive & Print-Ready Design  

---

## 📂 Data Fields

The dataset includes:
- `loan_status`
- `funded_amount`
- `term`
- `interest_rate`
- `grade`
- `purpose`
- `home_ownership`
- and more...

---

## 🛠 Built With

- Microsoft Excel  
- Pivot Tables  
- Pivot Charts  
- Slicers  
- Conditional Formatting  

---

## 📌 How to Use

1. Clone or download the repository.  
2. Open `Bank Loans Analysis.xlsx`.  
3. Use slicers to interact with grade, purpose, and dashboard views.  

---

## 👨‍💻 Developed By

**Hrithik Kumar**  
*Data Analyst | Power BI Analyst*  
🌐 [GitHub Profile](https://github.com/hrithik15082000)

---

## 📝 License

This project is licensed under the MIT License — feel free to use, modify, and share.
