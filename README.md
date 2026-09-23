# Sales Performance Dashboard – Power BI

## Project Overview

This project is an interactive **Sales Performance Dashboard** created using **Microsoft Power BI**.

The dashboard analyzes sales data to understand business performance through key metrics such as **Sales, Profit, Quantity, Category Performance, Regional Performance, Top Customers, and Sales Trends**.

The project demonstrates the use of **Power Query, DAX, Data Modeling, and Power BI visualizations** to transform raw sales data into meaningful business insights.

---

##  Project Objectives

The main objectives of this project are:

- Analyze overall sales performance
- Track total sales and profit
- Analyze sales by category and sub-category
- Compare regional performance
- Identify top customers
- Analyze sales trends over time
- Create interactive filters and visualizations
- Build an easy-to-understand business dashboard

---

## Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **Data Modeling**
- **Excel / CSV Dataset**
- **Data Visualization**

---

##  Dataset

The project uses a **Superstore Sales Dataset** containing information about:

- Order ID
- Order Date
- Ship Date
- Customer ID
- Customer Name
- Segment
- Country
- City
- State
- Region
- Product ID
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

---

##  Data Preparation

The raw dataset was cleaned and transformed using **Power Query**.

The main data-cleaning steps included:

- Removing empty rows and columns
- Correcting data types
- Formatting date columns
- Converting Sales and Profit into decimal values
- Setting Quantity as a whole number
- Checking missing values
- Preparing the dataset for analysis

---

##  Dashboard Features

<img width="1130" height="643" alt="Screenshot 2026-09-21 011717" src="https://github.com/user-attachments/assets/89b210a5-4bf3-44e5-bde0-85ea50269e5b" />


### 1. Sales Analysis

The dashboard provides an overview of:

- Total Sales
- Total Profit
- Total Quantity
- Sales trends
- Profit trends

### 2. Category Analysis

Sales and profit are analyzed across different product categories and sub-categories.

### 3. Regional Performance

The dashboard compares performance across different regions to identify variations in sales and profit.

### 4. Top Customers

The dashboard identifies customers based on their contribution to overall sales.

### 5. Sales Trend

Time-based analysis is used to understand changes in sales performance over different periods.

### 6. Interactive Filters

Users can interact with the dashboard using filters/slicers such as:

- Region
- Category
- Sub-Category
- Segment
- Date

---

##  DAX

DAX measures were created to calculate important business KPIs.

Example:

```DAX
Total Sales = SUM(Sales[Sales])

## Project Structure

Sales-Performance-Dashboard/
│
├── README.md
│
├── PowerBI/
│   └── Sales_Performance_Dashboard.pbix
│
├── Dataset/
│   └── Superstore_Sales.xlsx
│
├── Images/
│   └── dashboard.png
│
└── Documentation/
    └── Project_Report.pdf
