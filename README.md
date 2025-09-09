# 🏦 Bank Management System (C++)

## 📌 Overview
This project is a **console-based Bank Management System** implemented in **C++ (OOP)**.  
It allows managing **clients, users, transactions, and currencies** with full data persistence using text files.  
The system is designed with **Object-Oriented Programming principles**, using multiple classes and organized headers for better maintainability.

---

## ✨ Features
✔️ **Client Management**
- Add new clients
- Update client information
- Delete clients
- Search for clients
- List all clients

✔️ **User Management**
- Add new users
- Update user information
- Delete users
- List all users
- User login system with register tracking

✔️ **Bank Transactions**
- Deposit money
- Withdraw money
- Transfer between accounts
- View transfer logs
- Check total balances

✔️ **Currency Management**
- View currency list
- Update currency exchange rates
- Currency calculator

✔️ **Authentication & Logs**
- User login/logout
- Login history saved in `LoginRegister.txt`
- Transfer history saved in `TransfersLog.txt`

---

## 🛠️ Project Structure
```
├── ConsoleApplication239.cpp       # Main entry point
├── cls*.h                          # Class headers (screens, entities, utilities)
├── Global.h                        # Global variables & configurations
├── Data Files
│   ├── Clients.txt                 # Stores all client info
│   ├── Users.txt                   # Stores system users
│   ├── Currencies.txt              # Stores exchange rates
│   ├── TransfersLog.txt            # Stores transfer operations
│   └── LoginRegister.txt           # Stores login history
```

---

## 🚀 Getting Started

### ✅ Requirements
- C++ Compiler (MSVC / g++ / clang++)
- Visual Studio (recommended) or any IDE that supports C++

### ▶️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Bank-Management-System.git
   cd Bank-Management-System
   ```
2. Open the project in **Visual Studio** (or compile with g++):
   ```bash
   g++ ConsoleApplication239.cpp -o BankSystem
   ./BankSystem
   ```
3. Use the interactive console menu to navigate between features.

---

## 📂 Data Files
- `Clients.txt` → Stores all registered clients.
- `Users.txt` → System users with permissions.
- `Currencies.txt` → Currency exchange rates.
- `TransfersLog.txt` → Record of all transfers.
- `LoginRegister.txt` → User login history.

---

## 👨‍💻 Author
Developed by **[Tamer Mohamed]**  
🔗 [LinkedIn](https://www.linkedin.com/in/tamer-mohamed-509b66362?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app) 
