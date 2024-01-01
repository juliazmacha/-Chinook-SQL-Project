# Chinook SQL Project

## Overview

This SQL project focuses on analyzing the Chinook dataset, representing a digital media store. The database includes tables for artists, albums, media tracks, invoices, and customers. The project was executed using SQLite Studio.

## Database Diagram

![chinook](https://github.com/juliazmacha/-Chinook-SQL-Project/assets/115115006/211f84af-3eb4-4d45-9a52-403c10ebe2d7)

### employees Table
- Stores employees' data such as employee ID, last name, first name, etc.
- Contains a field named ReportsTo to specify reporting relationships.

### customers Table
- Stores customers' data.
- The line between employees.EmployeeID and customers.SupportRepID shows the relationship between the two tables.

### invoices and invoice_items Tables
- invoices table stores invoice header data (Customer ID, Billing Address, etc.).
- invoice_items table stores invoice line items data (Unit Price, Quantity).

### Other Tables
- artists, albums, media_types, genres, tracks, and playlists tables store relevant data.

## Project Steps

1. **Data Analysis**
   - Understand the dataset structure and relationships.

2. **Data Cleaning**
   - Ensure data quality and consistency.

3. **Business-Relevant Questions**
   - Formulate queries to address specific business questions.

## SQL Questions: 

### 1. Show Customers (their full names, customer ID, and country) who are not in the US. (Hint: != or <> can be used to say "is not equal to").
### 2. Show only the Customers from Brazil.
### 3. Find the Invoices of customers who are from Brazil. The resulting table should show the customer's full name, Invoice ID, Date of the invoice, and billing country.
### 4. Show the Employees who are Sales Agents.
### 5. Find a unique/distinct list of billing countries from the Invoice table.
### 6. Provide a query that shows the invoices associated with each sales agent. The resulting table should include the Sales Agent's full name.
### 7. Show the Invoice Total, Customer name, Country, and Sales Agent name for all invoices and customers.
### 8. How many Invoices were there in 2009?
### 9. What are the total sales for 2009?
### 10. Write a query that includes the purchased track name with each invoice line ID.
### 11. Write a query that includes the purchased track name AND artist name with each invoice line ID.
### 12. Provide a query that shows all the Tracks, and include the Album name, Media type, and Genre.
### 13. Show the total sales made by each sales agent.
### 14. Which sales agent made the most dollars in sales in 2009?
