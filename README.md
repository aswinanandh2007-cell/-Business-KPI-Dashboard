# Business KPI Dashboard: Customer Churn

Interactive dashboard that explains churn, retention, revenue risk and customer segments.

**Live dashboard:** https://YOUR-USERNAME.github.io/churn-kpi-dashboard/

## Files
- `index.html` – the dashboard (single file, no dependencies)
- `customer_churn_sample.csv` – source data (15 customers)

## KPI definitions
- **Churn rate** = churned customers ÷ all customers in the current filter
- **Retention rate** = 1 − churn rate
- **Revenue at risk** = sum of MonthlyCharges of churned customers (monthly recurring revenue lost), also shown as % of total monthly revenue
- **Tenure** = average TenureMonths, shown overall and for churned vs retained customers

## Filters
Contract type, tenure band (0–6, 7–12, 13–24, 25+ months), payment method.

## Key findings (full dataset)
- 7 of 15 customers churned (47% churn, 53% retention)
- Revenue at risk: $409.93 of $1,269.85 monthly revenue (about 32%)
- All churned customers are on month-to-month contracts; one-year and two-year contracts had no churn
- Churned customers have much shorter tenure, so early months are the danger zone

## Caveat
Only 15 customers, so each one moves a percentage by about 7 points. Treat patterns as directional.
