# 📊 Loan Default Risk Analysis Dashboard

This Power BI dashboard helps financial institutions identify high-risk borrowers and understand loan default trends based on income level, purpose, and demographic insights.

---

## 🧠 Project Objective

To develop a visual analytics tool that supports data-driven loan risk assessment by identifying default patterns and borrower segments that are most prone to default.

---

## 🛠️ Tools & Technologies Used

- **Power BI** – Dashboard development, DAX measures, and slicers  
- **Excel** – Source data preparation and cleaning  
- **DAX** – Used for calculated KPIs like Default Rate and High Risk Count  
- **Power Query** – Data transformation and modeling

---

## 📊 Dashboard Preview

![Dashboard Preview](images/dashboard-preview.png)

---

## 📌 Key Metrics

| Metric               | Value      |
|----------------------|------------|
| Total Loans          | 100        |
| Average Loan Amount  | $6,930     |
| Default Rate (%)     | 14%        |
| High Risk Count      | 3 Borrowers |

---

## 🔍 Insights

- 🔴 **Income-Level Defaults**:  
  - High-income borrowers account for 5 defaults  
  - Low-income borrowers: 6 defaults  
  - Moderate-income: 3 defaults

- 🟣 **Top At-Risk Borrowers** (age ≤ 25, high loan amounts):  
  - Customer C1099 (Age 24, High Income, ₦13,500)  
  - Customer C1048 (Age 22, Moderate Income, ₦12,000)

- 🔄 **Monthly Loan Trends**:  
  - Peak issuance in February (8 loans) and May (7 loans)  
  - Notable drop in November and December

- 🟠 **Loan Purpose Distribution**:  
  - Business (26%) and Personal (22%) dominate purpose types  
  - Medical (20%), Education (19%), and Housing (13%) follow

- 🔵 **Branch Distribution** (based on defaults):  
  - Abuja and Port Harcourt have multiple defaults among top borrowers

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `Loan_Default_Analysis.pbix` | Power BI dashboard |
| `Loan_Data_Cleaned.xlsx`     | Prepared dataset |
| `README.md`                  | Project documentation |
| `images/dashboard-preview.png` | Dashboard screenshot |

---

## 🚀 How to View the Dashboard

1. Clone this repository or download the files.
2. Open `Loan_Default_Analysis.pbix` in **Power BI Desktop**.
3. Use slicers (Branch, Income Level, Loan Purpose, Date) to explore.
4. Analyze KPIs, heatmaps, and charts for insights.

---

## 🧑‍💼 About Me

**Folakemi Abiodun**  
Data Analyst | Excel • SQL • Power BI • DAX • Tableau  
📍 Fishers, IN  
📧 folakemiabiodun353@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/folabiodun)

---

## 🧭 Next Steps

- 📈 Add credit score modeling for improved risk profiling  
- 🔄 Connect to live data sources via Power Automate  
- 📬 Integrate alerts for high-risk loan thresholds  
