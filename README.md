# Bank Management System

## About the Project

The Bank Management System is a Java desktop application that allows users to create bank accounts and perform basic banking operations using a graphical user interface.

## Technologies Used

* Java
* Java Swing
* JDBC
* MySQL
* IntelliJ IDEA

## Features

* Create a bank account
* Login using account number and PIN
* Check account balance
* Deposit money
* Withdraw money
* Transfer money between accounts
* View transaction history

## Database

The project uses MySQL to store account information, account balances, and transaction records.

## Setup Instructions

1. Install Java and MySQL.
2. Create the database and tables using `database.sql`.
3. Configure the database connection using the required environment variables.
4. Add the MySQL Connector/J library to the project.
5. Open the project in IntelliJ IDEA.
6. Run `BankManagementUI.java`.

## Project Structure

* `DBConnection.java` — Establishes the MySQL connection.
* `BankDAO.java` — Handles account operations and database transactions.
* `BankManagementUI.java` — Provides the graphical user interface.
* `database.sql` — Creates the database tables.

## Disclaimer

This project is intended for educational purposes. It is not designed for real banking operations.
