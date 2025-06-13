
# 🚚 Supplier Delivery Performance Tracker

### 📦 A Simple SQLite + Python Project (Carnets iPad)

This project is designed for students and professionals in **Logistics and Supply Chain Systems Engineering** to track and analyze **supplier delivery performance**. Built entirely on an iPad using Python and SQLite in the Carnets Jupyter environment.

---

## 🎯 Objectives

- Record supplier delivery data (expected vs. actual date)
- Monitor delivery punctuality
- Calculate on-time delivery percentage for each supplier
- Visualize supplier performance using a bar chart

---

## 🧰 Tools & Environment

- **Python**: Data analysis and plotting (`sqlite3`, `pandas`, `matplotlib`)
- **SQLite**: Lightweight relational database
- **Carnets**: Jupyter Notebook environment for iPad
- **GitHub**: Version control and project sharing

---

## 🗃️ Database Structure

### 📁 `suppliers` Table
| Column        | Type    | Description             |
|---------------|---------|-------------------------|
| supplier_id   | INTEGER | Primary key (auto ID)   |
| name          | TEXT    | Supplier name           |
| location      | TEXT    | City, country           |
| contact       | TEXT    | Email or phone          |

### 📁 `deliveries` Table
| Column        | Type    | Description                  |
|---------------|---------|------------------------------|
| delivery_id   | INTEGER | Primary key (auto ID)        |
| supplier_id   | INTEGER | Foreign key from suppliers   |
| expected_date | TEXT    | Planned delivery date (YYYY-MM-DD) |
| actual_date   | TEXT    | Actual delivery date (YYYY-MM-DD) |
| product       | TEXT    | Name of the product delivered|
| quantity      | INTEGER | Quantity delivered           |

---

## 📊 Output Example

- Table: Number of total deliveries, on-time deliveries, and on-time delivery percentage
- Chart: Bar chart comparing on-time delivery rates across suppliers

---

## ✅ How to Run

1. Open the `.ipynb` file in **Carnets**
2. Run each cell step-by-step
3. Database `supplier_tracker.db` will be automatically created
4. You’ll see a summary table printed and a bar chart generated

---

## 📈 Sample Chart

![Supplier Performance Chart](example_chart.png)  
*(Optional: Upload a screenshot of your chart and rename it `example_chart.png` for display.)*

---

## 📚 Learning Outcomes

- Hands-on practice with relational databases and SQL
- Calculating key supply chain KPIs (on-time delivery)
- Combining Python with data visualization
- Managing small projects with GitHub

---

## 👩‍🎓 Author

This project is part of my Master's studies in **Logistics and Supply Chain Systems Engineering**.  
Created using only my iPad and a passion for data!

---

## 🔗 License

This project is open-source. Feel free to use it for learning or your own portfolio!
