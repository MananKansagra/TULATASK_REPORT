# TULATASK_REPORT
As part of a data analytics internship application for Tula Capital, I developed a comprehensive Business Intelligence dashboard using Power BI to analyze trade strategy performance across three datasets. The goal was to consolidate, visualize, and derive actionable insights from trading activity.


🔧 Key Features & Tasks:
✅ Data Integration:

Merged 3 separate CSV files (each representing a unique trading strategy) into a single data model.

Added a custom column strategy_name to track the source strategy of each trade.

✅ Data Cleaning & Transformation:

Utilized Power Query to clean and format entry_datetime and exit_datetime fields.

Extracted new columns like Quarter, Hour of Entry, and Cumulative PnL using DAX and Power BI functions.

✅ Page 1 – Strategy Summary Dashboard:

Built a table showing:

Total PnL

Win Count (pnl > 0)

Loss Count (pnl < 0)

Enabled drillthrough to strategy-level detail view.

✅ Page 2 – Detailed Drillthrough Report:

Created KPI cards to show key stats for selected strategy.

Added a line chart for cumulative PnL over time and a bar chart to analyze PnL by hour of the day.

Incorporated a slicer for date range filtering and a full trade detail table.

✅ Python & SQL Integration:

Used Python (pandas) for initial CSV inspection and validation.

Designed SQL queries for future scalable integration with MySQL-based datasets.

🎯 Outcome & Learnings:
Mastered the end-to-end BI workflow—from data extraction and cleaning to dashboard deployment.

Gained practical experience with DAX, Power Query M, and interactive Power BI visuals.

Strengthened data storytelling skills and learned best practices in dashboard usability and performance.
