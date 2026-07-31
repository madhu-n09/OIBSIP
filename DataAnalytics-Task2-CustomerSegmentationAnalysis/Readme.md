# 🧩 Customer Segmentation Analysis using K-Means Clustering

## 📌 Project Overview
This project performs Customer Segmentation using the Online Retail dataset. The objective is to group customers into different segments  based on their purchasing behaviour using the RFM(Recency,Frequency,Monetary) model and the K-Means clustering algorithm. The analysis helps businesses understand customer behaviour and create targeted marketing strategies.

## 📂 Dataset
The dataset contains online retail transaction records with the following columns:
- Invoice
- StockCode
- Description
- Quantity
- InvoiceDate
- Price
- Customer ID
- Country

## 🔁 Project Workflow
- Data Loading
- Data Cleaning
- Exploratory Data Analysis(EDA)
- Feature Engineering (Sales & RFM)
- Data Scaling
- Elbow Method
- K-Means Clustering
- Cluster Analysis
- Business Recommendations

## 🛠 Technologies Used
- Python
- Pandas
- Numpy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📊 Results
The analysis identify four customer segments:
- **Cluster 0 - Regular Customers:**
Moderate purchase frequency and spending.

- **Cluster 1 - Inactive Customers:**
Low purchase activity and low spending.

- **Cluster 2 - VIP Customers:**
Highest purchase frequency and spending.

- **Cluster 3 - Loyal Customers:**
Frequent purchase with high spending.

## Project Screenshots
![Elbow Method](Screenshots/Elbow%20Method.png)
![Customer Segment_Frequency vs Monetary](Screenshots/Customer%20Segment_Frequency%20vs%20Monetary.png)
![Customer Segment_Recency vs Monetary](Screenshots/Customer%20Segment_Recency%20vs%20Monetary.png)
![Cluster Distribution](Screenshots/Cluster%20Distribution.png)

## 💡Business Recommendations
- Reward VIP customers with exclusive offers and loyalty programs.
- Retain Loyal customers through personalized recommendations.
- Re-engage inactive customers with discounts and email compaigns.
- Encourage regular customers to increase purchase frequency through promotional offers.

## ✅ Conclusion
The K-Means clustering model successfully segmented customers into four distinct groups based on purchasing behaviour. These customer segments can help businesses improve customer retantion, marketing strategies, and overall sales performance.