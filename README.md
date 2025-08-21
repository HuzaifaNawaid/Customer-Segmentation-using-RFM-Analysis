# Customer-Segmentation-using-RFM-Analysis
## 📌 Project Overview
This project implements a comprehensive Customer Segmentation analysis using RFM (Recency, Frequency, Monetary) methodology. RFM analysis is a powerful technique used in marketing to identify valuable customer segments based on their purchasing behavior.

## 📂 Dataset
https://www.kaggle.com/datasets/viridianachow/online-retail-uci-dataset
It contains information like:

- InvoiceNo: Invoice number (unique
identifier for each transaction)
- StockCode: Product code
- Description: Product description
- Quantity: Quantity of each product per transaction
- InvoiceDate: Invoice date and time
- UnitPrice: Unit price of product
- CustomerID: Customer identifier
- Country: Country where customer resides

## 🛠️ Tools & Libraries
- Python 3.x
- Pandas – data handling
- Seaborn – data visualization
- Matplotlib – plotting
- Jupyter Notebook – interactive coding

## 🔍 Steps Performed
1. Data Cleaning and Preparation
Removed records with missing CustomerID values
Handled negative quantities and prices (returns/cancellations)
Created a TotalPrice column (Quantity × UnitPrice)
Removed duplicate records
Converted data types for proper analysis

2. RFM Calculation
Recency: Days since last purchase (calculated from most recent invoice date)
Frequency: Number of purchases made by each customer
Monetary: Total monetary value of all purchases

3. Customer Segmentation
Customers were segmented into 5 groups based on RFM scores:
Best Customers (RFM Score: 444)
Loyal Customers
Potential Loyalists
At Risk Customers
Lost Customers

4. Marketing Strategy Development
Developed targeted marketing strategies for each customer segment to maximize engagement and revenue.

## 📊 Key Insights
- The dataset contains 4,373 unique customers from 38 different countries
- The UK represents the vast majority of customers (over 90%)
- Best Customers represent a small percentage of the customer base but contribute significantly to revenue
- There's a large group of Lost Customers who haven't purchased recently and represent an opportunity for re-engagement campaigns

## 📜 License
This project is distributed under the **MIT License**. See `LICENSE` for more information.

## 📞 Contact
**Huzaifa Nawaid**  
Email: nawaidhuzaifa@gmail.com
