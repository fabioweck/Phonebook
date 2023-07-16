# phonebook

A phonebook application with Object-Oriented Programming + file handler

This project explores the concept of OOP (Object-Oriented Programming) in Python language.

The phonebook is compounded by the following classes:

- Phonebook: initializes an object of a dictionary to store names and phone numbers in a list.
All attributes are private and are only accessed through internal methods.
- FileHandler: loads, reads and saves a '.txt' file. The file contains all the numbers stored by user.
- PhoneBookApplication: the core of the program. It takes the two objects instantiated from previous classes
and delivers the user interface to provide functionalities like serch by name or number and add entries.
It also handles the file, triggering the load when the application starts and calling the function to save new entries.
