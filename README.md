📊 Customer Behavior Analysis
🧩 Business Problem

A retail company aims to understand customer shopping behavior in order to improve sales performance, customer satisfaction, and long-term loyalty.
Recent changes in purchasing patterns across demographics, product categories, discounts, subscriptions, and shipping preferences require data-driven analysis to support strategic decisions.

🎯 Business Question
How can consumer shopping data be used to identify trends, improve customer engagement, and optimize marketing and product strategies?

📂 Dataset Overview

📌 Total transactions: 3,900

📌 Attributes per transaction: 18

📌 Missing values: 37 (Review Rating column only)

🔑 Key Fields

Customer demographics (age, gender)

Product category and item purchased

Purchase amount

Review rating

Discount applied

Subscription status

Shipping type

Previous purchases

🛠️ Tools and Technologies

🐍 Python (pandas, numpy)

🗄️ PostgreSQL (SQL analysis)

📊 Power BI (dashboard and visualization)

📓 Jupyter Notebook (data preparation and EDA)

📑 PowerPoint (project presentation)

🔄 Project Workflow
🧹 Data Preparation (Python)

Loaded raw CSV data using pandas

Handled missing values using median imputation by product category

Removed duplicates and corrected data types

Created derived features such as age groups and purchase frequency

🧮 Data Analysis (SQL)

Loaded cleaned data into PostgreSQL

Executed SQL queries using aggregations, subqueries, CTEs, and window functions

Performed customer segmentation and revenue analysis

📈 Visualization (Power BI)

Built an interactive dashboard to analyze:

Revenue trends

Customer segments

Product performance

Demographic patterns

📝 Reporting

Prepared a structured business problem document

Created a presentation summarizing insights and recommendations

🧾 SQL Analysis Scope

The SQL analysis covers:

Revenue comparison by gender

Identification of high-spending customers using discounts

Top products by average review rating

Comparison of purchase amounts by shipping type

Subscription vs non-subscription spending behavior

Discount dependency by product

Customer segmentation (New, Returning, Loyal)

Top products within each category

Subscription behavior of repeat buyers

Revenue contribution by age group

📌 Key Insights

Loyal customers account for the majority of total purchases

Male customers contribute a higher share of total revenue

Gloves, sandals, and boots receive the highest average ratings

A large portion of repeat buyers are not subscribed

Average purchase value is similar for subscribed and non-subscribed customers

📊 Power BI Dashboard

👥 Total customers: 3.9K

💰 Average purchase value: 59.76

⭐ Average rating: 3.75

Interactive filters are available for customer segments, demographics, and product categories.

📁 File: customer behavior.pbix

📁 Project Files

📓 Python notebooks for data cleaning and analysis

🧮 SQL scripts for business queries

📊 Power BI dashboard (.pbix)

📄 Business problem document (PDF)

📑 Project presentation (PPT)

▶️ How to Run
git clone https://github.com/jestinnjohn/Customer-Behavior-Analysis.git
pip install pandas numpy matplotlib seaborn
jupyter notebook


Run SQL queries in PostgreSQL

Open the Power BI dashboard file

Review findings in the PDF and PPT

👤 Author

Jestin John
📧 Email: jestin john 174@gmail.com

🔗 GitHub: https://github.com/jestinnjohn

🔗 LinkedIn: https://www.linkedin.com/in/jestin-john-5b4079295
