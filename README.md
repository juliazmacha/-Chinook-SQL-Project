# Chinook SQL Project

## Overview

This SQL project focuses on analyzing the Chinook dataset, representing a digital media store. The database includes tables for artists, albums, media tracks, invoices, and customers. The project was executed using SQLite Studio.

## Database Diagram

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

### Show Customers (their full names, customer ID, and country) who are not in the US. (Hint: != or <> can be used to say "is not equal to").
### Show only the Customers from Brazil.
### Find the Invoices of customers who are from Brazil. The resulting table should show the customer's full name, Invoice ID, Date of the invoice, and billing country.
### Show the Employees who are Sales Agents.
### Find a unique/distinct list of billing countries from the Invoice table.
### Provide a query that shows the invoices associated with each sales agent. The resulting table should include the Sales Agent's full name.
### Show the Invoice Total, Customer name, Country, and Sales Agent name for all invoices and customers.
### How many Invoices were there in 2009?
### What are the total sales for 2009?
### Write a query that includes the purchased track name with each invoice line ID.
### Write a query that includes the purchased track name AND artist name with each invoice line ID.
### Provide a query that shows all the Tracks, and include the Album name, Media type, and Genre.
### Show the total sales made by each sales agent.
### Which sales agent made the most dollars in sales in 2009?
