---
layout: project
type: project
image: ../img/Record_Database/record_database_header.png
title: "Record Database"
date: "2023-05"
published: true
labels:
  - Object-oriented programming 
  - User interface  
  - Writing and saving files 
summary: "A database created to edit and save records with different properties to a
          file that is updated every time the program is launched."
---

<div class="text-center p-4">
<img class="img-fluid" src="../img/Record_Database/record_database_header.png" width="400" alt="picture">
</div>

## About the Project 

I developed Record Database as part of my coursework in ICS 212: Program Structure. This program was made
using a blend of both C++ and Java programming languages. Record Database utilizes linked lists to
efficiently store a data entity called "Record", which includes multiple attributes  such as name, 
account number, and address. This project was designed with emphasis in object-oriented programming, 
user interface, optimal memory usage, and information security. 

This project taught me the fundamental principles of creating an information system tailored for
the organization and management of data. As a result, I am able to apply these concepts in 
practical, real-world scenarios. 

## Information Systems
Aside from the technical skills, this project made me discover my interest in backend development. 
I was captivated by the "behind-the-scenes" operations of information systems and felt eager 
to learn more. Witnessing the underlying mechanics of the C++ programming language fascinated me 
and propelled me towards exploration within the world of backend development. 



## Here is a sample of Record Database:

<hr>

```
Welcome to the bank database.
To access the database, please select an option:

add: add a new record in the database
printall: print all records in the database
find: find record(s) with a specified account #
delete: delete existing record(s) from the database using the account #
quit: quit the program

USER: add

Please enter your account number

USER: 123

Please enter your name

USER: Greg Johnson

PLease enter your address. Enter the "%" character to enter

USER: 422 Tree Ave. 97622 %

Action completed. Please select a new option. 

add: add a new record in the database
printall: print all records in the database
find: find record(s) with a specified account #
delete: delete existing record(s) from the database using the account #
quit: quit the program

USER: quit

*restart program* 

-----------------------DEBUG MODE INFORMATION-----------------------
FUNCTION: readfile

--------------------------------------------------------------------

-----------------------DEBUG MODE INFORMATION-----------------------
FUNCTION: addRecord
PARAMETERS:
(int) accountno: 123
char []) name: Greg Johnson
(char []) address: 422 Tree Ave. 97622
--------------------------------------------------------------------
```

<hr>

You can learn more at my GitHub link [here](https://github.com/salina-t/Record-Database).
