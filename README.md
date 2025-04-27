Library Management System - SQL Project
This project is a Library Management System designed using MySQL.
It showcases the fundamental operations of a library: managing books, branches, borrowers, publishers, and book loans.

🏗️ Project Structure
Database Name: LibraryManagement

Tables Included:

tbl_publisher — Stores publisher information (Name, Address, Phone)

tbl_library_branch — Stores library branch details (Branch ID, Name, Address)

tbl_borrower — Stores borrower information (Card Number, Name, Address, Phone)

tbl_book — Stores book details and publisher references

tbl_book_authors — Manages book authors linked to their respective books

tbl_book_copies — Tracks the number of book copies available at each library branch

tbl_book_loans — Records borrowing activities including issue and due dates

🔗 Key Features
Relational Database: Properly structured using primary and foreign keys.

Data Integrity: Includes ON UPDATE CASCADE and ON DELETE CASCADE to maintain database consistency.

Auto Incremented IDs: For easy identification of entries like branches, borrowers, and books.

Ready-to-Query: Includes SELECT * FROM statements for immediate data retrieval after table creation.

🛠️ Technologies Used
MySQL (Structured Query Language)

🚀 How to Run the Project
Clone this repository or download the SQL file.

Open your MySQL Workbench (or any SQL client).

Execute the Sql_project.sql script to create the database and tables.

source /path/to/Sql_project.sql
Start adding, managing, and querying the library data!

📋 Sample Queries to Try
-- View all books
SELECT * FROM tbl_book;

-- View all borrowers
SELECT * FROM tbl_borrower;

-- View available book copies in each branch
SELECT * FROM tbl_book_copies;



