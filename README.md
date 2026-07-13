# Online Bookstore Management System

## Project Overview

The Online Bookstore Management System is a database project developed using PostgreSQL. The project is designed to manage books, customers, and orders for an online bookstore while demonstrating fundamental and intermediate SQL concepts.

The database enables storage and analysis of bookstore operations, including inventory management, customer information, sales transactions, and business reporting.

---

## Objectives

* Design a relational database for an online bookstore.
* Manage book inventory and customer records.
* Track customer orders and sales transactions.
* Perform data analysis using SQL queries.
* Generate business insights such as revenue, stock levels, and customer spending patterns.

---

## Technologies Used

* PostgreSQL
* pgAdmin 4
* SQL

---

## Database Structure

### Books Table

Stores information about available books.

| Column         | Description            |
| -------------- | ---------------------- |
| Book_ID        | Unique Book Identifier |
| Title          | Book Title             |
| Author         | Author Name            |
| Genre          | Book Genre             |
| Published_Year | Publication Year       |
| Price          | Book Price             |
| Stock          | Available Stock        |

### Customers Table

Stores customer information.

| Column      | Description                |
| ----------- | -------------------------- |
| Customer_ID | Unique Customer Identifier |
| Name        | Customer Name              |
| Email       | Customer Email             |
| Phone       | Contact Number             |
| City        | Customer City              |
| Country     | Customer Country           |

### Orders Table

Stores order transaction details.

| Column       | Description             |
| ------------ | ----------------------- |
| Order_ID     | Unique Order Identifier |
| Customer_ID  | Customer Reference      |
| Book_ID      | Book Reference          |
| Order_Date   | Date of Order           |
| Quantity     | Quantity Purchased      |
| Total_Amount | Total Order Value       |

---

## Database Relationships

* One customer can place multiple orders.
* One book can appear in multiple orders.
* Orders table acts as a bridge between Customers and Books using Foreign Keys.

Customers → Orders ← Books

---

## SQL Concepts Implemented

### Data Definition Language (DDL)

* CREATE DATABASE
* CREATE TABLE
* DROP TABLE

### Data Query Operations

* SELECT
* WHERE
* ORDER BY
* DISTINCT
* LIMIT

### Aggregate Functions

* SUM()
* AVG()
* COUNT()

### Advanced SQL Concepts

* INNER JOIN
* LEFT JOIN
* GROUP BY
* HAVING
* Aggregate Analysis
* Revenue Calculations
* Inventory Analysis

---

## Key Business Queries

* Retrieve books by genre.
* Find books published after a specific year.
* Calculate total available stock.
* Identify the most expensive book.
* Calculate total revenue generated.
* Find the most frequently ordered book.
* Determine top-spending customers.
* Analyze book sales by genre and author.
* Monitor remaining inventory after sales.

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Relational Database Design
* PostgreSQL Database Management
* Writing SQL Queries
* Data Analysis Using SQL
* Working with Primary and Foreign Keys
* Business Reporting and Insights Generation

---

## Future Improvements

* Add payment information table.
* Add book categories and publishers.
* Implement stored procedures and triggers.
* Create views for reporting.
* Build a dashboard using Power BI or Excel.

---

## Author

Krish Sharma

BCA Student

Skills: SQL, PostgreSQL, Advanced Excel, MS Office, Python Basics
