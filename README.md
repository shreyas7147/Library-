Library Management System

Overview

This is a simple Java-based Library Management System that allows users to:

Add books to the library.

Issue books to users.

Return issued books.

View available books in the library.

Features

Add Books: Users can add books to the library's collection.

Issue Books: Users can issue books if they are available in the library.

Return Books: Users can return the books they have borrowed.

View Available Books: Users can check the list of books currently available in the library.

Installation & Execution

Prerequisites

Java Development Kit (JDK) installed

A Java compiler (e.g., javac)

Steps to Run

Save the Java code in a file named Library.java.

Open a terminal or command prompt and navigate to the directory containing the file.

Compile the code using:

javac Library.java

Run the program using:

java Library

Usage

The system starts by prompting users to add books.

After adding books, users can choose from the following options:

Press i to issue a book.

Press s to see the available books.

Press r to return a book.

Press e to exit the library system.

Follow the prompts to interact with the library system.

Known Issues & Fixes

Misspelled Class and Method Names:

Liaberary should be Library.

issuBooks() should be issueBook().

Logical Fixes:

The scanner should handle nextLine() properly to avoid skipping inputs.

Enhancements:

Implement a more structured menu loop.

Improve input validation to prevent errors.

Contributions

If you want to improve this project, feel free to fork it and submit a pull request.

License

This project is open-source and free to use. Modify it as needed!

