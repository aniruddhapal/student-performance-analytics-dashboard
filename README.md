# Student Performance Analytics Dashboard

## Problem
Schools track marks but miss performance trends and at-risk students.

## Solution
A Power BI dashboard that identifies:
- Class-wise risk (% declining students)
- Students requiring immediate attention
- Separation of absence vs performance decline

## Approach
- Data modeling (Fact_StudentMarks, Dim_Student)
- Student-level aggregation (T1 vs T2)
- Attendance-aware filtering
- DAX measures for KPIs

## Key Insights
- ~X% students declining in some classes
- Class X shows highest risk
- Only X students below 40%, but X% in 40–60% band

## Screenshots
(Overview, Risk & Intervention page)

## Tools
Power BI, DAX, Python
