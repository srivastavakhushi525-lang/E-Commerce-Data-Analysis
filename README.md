
# 🛒 E-Commerce Sales Data Analysis & Power BI Dashboard
📌 Project Overview

This project focuses on analyzing E-Commerce sales data to identify sales trends, customer purchasing patterns, top-performing products, profitable products, payment preferences, and geographical performance.
The project follows a complete Data Analyst workflow, starting from raw/uncleaned Excel data and progressing through Python data cleaning, SQL analysis, Power Query transformation, and Power BI dashboard development.
The objective was to transform raw business data into meaningful insights that can help management make data-driven decisions.


🎯 Problem Statement

An E-Commerce company has a large dataset containing sales transactions, but the raw data contains inconsistencies and requires cleaning before it can be used for analysis.

The business wants to understand:

📊 What is the total sales and total profit?

🛒 How many orders were placed?

📈 How are sales changing over time?

🏆 Which products generate the highest sales?

💰 Which products generate the highest profit?

🌎 Which cities/states generate the most sales?

💳 Which payment methods are most commonly used?

📦 Which product categories perform best?

📅 Which months have the highest and lowest sales?

The goal was to clean, analyze, and visualize the data to provide actionable business insights.

🔄 Project Workflow

              Raw Excel Data

                     ↓
             Python (Pandas & NumPy)

                     ↓
        Data Cleaning & Preprocessing

                     ↓
               Clean CSV File

                     ↓
                 SQL Server

                     ↓
          Business Analysis using SQL

                     ↓
                 Power Query

                     ↓
          Final Data Transformation

                     ↓
                 Power BI

                     ↓
          Interactive Dashboard & Insights

🧹 Step 1 — Data Cleaning Using Python

The original dataset was first loaded into Jupyter Notebook using Python.

Libraries Used

🐍 Python

🐼 Pandas

🔢 NumPy

Data Cleaning Activities

The raw dataset was inspected and cleaned using Python. The cleaning process included:
Checking the structure of the dataset
Inspecting missing values
Identifying duplicate records
Correcting inconsistent data
Standardizing columns
Handling incorrect/missing values
Converting columns into appropriate data types
Performing necessary transformations
Validating the cleaned dataset

After completing the cleaning process, the final dataset was exported into a CSV file for further analysis.

🔄 Project Workflow

                  Excel File

                       ↓
                Pandas DataFrame

                       ↓
                 Data Inspection

                       ↓
                 Data Cleaning

                       ↓
               Data Transformation

                       ↓
                 Clean Dataset

                       ↓
                    CSV File

Python Notebook

[E-Commerce_Data_Cleaning_python.ipynb](https://github.com/user-attachments/files/32238957/E-Commerce_Data_Cleaning_python.ipynb)

🗄️ Step 2 — SQL Analysis

The cleaned CSV data was then imported into SQL Server for further business analysis.
SQL was used to answer important business questions and generate analytical insights.

SQL Analysis Performed

📦 Total Orders

Calculated the total number of orders using COUNT().

💰 Total Sales

Calculated total revenue using:

             sum(Net_Amount)

Top Products

Grouped products and calculated their total sales:

      Group by Products
      Order by sum(Net_Amount) DESC

🌆 Top Cities

Analyzed sales performance by city.

💵 Highest Profit Products

Calculated total profit for each product and ranked products based on profitability.

💳 Payment Mode Distribution

Analyzed the number of orders for different payment methods such as:

.COD

.UPI

.Card

.Net Banking

.Wallet

SQL Query Screenshot



🧹 Step 3 — Power Query Transformation

After SQL analysis, the data was further checked and transformed using Power Query.
Power Query was used for the final data preparation before visualization.

Transformation Activities

.Removing unnecessary data

.Checking data types


.Standardizing columns


.Handling inconsistencies

.Checking duplicates

.Formatting fields

.Preparing data for Power BI

  This ensured that the final dataset was clean and suitable for creating the dashboard.
        

📊 Step 4 — Power BI Dashboard

The cleaned and transformed data was finally connected to Microsoft Power BI.
An interactive dashboard was created to provide a clear overview of the company's sales performance.
Dashboard KPIs

The dashboard includes:

    KPI            Value 
    Total Sales     3M
    Total Profit    670.74K
    Total Orders     295
    AverageOrderValue 11.37K 


Dashboard Analysis

The dashboard provides insights into:

📅 Monthly sales trends


📈 Year/month sales performance

🗺️ State-wise sales and profit

💳 Payment mode distribution

📦 Category-wise sales

🏆 Product-wise sales

🔎 City and month filters




🛠️ Tools & Technologies


Tool and purpose

🐍 Python

For Data cleaning & preprocessing

🐼 Pandas

For Data manipulation

🔢 NumPy


For Data processing

🗄️ SQL Server

For Data analysis

🔄 Power Query

For Data transformation

📊 Power BI

For Dashboard & visualization

📗 Excel

For Raw data source

📝 GitHub
Project documentation & portfolio



📸 Project Screenshots

SQL Analysis

![Image](https://github.com/user-attachments/assets/fe6d5c83-efe5-474a-a1bc-16294a6a3ead)

�
Power BI Dashboard

![Image](https://github.com/user-attachments/assets/44bc085a-d4ee-41d9-9119-97093abbc19f)


🚀 Project Outcome

This project demonstrates an end-to-end Data Analytics workflow, starting with raw business data and converting it into actionable insights.
The project helped me practice:

Data Cleaning → Data Transformation → SQL Analysis → Data Visualization → Business Insights

It also demonstrates practical experience with Python, SQL, Excel, Power Query, and Power BI.


 
         
