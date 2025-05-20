# English Dictionary App & Library Management System

## Overview

This project contains two Python-based sub-projects:

- **1A: English Dictionary App**
- **1B: Library Book Management System**

These are beginner-friendly projects aimed at helping students build strong fundamentals in Python programming while developing practical applications for their portfolio.

---

## 1A: English Dictionary App

### Objective

The objective of this application is to create an English Dictionary that allows users to:

- Add new words with meanings
- Find the meaning of existing words
- Update the meaning of existing words
- Exit the application gracefully

### Features

**Main Menu Options:**

1. Add a new word  
2. Find the meaning  
3. Update a word  
4. Exit  

### Functionality

- **Add a New Word:**  
  Prompts the user for a word and its meaning, then stores the word-meaning pair in a file (`words.txt`) using serialization.

- **Find the Meaning:**  
  Prompts the user for a word, searches the file (`words.txt`), and returns its meaning if found. If not found, an appropriate message is displayed.

- **Update a Word:**  
  Allows the user to update the meaning of an existing word in the dictionary.

- **Exit:**  
  Closes the application gracefully.

> Note: All data is stored in `words.txt` using dictionary serialization.

---

## 1B: Library Book Management System

### Objective

This project implements a Library Book Management System with:

- Front-end: Tkinter GUI  
- Back-end: SQLite database

### Features

- Single-window GUI for interaction
- CRUD operations:  
  - **Create**: Add new books  
  - **Read**: View/search existing books  
  - **Update**: Modify book details  
  - **Delete**: Remove book records

### Data Fields

- Book Title  
- Author Name  
- Year of Publication  
- ISBN (optional)

### Interface

- Text widgets to input and display book details
- List box or text area to display matched records

---

## Technologies Used

- **Python 3**
- **Tkinter** for GUI (Library App)
- **SQLite** for database management
- **Pickle/JSON** for serialization (Dictionary App)

---

