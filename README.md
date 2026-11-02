# PR.2 – Excel Analyzer

## 📌 Project Title
**Customer Sales Data Analyzer using Microsoft Excel**

## 📖 Introduction
The Excel Analyzer project is developed using Microsoft Excel. The main purpose of this project is to analyze customer sales data and present useful information in a clear and organized format.

Microsoft Excel is a powerful tool used for data entry, data management, calculations, analysis, and visualization. In this project, I used Excel features and formulas to understand sales performance, calculate important values, and create a dashboard.

This project helped me improve my practical knowledge of Microsoft Excel and understand how raw data can be converted into meaningful information.

## 🎯 Project Objectives
The main objectives of this project are:

- To organize customer sales data in Excel.
- To understand and analyze the given dataset.
- To calculate total sales, total quantity, and total profit.
- To analyze sales according to product categories.
- To use Excel formulas for automatic calculations.
- To create charts for data visualization.
- To design a professional dashboard.
- To present important information in a simple and understandable way.

## 📝 Project Overview
This project focuses on analyzing customer sales information. The dataset contains information related to customers, regions, product categories, sales, quantity, discounts, order dates, and profit.

The data is organized in the Dataset sheet. Different calculations are performed using Excel formulas. The results are displayed in the Sales Analysis sheet and the Dashboard sheet.

The dashboard provides a quick view of important sales information and helps users understand the overall performance of the data.

## 📂 Dataset Description
The dataset contains the following columns:

| Column | Description |
|---|---|
| Customer_ID | Unique identification number of a customer |
| Customer_Name | Name of the customer |
| Region | Region where the order was placed |
| Product_Category | Category of the product |
| Sales | Total sales amount |
| Quantity | Number of products sold |
| Discount | Discount applied to the order |
| Order_Date | Date of the order |
| Profit | Profit earned from the order |

The dataset is used as the main source for all calculations and analysis in this project.

## 🛠️ Tools and Technologies
The following tools and features were used:

- Microsoft Excel
- Excel Worksheets
- Excel Formulas
- Data Formatting
- Tables and Borders
- Charts
- Dashboard Design

## 📊 Excel Functions and Formulas Used

### 1. SUM Function
The SUM function is used to calculate the total of numeric values.

Example:

`=SUM(Dataset!E2:E202)`

This formula calculates the total sales.

### 2. SUMIF Function
The SUMIF function is used to calculate the total sales for a specific product category or region.

Example:

`=SUMIF(Dataset!D2:D202,A14,Dataset!E2:E202)`

This formula calculates sales for the category mentioned in cell A14.

### 3. COUNTIF Function
The COUNTIF function is used to count cells that match a particular condition.

Example:

`=COUNTIF(Dataset!D:D,A16)`

This formula counts the number of records matching the category in cell A16.

### 4. UNIQUE Function
The UNIQUE function is used to display distinct customer names from the dataset.

Example:

`=UNIQUE(Dataset!B2:B202)`

This helps identify unique customer names without displaying duplicates.

## 📈 Sales Analysis
The Sales Analysis sheet contains important calculations performed on the dataset.

The analysis includes:

- Total Sales
- Total Quantity
- Total Profit
- Region-wise Sales
- Product Category-wise Sales

These calculations help summarize the data and provide a better understanding of sales performance.

## 🌍 Region-wise Sales Analysis
Sales data is analyzed according to different regions.

The regions included in the analysis are:

- East
- West
- North
- South

The SUMIF function is used to calculate the total sales for each region. This analysis helps compare sales performance between regions.

## 🛍️ Product Category Analysis
Product category analysis is used to compare sales across different product categories.

The categories considered in the analysis are:

- Books
- Clothing
- Electronics
- Sports

The total sales for each category are calculated using the SUMIF function. This analysis helps identify which product categories contribute to the sales.

## 📊 Dashboard
The Dashboard sheet presents important information in a visual and organized format.

The dashboard includes:

- Total Sales
- Total Quantity
- Total Profit
- Product Category Sales Chart

The dashboard makes it easier to understand the results without reviewing every row of the dataset.

## 📉 Data Visualization
A column chart is used to display product category sales.

The chart helps compare the sales of different product categories. Visual representation makes the analysis easier to understand and improves the presentation of the project.

## 🔍 Key Findings
The analysis provides the following important observations:

- Total sales, quantity, and profit can be summarized using Excel formulas.
- Product category analysis helps compare sales between categories.
- Region-wise analysis helps understand sales distribution across regions.
- Charts provide a clear visual comparison of sales information.
- A dashboard helps present important results in one place.

## 🎓 Learning Outcomes
Through this project, I learned:

- How to organize data in Microsoft Excel.
- How to use SUM and SUMIF functions.
- How to use COUNTIF and UNIQUE functions.
- How to calculate totals from a dataset.
- How to analyze sales by region and product category.
- How to create charts in Excel.
- How to design a simple and professional dashboard.
- How to present data in a clear and meaningful format.

## 🚀 How to Use This Project
1. Download or clone this repository.
2. Open the Excel workbook.
3. Go to the Dataset sheet to view the original data.
4. Open the Sales Analysis sheet to view the calculations.
5. Open the Dashboard sheet to view the summary and chart.

## 📌 Conclusion
The Excel Analyzer project demonstrates how Microsoft Excel can be used for data organization, calculations, analysis, and visualization.

By using Excel formulas, charts, and a dashboard, the project converts raw customer sales data into useful information.

This project helped me gain practical experience in Microsoft Excel and improved my understanding of data analysis.

## 👩‍💻 Author
**Dhruvi Pattni**

## 📚 Project Type
Excel Data Analysis Project – PR.2
