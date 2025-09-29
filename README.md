🍕 Pizza Sales Analysis
=======================

This project analyzes a pizza sales dataset to uncover key business insights such as revenue trends, bestselling pizzas, and customer ordering patterns.

The goal is to provide actionable insights for decision-making (e.g., identifying underperforming menu items, peak sales periods, and customer preferences).

📂 Dataset
----------

The analysis uses four CSV files:

*   **orders.csv** → Contains order timestamps.
    
*   **order\_details.csv** → Contains quantity and pizza ID per order.
    
*   **pizzas.csv** → Contains pizza IDs, sizes, and prices.
    
*   **pizza\_types.csv** → Contains pizza categories and ingredients.
    

🔑 Key Findings
---------------

### 1\. 💰 Total Revenue

*   **Total Sales:** **$817,860.05**
    

### 2\. 📦 Total Quantity Sold

*   **49,574 pizzas** were sold.
    

### 3\. 🛒 Total Orders

*   **21,350 orders** were placed.
    

### 4\. 🍽️ Pizza Types & Price

*   **32 unique pizza types** are on the menu.
    
*   **Average Pizza Price:** **$13.23**
    

### 5\. ⏰ Peak Hours of Sales

*   Sales peaked between **12 PM – 1 PM** (lunchtime) and **5 PM – 7 PM** (dinnertime).
    

📌 **Insight:** These time slots suggest strong demand during meal hours → staff planning & promotions should focus here.

### 6\. 📅 Sales by Day of the Week

*   **Friday had the highest sales**, followed closely by Saturday.
    
*   **Monday had the lowest sales.**
    

📌 **Insight:** Weekends drive demand → “Weekend Specials” promotions may boost revenue further.

### 7\. ⭐ Top 5 Bestselling Pizzas

1.  The Classic Deluxe Pizza
    
2.  The Barbecue Chicken Pizza
    
3.  The Hawaiian Pizza
    
4.  The Pepperoni Pizza
    
5.  The Thai Chicken Pizza
    

📌 **Insight:** Traditional and chicken-based pizzas dominate customer preference.

### 8\. 📉 Worst 5 Selling Pizzas

*   The Brie Carre Pizza (only 490 sold).
    
*   The Mediterranean Pizza.
    
*   The Calabrese Pizza.
    
*   The Spinach Supreme Pizza.
    
*   The Soppressata Pizza.
    

📌 **Insight:** These underperforming pizzas may need menu re-evaluation or marketing push.

### 9\. 📊 Sales by Month

*   **July was the strongest month.**
    
*   **October showed a dip** in sales.
    

📌 **Insight:** Seasonal demand is evident; promotions in slow months could balance revenue.

### 10\. 📈 Average Order Value (AOV)

*   **$38.31 per order**
    

📌 **Insight:** Customers usually order multiple pizzas per transaction. Upselling sides & drinks could further increase AOV.

📊 Visuals
----------

The notebook includes visualizations for:

*   Orders per Day
    
*   Category Breakdown % (pie chart)
    
*   Weekdays vs Weekends Comparison
    
*   Monthly Sales Trends
    
*   Top/Bottom Selling Pizzas
    

🚀 How to Use
-------------

1.  git clone [Click here!](https://github.com/Samuel-Neche/Pizza-Place-Sales-Analysis-Data-Analysis-with-Python.git)
    
2.  pip install -r requirements.txt
    
3.  jupyter notebook pizza\_sales.ipynb
    

📌 Business Recommendations
---------------------------

*   **Menu Optimization:** Remove or promote underperforming pizzas (e.g., Brie Carre).
    
*   **Marketing Strategy:** Focus on **Fridays and Saturdays** with targeted deals.
    
*   **Peak Hours:** Staff more during lunch/dinner rush and run meal-time promotions.
    
*   **Upselling Opportunities:** Introduce bundles with sides/drinks to raise AOV.
    

✍️ **Author:** Samuel Neche
📅 **Year:** 2025
