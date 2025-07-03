# Retail Sales Dashboard – Power BI Project

## Overview

This project is a data visualization and analysis dashboard built using Microsoft Power BI. The dashboard provides interactive insights into sales, profit, discounting patterns, and product performance using the Sample Superstore dataset. The goal is to assist business decision-makers in tracking key retail metrics and identifying trends.

---

## Features

- Interactive KPI cards using DAX measures
- Profit trend analysis over time
- Sales and profit by category and sub-category
- Pie chart showing sales by shipping mode
- Customer-level insights using tables
- Region-based filtering using slicers
- Clean formatting and layout for clarity

---

## Dataset

**Source:** Sample Superstore Dataset  
**Format:** CSV  
**Key Fields:**
- Order ID
- Order Date
- Customer Name
- Region
- Sales
- Profit
- Discount
- Quantity
- Ship Mode
- Category
- Sub-Category

---

## DAX Measures Used

- `Total Orders` – Count of distinct orders
- `Profit Margin` – Ratio of profit to sales
- `Sales per Order` – Average sales per order
- `Total Quantity Sold` – Sum of quantity sold
- `Average Discount` – Average discount across all orders
- `Negative Profit` – Total value of orders with negative profit

All DAX formulas are available in the [DAX_Formulas.txt](./DAX_Formulas.txt) file.

---

## File Structure

Retail-Sales-Dashboard/
├── Retail_Sales_Dashboard.pbix
├── sample_superstore.csv
├── DAX_Formulas.txt
├── screenshots/
│ ├── dashboard.png
└── README.md

---

## Setup Instructions

1. Clone the repository or download it as a ZIP file.
2. Open the `Retail_Sales_Dashboard.pbix` file using Power BI Desktop.
3. Ensure that the dataset is correctly loaded (use `sample_superstore.csv` if needed).
4. Interact with slicers and visuals to explore insights.

---

## Demo Video

Watch the walkthrough and explanation on Loom:  
https://www.loom.com/share/8cc80ad138284335b8c2ede228a50b47?sid=c9747495-6170-431c-a783-dda96a36ba10

---

## Author

Ansh Khjauria 

---

## License

This project is provided for educational and demo purposes. Feel free to reuse with attribution.
