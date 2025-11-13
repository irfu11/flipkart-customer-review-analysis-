📊 Flipkart Product Analytics Dashboard — Power BI

🧠 Overview

This project presents an interactive Power BI dashboard built using a Flipkart product dataset.
The goal of this dashboard is to analyze product performance, customer ratings, and category trends, enabling data-driven insights into online retail analytics.

🚀 Key Objectives

Understand how price, rating, and reviews influence product popularity.

Identify top-performing categories and products.

Visualize customer engagement trends across product types.

Showcase data analytics and visualization skills using Power BI.

🧾 Dataset Information

Dataset Name: Flipkart Product Dataset

Source: Public dataset (cleaned for analysis)


Key Columns:

Product Name — Name of the product listed on Flipkart

Price — Product price in INR

Rating — Average customer rating

Reviews — Number of customer reviews

Category — Product category (e.g., Mobiles, Laptops, Footwear).


📈 Dashboard Features
1️⃣ KPI Cards

Total Products

Average Rating

Average Price

Total Reviews

2️⃣ Category Analysis

Bar chart showing average rating and review count by category

Tree map showing product distribution across categories

3️⃣ Price vs Rating Relationship

Scatter plot to visualize the correlation between product price and customer ratings

4️⃣ Top 10 Products

Ranked table showing top-rated and most-reviewed products

5️⃣ Review Distribution

Column chart showing rating frequency (1–5 stars)

6️⃣ Interactive Filters

Slicers for Category, Rating Range, and Price Range.


🧮 Tools & Technologies Used
| Tool                                | Purpose                                   |
| ----------------------------------- | ----------------------------------------- |
| **Power BI Desktop**                | Data visualization and dashboard creation |
| **Microsoft Excel / CSV**           | Data cleaning and formatting              |
| **DAX (Data Analysis Expressions)** | Measures and calculated columns           |
| **GitHub**                          | Project documentation and version control |


⚙️ DAX Formulas Used
-- Total Products
Total Products = COUNTROWS(Flipkart)

-- Average Rating
Average Rating = AVERAGE(Flipkart[Rating])

-- Total Reviews
Total Reviews = SUM(Flipkart[Reviews])

-- Average Price
Average Price = AVERAGE(Flipkart[Price])

-- Distinct Categories
Distinct Categories = DISTINCTCOUNT(Flipkart[Category])


🎨 Dashboard Theme

Colors inspired by Flipkart branding (Blue #2874F0, Yellow #FFD700)

Clean white background for professional readability

Minimalist layout with clear KPI and data hierarchy

🧩 Insights Derived

Electronics and Clothing are the top-selling categories.

Higher-rated products don’t always have higher prices — pricing strategy varies by category.

A few products dominate in review count, indicating strong brand loyalty or marketing success.

💼 Use Case

This dashboard demonstrates real-world data analytics and business intelligence skills, useful for:

Data Analyst / BI Internships

E-commerce analytics portfolios

Retail business decision-making.



Screenshot/Demo
Example :- https://github.com/irfu11/flipkart-customer-review-analysis-/blob/main/snap.png
