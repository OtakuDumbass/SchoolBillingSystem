# SchoolBillingSystem
Mini Project in C School Billing System

In this project, you perform billing or accounting operations under two account types: one for the students and one for teachers and staffs.
This project is complete and totally error-free. It utilizes file handling and data structures, and is one of the best C mini projects that will help you understand 
and learn whatever you need to know about developing small C projects.
School Billing System is a console application without graphic. It is compiled in Code::Blocks with gcc compiler. The source code for this project is over 1000 lines.

Features of School Billing System in C:
In this project, you can add, record, modify, search and delete the records of both account types. In addition to that, this mini project in C allows you to 
display fees, dues, total
and advance of students, and salary-related information of teachers and staffs.

For the entry of records, current date and month is asked. Then, you can select the account type, and perform billing operations like I mentioned above. 
In the add record, the name, class and roll no. of the student is asked, and it is similar for all other functions as well as the teachers account.

Data structures have been used effectively to handle co-related functions and store the record. This school billing system C project comprises the following data 
structures:

struct dat – to store the date (month and day) of entry of records
struct student – to store and organize the record of individual students
struct teacher – to store and organize the record of individual teachers/staffs

I have used the different functions for performing different billing operations in School Billing System. Listed below are some functions which will give you an 
outline of the project and help you understand it better.

start() – shows the account selection screen
chkdat() – for checking date
addrec() – for adding records
modrec() – for modifying records
searchrec() – for searching records
delrec() – for deleting records
fee() – for recording the fee paid and displaying fine, due, total and advance
salary() – for calculating the salary of teachers and staffs
ext() – for exiting
