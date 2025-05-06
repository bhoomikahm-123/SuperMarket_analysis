🛒 Supermarket Sales Analysis Project
📌 Objective
This project analyzes transactional data from a supermarket to derive meaningful insights on product performance, customer behavior, seasonal trends, and profitability using Microsoft Excel (without Power Query).

📁 Data Sources
1. Input Data
This sheet contains all transactional records.

Column	Description
DATE	Date of the transaction
PRODUCT ID	Unique product identifier
QUANTITY	Units sold
SALE TYPE	Channel (Wholesaler, Direct Sales, Online)
PAYMENT MODE	Mode of payment (Cash, Online, etc.)
DISCOUNT %	Discount percentage applied
PRODUCT	Product name
CATEGORY	Product category
UOM	Unit of Measure (Kg, Lt, etc.)
BUYING PRIZE	Cost per unit
SELLING PRICE	Selling price per unit
TOTAL BUYING VALUE	Total cost (QUANTITY * BUYING PRIZE)
TOTAL SELLING VALUE	Total revenue (QUANTITY * SELLING PRICE)
DAY, MONTH, YEAR	Extracted from DATE for analysis

2. Master Data
Column	Description
PRODUCT ID	Product code
PRODUCT	Product name
CATEGORY	Category classification
UOM	Unit of measure
BUYING PRIZE	Purchase price per unit
SELLING PRICE	Selling price per unit

3. Analysis
Pre-built pivot tables and summaries for:

Total Monthly Sales and Profit

Category-wise Sales Distribution

Top-Selling Categories

Sale Type Breakdown

Payment Mode Preferences

🧠 Key Excel Features Used
✅ Pivot Tables
Created dynamic pivot tables for sales trends, category performance, and month-wise breakdowns.

Used grouping on date fields (DAY, MONTH, YEAR).

✅ Calculated Columns
Total buying and selling values calculated directly in the Input Data sheet.

Profit margin % = (Selling Price - Buying Price) / Buying Price.

✅ Conditional Formatting
Heatmaps to visualize sales trends over months and categories.

Highlighted top-performing categories and products.

✅ Charts (optional)
Column and pie charts for:

Monthly Revenue

Category Contribution

Payment Mode Share

✅ Lookup Functions
VLOOKUP / XLOOKUP used to map product IDs to details in Master Data (if needed).

🏁 Final Insights Delivered
Total Sales: ₹401,411.92

Total Buying Cost: ₹332,504.00

Total Profit: ₹68,907.92

Profit Percentage: ~20.7%

Top Category: Category04

Top Sales Channel: Direct Sales

Top Payment Method: Online
