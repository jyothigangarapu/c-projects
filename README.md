🧾 Address Book in C
📘 Project Overview

The Address Book is a menu-driven C program that allows users to store, search, modify, delete, and display contact information.
It demonstrates strong knowledge of file handling, structures, and user interface design in C — making it a perfect beginner-to-intermediate level project for students and embedded developers.

⚙️ Features

➕ Add Contact — Store a new person’s name, phone number, email, and address

🔍 Search Contact — Search by name or phone number

✏️ Edit Contact — Modify existing details

❌ Delete Contact — Remove a record permanently

📜 Display All Contacts — View all stored contacts in a formatted table

💾 File Handling — All data is stored persistently in a file (addressbook.dat)

🧠 Concepts Used

Structures – To store contact details (name, phone, email, etc.)

File Handling – Using fopen(), fwrite(), fread(), and fseek() for data storage

Menu-driven Interface – Implemented with loops and switch cases

String Handling – Using standard functions like strcmp(), strcpy(), strlen()

💻 How to Compile and Run
gcc address_book.c -o address_book
./address_book

📋 Sample Menu
========== Address Book ==========
1. Add Contact
2. Search Contact
3. Edit Contact
4. Delete Contact
5. Display All Contacts
6. Exit
==================================
Enter your choice: 

🧩 Example Contact Format
Name  : Jyothi Gangarapu
Phone : 9876543210
Email : jyothi@gmail.com
Addr  : Palamaner, Andhra Pradesh
