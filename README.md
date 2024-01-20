# Library Management System (Java, MySQL, Swing)

## Overview

This is a simple Library Management System implemented in Java, utilizing MySQL for database management and Swing for the graphical user interface. The project is designed to efficiently manage and organize library resources such as books, users, and transactions.

## Features

- **User Management**: Allows librarians to add, edit, and delete user information.
- **Book Management**: Enables librarians to add, edit, and delete book details.
- **Borrowing and Returning**: Facilitates the borrowing and returning of books, maintaining transaction history.
- **Search Functionality**: Provides a search feature for users and books for quick and easy access.
- **Database Integration**: Utilizes MySQL for database management, ensuring data persistence.

## Technologies Used

- **Java**: The core programming language for the project.
- **MySQL**: Used for database management, storing user, book, and transaction information.
- **Swing**: A Java GUI library for creating the graphical user interface.
- **JDBC (Java Database Connectivity)**: Enables Java applications to interact with databases.


## Setup

1. **Database Configuration**:
   - Create a MySQL database named `library_management`.
   - Import the provided `library_management.sql` script to set up the necessary tables and initial data.

2. **JDBC Configuration**:
   - Modify the `DBConfig.java` file in the `src` directory with your MySQL database credentials.

```java
public class DBConfig {
    public static final String URL = "jdbc:mysql://localhost:3306/library_management";
    public static final String USER = "your_username";
    public static final String PASSWORD = "your_password";
}
```

3. **Build and Run**:
   - Compile and run the project using your preferred IDE or command line.

## Usage

1. Launch the application.
2. Log in using the default admin credentials:
   - Username: admin
   - Password: admin123
3. Explore the various features, including user and book management, borrowing, and returning.

