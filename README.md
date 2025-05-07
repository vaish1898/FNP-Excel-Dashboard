# 🧾 FNP Excel Dashboard Project

📌 **Project Overview**  
Ferns N Petals (FNP), a popular gift delivery platform, specializes in delivering gifts for occasions like Diwali, Raksha Bandhan, and Valentine’s Day. This project explores 1,000 rows of order, customer, and product data using Excel to generate a clean, interactive dashboard uncovering key sales and delivery insights.

---

## 📂 Dataset Description

The project uses three CSV files:
- `orders.csv`: Order_ID, Customer_ID, Product_ID, Quantity, Order_Date	Order_Time, Delivery_Date, Delivery_Time, Location, Occasion
- `products.csv`: Product_ID	Product_Name	Category	Price (INR)	Occasion
- `customers.csv`: ustomer_ID	Name	City	Contact_Number	Email	Gender	Address

---

## 🛠️ Data Preparation & Analysis Workflow

1. **Data Cleaning**: Removed duplicates/nulls, changed types, calculated revenue and delivery time.
2. **Data Modeling**: Used Star Schema with Orders (fact) linked to Products and Customers (dimensions).
3. **Pivot Table Analysis**: Summarized KPIs, trends, product/city performance.
4. **Dashboard Creation**: Built interactive visuals with slicers, cards, charts.

---

## 🎯 Business Questions Answered
The analysis aimed to answer 10 critical business questions:

1. Total Revenue: What is the overall revenue generated?
2. Average Order and Delivery Time: How long do orders take from placement to delivery?
3. Monthly Sales Performance: Are there any seasonal trends?
4. Top Products by Revenue: Which products are the top performers?
5. Customer Spending Analysis: How much do customers spend on average?
6. Top 5 Products Sales Performance: What are the best-performing products?
7. Top 10 Cities by Orders: Which locations have the highest number of orders?
8. Order Quantity vs Delivery Time: Does quantity affect delivery?
9. Revenue by Occasion: Which occasions generate the most revenue?
10. Product Popularity by Occasion: Which products are most ordered for each occasion?

---

## 📊 Key Insights
1. Total Revenue: ₹35,20,984.00;
2. Avg. Order-Delivery Time: 5.53 days;
3. Monthly Sales Trend: Peaks in Feb, Aug, Nov;
4. Top Products by Revenue: Magnam Set, Quia Gift, Dolores Gift, Harum Pack, Deserunt Box;
5. Avg. Customer Spend: ₹3,520.98;
6. Best-Selling Products: Same top 5 as above;
7. Top Cities by Orders: Imphal, Kavali, Haridwar, Dibrugarh, Guniael;
9. Top Revenue Occasions: Anniversary, Raksha Bandhan, Holi, Valentine’s Day;
10. Product Popularity by Occasion: Not shown, suggest adding matrix or stacked chart.

---

## 💡 Recommendations

- Target Valentine’s Day and Raksha Bandhan for promotions
- Expand top-performing products
- Localized marketing in high-order cities
- Launch customer loyalty programs
- Reduce average delivery time

---

## 🛠️ Tools Used

- Microsoft Excel (Power Query, PivotTables, Charts)
- Dataset files: `orders.csv`, `products.csv`, `customers.csv`

---

## 📎 Conclusion

This Excel-based dashboard offers a strategic overview of FNP’s sales and operations, enabling better planning, marketing, and inventory decisions.

---

📸 _Dashboard preview and file available in this repository._  
📬 **Connect with me on [LinkedIn](https://www.linkedin.com/in/vaishnavi-raut18/)**  
