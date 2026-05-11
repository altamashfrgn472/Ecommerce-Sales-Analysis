# E-Commerce Sales Analysis

## Project overview
This project focus on analyzing e-commerece sales data to identify sales tredns, top-performing product categories, high-revenue states, and order status patterns. The analysis was performed using Python and data analysis libraries.

---

## Objective
The main objective of this project is to:
- Analyze sales performances across categories and states
- Identify top-performing product styles
- Understand monthly sales trends
- Analyze order status distribution
- Performing data cleaning and preprocessing on raw sales data

---

## Dataset Information
The dataset contains e-commerce order information such as:
- Order ID
- Date
- Product Category
- Product Style
- Sales Amount
- Quantity
- Order Status
- Shipping State
- Shipping Details

---
## Tools and Libraries Used
- Python
- Pandas
- Numpy
- Matplotlin
- Seaborn
- Jupyter Notebook
- VS Code

---

## Data Cleaning Performed
The following preprocessing steps were performed:
- Removed unnecessary column
- Handled missing values
- Converted date column into datetime format
- Extracted month and year from date
- Standardized state names
- Grouped and simplified order status
- Cleaned inconsistent categorical values

---

## Analysis Performed
The following analyses were performed:
- Total sales analysis
- Category-wise sales analysis
- Monthly sales trend analysis
- Top 10 states by sales
- Top-performing product styles
- Order status distribution analysis

---

## key Insights
- MAharashtra generated the highest slaes revenue among all states
- The 'Set' category cpntrobuted the highest sales revenue
- Style JNE3797 was top-performing product style
- A significant amount f evenue was associated with returned/cancelled orders
- Most orders were in the shipping/in-transit stage

---

## Project Structure
```text
Ecommerce-Sales-Analysis/
│
├── data/
│   ├── raw/
│   ├── cleaned/
│
├── notebooks/
│   ├── sales.analysis.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore