# Project Documentation

## Dataset
The dataset used for this project can be found here:
[Sales Data](https://www.kaggle.com/datasets/miketaylor123/sales-data)

## Dataset Statistics
**Total Records:** 286,392 entries
**Total Columns:** 36

## About Dataset
The Sales Data dataset contains information about the sales of a company over a period of several years. The dataset includes the following columns:

- Order ID: A unique identifier for each order.
- Product: The name of the product sold.
- Quantity Ordered: The quantity of the product ordered in each order.
- Price Each: The price of each unit of the product.
- Order Date: The date on which the order was placed.
- Purchase Address: The address where the order was shipped.
- The data covers the period from January 2019 to December 2020 and includes over 180,000 rows. This dataset can be used for various types of analysis, such as identifying top-selling products, analyzing sales trends over time, and identifying patterns in customer behavior. It's a great dataset for practicing data cleaning, data preparation, and data visualization techniques.

### Column Descriptions
| # | Column Name | Data Type | Description |
|---|---|---|---|
| 0 | order_id | object | Unique identifier for the order |
| 1 | order_date | object | Date when the order was placed |
| 2 | status | object | Current status of the order |
| 4 | sku | object | Stock Keeping Unit (product code) |
| 5 | qty_ordered | float64 | Quantity of the item ordered |
| 6 | price | float64 | Unit price of the item |
| 7 | value | float64 | Total value (likely Price * Qty) |
| 8 | discount_amount | float64 | Discount amount applied |
| 9 | total | float64 | Final total amount |
| 10 | category | object | Product category |
| 11 | payment_method | object | Payment method used |
| 12 | cust_id | float64 | Unique customer identifier |
| 13 | year | int64 | Year of the transaction |
| 14 | month | object | Month of the transaction |
| 15 | Name Prefix | object | Customer's name prefix |
| 16 | First Name | object | Customer's first name |
| 17 | Middle Initial | object | Customer's middle initial |
| 18 | Last Name | object | Customer's last name |
| 19 | Gender | object | Customer's gender |
| 20 | age | float64 | Customer's age |
| 21 | full_name | object | Customer's full name |
| 22 | E Mail | object | Customer's email address |
| 23 | Customer Since | object | Date when the customer joined |
| 24 | Phone No. | object | Customer's phone number |
| 25 | Place Name | object | Place name associated with the address |
| 26 | County | object | County of the address |
| 27 | City | object | City of the address |
| 28 | State | object | State of the address |
| 29 | Region | object | Region of the address |
| 30 | User Name | object | Customer's username |
| 31 | Discount_Percent | float64 | Discount percentage applied |


---

