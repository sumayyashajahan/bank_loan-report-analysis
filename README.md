# 📊 Bank Loan Data Analysis Report 

This project presents a comprehensive analysis of loan application data using **SQL queries executed in Microsoft SQL Server (MSSQL)**. The objective is to extract business insights from loan data, covering key performance indicators (KPIs), loan performance trends, regional analysis, and borrower segmentation. 
An **Excel Dashboard** was created to visualize the same insights. Various Excel visual elements such as Slicers, Bar Charts, Donut Charts, Line Charts, Tree Maps, and Maps were used for dynamic analysis and presentation of results.

---

## ✅ Key Performance Indicators (KPIs)

- Total loan applications.
- Total funded loan amount.
- Total amount received from borrowers.
- Average interest rate.
- Average Debt-to-Income (DTI) ratio.

All KPIs were computed using SQL aggregation queries within MSSQL. KPIs are also visualised using Exceldashboard.

---

## 📊 Good Loans vs Bad Loans Analysis

Loan statuses were categorized to distinguish:
- **Good Loans**: Fully Paid, Current.
- **Bad Loans**:  Charged Off.

Percentage distributions were calculated to evaluate loan portfolio health and default risks. Also Visualised in Excel interactive dashboard

---

## 🗓️ Monthly Trends Analysis

Analyzed loan issuance patterns based on issue dates:
- Monthly trends of loan applications.
- Funded amounts and repayments over time.
- Seasonal patterns identified.

SQL date functions were used for time-based grouping and trend analysis. Excel dashbord helps easy visualisation.

---

## 🌍 Regional Analysis (State-wise)

A state-wise analysis was conducted to:
- Identify regions with higher loan activity.
- Analyze funded and received amounts per state.
- Observe regional variations in loan performance.

All computations were performed via SQL queries using GROUP BY and aggregate functions and the result is compared with that in Excel dashboard.

---

## 🏷️ Segmentation Analysis

The dataset was segmented based on multiple borrower attributes:

### Loan Term
- Comparative analysis of 36-month vs 60-month loans.
- Impact of loan term on interest rates and defaults.

### Employment Length
- Loan performance trends based on borrower employment history.
- Higher default tendencies in borrowers with shorter employment durations.

### Purpose of Loan
- Loans segmented by stated purposes (Debt Consolidation, Credit Card, Small Business, etc.).
- Identified high-risk purposes based on default rates.

### Home Ownership
- Performance analyzed by ownership types: Rent, Mortgage, Own.
- Correlations between ownership status and repayment behavior were observed.

Segmentation was achieved using SQL filters, CASE statements, and grouping. And visualised in Excel dashboard for analysis.

---

## 🛠️ Filters & Dynamic Analysis

- Multiple filters applied through SQL WHERE clauses for deeper analysis.
- Filters include Loan Status, Region, Term, Employment Length, Purpose, Home Ownership.
- Users can modify queries to explore specific segments and compare results dynamically.

---

## 📝 Conclusion

All insights were generated using **pure SQL queries in Microsoft SQL Server (MSSQL)** and Visualised using **Excel dashboard**. This analysis helps in understanding borrower behavior, loan performance trends, and regional dynamics, assisting in data-driven decision-making for financial institutions.

---

## 📂 Tools & Technologies
- **Database**: Microsoft SQL Server (MSSQL)
- **Query Language**: SQL
- **Visualization**: SQL Result Sets 
- **Source Data**: Loan Applications Dataset (imported into MSSQL)

