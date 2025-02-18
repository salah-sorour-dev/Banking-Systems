# 🏦 Bank Management System (C++ Project)

This is a simple **Bank Management System** built in **C++**, designed to manage client accounts efficiently using file handling. The system allows users to perform various banking operations such as:

## ✨ Features
- ✔️ Add new clients with unique account numbers  
- ✔️ View all registered clients with their details  
- ✔️ Search for a client by account number  
- ✔️ Update client information  
- ✔️ Delete client records  
- ✔️ Deposit money into an account  
- ✔️ Withdraw money from an account  
- ✔️ View total balances of all clients  

## 🛠️ Technologies Used
- **C++** (File Handling, Vectors, Structs, and Standard Library)  
- **File-Based Storage** (Data is stored in a `.txt` file)  

## 📂 Project Structure
- `Clients.txt` → Stores client account details  
- `main.cpp` → Contains all the banking system logic  
- `Bank.h` (if used) → Header file for struct and function declarations  

## 🚀 How to Use
1. Clone the repository:  
   ```bash
   git clone https://github.com/salah-sorour-dev/bank-management-system.git
   cd bank-management-system
   ```
2. Compile the code using any C++ compiler:  
   ```bash
   g++ main.cpp -o bank.exe
   ```  
3. Run the executable:  
   ```bash
   ./bank.exe
   ```  

## 📌 Notes
- The program uses a **file-based approach**, meaning data persists even after closing the application.  
- Ensure `Clients.txt` exists in the project directory; otherwise, it will be created automatically.  
