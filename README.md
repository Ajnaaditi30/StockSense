**Dead-Stock-Risk-Prediction**

It is a Python-based Inventory Management and Risk Classification System developed using Streamlit and MySQL.
The system identifies slow-moving and stagnant products (dead stock) using rule-based risk logic and displays results in an interactive dashboard.

**1.What is Dead Stock?**

Dead stock refers to inventory that has not been sold for a long period of time and is unlikely to be sold in the future.
It blocks working capital, increases storage costs, and reduces overall business profitability.

**2.Objective**

The primary objective of this project is to identify and classify slow-moving inventory using Python-based analysis.
The system categorizes products into High, Medium, and Low Risk based on stock quantity and days since last sale.

**3.Dataset**

The dataset consists of product inventory records including:

Product ID

Product Name

Category

Stock Quantity

Last Sale Date

Unit Price

(Data stored in MySQL database)

**4.Risk Classification Logic**

If days since last sale > 90 and stock > 30 → High Risk

If days since last sale > 30 → Medium Risk

Else → Low Risk

**5.Features**

User Authentication (Login / Signup)

Inventory Dashboard

Risk Categorization

Data Filtering & Search

Visualization using Charts

MySQL Database Integration

**6.Libraries Used**

Streamlit (for GUI dashboard)

Pandas (for data manipulation)

NumPy (for numerical operations)

Matplotlib (for data visualization)

MySQL Connector (for database connectivity)

Datetime (for date calculations)

**7.About**

Dead Stock Risk Prediction System using Python and MySQL for inventory optimization.

Topics

python inventory-management mysql streamlit pandas matplotlib data-analysis risk-classification dashboard
