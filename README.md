📊 Sales Summary using SQLite & Python
✅ Task
Extract and visualize basic sales data (total quantity sold, total revenue per product) from a SQLite database using Python.

🛠 Tools Used
Python
SQLite (sqlite3)
Pandas
Matplotlib
Jupyter Notebook
📌 What I Did
Created a small SQLite database (sales_data.db) with sample sales data.
Used SQL queries in Python to summarize sales:
SUM(quantity) for total quantity
SUM(quantity * price) for revenue
Loaded results into a Pandas DataFrame.
Printed the output and visualized revenue by product using a bar chart.




⚙️ Implementation
Connect to the database using sqlite3.
Run SQL query with GROUP BY product.
Read results with pandas.read_sql_query().
Plot bar chart with matplotlib.
Output: Printed table + bar chart (sales_chart.png) showing revenue per product.
