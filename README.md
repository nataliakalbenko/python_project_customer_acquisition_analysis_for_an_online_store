# python_project_customer_acquisition_analysis_for_an_online_store
## About the Project

This project was developed in Python as part of my Data Analyst portfolio.
The analysis is based on a training e-commerce dataset prepared for educational purposes. The project explores customer purchasing behavior through Exploratory Data Analysis (EDA) and Cohort Analysis, helping identify customer retention patterns, revenue trends, and business opportunities.

## Business Question

How do customer retention and revenue change across monthly cohorts, and which cohorts generate the strongest customer value over time?

**Supporting Questions**
- How many new customers joined each monthly cohort?
- How does monthly revenue change over time?
- How does customer retention evolve after the first purchase?
- Which cohorts generate the highest cumulative revenue?
- What additional analyses could improve business insights?
- Which acquisition channels and customer segments contribute the most to business activity?

## Tech Stack
**Category	Tools**
- Programming	Python, Development	Google Colab 
- Data Analysis	pandas, NumPy
- Visualization	Matplotlib
- Reporting	HTML

## Project Structure

```text
python-cohort-analysis/
├── requirements
├── data/
│   └── client_base.xlsx
│
├── notebooks/
│   └── Retention_&_Cohort_Analysis.ipynb
│
└── docs/
    └── index.html
```

## Analysis Steps

- Imported and explored the dataset
- Checked data quality and missing values
- Created Cohort Month and Cohort Index
- Calculated monthly cohort sizes
- Analyzed revenue and order dynamics
- Calculated retention rates
- Analyzed cumulative cohort revenue

## Key Insights

The analysis revealed several important business findings:

- July 2025 produced the largest customer cohort with 452 new customers.
- Monthly revenue reached its highest level in August 2025.
- August also recorded the largest number of orders.
- Most cohorts retained approximately 50–60% of customers after the first month before gradually declining.
- The July 2025 cohort generated the highest cumulative revenue.

## Recommendations / Next Steps

- Investigate why the July cohort performed best.
- Analyze the relationship between payment methods and customer retention.
- Segment customers by demographics or location.

## How to Use This Repository

- Open the notebook in Google Colab.
- Upload client_base.xlsx.
- Run the notebook cells.
- Export the result as .ipynb or HTML if needed.
