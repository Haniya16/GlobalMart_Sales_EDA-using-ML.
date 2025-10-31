🛍️ GlobalMart Sales Data Analysis (EDA)

This project performs Exploratory Data Analysis (EDA) on a sales dataset using Python.
It provides detailed data visualizations, statistical summaries, and an automatically generated PDF report summarizing the findings.

📘 Project Overview

The goal of this project is to analyze supermarket sales data and extract meaningful insights about:
Top-performing products
Sales trends by country
Customer segment distribution
Sales representatives’ performance
Correlation among numeric features
Outlier detection using boxplots

Finally, a summary report of key insights is generated and exported as a PDF.

⚙️ Technologies Used
Category	Tools / Libraries
Programming Language	Python
Data Analysis	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Reporting	Matplotlib PDFPages
Environment	Google Colab

📂 Folder Structure
📁 GlobalMart_EDA_Project
│
├── supermarket_sales.csv                # Dataset file
├── GlobalMart_Sales_Graphs.pdf          # PDF with visualizations
├── GlobalMart_Sales_Insights.pdf        # PDF with insights summary
├── GlobalMart_Sales_EDA.ipynb           # Google Colab notebook
└── README.md                            # Project documentation

🔍 How to Run in Google Colab

Mount Google Drive
from google.colab import drive
drive.mount('/content/drive')

Upload Dataset
Place your dataset (supermarket_sales.csv) in the same folder as your notebook.
Run Steps in Order

STEP 1 → STEP 2 → STEP 3 → STEP 4 → STEP 5


Step 4: Generates visualizations PDF

Step 5: Generates insights summary PDF and displays summary in runtime

View Generated Files

GlobalMart_Sales_Graphs.pdf → Visual graphs

📊 Generated Reports
1️⃣ GlobalMart_Sales_Graphs.pdf

Contains:

Top 10 Selling Products
Total Revenue by Country

Customer Segment Distribution

Sales by Sales Representative
Correlation Heatmap
Revenue Boxplot

2️⃣ GlobalMart_Sales_Insights.pdf
Contains:
Dataset Overview

Revenue, Product, and Geographical Insights
Customer Segment & Sales Rep Analysis
Correlation and Observations Summary

✨ Output Example
GLOBALMART SALES ANALYSIS - INSIGHTS SUMMARY
-------------------------------------------------------------
Date Generated: 2025-10-31

Total Records: 1000
Total Columns: 12

Top Country by Revenue: United States
Top Product: Health and Beauty
Dominant Customer Segment: Member

🧠 Learning Outcome
Through this project, you will learn:
How to clean and preprocess real-world datasets.

How to visualize relationships and patterns in sales data.

How to automate report generation using Python.
