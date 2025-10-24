# 🏦 Bank Application

A simple and modular Bank Management Application built with clean architecture principles.  
This project follows a layered structure for better scalability, readability, and maintainability.

---

## 📁 Project Structure
```
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
```
---


---

## ⚙️ Features
- Create and manage customer accounts  
- Deposit and withdraw funds  
- Transfer money between accounts  
- Handle exceptions gracefully  
- Modular and maintainable architecture  

---

## 🚀 Getting Started
```bash
git clone https://github.com/AryanYadav888/bank-application.git
cd bank-application
javac app/main/Main.java
java app.main.Main


