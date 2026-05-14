# 📊 Sales Performance Dashboard
This project analyzes and visualizes sales performance across 6 US states over 5 years (2020–2025) using Power BI, uncovering key insights on revenue, profit, and product trends.

---

# Table of Content

* [Brief](#Brief)
* [DataSet](#DataSet)
* [How It Works](#How_It_Works)
* [Tools](#Tools)
* [Dashboard Visuals](#Dashboard_Visuals)
* [Key Insights](#Key_Insights)
* [Remarks](#Remarks)
* [Usage](#Usage)

---

# Brief

Sales performance is influenced by various factors such as product category, geographic location, order volume, and seasonal trends.
Understanding these factors helps businesses identify top-performing regions and products, optimize pricing strategies, and improve profitability.
In this project, we use **Power BI** to clean raw sales data, build interactive visualizations, and create a professional dashboard that reveals **$6.18M in revenue** and **$1.61M in profit** across multiple states and product categories.

---

# DataSet

The dataset used in this project is a sales transactions dataset containing **1,194 records** and **12 columns** covering orders from **2020 to 2025**.

| Column | Description |
|--------|-------------|
| `Order ID` | Unique order identifier |
| `Amount` | Total order amount ($) |
| `Profit` | Profit earned per order ($) |
| `Quantity` | Number of items ordered |
| `Category` | Product category |
| `Sub-Category` | Product sub-category |
| `PaymentMode` | Payment method used |
| `Order Date` | Date of the order |
| `CustomerName` | Name of the customer |
| `State` | US state of the order |
| `City` | City of the order |
| `Year-Month` | Year and month of the order |

**Categories:** Electronics, Office Supplies, Furniture

**Sub-Categories:** Laptops, Phones, Printers, Markers, Tables, Chairs, Sofas, Paper, Pens, Binders, Bookcases, Electronic Games

**States:** New York, California, Florida, Texas, Illinois, Ohio

---

# How It Works

1. **Data Loading** — Import raw CSV data into Power BI
2. **Data Cleaning** — Handle nulls, fix data types, remove duplicates using Power Query
3. **Data Modeling** — Create relationships and calculated columns
4. **DAX Measures** — Build KPI calculations (Total Revenue, Profit, Gross Rate)
5. **Visualization** — Design interactive charts and dashboard layout
6. **Insights** — Extract business insights from visual analysis

---

# Dashboard Visuals

| Visual | Description |
|--------|-------------|
| **KPI Cards** | Sum of Quantity, Gross Rate, Sum of Amount, Count of Orders, Sum of Profit |
| **Bar Chart** | Count of Order ID by State |
| **Donut Chart** | Sum of Profit by Category |
| **Line Chart** | Count of Order ID by Year (2020–2025) |
| **Horizontal Bar** | Sum of Profit by Sub-Category |
| **Stacked Column** | Sum of Profit by Sub-Category stacked by Category |

---

# Key Insights

- 📦 **12,750** total units sold
- 💰 **$6.18M** total revenue
- 📈 **$1.61M** total profit
- 🏆 **New York** is the top state by order count
- 🥇 **Office Supplies** leads profit at **34.24%**
- 📅 Sales **peaked in 2022** then stabilized
- 🖊️ **Markers** is the most profitable sub-category

---

# Tools

  I. Power BI Desktop

  II. Power Query (Data Cleaning & Transformation)

  III. DAX (Calculated Measures & KPIs)

  IV. Microsoft Excel (Data Preview)

---

# Remarks

* This dashboard was built and tested in **Power BI Desktop**.

* Ensure you have Power BI Desktop installed before opening the `.pbix` file:
  ```
  Download: https://powerbi.microsoft.com/desktop
  ```

* Canvas size is set to **1280 × 720 px** (16:9) for best viewing experience.

* Dark theme colors used:
  ```
  Background:   #0b1120
  Card/Chart:   #111e35
  Accent Blue:  #38bdf8
  Accent Purple:#818cf8
  Accent Green: #34d399
  ```

---

# Usage

To begin utilizing this project, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Sales-Performance-Dashboard
   ```

2. Open the `.pbix` file in **Power BI Desktop**

3. If the data source path changes, update it via:
   ```
   Home → Transform Data → Data Source Settings
   ```

4. Refresh the data:
   ```
   Home → Refresh
   ```

5. Explore the dashboard using the filters and slicers

---

# Author

**Your Name**
- LinkedIn: [your-linkedin-url](https://linkedin.com)
- GitHub: [your-github-url](https://github.com)

---

# License

This project is open source and available under the [MIT License](LICENSE).
