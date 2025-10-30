# Customer-Behavior-Analysis
This project, Customer Shopping Behavior, follows a clear analytical pipeline from raw data to actionable reporting.

Phase 1: **Data Setup and Transformation** (Python/Jupyter)

Ingest and Clean: The raw data (customer_shopping_behavior.csv) was ingested and cleaned within a Python environment (customer_shopping_behaviour.ipynb).

Database Loading: The cleaned data was loaded into a PostgreSQL database table named customer to enable complex relational querying.

Phase 2: **Core Analysis and Metric Generation** (SQL)

The primary analysis was performed using advanced SQL queries (customer_shopping_behaviorSQL.sql) to generate key performance indicators (KPIs) and segments.

Revenue Analysis (Q1 & Q5): Calculated total revenue by gender and compared average spend/total revenue between subscribed and non-subscribed customers to quantify financial disparity.

Segmentation (Q7): Used conditional logic to segment the entire customer base into Loyal, Returning, and New groups based on previous purchases, providing a foundational marketing framework.

Product/Discount Analysis (Q3 & Q6): Identified the top 5 highest-rated products and analyzed the effectiveness of discounts on high-value transactions.

Phase 3: **Reporting and Visualization** (Power BI)

Data Connection: The final output of the SQL queries was connected to the visualization tool (Customer Behavior Dashboard.pbix).

Dashboarding: A dynamic Power BI dashboard was built to visualize the key metrics (e.g., segmentation counts and gender revenue disparity) for business stakeholders.
