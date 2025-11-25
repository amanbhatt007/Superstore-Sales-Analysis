# Superstore-Sales-Analysis
## Project Objective
To conduct a comprehensive Exploratory Data Analysis (EDA) on the Superstore Sales dataset to identify key business performance indicators, uncover sales trends and patterns across different product categories, customer segments, and geographical regions, and ultimately provide actionable, data-driven insights to optimize business strategy, inventory management, and marketing efforts.


## Dataset Used
- <a href="https://github.com/amanbhatt007/Superstore-Sales-Analysis/blob/main/train.csv">Superstore Sales Dataset</a>


##  Questions (KPI)
- Which product categories are the primary revenue drivers?
- Which sub-categories should be prioritized for inventory?
- Is the business growing annually, and is it seasonal?
- When is the best time for deep sales or promotions?
- Which regions are performing the strongest/weakest?
- Which states require targeted sales efforts?
- Which customer segment is the most valuable?
- What is the most popular and efficient shipping method?

- Dashboard Interaction <a href="https://github.com/amanbhatt007/Superstore-Sales-Analysis/blob/main/Project%201.png">View Dashboard</a>


## Process
Step 1: Get the Raw Data 📥
You started with the raw, messy Superstore Sales data contained in your CSV file (- <a href="https://github.com/amanbhatt007/Superstore-Sales-Analysis/blob/main/train.csv">Superstore Sales Dataset</a>). This file lists every single order line item.

Step 2: Clean and Prepare 🧹
You loaded the data and tidied it up. This involved getting rid of any unnecessary blank columns (Unnamed columns) and ensuring the key numbers, like the Sales column, were correctly recognized so they could be added together.

Step 3: Define the Question ❓
You decided on a specific Key Performance Indicator (KPI) to measure, for example:

"Which Product Category generates the highest total sales revenue?"

Step 4: Crunch the Numbers (Aggregate) ➕
You took the hundreds of individual sales records and grouped them by the Category column. Then, you added up (summed) the total sales for each group (Technology, Furniture, Office Supplies).

Step 5: Rank the Results 🥇
You sorted the calculated sales totals so the category with the most revenue appears first, and the category with the least revenue appears last. This makes the data immediately comparable.

Step 6: Create the Picture (Visualize) 📊
You took the ranked numbers and converted them into a bar chart. This visualization instantly and clearly shows which product category bar is the tallest.
