# Logistics & Fleet Performance Analytics | Power BI

## Project Overview
I developed this six-page Power BI analytics solution for a logistics project and am showcasing my own analytics, modeling, DAX, and dashboard-development contribution as part of my professional portfolio.

The solution integrates 14 operational datasets and analyzes 85,410 loads representing approximately $262.53M in revenue. It covers executive performance, revenue and customers, delivery and routes, driver performance, fleet/fuel/maintenance, and safety/risk.

> Portfolio note: This project was completed for another party. The portfolio presentation focuses on my contribution to the analytics solution and does not imply ownership of the underlying business or data.

## Business Questions
- How much revenue and load volume are being generated?
- Which customers and customer segments contribute the most revenue?
- Which routes and facilities require delivery-performance investigation?
- How do drivers compare on revenue, miles, trips, and efficiency?
- How efficiently is the fleet utilized and what are the major fuel/maintenance costs?
- What safety incident patterns and claims exposure are present?

## Tools & Skills
Power BI Desktop, Power Query, DAX, data cleaning, dimensional modeling, time intelligence, KPI development, data visualization, business analysis, and data-quality assessment.

## Dashboard Pages
1. Executive Overview
2. Revenue & Customers
3. Delivery & Routes
4. Driver Performance
5. Fleet, Fuel & Maintenance
6. Safety & Risk

## Selected Findings
- Revenue: approximately $262.53M from 85,410 loads.
- Revenue per load: approximately $3.07K.
- On-time delivery: 44.6%; late delivery: 55.4%.
- Average delivery detention: approximately 106.6 minutes.
- Fleet utilization: approximately 83.0%.
- Fleet MPG: approximately 6.45.
- Fuel cost: approximately $95.59M.
- Maintenance cost: approximately $5.73M.
- Safety incidents: 170; preventable incidents: 64 (37.6%).
- Recorded claims: approximately $2.65M.

## Data Quality & Limitations
3,880 fuel-purchase records have no truck identifier. They remain in fleet-wide fuel totals but cannot be attributed to an individual truck. One safety incident has no driver identifier and remains in overall safety metrics but cannot be attributed to a driver. Delivery-event data includes only 86 events in 2025, so 2025 is treated as a partial/spillover period rather than a complete-year comparison.

The dashboard identifies associations and patterns; it does not establish causal relationships.

## Repository Contents
- `Logistics_Fleet_Performance_Case_Study.pdf` - portfolio case study.
- `Logistics_Fleet_Performance_Findings.docx` - findings-only document.
- `Portfolio_Presentation_and_Interview_Guide.docx` - presentation, CV, LinkedIn, and interview material.
- `screenshots/` - six finished dashboard screenshots.
- `README.md` - this project overview.

## Power BI Files
Add your own `.pbix` and/or `.pbit` files to this folder before publishing if you have permission to redistribute them. If the client data is confidential or redistribution is restricted, publish the screenshots, case study, and an appropriately anonymized/template version instead.

## Suggested Repository Name
`logistics-fleet-performance-powerbi`
