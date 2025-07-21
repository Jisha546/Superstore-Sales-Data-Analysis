📊 Superstore Sales Data Analysis
Overview
This project analyzes the Superstore dataset to uncover business insights and recommend actionable strategies.
It includes data cleaning, exploratory data analysis (EDA), visualizations, and business recommendations based on sales, profit, discounts, and shipping efficiency.

📄 Dataset
Source: Sample - Superstore.csv

Rows: 9,994

Columns: 20 (after cleaning)

Features:

Order details: order_id, order_date, ship_date, ship_mode

Customer info: customer_id, customer_name, segment, region

Product info: category, sub-category, product_name

Metrics: sales, quantity, discount, profit, shipping_days

🧹 Data Cleaning
✔ Removed duplicates & missing records
✔ Converted Order Date & Ship Date to datetime
✔ Standardized column names to snake_case
✔ Removed irrelevant columns (row_id, postal_code)
✔ Added derived column: shipping_days

🔷 Business Questions
✅ Which regions generate the highest sales & profit?
✅ Which customer segments contribute most to profit?
✅ Which product categories and sub-categories perform best?
✅ How do discounts impact profitability?
✅ How efficient is the shipping process?

📊 Exploratory Data Analysis
📍 Region-wise sales & profit

📍 Segment-wise sales & profit

📍 Category & sub-category performance

📍 Impact of discounts on profits

📍 Shipping efficiency analysis

📈 Visualizations using matplotlib & seaborn

📋 Insights
West & East regions perform the best.

Consumer segment generates the most profit.

Technology category performs better than Furniture.

High discounts (>30%) reduce profits.

Average shipping time is ~4 days.

📌 Recommendations
✔ Invest further in West & East regions.
✔ Improve performance in South region & Home Office segment.
✔ Optimize costs/pricing in Furniture category.
✔ Cap discounts at ~20–30%.
✔ Maintain fast shipping (~3–4 days).

📦 Tools & Skills
Languages & Libraries: Python, pandas, numpy, matplotlib, seaborn

Skills: Data cleaning, EDA, descriptive statistics, business insights, storytelling with data

🚀 How to Run
1️⃣ Clone this repository

bash
Copy code
git clone https://github.com/your-username/superstore-analysis.git
cd superstore-analysis
2️⃣ Install required libraries

bash
Copy code
pip install pandas matplotlib seaborn
3️⃣ Run the Jupyter notebook or Python script

bash
Copy code
jupyter notebook superstore_analysis.ipynb
📜 License
This project is for educational & portfolio purposes.
