# 🛍️ Customer Behaviour Analysis

This project, **Customer Shopping Behavior**, follows a clear analytical pipeline — from raw data preparation to insightful reporting — to understand and visualize how different customer groups behave, spend, and respond to discounts.

---

## 📊 Phase 1: Data Setup and Transformation (Python/Jupyter)

### 🔹 Ingest and Clean
The raw dataset (`customer_shopping_behavior.csv`) was imported and cleaned within a **Python Jupyter Notebook** (`customer_shopping_behaviour.ipynb`).

### 🔹 Database Loading
After cleaning, the data was loaded into a **PostgreSQL** database table named `customer` to enable structured querying and relational analysis.

---

## 🧮 Phase 2: Core Analysis and Metric Generation (SQL)

Key analyses were performed using advanced **SQL queries** (`customer_shopping_behaviorSQL.sql`) to generate **KPIs**, customer segmentation, and business insights.

### 🔸 Revenue Analysis (Q1 & Q5)
- Calculated **total revenue by gender**.  
- Compared **average spend** and **total revenue** between **subscribed** and **non-subscribed** customers.

### 🔸 Customer Segmentation (Q7)
Segmented the customer base into:
- **Loyal Customers** — Repeat purchasers with multiple transactions.  
- **Returning Customers** — Occasional repeat buyers.  
- **New Customers** — First-time purchasers.

### 🔸 Product & Discount Analysis (Q3 & Q6)
- Identified the **Top 5 highest-rated products**.  
- Analyzed the **impact of discounts** on high-value transactions to assess promotional effectiveness.

---

## 📈 Phase 3: Reporting and Visualization (Power BI)

### 🔹 Data Connection
The output from SQL queries was connected to **Power BI** (`Customer Behavior Dashboard.pbix`) for business reporting.

### 🔹 Dashboard Highlights
- Dynamic visual representation of **revenue trends**, **customer segments**, and **gender-based insights**.  
- Real-time KPIs for management decisions.  
- Drill-through analytics for exploring purchase patterns.

---

## 🛠️ Tools and Technologies

| Category | Tools Used |
|-----------|------------|
| Data Cleaning | Python, Pandas |
| Database | PostgreSQL |
| Querying | SQL |
| Visualization | Power BI |
| IDE/Environment | Jupyter Notebook, VS Code |

---

## 📂 Project Structure

Customer-Behaviour-Analysis/
│
├── customer_shopping_behavior.csv
├── customer_shopping_behaviour.ipynb
├── customer_shopping_behaviorSQL.sql
├── Customer Behavior Dashboard.pbix
└── README.md                                                                                                                                                                  
---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/vaibhavipatil0241/Customer-Behaviour-Analysis.git
   cd Customer-Behaviour-Analysis
2. Open and run the Jupyter Notebook for data cleaning:

   jupyter notebook customer_shopping_behaviour.ipynbjupyter notebook customer_shopping_behaviour.ipynb
3. Execute SQL scripts in PostgreSQL.

4. Open Power BI Dashboard (.pbix) file to explore the interactive reports.

📢 Summary
   This end-to-end data analysis project demonstrates:

   Data cleaning and transformation using Python

   Advanced SQL analytics for insight generation

   Professional visualization through Power BI

   It provides actionable business insights into customer loyalty, purchase behavior, and marketing effectiveness — empowering data-driven decision-making.
