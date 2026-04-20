🏦 Bank Management System (C++)

📌 Overview

This is a simple Bank Management System written in C++ using Object-Oriented Programming (OOP) concepts.
It allows users to create accounts, login securely, and perform banking operations like deposit, withdraw, transfer, and update details.

---

🚀 Features

🔐 Account Management

- Create Savings or Current account
- Secure login using Account Number + PIN

💰 Banking Operations

- Check Balance
- Deposit Money
- Withdraw Money
- Transfer Money between accounts

⚙️ Special Features

- Savings Account → Calculates Interest
- Current Account → Provides Overdraft facility

📝 Profile Management

- Update:
  - Name
  - PIN
  - Mobile Number
  - Address
  - City / State
  - Pincode
  - Nominee

📄 Account Details

- View complete account information

---

🧱 Concepts Used

- Classes & Objects
- Inheritance
- Polymorphism (Virtual Functions)
- Abstraction
- Dynamic Memory Allocation ("new" / "delete")

---

📂 Class Structure

1. "Account" (Abstract Class)

- Base class for all account types
- Contains common data:
  - Name, Account No, Balance, PIN, etc.
- Virtual Functions:
  - "take_input()"
  - "special()"

---

2. "Savings" (Derived Class)

- Adds Interest Rate
- Special Function:
  - Calculates interest

---

3. "Current" (Derived Class)

- Adds Overdraft Facility
- Allows withdrawal beyond balance (within limit)

---

4. "Bank"

- Manages all accounts
- Handles:
  - Account Creation
  - Login System
  - Transactions
  - Updates

---

▶️ How to Run

1. Compile the program:

g++ filename.cpp -o bank

2. Run the program:

./bank

---

📋 Menu Options

Main Menu

1. Create Account
2. Login
3. Exit

After Login

1. Balance
2. Deposit
3. Withdraw
4. Transfer
5. Special
6. Update
7. Show
8. Logout

---

⚠️ Limitations

- Data is not stored permanently (no file/database)
- Max 100 accounts only
- No encryption for PIN

---

💡 Future Improvements

- Add file handling (save data permanently)
- Add password encryption
- Improve UI (GUI or web-based)
- Add transaction history

---

👨‍💻 Author

- Developed for learning C++ OOP concepts

---

✅ Conclusion

This project is a beginner-friendly implementation of a banking system that demonstrates core OOP concepts in C++ with real-world logic.

---
