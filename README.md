Expense Tracker System

A terminal-based expense tracking application built with Python and MySQL that allows multiple users to securely manage and monitor their personal expenses.

Features
- User account creation and authentication
- Secure password hashing using bcrypt
- Add, remove, and manage expenses
- Monthly expense summaries using SQL aggregation
- Relational database structure with MySQL
- Admin dashboard functionality
- Persistent admin PIN using file handling
- SQL JOIN queries for analytics and reporting
- Expense descriptions and categorized logging
- Technologies Used
- Python
- MySQL
- SQL
- bcrypt
- python-dotenv
- Database Structure

The project uses a relational database with two main tables:

users stores:

user IDs
names
emails
hashed passwords

expenditures stores:

expense entries
purchase dates
item names
descriptions
costs
linked user IDs

The tables are connected using a foreign key relationship.

Security Features
- Passwords are never stored in plain text
- bcrypt hashing is used for authentication
- User-specific expense access restrictions
- Admin authentication through a separate PIN system

Future Improvements
- CSV export functionality using pandas
- Power BI integration for analytics dashboards
- Flask REST API conversion
- Expense categories and budgeting
- Data visualization and charts
- Web-based frontend
- 
Purpose:
This project was created to strengthen backend development skills involving:

- relational databases
- SQL queries and JOINs
- authentication systems
- file handling
- data management
- terminal-based application design

It also serves as a progression project from earlier beginner Python and SQL applications.
