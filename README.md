# Library Management System - Flask API

## Overview
The **Library Management System** is a web API built using Flask that allows for managing library resources such as books and members. It supports basic CRUD operations, allowing users to:

- **Create** new books and members
- **Read** (view) details of books and members
- **Update** details of existing books and members
- **Delete** books and members

The system also includes a search functionality to find books by **title** or **author**.

## Features

- **CRUD Operations for Books**: 
  - Add, update, delete, and view book details.
  
- **CRUD Operations for Members**: 
  - Manage member details (add, update, view, and remove members).
  
- **Search Functionality**: 
  - Search books by **title** or **author**.
## Limitations

- The search functionality currently performs a simple substring match on book titles or authors, which may not be ideal for large datasets or complex search queries.
- The system does not implement advanced database features such as indexing or optimization for large-scale queries, which might impact performance with a large number of records.
- The API is designed for basic CRUD operations. More advanced features like book categorization, multi-level user permissions, and batch operations may require additional development.
- The system is built to handle a single database type (SQLite), which limits its scalability and use in production environments.
- Error handling is basic and may need refinement for production-level use.
## How to Run the Project

### Step 1: Clone the Repository
Clone the repository to your local machine:
```bash
git clone https://github.com/AsthaDurge/Library-Managment.git
cd Library-Managment

