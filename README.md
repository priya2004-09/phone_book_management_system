# phone_book_management_system
A modular console application written in C designed for efficient contact management. It features robust operations for adding, searching, updating, and deleting contacts, with persistent storage utilizing text files.
# Overview
The Phone Book Management System is a modular console-based application written in C. It provides an efficient and reliable way to manage personal or professional contacts directly from the command line, leveraging persistent storage to save data across sessions.
# Objective
The primary objective of this project is to implement core data management concepts in C—such as structures, pointers, modular programming, and file handling—to build a practical utility that handles daily contact storage and retrieval needs seamlessly.
# Features
Contact Management: Easily add, update, and delete contact entries.
Search Capabilities: Quickly look up saved contacts using specific identifiers or names.
Persistent Storage: Automatically saves and loads contact records using local text files.
Modular Architecture: Cleanly separated code into headers, operations, and execution logic for better maintainability and code readability.
# Project Structure
phone_book/
│
├── phone_book/
│   ├── phone_book.h       # Header file containing structure definitions and function prototypes[cite: 1]
│   ├── operations.c       # Core logic implementation for add, search, update, and delete functions[cite: 1]
│   ├── phonebook.c        # Main application flow and menu handler[cite: 1]
│   └── main.c             # Entry point of the program[cite: 1]
│
├── contact.txt            # Data file used for persistent contact storage[cite: 1]
└── a. out.txt             # Compiled output logs or build records[cite: 1]
