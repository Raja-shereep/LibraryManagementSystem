# Library Management System

A simple console-based Library Management System implemented in Java. This system allows users to manage books and students, including adding books, registering students, searching for books, and handling book checkouts and check-ins.

## Features

- **Book Management**:
  - Add new books with details like serial number, name, author, and quantity.
  - Upgrade the quantity of existing books.
  - Search books by serial number or author name.
  - Display all books with their details.

- **Student Management**:
  - Register new students with name and registration number.
  - Display all registered students.

- **Book Transactions**:
  - Check out books for registered students (up to 3 books per student).
  - Check in books to return them to the library.

## Classes Overview

- **Library.java**: The main class that provides a menu-driven interface for user interactions. It handles the overall flow of the application.

- **Book.java**: Represents a book entity with attributes such as serial number, book name, author name, and quantity. Includes a constructor to input book details.

- **Books.java**: Manages a collection of books (array of up to 50 books). Provides methods for adding books, searching, displaying, upgrading quantities, and handling checkouts/check-ins.

- **Student.java**: Represents a student with attributes like name, registration number, and a list of borrowed books (up to 3). Includes a constructor to input student details.

- **Students.java**: Manages a collection of students (array of up to 50 students). Provides methods for adding students, displaying, and managing book transactions for students.

## How to Run

1. Ensure you have Java installed on your system.
2. Compile the Java files:
   ```
   javac College/*.java
   ```
3. Run the main class:
   ```
   java -cp . College.Library
   ```
4. Follow the on-screen menu to interact with the system.

## Usage Instructions

- Start the application and select options from the menu (1-8).
- Add books and students before performing transactions.
- Students can borrow up to 3 books at a time.
- Use serial numbers for book operations.

## Limitations

- Maximum of 50 books and 50 students.
- Console-based interface (no GUI).
- Data is not persisted; restarts will lose all data.

## Contributing

Feel free to fork and contribute improvements or additional features.

## License

This project is open-source. Use at your own risk.
