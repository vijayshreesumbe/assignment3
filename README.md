# 📊 Sales Data Analysis using Python 🐍

## 📁 Project Overview
This project analyzes sales data using Python, focusing on a subset of key features like:
- `ORDERNUMBER`
- `QUANTITYORDERED`
- `PRICEEACH`
- `ORDERLINENUMBER`
- `SALES`
- `ORDERDATE`
- `MONTH_ID`
- `YEAR_ID`

The goal is to derive insights into sales trends, product performance, and customer purchasing behavior using visualizations and basic analytics.

---

## 🧰 Tools & Libraries Used
- **Python 3.x**
- **Pandas** – for data cleaning and analysis
- **Matplotlib** – for basic plotting
- **Seaborn** – for aesthetic and statistical visualizations

---

## 📌 Key Features & Visualizations

### 1️⃣ Total Sales Per Month
Shows how revenue fluctuates month-by-month.

### 2️⃣ Total Sales Per Year
Identifies the most profitable years in the dataset.

### 3️⃣ Average Order Value (AOV)
Calculates and visualizes the average revenue per order.

### 4️⃣ Quantity Ordered vs. Price Each
Reveals product price vs demand trends through scatter plotting.

### 5️⃣ Sales by Order Line Number
Shows how the position of a product in an order (first, second, etc.) affects revenue.

---

## 📈 Dataset Info
The dataset includes transaction-level data with order dates, quantities, prices, and calculated sales values. Only the following columns were used:

| Column Name        | Description |
|--------------------|-------------|
| `ORDERNUMBER`      | Unique identifier for each order |
| `QUANTITYORDERED`  | Number of units purchased |
| `PRICEEACH`        | Price per unit |
| `ORDERLINENUMBER`  | Line number of the item in the order |
| `SALES`            | Total revenue from the line item |
| `ORDERDATE`        | Date when the order was placed |
| `MONTH_ID`         | Month extracted from the order date |
| `YEAR_ID`          | Year extracted from the order date |

---

## 📁 How to Run

1. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
