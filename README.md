# Restaurant Sales Analysis with Python

# Project Overview
This project presents a comprehensive sales analysis for a restaurant business using Python. The analysis explores transactional data to uncover trends in food category performance, sales by branch, customer behavior, and other key operational metrics.

# Objective
The goal of this project is to:

Perform exploratory data analysis (EDA) on restaurant transactions.

Evaluate sales and customer feedback by category, branch, and customer type.

Identify actionable insights to improve customer experience and sales strategies.

Calculate important KPIs such as:

Total Revenue

Average Rating

Sales by Gender & Customer Type

Revenue per Branch & Product Line

# Dataset
The dataset contains real-world transactional records from a restaurant chain. Each row represents a purchase, and the features include:

Column	Description
Invoice ID	Unique ID for each transaction
Branch	Branch location (A, B, C)
City	City where the branch is located
Customer type	Member or Normal customer
Gender	Customer gender
Product line	Category of the purchase (e.g., Food, Drinks)
Unit price	Price per item
Quantity	Number of items bought
Tax & Total	Calculated tax and total price
Date, Time	Timestamp of transaction
Payment	Payment method (Cash, Credit Card, etc.)
Rating	Customer feedback score (1–10)

# Tools & Technologies Used
Python – Primary language

Pandas – Data manipulation

Seaborn & Matplotlib – Visualizations

Jupyter Notebook – Analysis environment

# Analysis Workflow

🔹 1. Data Cleaning
Checked for nulls and duplicates

Verified data types (e.g., date/time format)

Created new time-based features (e.g., hour, day of week)

🔹 2. Exploratory Data Analysis (EDA)
Visualized and analyzed:

🏙️ Branch and City Sales
Compared revenue and sales volume across different branches.

🧑‍🤝‍🧑 Gender and Customer Type Behavior
Insights on which gender/customer type purchases more or rates higher.

🍔 Product Line Performance
Analyzed revenue contribution and quantity sold per product category.

🕐 Sales by Time of Day
Identified peak business hours using time-based plots.

💳 Payment Method Preferences
Visualized the most common payment types.

⭐ Customer Rating Distribution
Evaluated overall satisfaction and trends by category/branch.

📌 Key Insights
Branch B recorded the highest revenue, while Branch C had the highest average rating.

Female customers spent slightly more on average and gave higher ratings.

"Food and Beverages" is the top-performing product line.

Evenings (6 PM–9 PM) are peak sales hours.

Credit Card was the most used payment method.

📈 KPIs Calculated
Total Revenue

Average Rating (by branch, gender, and product)

Quantity Sold by Category

Sales Distribution by Time of Day

Top-Selling Product Lines

📦 How to Run the Project
bash
Copy
Edit
# Clone the repository
git clone https://github.com/Harquin14/RESTURANT-SALES-ANALYSIS-WITH-PYTHON.git
cd RESTURANT-SALES-ANALYSIS-WITH-PYTHON

# Install required libraries
pip install pandas matplotlib seaborn

# Run the analysis notebook or script
jupyter notebook restaurant_sales_analysis.ipynb
# or
python restaurant_sales_analysis.py
📌 Recommendations
Promote Branch B with customer engagement programs based on its revenue potential.

Extend hours for Branch C and leverage its higher customer satisfaction.

Tailor marketing toward female and member customers, who show stronger purchase behavior.

Introduce combo offers in high-performing categories like "Food and Beverages."

Optimize staff and kitchen resources during peak time slots in the evening.

🚀 Future Improvements
Integrate sentiment analysis from customer reviews.

Deploy an interactive dashboard (e.g., Tableau, Power BI).

Predict future revenue using time series models.

Expand dataset with delivery orders and loyalty program data.

📝 License
This project is licensed under the MIT License.

📬 Contact
Simon Owusu Ansah
📧 skemsit0@gmail.com
🔗 GitHub
🔗 Tableau Portfolio
