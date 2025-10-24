# 🏦 Bank Application

A simple and modular Bank Management Application built with clean architecture principles.  
This project follows a layered structure for better scalability, readability, and maintainability.

---

## 📁 Project Structure
bank-application/
│
├── app/
│ └── main/
│ └── Main.java
│
├── domain/
│ ├── account/
│ │ └── Account.java
│ ├── customer/
│ │ └── Customer.java
│ ├── transaction/
│ │ └── Transaction.java
│ └── type/
│ └── AccountType.java
│
├── exception/
│ ├── AccountNotFoundException.java
│ ├── InsufficientFundsException.java
│ └── ValidationException.java
│
├── repository/
│ ├── AccountRepository.java
│ ├── CustomerRepository.java
│ └── TransactionRepository.java
│
└── README.md




