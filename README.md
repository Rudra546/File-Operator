# 📝 Simple Journal App (Python File Handling Project)

A beginner-friendly **Python console application** that allows users to write, view, search, and delete journal entries using **file handling techniques**.
Each entry is stored with a **timestamp**, making it easy to track when it was created.

---

## 🚀 Project Overview

The **Simple Journal App** is designed to demonstrate basic programming concepts such as:

* File handling (`read`, `write`, `append`)
* User input handling
* Conditional statements
* Looping
* Error handling using `try-except`
* Working with date and time

This project is ideal for beginners learning Python and understanding how real-world applications store and manage data.

---

## ✨ Features

✔️ Add journal entries with **timestamp**
✔️ View all saved entries
✔️ Search entries using a keyword
✔️ Delete all entries with confirmation
✔️ Menu-driven interface for easy use
✔️ Basic error handling for file operations

---

## 🛠️ Technologies Used

* Python 3.x
* Built-in `datetime` module
* File Handling (`open`, `readlines`, `write`)

---

## 📂 Project Structure

```id="r9k2d1"
simple-journal-app/
│── main.py          # Main Python program
│── journal.txt      # Stores user entries (auto-created)
│── README.md        # Project documentation
```

---

## ▶️ How to Run the Project

1. Install Python (if not already installed)
2. Download or clone this repository
3. Open terminal or command prompt
4. Navigate to project folder
5. Run the program:

```id="q7d2la"
python main.py
```

---

## 💡 How It Works

### 🔹 1. Add Entry

* User writes a journal entry
* System adds **current date & time** automatically
* Entry is saved in `journal.txt`

Example:

```id="d4p2ka"
[2026-04-19 21:12:50] My first journal entry
```

---

### 🔹 2. View Entries

* Reads all entries from the file
* Displays them in numbered format

---

### 🔹 3. Search Entry

* User enters a keyword
* Program searches all entries
* Displays matching results

---

### 🔹 4. Delete All Entries

* Asks for confirmation (`yes/no`)
* Clears all data from file

---

### 🔹 5. Exit

* Terminates the program safely

---

## ⚠️ Error Handling

The program uses `try-except` blocks to handle errors such as:

* File not found
* Invalid input
* Unexpected runtime errors

This ensures the program does not crash and provides user-friendly messages.

---

## 📌 Sample Output

```id="m3k2la"
=== Simple Journal App ===

1. Add Entry
2. View Entries
3. Search Entry
4. Delete All
5. Exit

Enter choice: 1
Write something: Hello World
Entry added successfully!

Enter choice: 2
1. [2026-04-19 21:12:50] Hello World
```

---

## 🧠 Concepts Covered

* File Handling in Python
* Exception Handling
* Loops and Conditions
* String Operations
* Date and Time Formatting

---

## 📈 Future Improvements

* Add edit/update entry feature
* Store data in database (SQLite/MySQL)
* Add password protection
* Create GUI using Tkinter or Web App
* Export entries to PDF

---

## 🤝 Contributing

Feel free to fork this repository and enhance the project. Contributions are welcome!

---

## 📄 License

This project is free to use for educational purposes.

---

## 🙌 Author

**Rudra Patel**
B.Tech IT Student

---

⭐ If you found this project useful, don’t forget to **star the repository!**
