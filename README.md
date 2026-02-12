## Library Management System

## Project Overview

The Library Management System is a Java-based web application developed using Servlets, JDBC, and Object-Oriented Programming (OOP) concepts.

This system helps manage library operations such as adding books, viewing books, managing authors, and handling database connectivity efficiently.

The project follows a layered architecture using Bean, DAO, Service, Servlet, and Utility layers, ensuring clean separation of concerns and easy maintenance.

## Objectives
The system is designed to:
 - Add new books with author details
 - View available books in the library
 - Maintain author and book information
 - Perform database operations using JDBC
 - Handle user requests using Servlets
 - Provide simple HTML-based user interfaces
 - Apply DAO pattern and Service layer architecture

## Project Structure
``` plaintext
LibraryManagement
│
├── src/main/java
│   └── com.wipro.book
│       ├── bean
│       │   ├── AuthorBean.java
│       │   └── BookBean.java
│       │
│       ├── dao
│       │   ├── AuthorDAO.java
│       │   └── BookDAO.java
│       │
│       ├── service
│       │   └── Administrator.java
│       │
│       ├── servlets
│       │   ├── MainServlet.java
│       │   └── ViewServlet.java
│       │
│       └── util
│           └── DBUtil.java
├── src/main/webapp
│   ├── META-INF
│   ├── WEB-INF
│   ├── AddBook.html
│   ├── ViewBook.html
│   ├── Menu.html
│   ├── Invalid.html
│   └── Failure.html
└── build
```

## Description of Packages
- com.wipro.book.bean
  - AuthorBean.java – Stores author details
  - BookBean.java – Stores book details

- com.wipro.book.dao
  - AuthorDAO.java – Performs database operations related to authors
  - BookDAO.java – Performs database operations related to books

- com.wipro.book.service
  - Administrator.java – Acts as the service layer to coordinate DAO operations

- com.wipro.book.servlets
   - MainServlet.java – Handles requests such as adding books
   - ViewServlet.java – Handles viewing of books

- com.wipro.book.util
  - DBUtil.java – Manages database connection using JDBC

## Features

- Add new books with author information
  
- View all books stored in the database
  
- Input validation for book details
  
- Centralized database connection handling
  
- Simple and user-friendly HTML pages

## Database Details

- Tables Used:

  1. BOOK_TABLE – Stores book details
  <img width="767" height="363" alt="image" src="https://github.com/user-attachments/assets/6480a76e-c03d-4649-849f-7093c1aed5e1" />

  2. AUTHOR_TABLE – Stores author details
  <img width="582" height="176" alt="image" src="https://github.com/user-attachments/assets/4b2429be-0372-4881-9c41-0792970a9c25" />

 ## How to Run in Eclipse IDE
- Step 1: Install Required Software
 - Eclipse IDE
 - Apache Tomcat Server (v9.0 or above)
 - Oracle Database
 - Oracle JDBC Driver (ojdbc8.jar / ojdbc11.jar)
- Step 2: Import Project
 - Open Eclipse
 - Go to File → Import → Existing Maven / Dynamic Web Project
 - Select the LibraryManagement folder
 - Click Finish
- Step 3: Configure Tomcat Server
 - Go to Servers tab
 - Add Apache Tomcat
 - Configure server runtime environment
- Step 4: Add JDBC Driver
 - Right-click project → Build Path → Add External Archives
 - Select ojdbc8.jar
- Step 5: Run the Project
 - Right-click project
 - Run As → Run on Server
 - Choose Tomcat Server
 
## Output
- The application provides:

<img width="598" height="419" alt="Screenshot 2026-02-09 110843" src="https://github.com/user-attachments/assets/532fe1fa-d54c-4f3c-883a-53903798cfa6" />
<img width="611" height="467" alt="Screenshot 2026-02-09 110818" src="https://github.com/user-attachments/assets/10c60077-c130-401a-b9db-0ae533bcbc56" />
<img width="636" height="334" alt="Screenshot 2026-02-09 110857" src="https://github.com/user-attachments/assets/4c258d98-c089-437f-8c29-115043eab9a4" />
<img width="619" height="382" alt="Screenshot 2026-02-09 110944" src="https://github.com/user-attachments/assets/575ea845-3447-4ae0-bff7-93cd721bcec7" />
<img width="605" height="295" alt="image" src="https://github.com/user-attachments/assets/c96e962a-b270-4ded-a3a8-d3f91e0120d4" />
<img width="556" height="242" alt="image" src="https://github.com/user-attachments/assets/07a64051-9d87-4655-937e-a1552a8c130b" />

## Student Details

- Name: Nikitha S
  
- Roll No: 717823P136

