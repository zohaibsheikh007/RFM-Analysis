# RFM-Analysis
Customer Segmentation

# Introduction
RFM (Recency, Frequency, Monetary) analysis is a marketing technique used to identify a firm's best customers by measuring certain factors. This project implements RFM analysis using a transactional dataset. It calculates the RFM values, segments the customers into different groups, and visualizes the distribution of these segments.


# Data
The dataset used in this project is a transactional dataset and some of the useful columns were:

CustomerID: Unique ID of the customer

InvoiceDate: Date of the transaction

InvoiceNo: Invoice number

Quantity: Quantity of items purchased

UnitPrice: Price per unit of the item


# RFM Analysis
RFM analysis involves the following steps:

Recency: Time since the last purchase. Calculated as the difference between the current date and the last purchase date.

Frequency: Total number of purchases made by the customer.

Monetary: Total amount spent by the customer.


# Steps in the Notebook
Data Import and Preparation: Load the dataset, handle missing values, and prepare the data.

RFM Calculation: Calculate the Recency, Frequency, and Monetary values for each customer.

Quartile Calculation: Segment the RFM values into quartiles using pd.qcut().

RFM Segmentation: Create RFM scores (custome weightage can be given for R F M as per need) and categorize customers into different segments.

Visualization: Visualize the distribution of customer segments using pie chart.


# Usage
This project can be used to:

Identify high-value customers for targeted marketing.

Improve customer retention strategies.

Analyze customer purchase behavior.


# Requirements
Python 3.x

pandas

matplotlib

numpy


# Results
The RFM analysis segments customers into different groups based on their purchasing behavior. This information can be used to tailor marketing strategies and improve customer engagement.


# Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.
