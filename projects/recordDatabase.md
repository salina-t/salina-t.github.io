---
layout: project
type: project
image: ../img/Record_Database/record_database_header.png
title: "Record Database"
date: "2023"
published: true
labels:
  - Object-oriented programming 
  - User interface  
  - Writing and saving files 
summary: "A database created to edit and save records with different properties to a
          file that is updated every time the program is launched."
---

<img class="img-fluid" src="../img/Record_Database/record_database_header.png" width="400" alt="picture">

Record Database is a program I created for my ICS 212 class using C++ and Java. This program uses linked lists
to efficiently store an object called "Record", which includes multiple elements such as name, account number, and address. 
This project was designed with emphasis in object-oriented programming, user interface, optimization of memory usage, and information security. 

Here is an excerpt from one run:

<hr>

<pre>
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

Debug Mode ON

Welcome to the bank database.
To access the database, please select an option:

add: add a new record in the database
printall: print all records in the database
find: find record(s) with a specified account #
delete: delete existing record(s) from the database using the account #
quit: quit the program

USER: printall

Account Number: 123
Account Name: Greg Johnson 
Account Address: 422 Tree Ave. 97622

</pre>

<hr>

Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>
