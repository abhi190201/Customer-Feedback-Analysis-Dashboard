# Customer Feedback Analysis Dashboard (Simple)

This project contains a simple, runnable Excel dashboard suitable for a Data Analyst fresher portfolio.
It uses a sample customer feedback dataset and produces summary tables and visual charts for quick analysis.

## Files
- `data/customer_feedback_data.csv` - source dataset (200 rows)
- `Customer_Feedback_Analysis.xlsx` - Excel workbook with sheets: Data, Pivot_Tables, Dashboard
  - Data: raw dataset with added 'Sentiment' column
  - Pivot_Tables: precomputed summary tables (Avg rating by Product, Region, Month) and KPIs
  - Dashboard: KPI values and charts (images embedded)

## How to open (Excel 2019)
1. Download the ZIP and extract the folder.
2. Open `Customer_Feedback_Analysis.xlsx` in Excel 2019.
3. Go to the 'Dashboard' sheet to view KPIs and charts.
4. If you want interactive pivot tables or slicers, you can create PivotTables in Excel using the 'Data' sheet as the source (Pivot quick steps are provided in the sheet 'Pivot_Tables').

## Notes / Limitations
- This is a **simple** dashboard version. Some advanced Excel features (live PivotTable objects with slicers) are not created programmatically here for maximum Excel compatibility. 
- The 'Sentiment' column is stored as values (Positive/Negative). If you prefer an Excel formula instead, use `=IF(E2>=4,"Positive","Negative")` in column G in the Data sheet.
- Charts are embedded as images to ensure consistent appearance across environments.

## Resume/GitHub Description
```
Customer Feedback Analysis Dashboard | Tech Stack: Microsoft Excel (Pivot Tables, Charts)
• Built a simple Excel dashboard to analyze customer feedback, including KPIs and trend charts.
• Processed 200+ feedback entries and implemented sentiment classification to highlight positive vs negative feedback.
• Created pivot summaries for product, region, and monthly trends to provide actionable insights for product teams.
```

---
Generated on 2025-11-01 18:43:10 UTC
