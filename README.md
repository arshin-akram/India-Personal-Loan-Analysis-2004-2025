# 📊 India Personal Loan Trends Analysis (2004-2025)

## 🎯 Project Objective
This project analyzes 21 years of Reserve Bank of India (RBI) historical data to identify regional credit growth hubs and the impact of fintech adoption on personal loan disbursements.

## 💡 Strategic Insights
* **Post-2021 Surge:** Identified a "Hockey Stick" growth curve following the rapid adoption of digital lending platforms.
* **Regional Hubs:** Maharashtra remains the financial leader, followed closely by Karnataka and Tamil Nadu.
* **National Volume:** The total disbursed amount analyzed stands at **₹37.89M Cr**.

## 🛠️ Technical Implementation (ETL & DAX)
* **Data Reconciliation:** Manually merged historical reporting entities (Dadra & Nagar Haveli and Daman & Diu) to align with the current **36 States/UTs** of India.
* **ETL Pipeline:** Performed **Unpivoting** in Power Query to transform raw "Wide" RBI formats into "Long" time-series data for analysis.
* **DAX Modeling:** Developed a dynamic market-share measure to calculate the % of Total India for each state, providing immediate context on regional credit concentration. This formula allowed for the identification of Maharashtra's leading position in the national portfolio.
* **Data Visualization:** Designed a high-density dashboard featuring KPI cards, interactive maps, and trend forecasting (Exponential Smoothing).

## 📂 Project Assets
* [Executive Report (PDF)](RBI_Personal_Loan_Analysis_Report.pdf): A deep-dive analysis for business stakeholders.
* [Power BI File (.pbix)](India_Personal_Loan_Trends_2004_2025.pbix): The interactive technical solution.
* [CSV File(.csv)](India_Personal_Loans_Raw.csv): Original RBI source data for ETL transparency.

## 🚀 How to Use
1. Download the `.pbix` file.
2. Open in Power BI Desktop.
3. Use the **State/Union Territory** slicer to see regional market share vs. national totals.
