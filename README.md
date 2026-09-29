# VEDA Technology Internship — Day 22

## Cohort Retention Analysis

### Project Overview

This project focuses on **Cohort Retention Analysis** to understand customer retention patterns over time. Customers are grouped into cohorts based on the month of their first purchase, and their subsequent activity is analyzed to identify retention trends.

The project uses Python, Pandas, SQL, and data visualization techniques to transform transaction data into meaningful insights that can support data-driven business decisions.

### Objectives

* Understand the concept of customer cohort analysis.
* Group customers according to their first purchase month.
* Calculate monthly cohort retention rates.
* Build a cohort retention table using Python and Pandas.
* Visualize retention patterns through a heatmap.
* Perform SQL-based customer and retention analysis.
* Extract business insights and suggest actionable recommendations.

### Tools and Technologies

* **Python** — Data analysis and calculations
* **Pandas** — Data cleaning, transformation, and cohort calculations
* **Matplotlib / Seaborn** — Data visualization and heatmap
* **SQLite** — SQL-based data analysis
* **Google Colab / Jupyter Notebook** — Development environment
* **GitHub** — Project version control and documentation

### Dataset

The project uses a **synthetic practice transaction dataset** prepared for this learning exercise. It contains customer transaction records across multiple months.

The dataset is used to demonstrate cohort formation, customer activity, and retention calculations. It is not presented as real company or customer data.

### Project Workflow

1. **Data Loading:** Imported the transaction dataset into a Pandas DataFrame.
2. **Data Cleaning:** Checked the dataset structure and prepared the required date and customer fields.
3. **Cohort Assignment:** Identified each customer's first purchase month and assigned the customer to a cohort.
4. **Cohort Index Calculation:** Calculated the number of months between the customer's cohort month and subsequent activity month.
5. **Cohort Table Creation:** Aggregated customer activity to build the cohort retention table.
6. **Retention Calculation:** Converted cohort activity counts into retention percentages.
7. **Heatmap Visualization:** Created a heatmap to compare retention across cohorts and months.
8. **SQL Analysis:** Executed three SQL queries to analyze cohort sizes, monthly active customers, and retention percentages.
9. **Business Insights:** Interpreted the analysis and prepared recommendations based on the observed patterns.

### Key Deliverables

* `VEDA_Day22_Cohort_Retention.ipynb` — Complete analysis notebook with code and outputs.
* `veda_day22_cohort_retention_practice_data.csv` — Synthetic practice dataset.
* `cohort_retention_heatmap.png` — Cohort retention heatmap.
* `sql_query1_cohort_sizes.csv` — SQL output for cohort sizes.
* `sql_query2_monthly_active_customers.csv` — SQL output for monthly active customers.
* `sql_query3_retention_percentages.csv` — SQL output for retention percentages.

### SQL Analysis

Three SQL analyses were performed:

**1. Cohort Sizes**

Calculated the number of customers belonging to each cohort.

**2. Monthly Active Customers**

Analyzed customer activity across different months.

**3. Retention Percentages**

Calculated the percentage of customers retained in subsequent months relative to their original cohort size.

### Business Insights

The analysis helps understand:

* How customer activity changes after the first purchase.
* How retention differs across customer cohorts.
* Which cohort-month combinations show higher or lower retention.
* How businesses can use retention analysis to evaluate customer engagement.
* Why customer retention should be monitored over time rather than through total sales alone.

**Note:** Final numerical findings should be interpreted from the actual notebook outputs. Retention comparisons should account for the fact that newer cohorts have fewer months of observable activity.

### Business Recommendations

* Monitor customer retention on a regular basis.
* Investigate months where retention declines.
* Develop targeted engagement campaigns for customers who stop purchasing.
* Compare cohorts over equivalent periods to avoid misleading conclusions.
* Use retention metrics alongside revenue, purchase frequency, and customer lifetime value for broader analysis.

### Learning Outcomes

Through this project, I practiced:

* Data cleaning and exploratory data analysis.
* Customer cohort identification.
* Retention rate calculation.
* Data aggregation using Pandas.
* SQL queries and grouped analysis.
* Heatmap creation and interpretation.
* Converting analytical outputs into business insights.
* Documenting and publishing a data analytics project on GitHub.

### Conclusion

This project demonstrates an end-to-end introductory cohort retention workflow using Python, Pandas, SQL, and visualization techniques. It provides practical experience in analyzing customer behavior, measuring retention, and presenting data-driven findings in a structured format.

### Author

**Bhagya**

VEDA Technology Internship — Level 2, Day 22

---

*This project was completed for learning and practice purposes. The dataset used is synthetic and intended for educational analysis.*
