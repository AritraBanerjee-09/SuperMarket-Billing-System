# 🛒 SuperMarket Billing System

## 📌 Overview

The **SuperMarket Billing System** is a **console-based C++ application** that helps manage items, track stock, and generate bills.

It allows you to:

* ➕ Add items with **name, rate, and quantity**
* 💾 Store item details in a **text file** (`Bill.txt`)
* 🧾 Generate bills by selecting items and quantities
* 🔄 Update stock automatically after billing
* 💰 Display the **total bill** and a closing message

This project demonstrates **File Handling, Object-Oriented Programming (OOP), and basic I/O operations in C++**.

---

## 🚀 Features

* ✔ Add new items to the system
* ✔ Store data persistently in `Bill.txt`
* ✔ Generate bills based on purchased items
* ✔ Update available stock after each purchase
* ✔ Calculate and display total bill
* ✔ Simple **text-based interface**

---

## 🛠 Technologies Used

* **C++** (Object-Oriented Programming)
* **File Handling** (`ifstream`, `ofstream`)
* **Windows API** (`Sleep`, `system("cls")`)
* **OOP Design** (Encapsulation with `Bill` class)

---

## 📂 Project Structure

```
SuperMarket-Billing-System/
│── billing system.cpp    # Main source code
│── Bill.txt              # Stores item details
│── Bill Temp.txt         # Temporary file for stock updates
│── README.md             # Documentation
│── .vscode/              # (Optional) VSCode settings
│── output/               # (Optional) Compiled binaries/output
```

---

## ⚙️ How It Works

### 🏠 Main Menu

1️⃣ Add Item
2️⃣ Print Bill
3️⃣ Exit

---

### ➕ Add Item

* Enter item **name, rate, and quantity**
* Data is saved to `Bill.txt`

### 🧾 Print Bill

* Enter **item name** and **quantity** to purchase
* Validates stock availability
* Calculates **amount = rate × quantity**
* Updates remaining stock in `Bill.txt`
* Shows **total bill at the end**

---

## ▶️ Running the Program

### 🔧 Compile

```bash
g++ "billing system.cpp" -o billing.exe
```

### ▶️ Run

```bash
./billing.exe
```

---

## 📖 Example

**Adding Item**

```
Enter Item Name: Apple
Enter Rate Of Item: 20
Enter Quantity Of Item: 10
Item Added Successfully
```

**Billing**

```
Enter Item: Apple
Enter Quantity: 3

Item | Rate | Quantity | Amount
Apple    20      3        60
```

**Final Output**

```
Total Bill ----------------- : 60
Thanks For Shopping!
```

---

## 📌 Future Enhancements

* 📝 Support **multi-word item names** (e.g., "Green Apple")
* 🗄️ Use **databases** (SQLite/MySQL) instead of text files
* 🔐 Add **Admin & Cashier login system**
* 💸 Include **discounts & GST calculation**
* 📄 Export bill as **PDF/Excel**

---

