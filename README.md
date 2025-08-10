# target-sales-sql-case-study
SQL case study analyzing sales data for a Target retail store.
# 🛒 Target Store Sales Analysis (SQL Case Study)

## 📝 Overview
This project is a business-focused SQL case study aimed at analyzing the sales performance of a Target store using structured query techniques. The goal is to uncover key insights into revenue trends, product performance, customer behavior, and operational efficiency.

## 🧰 Tools & Technologies
- SQL (MySQL)
- DBMS: [MySQL Workbench]
- Excel (for any data prep or exporting)

## 📁 Dataset
The dataset simulates a real-world retail scenario for Target stores and includes the following tables:
- `customers`
- `orders`
- `order_items`
- `products`
- `stores`
- `categories`
- `payments`

Total rows: ~10,000+  
Data timeframe: Jan 2021 – Dec 2021  
Source: [Scaler Academy] 

## 🔍 Process

1. **Data Exploration**
   - Inspected table structures and relationships
   - Used ER diagram to understand joins between orders, customers, and products

2. **Key Business Questions Answered**
   - Is there a growing trend in the no. of orders placed over the past years?
   - Can we see some kind of monthly seasonality in terms of the no. of orders being placed?
   - During what time of the day, do the Brazilian customers mostly place their orders? (Dawn, Morning, Afternoon or Night)
   . 0-6 hrs : Dawn
   . 7-12 hrs : Mornings
   . 13-18 hrs : Afternoon
   . 19-23 hrs : Night
   - Get the month-on-month no. of orders placed in each state.
  

3. **SQL Techniques Used**
   - JOINs (INNER, LEFT)
   - GROUP BY + aggregation (SUM, COUNT, AVG)
   - Subqueries and CTEs
   - Date functions (MONTH, YEAR)
   - ORDER BY and LIMIT for rankings

## 📊 Output

- Get the % increase in the cost of orders from year 2017 to 2018 (include months
between Jan to Aug only).

<img width="612" height="792" alt="image" src="https://github.com/user-attachments/assets/ae598f10-6dbe-4e38-b67b-bcb664e29c6b" />

- Find out the top 5 states with the highest & lowest average delivery time.

<img width="612" height="792" alt="image" src="https://github.com/user-attachments/assets/0399a696-4772-48ed-a084-eddc67cf9b34" />
 

## 🧠 Key Insights

📈 E-commerce growth over the years 2016–2018 with increasing monthly order volumes, reflecting expanding online retail.

🏙️ Higher concentration of orders and customers in major Brazilian states like São Paulo and Rio de Janeiro, indicating regional demand hotspots.

🚚 Average delivery time ranges between 3 to 4 days, with some variability depending on the region. Some delivery delays noted in less accessible areas.

💳 Payment methods vary widely, but credit and debit cards dominate transactions (over 60%), with some use of vouchers and bank transfers.

🛒 Popular product categories and top sellers can be identified by sales volume, but specifics depend on your dataset.

⭐ Customer reviews reveal average ratings around 4 out of 5, with some variance by seller and product category.
## 📌 Conclusion

This case study demonstrates how SQL can drive actionable insights from transactional data. By answering key business questions using real-world datasets, we can help Target make informed decisions on inventory planning, marketing focus, and customer retention.

## 🔗 Links
- 📂 SQL Scripts: [Link to your .sql file in this repo]
