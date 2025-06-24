# Data-Visualization-and-Storytelling-task_2-

# 🛍 Superstore Data Analysis & Visualization

## 📌 Objective
To explore and analyze the Superstore sales dataset through data cleaning, transformation, and powerful visual storytelling using Python (Colab). The goal is to derive actionable business insights and present them clearly through meaningful charts.

---

## 📁 Dataset

**File:** `Sample - Superstore.csv`  
The dataset contains information on customer orders from a US-based retail store, including:
- Sales, Profit, Discount, Quantity
- Order and Ship Dates
- Product Category/Sub-category
- Region, Customer, and Location details

---

## 🧹 Data Cleaning Steps

Performed in Colab using `pandas`:
- Removed duplicate rows
- Converted date columns (`Order Date`, `Ship Date`)
- Handled missing/null values
- Verified categorical columns (e.g., Region, Category)
- Detected and removed extreme outliers in `Profit`
- Created derived columns:
  - `Month`, `Year` from Order Date
  - `Profit Ratio` (Profit / Sales)

---

## 📊 Visualizations (Seaborn & Matplotlib)

1. **Total Sales by Region**  
2. **Sales & Profit Trend Over Time**  
3. **Sales by Category & Sub-Category**  
4. **Discount vs Profit Scatter Plot**  
5. **Top 10 Customers by Sales**  
6. **Total Profit by Sub-Category**  
7. **Sales vs Quantity by Sub-Category (Bubble Plot)**

---

## 💡 Insights

- 📈 **West** and **East** are the top performing regions.
- 💰 **Technology** category yields the highest profits.
- 🚨 High **discounts** often correlate with **losses**.
- 🗓 Sales peak during **November–December** (seasonal).
- 🧑‍💼 A small set of customers accounts for a large portion of revenue.
- ❗ Certain **sub-categories such as Tables** show overall **negative profit**, indicating a need for review or repositioning.
- ⚖️ Some sub-categories show **high quantity sold but low total sales**, revealing low-value, high-effort products that may not be efficient to push.


---

## 🚀 Tools Used

- Python (Google Colab)
- Pandas, Seaborn, Matplotlib
- CSV file handling with encoding fixes (`ISO-8859-1`)

---

## 🧠 Author

Akshitha Reddy  
Data Analyst Internship — Task 2  
Visualization & Storytelling using Python and Colab

