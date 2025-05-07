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

- What is total revenue and average customer spend?
- Which occasions and products generate the most revenue?
- What are the top-performing cities?
- Are there seasonal trends in orders and delivery times?

---

## 📊 Key Insights

- **Total Revenue**: ₹35,20,984  
- **Avg. Delivery Time**: 5.53 days  
- **Top Cities**: Imphal, Kavali, Dhanbad  
- **Top Products**: Magnum Set, Qula Gift  
- **Sales Peak**: February & August  

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
