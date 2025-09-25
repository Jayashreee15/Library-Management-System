
 📚 Library Management System (Java OOP Project)

 🎯 Objective

This project is part of the *Java Developer Internship Task 3*.
The aim is to build a **mini Library Management System** using **Object-Oriented Programming (OOP)** principles in Java.

It demonstrates key OOP concepts:

* **Encapsulation** – private fields with getters/setters
* **Abstraction** – Library hides internal details
* **Inheritance & Polymorphism** – easily extendable for future enhancements
 🛠 Tools & Prerequisites

* Java (JDK 8 or higher)
* Any IDE (IntelliJ / VS Code / Eclipse) or terminal
* Git (optional, for version control)

---

 ✅ Implemented Features

* Add books
* Display available books
* Issue a book to a user
* Return a book
* Track issued books per user

This project consists of four Java files:

* `Book.java`
* `User.java`
* `Library.java`
* `Main.java`


 📂 Project Structure


LibraryManagement/
├── Book.java
├── User.java
├── Library.java
└── Main.java


 🚀 System Capabilities

* Add new books to the library
* View available books
* Issue books to users
* Return issued books
* Maintain records of books issued per user

 ▶ Running the Program

1. Clone or download the project
2. Open a terminal in the project directory
3. Compile all Java files:

   ```bash
   javac *.java
   ```
4. Run the main program:

   ```bash
   java Main
   ```

---

📋 Sample Console Output

--- Library Menu ---
1. Show available books
2. Issue a book
3. Return a book
4. Show user's issued books
5. Exit
Enter choice: 1

Available Books:
- Java Basics by James Gosling (Available)
- OOP Concepts by Bjarne Stroustrup (Available)
- Data Structures by Donald Knuth (Available)

--- Library Menu ---
Enter choice: 2
Enter book title to issue: Java Basics
Book issued: Java Basics by James Gosling (Issued)

--- Library Menu ---
Enter choice: 4
John Doe's issued books:
- Java Basics by James Gosling (Issued)

--- Library Menu ---
Enter choice: 3
Enter book title to return: Java Basics
Book returned: Java Basics by James Gosling (Available)

--- Library Menu ---
Enter choice: 5
Exiting... Thank you!

🎓 Key Learning Outcomes

By completing this project, you will:

* Strengthen your understanding of OOP in Java
* Gain experience in working with multiple classes
* Practice building console-based interactive applications

