# 🏦 SQL Lab 3 – Bank Database Relationships & EER Diagram

![SQL](https://img.shields.io/badge/SQL-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-Intermediate-blue?style=for-the-badge)

> Completing the Bank Database by adding remaining Primary Keys, Foreign Keys, and designing the full EER Diagram in MySQL Workbench.

---

### 📌 Project Overview
This lab continues from the previous Bank Database labs.  
It focuses on establishing complete **table relationships** using Primary Keys and Foreign Keys, and visualizing the database structure through an **EER Diagram**.

---

### ✨ What Was Done

| Action | Details |
|--------|---------|
| Primary Key | Added on `Accounts (AccountId)` and `Branches (BranchId)` |
| Foreign Key | `Loans.CustomerId` → `Customers.CustomerId` |
| Foreign Key | `Transactions.AccountId` → `Accounts.AccountId` |
| Foreign Key | `Accounts.BranchId` → `Branches.BranchId` |
| EER Diagram | Designed full relationship diagram in MySQL Workbench |


- One Customer can have multiple Accounts
- One Customer can have multiple Loans
- One Account can have multiple Transactions
- One Branch can have multiple Accounts

---

### 🛠️ Skills Demonstrated
- `PRIMARY KEY`
- `FOREIGN KEY`
- `ALTER TABLE`
- Table relationships (1:N)
- EER Diagram design in MySQL Workbench
- Database modeling

---

### 🚀 How to Run
1. Make sure Lab 1 and Lab 2 are already executed
2. Open MySQL Workbench
3. Run the `BankDatabase3.sql` script
4. Open the EER Diagram to view relationships

---

### 🧰 Tools Used
- MySQL
- MySQL Workbench (EER Diagram)

---

**Series Navigation**  
← [Lab 2 – Bank Database Constraints](https://github.com/abhishekjambhale18-creator/Bank-Database-Constraints) | Next Lab Coming Soon →
