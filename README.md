 
# Product Sales Analysis

# Tables Description
1. Orders Table:
- Contains information about the orders placed by customers.
- Includes order ID, date of the order, customer ID, product ID, and quantity of the product ordered.
2. Products Table:
- Contains information about the products offered by the company.
- Includes product ID, product name, nutritional information (calories, protein, carbs, and fat), and price in Indian Rupees.
3. Customer Table:
- Contains information about the customers who have placed orders.
- Includes customer ID and name.

# Tasks Overview
## Task 1: Cleaning the Bad Data
# Orders Table:
- Eliminate duplicate 'order_id' to prevent double-counting in data analysis.
- Convert the data type of 'product_id' from number to text.
- Replace incorrect entries in the 'qty' field and address data entry issues.
- Substitute any empty values in the 'qty' column with the text 'Not Available'.
# Products Table:
- Remove leading and trailing spaces in the product names.
- Split the 'price (in Rs)' column and extract numerical values. Rename columns accordingly.
# Customer Table:
- Convert all customer names to lowercase.
- Copy and paste customer names permanently using 'Paste Special' -> 'Values'.

## Task 2: Merging Data
- Use VLOOKUP() function to retrieve customer names corresponding to their 'customer_id' in the orders table.
- Use INDEX-MATCH() function to retrieve product names corresponding to their 'product_id' in the orders table.
- Use XLOOKUP() to obtain corresponding prices of the products listed in the orders table.
- Create a new column named "total_price" in the orders table to calculate the product of 'qty' and 'price (in INR)'.

# Note:
Before applying formulas, ensure to change the cell type to 'General'.

This exercise will help you practice data cleaning and merging techniques, essential for data analysis tasks.