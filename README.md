## 📊 Basic Sales Summary using SQLite and Python

### 📝 Objective
The goal of this project was to extract basic sales information (such as total quantity sold and total revenue) from a simple SQLite database and display it using Python with both print statements and a basic bar chart.

---

### ✅ Tools Used
- Python (`sqlite3`, `pandas`, `matplotlib`)
- Jupyter Notebook
- SQLite (built-in with Python)

---

### 🗂️ Steps Performed

1. **Created SQLite Database**  
   - Established a connection using `sqlite3.connect('Sales_data.db')`.

2. **Defined and Created Table**  
   - Table Name: `Sales`  
   - Columns: `order_number`, `quantity_ordered`, `product_line`, `sales`, `order_date`, `country`.

3. **Inserted Sample Data**  
   - Manually inserted 18 rows of sales data related to different product lines and countries.

4. **Executed SQL Queries**  
   - Queried for:
     - Total revenue  
     - Total quantity ordered  
     - Revenue by product line  
     - Revenue by country  
     - Most sold product line

5. **Loaded SQL Results into Pandas**  
   - Used `pd.read_sql_query()` to handle query outputs for analysis and visualization.

6. **Printed Data Summary in Console**  
   - Displayed results of each SQL query using `print()`.

7. **Plotted Revenue by Product Line**  
   - Used `matplotlib.pyplot` to generate a bar chart visualizing product-wise revenue.

---

### 🧠 Skills Practiced

- Writing basic SQL queries inside Python
- Creating and managing SQLite databases
- Data manipulation with pandas
- Basic data visualization with matplotlib

---
