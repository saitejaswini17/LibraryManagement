# 📚 Library Management System

Welcome to the **Library Management System**!  
A simple yet powerful Python-based console application to manage your library’s collection, lending, and returns. Perfect for small libraries or as a foundational project for learning Python and object-oriented programming.

---

## 🚀 Features

- **Display Books:** View all the books available in the library.
- **Lend a Book:** Issue a book to a user and keep track of all borrowed books.
- **Add a Book:** Expand your library by adding new titles to the collection.
- **Return a Book:** Process book returns and update the system seamlessly.
- **User-Friendly Menu:** Interactive command-line interface for easy navigation.

---

## 🛠️ Getting Started

### 1. **Clone the Repository**
```bash
git clone https://github.com/saitejaswini17/LibraryManagement.git
cd LibraryManagement
```

### 2. **Prepare the Database File**
- Create a simple text file (e.g., `books.txt`) with each book title on a separate line.  
  Example:
  ```
  The Great Gatsby
  To Kill a Mockingbird
  1984
  Pride and Prejudice
  ```

### 3. **Run the Application**
```bash
python LibraryManagement.py
```
- Enter your database file name when prompted (e.g., `books.txt`).

---

## 🖥️ Usage

- **Display Books:** See all books available for lending.
- **Lend a Book:** Input the book name and user’s name to issue a book.
- **Add a Book:** Add new books by entering their names.
- **Return a Book:** Mark a book as returned to make it available for others.

---

## 💡 Example Interaction

```
Enter the name of the database file with extension: books.txt
Welcome to the PythonX library. Following are the options,

1. Display Books
2. Lend a Book
3. Add a Book
4. Return a Book

Press Q to quit and C to continue: C
Select an option to continue: 1
We have following books in our library: PythonX
The Great Gatsby
To Kill a Mockingbird
1984
Pride and Prejudice
```

---

## 🏗️ How It Works

- The system loads your books from a text file.
- All lending, adding, or returning actions update the system in real-time.
- Easy to customize and extend for advanced features!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---
