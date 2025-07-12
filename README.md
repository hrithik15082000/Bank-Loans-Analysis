# 💼 LendAnalytics: Bank Loan Analysis Dashboard

This Excel-powered dashboard provides a comprehensive visual analysis of a bank's historical loan data, helping stakeholders monitor key metrics like loan disbursement, repayment patterns, interest trends, and risk profiling.

---

## 📁 Project Files

- `Bank Loans Analysis.xlsx` — Main Excel dashboard
- `financial_loan.csv` — Source dataset used for visualization

---

## 📊 Dashboards Included

### 🔷 1. **Summary Dashboard**
A high-level comparison of Good Loans vs Bad Loans with percentages, amounts, and counts.

- Good Loan Issued %
- Bad Loan Issued %
- Total Applications, Funded Amount, Amount Received
- Loan Status-wise Split (Fully Paid, Charged Off, Current)
- Interest Rate & DTI comparison by loan type

![Summary Dashboard](assets/Summary%20Dashboard.png)

---

### 🔶 2. **Overview Dashboard**
A broader view of overall loan performance with category-wise trends.

- Applications by Month, State, Term, Purpose
- Loan Trends by Home Ownership & Employee Length
- Key MoM and MTD indicators

![Overview Dashboard](assets/Overview%20Dashboard.png)

---

## 🎛️ Slicers Used

### 🔹 Grade & Purpose Filters

These slicers help users explore loan metrics across:
- **Grade**: A–G
- **Purpose**: Car, Credit Card, Education, Home Improvement, etc.

![Slicer Grade Purpose](assets/Slicer%20For%20Grade%20And%20Purpose.png)

---

### 🔹 Dashboard Navigation Slicer

Quickly switch between the three dashboard views:
- **Summary**
- **Overview**
- **Details (optional)**

![Slicer Navigation](assets/Slicer%20To%20Change%20The%20Dashboards.png)

---

## 🔍 Features

- Clean and interactive UI using Excel Pivot Tables & Slicers
- Dynamic filtering without macros
- Month-over-month growth indicators
- High-level loan health summary
- Geographic and categorical trend breakdowns

---

## 📂 Data Source

- `financial_loan.csv`  
Includes fields like:
`loan_status`, `funded_amount`, `term`, `interest_rate`, `grade`, `purpose`, `home_ownership`, and more.

---

## 🛠 Built With

- Microsoft Excel
- Pivot Tables & Pivot Charts
- Slicers for interactivity
- Conditional Formatting

---

## 📌 How to Use

1. Clone or download the repository.
2. Open `Bank Loans Analysis.xlsx`.
3. Use the slicers on the left to filter data (by grade, purpose).
4. Use the navigation slicer to switch between dashboards.

---

## 📈 Screenshots

> All dashboard and slicer screenshots are stored in the `assets/` folder.

---

## 👨‍💻 Developed By

**Hrithik Kumar**  
*Data Analyst | Power BI Analyst*  
🌐 [GitHub Profile](https://github.com/hrithikb-tech)

---

## 📝 License

This project is licensed under the MIT License — feel free to use, modify, and share.
