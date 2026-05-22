# Banking System Java Project

## Description
This project is a simple Banking Management System developed using Java, NetBeans, MySQL, and JDBC.

The system allows users to:
- Add customers
- Create accounts
- Deposit money
- Withdraw money
- View transaction history
- Search customer records
- Display records using JTable

---

## Technologies Used
- Java
- NetBeans IDE
- MySQL
- JDBC
- XAMPP
- phpMyAdmin

---

## Features
### Customer Management
- Add customer records
- View customer records
- Search customer information

### Account Management
- Create bank accounts
- Store account balances
- Support account types

### Transaction Management
- Deposit money
- Withdraw money
- Prevent insufficient balance withdrawals
- Save transaction history

---

## Database Name
banking_system

---

## Database Tables
### customer
- customer_id
- first_name
- last_name
- email
- phone_number

### account
- account_id
- customer_id
- account_type
- balance

### transactions
- transaction_id
- account_id
- transaction_type
- amount
- transaction_date

---

## How to Run the Project

### 1. Start XAMPP
Start:
- Apache
- MySQL

### 2. Open phpMyAdmin
Open:
http://localhost/phpmyadmin

### 3. Create Database
Create database named:
banking_system

### 4. Import/Create Tables
Run the SQL queries included in the project.

### 5. Open Project in NetBeans
Open the project folder in NetBeans.

### 6. Run the Program
Run the Java forms to test:
- Add Customer
- Deposit
- Withdraw
- View Transactions

---

## Author
Created by: Kinsley Nacua
