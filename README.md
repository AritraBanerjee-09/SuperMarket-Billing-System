# SuperMarket-Billing-System
A billing system, of a supper market using C++
📌 Overview

The SuperMarket Billing System is a console-based C++ application that helps manage items, track stock, and generate bills.
It allows you to:

Add items with name, rate, and quantity.

Store item details in a text file.

Generate bills by selecting items and quantities.

Update stock after billing.

Display the total bill and a closing message.

This project demonstrates file handling, OOP (class-based design), and basic I/O operations in C++.

🚀 Features

✔ Add new items to the system
✔ Store data persistently in Bill.txt
✔ Generate bills based on purchased items
✔ Update available stock after each purchase
✔ Calculate and display total bill
✔ Simple text-based interface

🛠 Technologies Used

C++ (Object-Oriented Programming)

File Handling (ifstream, ofstream)

Windows API (Sleep, system("cls"))

Object-Oriented Design (Bill class for items)

📂 Project Structure
SuperMarket-Billing-System/
│── billing system.cpp      # Main source code
│── Bill.txt                # Stores item details
│── Bill Temp.txt           # Temporary file used for stock updates
│── README.md               # Documentation
│── .vscode/                # (Optional) VSCode settings
│── output/                 # (Optional) Compiled binaries/output

⚙️ How It Works

Main Menu

Add Item

Print Bill

Exit

Add Item

Enter item name, rate, and quantity.

Saves details to Bill.txt.

Print Bill

Enter item and quantity to purchase.

Validates stock availability.

Calculates amount = rate × quantity.

Updates stock in Bill.txt.

Displays total bill at the end of the session.
