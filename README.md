# HR Employee Attrition Analysis

An interactive Power BI dashboard analyzing employee attrition patterns across 1,470 employee records to identify key drivers of turnover.

## Tools Used
- Microsoft Excel (data cleaning, pivot table validation)
- Microsoft Power BI (dashboard, KPI measures)

## Dataset
IBM HR Analytics Employee Attrition dataset — 1,470 records, 35 original columns (Age, Department, JobRole, MonthlyIncome, Attrition, JobSatisfaction, OverTime, YearsAtCompany, etc.)

## Process
1. **Data Cleaning (Excel):** Removed constant/irrelevant columns (EmployeeCount, StandardHours, Over18), checked for duplicates and blanks.
2. **Feature Engineering:** Added AgeGroup, AttritionFlag (numeric 1/0), and TenureGroup helper columns for easier analysis.
3. **Validation (Pivot Tables):** Cross-checked attrition rates by Department, JobRole, OverTime, and AgeGroup before building the dashboard.
4. **Dashboard (Power BI):** Built KPI cards, bar charts, and slicers to visualize attrition drivers interactively.

## Key Insights

- **Overtime is the strongest single driver of attrition:** employees working overtime show a **30.5%** attrition rate vs. **10.4%** for those who don't — nearly 3x higher.
- **Sales Representatives are the highest-risk role** at **39.8%** attrition, followed by Laboratory Technicians (23.9%) and HR (23.1%).
- **Younger employees (18–25) attrite far more** at **35.8%**, dropping sharply to 9.2% for the 36–45 age group.
- **Sales department has the highest departmental attrition** at 20.6%, while R&D is lowest at 13.8%.

**Overall attrition rate:** 16.1% across all 1,470 employees.

## Files
- `hr_attrition.xlsx` — cleaned dataset with helper columns
- Dashboard screenshots

## Recommendations
Retention efforts should prioritize young, overtime-working Sales Representatives — the segment showing the highest compounded attrition risk.

---
**Author:** Sunny Kakkar | [LinkedIn](https://linkedin.com/in/sunny-kakkar-53827b321)
