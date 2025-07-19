# Blinkit-Data-Analysis
<img width="876" height="496" alt="image" src="https://github.com/user-attachments/assets/5ab70209-a06a-45ad-8d0f-451f231f6bd9" />


This is a Power BI project I worked on where I analyzed Blinkit's data. Blinkit is a quick-commerce app that delivers groceries, and I thought it would be fun to break down how things work behind the scenes using data.
I used sample data and created a full dashboard to understand things like which products are in demand, when people order the most, and how the sales are trending.

---

##  Dashboard & Charts Explanation

I divided the report into different sections to focus on specific questions. Here's a breakdown of all the charts I included:

### 1. **Total Sales, Total Orders & Avg. Order Value (KPI Cards)**
At the top of the report, I added three KPI cards:
- **Total Sales** – This shows how much revenue was generated overall.
- **Total Orders** – Just counts how many orders were placed.
- **Average Order Value** – This one divides total sales by total orders to see how much customers usually spend per order.
These give a quick overview of how the business is doing.

---

### 2. **Monthly Sales Trend (Line Chart)**
This line chart shows how the sales changed over different months.  
I used it to figure out which months performed better and if there are any seasonal trends (like sales going up in festive months or dipping during off-seasons).

---

### 3. **Top 10 Selling Products (Bar Chart)**
I made a bar chart that shows the top 10 products based on how much revenue they brought in.  
This helped me identify what people are buying the most. For example, dairy products or packaged snacks were ranking higher in the sample data.

---

### 4. **Orders by Day of the Week (Column Chart)**
This chart helped me see which days are the busiest for Blinkit.  
Interestingly, I noticed that weekends (especially Saturday and Sunday) had more orders. Probably because people stock up on groceries for the week.

---

### 5. **Orders by Time of the Day (Pie Chart)**
I used a pie chart to check what time slots are most active.  
Most orders were placed in the evening, which makes sense because people usually order after work.

---

### 6. **Product Category-Wise Sales (Donut Chart)**
Here, I broke the sales down by product categories like Beverages, Dairy, Snacks, Fruits & Vegetables, etc.  
It helped me see which types of products are the biggest contributors to total sales.

---

### 7. **New vs Returning Customers (Stacked Column Chart)**
This one compared how many new customers placed orders vs how many existing customers returned.  
This chart gave me insights into customer loyalty. More returning customers means the service is probably doing well in customer satisfaction.

---

### 8. **City-wise Order Distribution (Map Visual)**
If the data includes multiple cities, I added a map that shows where the most orders are coming from.  
Bigger circles = more orders. It’s an easy way to find out which cities are performing best.

---

### 9. **Filters / Slicers**
To make the report interactive, I added slicers to filter data based on:
- Product category
- Month
- Customer type (new/returning)
- City
These filters let the user explore the report however they want.

---

This project helped me:
- Practice using Power Query for cleaning raw data
- Use DAX formulas to calculate KPIs like average order value
- Design a dashboard that actually tells a story using visuals
