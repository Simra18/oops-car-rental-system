# Car Rental System in C++
This mini-project implements a **Car Rental Management System in C++** as part of the **OOPs (PBL) internal assessment**.  
It demonstrates core OOP concepts including **inheritance**, **file handling**, **encapsulation**, **login authentication**, and **invoice generation**.

---

## Team Members

| Name | Roll Number |
|------|-------------|
| **Simra Fatima** | 1/24/SET/BCS/307 |
| **Kiranjeet Kaur** | 1/24/SET/BCS/295 |
| **Drishti Parashar** | 1/24/SET/BCS/298 |
| **Mayank Kashyap** | 1/24/SET/BCS/281 |

**Faculty Mentor:** Mr. Ashok Madaan (Assistant Professor)  
**Department:** Computer Science & Engineering  
**Institute:** MRIIRS  
**Academic Year:** 2025–2026  

---

## Overview
The Car Rental System automates the process of renting vehicles through a console-based interface.  
It allows an admin to log in, display available cars, calculate rental charges, and generate a final invoice.

Key operations include:

- Secure admin login  
- Car selection menu  
- Reading car details from files  
- Capturing customer information  
- Computing total rental charges  
- Generating formatted invoices  
- Displaying welcome and thank-you messages  

The project emphasizes the application of **Object-Oriented Programming** to create modular and structured code.

---

## Features

### Admin Login
- Password-protected (`admin`)
- Masked input using `_getch()`

### Car Selection
Customer can choose from:

- Tesla 2023  
- Hyundai 2020  
- Ford 2022  

Car descriptions load from:
- `A.txt`
- `B.txt`
- `C.txt`

### Rent Calculation

| Car Model    | Rate/Day |
|---------------|-----------|
| Tesla 2023    | ₹56 |
| Hyundai 2020  | ₹60 |
| Ford 2022     | ₹75 |

### Invoice Generation
The invoice displays:

- Customer name  
- Car model  
- Car number  
- Number of days  
- Total rental fee  

### File Handling
Uses separate files for:
- welcome screen  
- car model details  
- thank-you message  

---

## OOP Concepts Used

### **1. Class: `customer`**
Stores:
- customer name  
- car model  
- car number  

### **2. Class: `rent` (inherits from `customer`)**
Handles:
- renting process  
- car selection  
- rental duration  
- fee calculation  
- invoice printing  

### **3. Class: `welcome`**
Displays:
- welcome text  
- loading animation  

Additional concepts:
- function calls  
- loops & conditionals  
- input validation  
- encapsulation  

---

## Sample Output 

<img width="400" alt="image" src="https://github.com/user-attachments/assets/5e360322-a32c-49e3-9859-6cab09dc78c5" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/7095816b-1d28-4419-94a9-071903c43cad" />
<img width="400" alt="image" src="https://github.com/user-attachments/assets/c02e1957-7691-4cdd-9f88-5de51f4c60ca" />

---

## Conclusion
This project successfully demonstrates the implementation of a **console-based Car Rental System** using C++ and OOP principles.  
It highlights important concepts such as inheritance, file handling, and structured program design.

---

## Future Enhancements
- Database integration for persistent storage  
- Car availability tracking  
- Graphical User Interface (GUI)  
- Customer rental history  
- Online booking model  

---

