Bank Account Management System
Mini Project – 24UCS271 Lab
Objective

This mini project focuses on understanding, modifying, and extending a Bank Account Management System program using the C programming language. Students are expected to analyze the existing code, improve the logic, optimize performance, and implement additional functionalities while following good coding practices.

Reference Code

Review the given source code before starting the project:

🔗 credit.c – Random Access File Processing Program

Tasks to be Performed
Compile and execute the given C program.
Test all existing functionalities:
Add account
Update account
Delete account
Generate text file
Add a new account and regenerate the accounts.txt file.
Verify whether the generated output is correct.
Identify and fix logical errors in the code.
Add new functionalities:
Display all account information
Search account by account number
Calculate total bank balance
Optimize the program for:
Better memory usage
Faster file processing
Improved code readability
Features Added
Existing Features
Add new customer account
Update account balance
Delete account
Store records in binary file
Generate formatted text file
New Features Added
Display all accounts
Search account details
Total balance calculation
Better menu-driven interface
Improved error handling
Safer file reading using fread()
User-friendly output messages
Logical Errors Fixed
Problem	Solution
Using while(!feof())	Replaced with while(fread())
Poor menu readability	Improved menu format
Missing validation messages	Added error handling
Hard-to-read code	Added comments and formatting
Optimization Performed
Memory Optimization
Reused structures efficiently
Reduced unnecessary variables
Speed Optimization
Used direct random-access file operations
Reduced repeated file scans
Code Improvement
Functional decomposition used
Separate functions for each operation
Better modular programming
Evaluation Criteria
1. General (25 Points)
Activity	Points	Remarks
Self-effort	5	Individual implementation
Turnaround Time	10	Early submission gets more marks
Project Demo	10	Demo using repl.it or local compiler
2. Comprehension (15 Points)
Activity	Points
Domain Knowledge	5
Added Functionality	5
Code Understanding	5
3. Modification (35 Points)
Activity	Points
Code Improvement	5
Functional Decomposition	10
Memory Optimization	10
Speed Optimization	10
4. Innovation (45 Points)
Activity	Points
New Features	5
Requirement to Code Translation	10
Error Handling	10
Advanced Functionalities	20
Total Marks

120 Marks
➡ Reduced to 20 Marks for final evaluation

Rules for Mini Project Implementation
Maximum of 2 attempts allowed for project presentation.
Best score among two attempts will be considered.
Students may discuss concepts but should write their own code.
Copying code from others is strictly prohibited.
Plagiarism will result in zero marks.
Software Requirements
GCC Compiler / Turbo C / CodeBlocks / VS Code
Repl.it Online Compiler
Operating System: Windows / Linux
Output Files Used
File Name	Purpose
credit.dat	Binary random-access file
accounts.txt	Formatted text output file
Future Enhancements
Password-protected login
Transaction history
ATM simulation
Interest calculation
Sorting customer records
Mini bank management dashboard
Conclusion

This project helped in understanding:

File handling in C
Random-access file processing
Structures in C
Modular programming
Error handling
Code optimization techniques

The enhanced system provides a simple and efficient banking application with additional functionalities and improved performance.

Date: 11/05/2026
Subject: C Programming Laboratory
Project Title: Bank Account Management System Using Random Access files