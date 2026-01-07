Shop Billing System (Python + SQLite)
About the Project:-

This is a command-line based Shop Billing System developed using Python and SQLite.
The goal of this project is to understand how Python works with databases and how a real-world shop billing flow can be implemented logically.

The system supports product management, customer billing, automatic stock reduction, and permanent storage of sales data.
This project was built step by step while learning Python and SQL.

Key Features:-
Product Management

Add new products

View all products

Update existing product details

Delete products

Billing System

Add customer details

Create a bill with multiple products

Check available stock before billing

Automatically calculate total bill amount

Reduce stock after billing

Store sales information in the database

Technologies Used:-

Python 3

SQLite (using built-in sqlite3 module)

Visual Studio Code

Terminal

No external libraries or frameworks are used.

Project Folder Structure:-


ShopBillingSystem/

├── main.py             # Main application logic

├── database.py         # Database operations and queries

├── shop.db             # SQLite database file

└── README.md           # Project documentation


How to Run the Project

Open the terminal inside the project folder

Run the following command:

python3 main.py


Use the menu options displayed on the screen

Menu Options
1. Add Product
2. View Products
3. Update Product
4. Delete Product
5. Create Bill
6. Exit

Database Tables Used

products – stores product details

customers – stores customer information

sales – stores bill summary

sale_items – stores items included in each bill

This structure helps maintain proper relationships between products, customers, and sales.

What I Learned from This Project:-

* How CRUD operations work in real applications

* How to connect Python with SQLite

* How to design a simple relational database schema

* How billing systems manage inventory

* How to structure a Python project properly

* How to debug runtime and logical errors

* Basics of Git and GitHub workflow

* Future Improvements

* Add sales history and reports

* Improve input validation

* Add error handling using (try-except)

* Convert the project into a GUI application

* Build a web-based version

Author:-

Uday Mangalagiri.


Python + SQL Learning Project.
