
# 💼 Loan Default Risk Dashboard

This interactive Power BI dashboard analyzes loan issuance and default patterns across multiple branches and income levels. It is designed for financial institutions to proactively monitor risk and identify high-risk borrowers through visual insights.

---

## 📊 Project Overview

Banks and microfinance institutions face growing exposure to non-performing loans. This dashboard provides a dynamic risk analysis by leveraging borrower data to identify default trends, highlight at-risk customers, and drive smarter lending decisions.

### 🎯 Objectives:
- Monitor loan performance metrics (volume, average size, default rate)
- Identify borrower risk segments by income level and age
- Visualize trends and distributions by branch and loan purpose
- Support decision-makers with data-backed insights

---

## 🔧 Tools Used
- **Power BI** – Dashboard creation, DAX measures, data visualization
- **Excel** – Data cleaning and structuring
- **SQL (conceptual)** – Used to plan data logic and filtering
- **JSON Theme File** – Custom styling for light and professional dashboard themes

---

## 📁 Dataset Overview

A synthetic dataset of 100+ loan records includes:

| Column        | Description |
|---------------|-------------|
| Loan_ID       | Unique loan identifier |
| Customer_ID   | Borrower reference |
| Loan_Amount   | Amount disbursed |
| Term_Months   | Duration of the loan |
| Income_Level  | Low, Moderate, or High |
| Age           | Borrower age |
| Loan_Purpose  | Business, Medical, Housing, etc. |
| Branch        | Branch location |
| Status        | Paid or Default |
| Issue_Date    | Loan issuance date |

---

## 📈 Dashboard Features

- **📌 KPI Cards**: Total Loans, Average Loan Amount, Default Rate (%), High-Risk Count
- **📊 Bar Chart**: Defaulted Loans by Income Level
- **📉 Line Chart**: Monthly Loan Issuance Trend
- **🍩 Donut Chart**: Loan Purpose Distribution
- **📋 Table**: Top At-Risk Borrowers (highlighted by age and loan size)
- **🔎 Slicers**: Filter by Branch, Income Level, Loan Purpose, and Issue Date

---

## 🎨 Styling Highlights

- Light gray background with soft blue cards for clean presentation
- Conditional formatting on loan amounts (red) and borrower age under 25 (yellow)
- Custom JSON theme with fonts, border styles, and modern palette
- Professionally formatted layout and slicer positioning

---

## 📷 Screenshot

![Loan Default Risk Dashboard](images/dashboard-preview.png)

> *Note: Image above is for preview. Replace with your own dashboard screenshot.*

---

## 🚀 Getting Started

1. Clone this repo or download the ZIP.
2. Open the `.pbix` file in Power BI Desktop (or import the Excel dataset).
3. Apply the included theme from the `/themes/` folder.
4. Explore or publish the dashboard via Power BI Service.

---

## 🧠 Key Learnings

- Built DAX measures to define KPIs and segment high-risk customers
- Applied UX best practices to slicer placement, color contrast, and formatting
- Created a polished dashboard ready for stakeholder presentation or portfolio use

---

## 🤝 Connect

**Folakemi Abiodun**  
📍 Fishers, IN  
🔗 [LinkedIn](https://www.linkedin.com/in/folakemiabi)  
📬 fabiodun855@gmail.com  

---

## 📁 Folder Structure

```
Loan_Default_Risk_Dashboard/
│
├── Loan_Default_Risk_Dataset.xlsx
├── Folakemi_Professional_Theme.json
├── Folakemi_Dark_Loan_Theme.json
├── README.md
└── images/
    └── dashboard-preview.png
```
