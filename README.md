📚 Bookstore Data Analysis Project
📝 Overview

This project simulates a complete bookstore management system and performs end-to-end data analysis.
It includes:

Database design (ERD & schema)

Data preprocessing (Python & Excel)

Data storage (SQL)

Analysis queries

Interactive dashboards (Power BI)

The goal is to analyze sales performance, customer activity, best-selling books, and inventory management through structured data pipelines and visualization.

📂 Database Design

The relational database contains:

Core tables: Book, Author, Category, Employee, Branch, Review, Customer, Sale, SaleLine, Inventory

Relationship tables: Belongs_to, Written_by

The schema was designed to support:

Tracking book sales & inventory per branch

Customer reviews & behavior

Employee & branch performance

🔑 Features

Database Design → ERD + schema for bookstore operations.

Data Preprocessing → Cleaned & transformed raw bookstore data with Python (Pandas, NumPy).

SQL Queries → Extracted insights on sales, best-selling books, customer patterns, inventory.

Visualization → Built interactive Power BI dashboards with DAX + Excel preprocessing.

🧰 Tools & Technologies

SQL (MySQL / SQL Server)

Python (Pandas, NumPy, Matplotlib)

Excel & Power Query

Power BI

🚀 How to Run the Project
1️⃣ Database Setup

Go to /Database folder.

Run schema.sql to create the database and tables.

Run data.sql to insert sample bookstore data.

2️⃣ Data Preprocessing (Python)

Open /Python/preprocessing.ipynb in Jupyter Notebook.

Run all cells to clean & transform the raw dataset.

Export the cleaned dataset as .csv (or load directly into SQL).

3️⃣ SQL Queries

Inside /Queries, run the .sql files to explore:

Top-selling books

Sales by category

Inventory levels per branch

Customer purchase patterns

4️⃣ Power BI Dashboard

Open /Dashboard/Bookstore.pbix.

Connect the .pbix file to the SQL database (or the cleaned CSVs).

Explore the interactive dashboard.

📊 Dashboard Explanation

The Power BI dashboard provides insights into:

Total Sales 💰

Best-Selling Books & Categories 📖

Branch Performance 🏢

Customer Purchase Trends 👥

🔘 Interactive Icons & Filters:

Year Buttons/Icons → Filter all visuals by a specific year (e.g., 2020, 2021, 2022).

Category Filter → Show sales for a specific book category.

Branch Selector → Compare sales & performance across bookstore branches.

Dynamic KPIs → Update automatically when filters are applied (Sales, Profit, Top Authors).

This allows users to drill down into sales and customer behavior dynamically.

📂 Project Structure
📦 Bookstore-Analysis
 ┣ 📂 Database        → Schema & Data scripts (.sql)
 ┣ 📂 Python          → Preprocessing & analysis notebooks
 ┣ 📂 Queries         → SQL queries for analysis
 ┣ 📂 Dashboard       → Power BI file (.pbix)
 ┣ 📂 Excel           → Preprocessing steps (optional)
 ┗ 📜 README.md       → Project documentation
