# Banking Management System

Overview

The Banking Management System is a SQL-based project that manages customer account creation, transactions, and account details. It ensures secure and efficient handling of financial operations using stored procedures and triggers.

Features

Account Opening: Create new customer accounts with personal details and initial deposit.

Bank Records: Maintain account details with balance tracking.

Account Holder Details: Store customer information securely.

Transactions: Handle credit and debit transactions efficiently.

Triggers: Automate account activation upon KYC approval.

Stored Procedures: Implement core banking functionalities such as deposits, withdrawals, and passbook generation.

Database Schema

The system consists of multiple tables, including:

Account Opening Table: Stores customer details and initial deposit information.

Bank Table: Manages account types, opening dates, and current balances.

Account Holder Table: Contains personal details of account holders.

Transaction Details Table: Tracks all financial transactions, including credits and debits.

Triggers

The system includes a trigger that updates the KYC status. Once approved, it automatically creates a bank account and inserts customer details into the relevant tables.

Stored Procedures

Credit Transaction: Adds a specified amount to an account.

Debit Transaction: Deducts a specified amount from an account, ensuring the balance does not go negative.

Generate Passbook: Retrieves all transactions for a specified account within a given timeframe.

Usage

Open an account by inserting data into the ACCOUNT_OPENING table.

Approve KYC to automatically create a bank account.

Perform credit and debit transactions using stored procedures.

Generate a passbook to view transaction history.

Requirements

SQL Server

Basic knowledge of SQL procedures and triggers

Future Enhancements

Implement user authentication for better security.

Add more account types and interest calculations.

Develop a UI for better accessibility.
