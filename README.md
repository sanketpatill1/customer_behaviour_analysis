# Customer Shopping Behaviour Analysis

## Overview

This project focuses on analyzing customer shopping behavior to uncover purchasing patterns, customer preferences, and business insights. The project follows a complete data analytics workflow, including data cleaning, exploratory data analysis (EDA), SQL-based analysis, dashboard creation in Power BI, and presentation of findings through reports and presentations.

The goal is to transform raw customer data into actionable insights that can support business decision-making and improve customer understanding.

---

## Dataset

The dataset contains customer shopping information, including demographic details, purchasing behavior, product categories, spending patterns, review ratings, subscription status, and payment preferences.

### Key Features

* Customer ID
* Age
* Gender
* Item Purchased
* Category
* Purchase Amount (USD)
* Review Rating
* Subscription Status
* Discount Applied
* Promo Code Used
* Payment Method
* Shipping Type
* Previous Purchases

---

## Tools & Technologies

### Programming & Analysis

* Python
* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Database

* SQL
* PostgreSQL / MySQL / SQL Server

### Business Intelligence

* Power BI

### Reporting & Presentation

* Microsoft PowerPoint
* Gamma AI

### Development Environment

* Jupyter Notebook
* VS Code

---

## Project Workflow

### 1. Data Loading

* Imported the dataset using Python.
* Performed initial inspection of data structure and quality.

### 2. Data Cleaning

* Checked missing values.
* Handled missing data using appropriate techniques.
* Verified data types and consistency.
* Removed duplicates where necessary.

### 3. Exploratory Data Analysis (EDA)

* Analyzed customer demographics.
* Studied purchasing behavior across categories.
* Examined spending trends and review ratings.
* Identified patterns using visualizations and summary statistics.

### 4. SQL Analysis

* Imported data into a relational database.
* Wrote SQL queries to answer business questions.
* Performed aggregations, filtering, joins, and ranking operations.
* Generated insights related to customer behavior and sales performance.

### 5. Dashboard Development

* Built an interactive Power BI dashboard.
* Created KPI cards and business metrics.
* Added charts and filters for deeper analysis.
* Enabled interactive exploration of customer behavior.

### 6. Reporting & Presentation

* Documented findings in a business report.
* Created a presentation summarizing insights and recommendations using Gamma.

---

## Dashboard

The Power BI dashboard provides interactive visualizations for:

* Customer Demographics Analysis
* Category-wise Sales Analysis
* Customer Spending Patterns
* Review Rating Insights
* Subscription Status Analysis
* Payment Method Preferences
* Business KPI Tracking

---

## Key Results & Insights

* Identified top-performing product categories.
* Analyzed customer spending behavior across demographics.
* Evaluated the impact of discounts and promotions.
* Identified preferred payment methods and shipping options.
* Discovered trends that can support customer retention and business growth.

---

## Project Structure

```text
Customer-Shopping-Behaviour-Analysis/
│
├── data/
├── notebooks/
│   └── customer_analysis.ipynb
│
├── sql/
│   └── customer_behavior_sql_queries.sql
│
├── powerbi/
│   └── Customer_Shopping_Dashboard.pbix
│
├── reports/
│   └── Customer_Shopping_Report.pdf
│
├── presentation/
│   └── Customer_Shopping_Presentation.pptx
│
├── dashboard_images/
│
├── README.md
└── LICENSE
```

## How to Run

### Clone the Repository

```bash
git clone <repository-url>
```

### Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### Run the Notebook

```bash
jupyter notebook
```

Open the notebook and execute all cells to reproduce the analysis.

### SQL Analysis

* Import the dataset into PostgreSQL, MySQL, or SQL Server.
* Execute the SQL queries provided in the SQL folder.

### Power BI Dashboard

* Open the `.pbix` file using Power BI Desktop.
* Refresh the dataset connection if required.

---

## Conclusion

This project demonstrates an end-to-end data analytics workflow, covering data cleaning, exploratory analysis, SQL querying, dashboard development, and business reporting. It highlights the practical application of Python, SQL, and Power BI to generate meaningful business insights from customer shopping data.
