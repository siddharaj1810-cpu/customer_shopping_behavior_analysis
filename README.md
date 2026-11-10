# customer_shopping_behavior_analysis
Data analysis project using Python, SQL, power Bi. 
# Customer Shopping Behavior Analysis

## 1. Overview

This project analyzes customer shopping behavior to understand purchasing patterns, product preferences, spending habits, and customer loyalty.

The project follows an end-to-end data analytics workflow using Python for data cleaning and exploratory data analysis (EDA), PostgreSQL for SQL-based business analysis, and Power BI for interactive data visualization.

The goal is to transform raw customer shopping data into meaningful insights that can support data-driven business decisions.

## 2. Dataset

- **Dataset:** Customer Shopping Behavior Dataset
- **Format:** CSV
- **Source:** Included in this repository
- **Data Type:** Customer demographics, purchase details, and shopping preferences

The dataset includes information such as:

- Customer age and gender
- Product categories and items purchased
- Purchase amounts and discount usage
- Shipping types and payment methods
- Customer subscription status
- Review ratings and previous purchases
- Shopping frequency and seasonal preferences

## 3. Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualization during EDA |
| Jupyter Notebook | Analysis and documentation |
| PostgreSQL | Database management and SQL analysis |
| SQL | Business queries and customer segmentation |
| Power BI | Interactive dashboard development |
| Gamma | Project presentation |

## 4. Project Workflow

### Step 1: Data Loading

- Imported the customer shopping dataset into Python.
- Examined the dataset structure, columns, data types, and summary statistics.
- Identified data quality issues before analysis.

### Step 2: Exploratory Data Analysis (EDA)

- Explored customer demographics and purchasing patterns.
- Analyzed purchase amounts and product preferences.
- Examined discount usage, subscription status, and review ratings.
- Used visualizations to identify patterns and relationships.

### Step 3: Data Cleaning & Preprocessing

- Checked for missing values and duplicate records.
- Corrected data types and inconsistent values where required.
- Prepared the dataset for further analysis.
- Created derived features, including age groups, where applicable.

### Step 4: SQL Analysis using PostgreSQL

Loaded the prepared dataset into PostgreSQL and used SQL queries to answer business questions, including:

- What is the total purchase revenue by gender?
- Which customers used discounts but spent above the average purchase amount?
- Which products have the highest average review ratings?
- How does average spending compare between Standard and Express shipping?
- Do subscribed customers spend more than non-subscribers?
- Which products have the highest discount usage rates?
- How can customers be segmented into New, Returning, and Loyal groups?
- What are the most purchased products within each category?
- Are repeat customers more likely to subscribe?
- Which age groups contribute the most revenue?

SQL techniques include filtering, aggregation, subqueries, conditional logic, Common Table Expressions (CTEs), and window functions.

### Step 5: Power BI Dashboard

Developed an interactive Power BI dashboard to present key metrics and customer behavior insights.

The dashboard helps explore:

- Customer purchasing patterns
- Revenue contribution across customer groups
- Product and category performance
- Customer subscription behavior
- Discount usage and shopping preferences

The dashboard makes it easier to compare customer segments and identify patterns in the data.

## 5. Dashboard

**Power BI Dashboard Preview**

Open the `.pbix` file using Power BI Desktop to explore the dashboard.

<img width="1153" height="641" alt="image" src="https://github.com/user-attachments/assets/6d7fbdf1-2ea4-4a7c-b6b0-f003db8b0d0c" />

## 6. Results & Business Insights

The analysis focuses on identifying actionable insights related to customer purchasing behavior.

Key areas investigated include:

- **Customer Segmentation:** Understanding purchasing history across New, Returning, and Loyal customers.
- **Revenue Analysis:** Comparing purchase revenue across gender and age groups.
- **Product Performance:** Identifying popular products and products with high customer ratings.
- **Discount Analysis:** Examining discount usage across products and customer purchases.
- **Subscription Analysis:** Comparing spending behavior between subscribed and non-subscribed customers.
- **Shopping Preferences:** Evaluating differences in spending by shipping type and other shopping characteristics.

These findings can help businesses improve customer engagement, evaluate promotional strategies, and make better-informed decisions.

## 7. Project Files

| File | Description |
|---|---|
| `customer_shopping_behavior.csv` | Customer shopping dataset |
| `Customer_Shopping_Behaviour_Analysis.ipynb` | Python EDA and data analysis |
| `customer_behaviour_analysis.sql` | PostgreSQL analysis queries |
| `customer_behavior_dashboard.pbix` | Power BI dashboard |
| `README.md` | Project documentation |

## 8. How to Run

### Prerequisites

Install Python, PostgreSQL, Jupyter Notebook, and Power BI Desktop.

### Step 1: Clone the Repository

```bash
git clone https://github.com/siddharaj1810-cpu/customer_shopping_behavior_analysis.git
cd customer_shopping_behavior_analysis
```

### Step 2: Install Python Libraries

```bash
pip install pandas numpy matplotlib jupyter sqlalchemy psycopg2-binary
```

### Step 3: Run the Python Notebook

1. Start Jupyter Notebook.
2. Open `Customer_Shopping_Behaviour_Analysis.ipynb`.
3. Execute the cells to review the data loading, cleaning, and analysis workflow.

### Step 4: Run SQL Queries

1. Open PostgreSQL using pgAdmin or your preferred SQL client.
2. Create a database and load the prepared customer dataset into a table named `customer`.
3. Configure the database connection if you are using Python to transfer data.
4. Open `customer_behaviour_analysis.sql`.
5. Execute the queries against the loaded table.

**Note:** Ensure the table and column names match the SQL script before running the queries.

### Step 5: Open the Power BI Dashboard

1. Open `customer_behavior_dashboard.pbix` in Power BI Desktop.
2. Configure the data source if prompted.
3. Refresh the data if necessary.
4. Explore the available visualizations and filters.

## 9. Project Deliverables

- Python notebook for data exploration and cleaning
- PostgreSQL queries for business analysis
- Interactive Power BI dashboard
- Project report documenting the methodology and findings
- Gamma presentation summarizing the project

*The report and presentation can be added to the repository as downloadable files when available.*

## 10. Author

**Siddharaj Jadhav**

Aspiring Data Analyst

- **GitHub:** [siddharaj1810-cpu](https://github.com/siddharaj1810-cpu)
- **LinkedIn:** [Siddharaj Jadhav](https://www.linkedin.com/in/siddharajjadhav/)

---

*This project demonstrates practical data analytics skills through data cleaning, exploratory analysis, SQL querying, and interactive dashboard development.*
