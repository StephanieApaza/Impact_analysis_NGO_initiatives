# Impact analysis NGO initiatives (SQL)

## Overview
This project analyzes the GoodThought NGO's assignments, donations, and donors to understand the impact and effectiveness of its initiatives over time.
GoodThought NGO has led transformative efforts in education, healthcare, and sustainability worldwide.

## 🎯 Research Questions
1. Who are the top five assignments based on the total value of donations, categorized by donor type?
2. Which assignments have the highest impact score in each region?
3. How have donations varied over time?
4. Which regions receive the highest total donations and achieve the greatest impact?
5. How are assignments categorized by impact score and duration?

## ✅Methodology
- Data Sources: PostgreSQL database containing assignments, donations, and donors tables.
- Data Cleaning: Standardized date formats to ISO 8601, verified numeric values, and handled missing or inconsistent data.
- Analysis Tools: SQL queries with aggregations, joins, window functions, and CASE WHEN statements for categorization.

## 🧩Key Findings
- Donations Over Time: 2020–2022 donations remained consistent, peaking at $866,914 in 2020.
- Regional Impact: South region leads in total donations ($644,650) and has the highest average impact score (5.54).
- Impact Categorization: Most projects fall in the medium impact range (4–6), with very high impact (9–10) and low impact (1–3) projects being roughly equal.
- Budget vs. Impact: Projects with negative budgets (1730) show slightly higher average impact (5.51) than those with positive budgets (5.41), suggesting that limited resources do not necessarily reduce effectiveness.

## 🧭Conclusion
GoodThought NGO demonstrates consistent global impact across regions, independent of budget constraints. Data-driven insights reveal that while most projects operate with positive budgets, high-impact outcomes can still be achieved with limited resources. 
Regional and donor-specific analyses help guide strategic planning and resource allocation for future initiatives.



