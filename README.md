# 📊 Customer Support SQL & Python Analysis

An end-to-end Data Analytics project that analyzes customer support ticket data using **MySQL**, **Python**, and **Data Visualization**.

---

## 📌 Project Overview

This project demonstrates how SQL and Python can be used together to analyze customer support operations, identify trends, measure performance, and generate actionable business insights.

The analysis includes:

- SQL queries from basic to advanced
- Business case studies
- Exploratory Data Analysis (EDA)
- Data visualization using Python
- Customer Support KPI analysis

---

## 🛠️ Technologies Used

- Python
- Pandas
- MySQL
- SQLAlchemy
- PyMySQL
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Structure

```text
Customer Support SQL Python Analysis/
│
├── Dataset/
│   └── customer_support_data.csv
│
├── Images/
│
├── Python/
│   ├── mysql_import.ipynb
│   ├── eda_analysis.ipynb
│   └── visualization.ipynb
│
├── SQL/
│   ├── 01_database_setup.sql
│   ├── 02_basic_queries.sql
│   ├── 03_intermediate_queries.sql
│   ├── 04_advanced_queries.sql
│   └── 05_business_case_study.sql
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 📊 SQL Analysis

The SQL section includes:

- Database Creation
- Table Creation
- Basic SQL Queries
- Intermediate SQL Queries
- Advanced SQL
- CASE Statements
- Window Functions
- CTEs
- Subqueries
- Business Case Studies

---

## 🐍 Python Analysis

Python was used for:

- Connecting to MySQL
- Reading SQL tables into Pandas
- Exploratory Data Analysis
- Missing Value Analysis
- Descriptive Statistics
- Business Insights

---

## 📈 Visualizations

The project includes visualizations such as:

- Tickets by Category
- Ticket Status Distribution
- Priority Distribution
- Monthly Ticket Trend
- Top Support Agents
- Resolution Time by Category
- Average CSAT by Channel
- SLA Compliance

---

## 📷 Sample Visualizations

### Tickets by Category

![Tickets by Category](Images/tickets-by-category.png)

---

### Ticket Status Distribution

![Ticket Status](Images/ticket-status.png)

---

### Monthly Ticket Trend

![Monthly Ticket Trend](Images/monthly-ticket-trend.png)

---

### Top Support Agents

![Top Agents](Images/top-agents.png)

---

## 💡 Key Business Insights

- Most customer requests belong to a few high-volume categories.
- Ticket resolution time varies across categories.
- SLA compliance can be monitored to improve operational efficiency.
- Customer satisfaction differs by support channel.
- Agent performance can be evaluated using ticket volume and CSAT.

---

## 🚀 How to Run the Project

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/customer-support-sql-python-analysis.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Import the dataset into MySQL

Run:

```
01_database_setup.sql
```

Then import the dataset using:

```
Python/mysql_import.ipynb
```

Run the remaining notebooks:

- eda_analysis.ipynb
- visualization.ipynb

---

## 👩‍💻 Author

**Lingeshwari M**

- Data Analytics Enthusiast
- SQL | Python | Excel | Power BI
