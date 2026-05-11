Bank Account File Management System:

Project Overview

The Bank Account File Management System is a C programming project developed using Binary File Handling concepts.
This system is used to store and manage customer bank account records permanently using files.

The project performs operations such as:

1.Adding new account records
2.Updating account balance
3.Deleting records
4.Creating a text report

The program uses Random Access File Processing to directly access specific records inside the file efficiently.

Features:
1.Menu-driven application
2.Add new customer accounts
3.Update account balance
4.Delete existing records
5.Create readable text file report
6.Permanent data storage using files
7.Random access record management

Concepts Used:

C Programming Concepts:
1.Structures (struct)
2.Functions
3.Arrays
4.Menu Driven Programming

File Handling Concepts:

1.Binary File Handling
2.Text File Handling
3.Random Access Files
4.File Reading and Writing

Files Used:

File Name           Type              Purpose
1.credit.dat     Binary File      Stores account records
2.accounts.txt   Text File        Stores readable account details

Functional Modules:

   Function     	             Description
1.enterChoice()   	     Displays menu and gets user choice
2.textFile()   	         Creates text report file
3.updateRecord()	     Updates customer balance
4.newRecord()	         Adds new customer record
5.deleteRecord()     	 Deletes customer record

Sample Input:

Add New Record

Enter choice: 3
Enter new account number: 1
Enter lastname firstname balance:
Ravi Kumar 5000

Sample Output:

Account added successfully.

Update Record Example:

Input:
Enter choice: 2
Enter account number: 1
Enter amount: 2000

Output:
Current balance: 5000.00
Updated balance: 7000.00


