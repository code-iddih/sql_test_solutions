# SQL Test Solutions

This repository contains solutions for the SQL tests.

## **SQL Test 1: Customer Query**
### **Task**
- Create a CSV file with customer details (e.g., first name, last name, company, country, subscription start date).
- Write an SQLite query to find the **company** of a customer from **Latvia** whose **first name starts with "X"** and whose **subscription started before today**.

### **Files**
- 📜 `customers.csv` → Sample customer data in CSV format.
- 📜 `find_latvian_customer.sql` → SQLite query to find the required customer.

---

## **SQL Test 2: Books Table**
### **Task**
- Create a `books` table with the following fields:
  - `title` (cannot be null)
  - `author` (cannot be null)
  - `isbn` (unique, cannot be null)
  - `genre`
  - `publication_year`
  - `price`
  - `stock_quantity`
- Insert a book into the table.

### **Files**
- 📜 `create_books_table.sql` → SQL script to create the `books` table.
- 📜 `insert_book.sql` → SQL script to insert **"The Hitchhiker's Guide to the Galaxy"** into the table.

---

## **How to Run the Queries in DBeaver**
1. **Load CSV Data:**
   - Open DBeaver.
   - Connect to your **SQLite database**.
   - Use `File → Import Data` to import `customers.csv` into a table.
   
2. **Run SQL Queries:**
   - Open the `.sql` files in DBeaver.
   - Execute them using **Ctrl + Enter**.

---

