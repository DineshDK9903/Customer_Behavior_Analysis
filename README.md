# Customer_Behavior_Analysis
Data Analytics project showcasing customer behavior analysis using SQL, python and Power BI 

🧭 Overview

This project focuses on understanding customer behavior through data analysis and visualization.
The goal is to identify key factors influencing customer purchases, preferences, and engagement.
It demonstrates a full end-to-end data analytics workflow — from data loading and cleaning in Python, querying in SQL, visualizing in Power BI, and summarizing insights in a Gamma presentation.

📂 Dataset

Dataset Name: Customer Shopping Behavior Dataset

Source: Public dataset (Kaggle / Mock Retail Data)

Records: Includes details such as CustomerID, Age, Gender, Product Category, Purchase Amount, Review Rating, and Date of Purchase.

Purpose: To analyze customer demographics, spending patterns, and product preferences to help improve marketing and business strategy.

🛠️ Tools & Technologies
Category	Tools/Technologies
Programming	Python (Pandas, NumPy, Matplotlib, Seaborn)
Database	PostgreSQL / MySQL / SQL Server
Visualization	Power BI
Presentation	Gamma
Environment	Jupyter Notebook / VS Code
🪜 Project Workflow
1. Data Loading (Python)

Imported the dataset using Pandas.

Checked data types, null values, and overall structure.

2. Exploratory Data Analysis (EDA)

Analyzed customer demographics and purchase distributions.

Explored correlations between age, gender, product category, and purchase amount.

Visualized trends and key metrics using Matplotlib and Seaborn.

3. Data Cleaning

Handled missing values in columns like Review Rating.

Removed duplicates and standardized text formats.

Converted columns (e.g., Date of Purchase) into correct data types.

4. SQL Analysis

Loaded the cleaned dataset into a PostgreSQL/MySQL/SQL Server database.

Wrote SQL queries to answer business questions such as:

Which product categories generate the most revenue?

What is the average purchase amount by gender and age group?

Who are the top 10 highest spending customers?

Which regions have the highest sales performance?

5. Power BI Dashboard

Connected Power BI to the SQL database.

Designed an interactive dashboard highlighting:

🧾 Total Revenue & Purchase Count

👥 Customer Demographics (Age, Gender)

🛍️ Top Product Categories

📅 Monthly Purchase Trends

⭐ Review Ratings Distribution

6. Report & Presentation

Created a summary report covering business insights and data-driven recommendations.

Designed a Gamma presentation for professional storytelling — including objectives, findings, visuals, and key outcomes.

📊 Dashboard Preview

(Add Power BI screenshot or link here)

Key Insights Visualized:

Revenue by Product Category

Gender-wise Purchase Analysis

Age Group Spending Trend

Review Ratings Distribution

💡 Results & Insights

High-value customers tend to purchase from a few premium categories.

Female customers showed slightly higher average spending than males in specific segments.

Young adults (25–34 years) are the most active shoppers.

Positive review ratings correlate with repeat purchases and higher average spend.

▶️ How to Run
Prerequisites

Python 3.x

PostgreSQL/MySQL/SQL Server

Power BI Desktop

Steps

Clone the Repository

git clone https://github.com/yourusername/customer-behavior-analytics.git
cd customer-behavior-analytics


Install Required Libraries

pip install -r requirements.txt


Run Python Notebook
Open the Jupyter Notebook and execute all cells for EDA and data cleaning.

Import Cleaned Data to SQL
Use your database connection to import the cleaned dataset.

Run SQL Queries
Execute the SQL scripts from the sql/ folder for analysis.

Open Power BI Dashboard
Connect Power BI to your SQL database or CSV file.

View Gamma Presentation
Open the Gamma link in the presentation/ folder to view the final storytelling presentation.

📁 Folder Structure:
 customer-behavior-analytics

data/                  # Raw and cleaned datasets
notebooks/             # Python notebooks (EDA, cleaning)
sql/                   # SQL query scripts
dashboard/             # Power BI dashboard files (.pbix)
report/                # Project summary report
presentation/          # Gamma presentation link/slides
README.md              # Project documentation

🚀 Key Takeaways

Real-world simulation of a complete data analytics workflow.

Combines Python, SQL, and Power BI for data-driven decision making.

Communicates insights effectively through visual storytelling in Gamma.

Ideal project to showcase analytical thinking, technical skills, and business insight to recruiters.
