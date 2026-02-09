## Library Management System

## Project Overview
The Library Management System is a Java-based web application developed using Servlets, JDBC, and Object-Oriented Programming (OOP) concepts.
This system helps manage library operations such as adding books, viewing books, managing authors, and handling database connectivity efficiently.
The project follows a layered architecture using Bean, DAO, Service, Servlet, and Utility layers, ensuring clean separation of concerns and easy maintenance.

## Objectives
The system is designed to:
 -Add new books with author details
 -View available books in the library
 -Maintain author and book information
 -Perform database operations using JDBC
 -Handle user requests using Servlets
 -Provide simple HTML-based user interfaces
 -Apply DAO pattern and Service layer architecture

## Project Structure
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


## Description of Packages
com.wipro.book.bean
 -AuthorBean.java – Stores author details
 -BookBean.java – Stores book details

com.wipro.book.dao
 -AuthorDAO.java – Performs database operations related to authors
 -BookDAO.java – Performs database operations related to books

com.wipro.book.service
 -Administrator.java – Acts as the service layer to coordinate DAO operations

com.wipro.book.servlets
 -MainServlet.java – Handles requests such as adding books
 -ViewServlet.java – Handles viewing of books

com.wipro.book.util
 -DBUtil.java – Manages database connection using JDBC

## Features

1.Add new books with author information
2.View all books stored in the database
3.Input validation for book details
4.Centralized database connection handling
5.Simple and user-friendly HTML pages

## Database Details
Tables Used
 -BOOK_TABLE – Stores book details
 -AUTHOR_TABLE – Stores author details
