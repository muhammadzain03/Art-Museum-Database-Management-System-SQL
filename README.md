# 🖼️ Art Museum Database Management System

This project is a comprehensive database management system designed to handle an art museum’s operational needs. Developed with MySQL and Python, it manages artworks, museum staff, and visitor interactions. The project is organized into SQL scripts for database creation and querying, along with a Python application for user management.

## 📂 Project Structure

- **art_museum.sql**: SQL script to build and populate the database. This file contains:
  - Table creation with constraints and relationships.
  - Initial data insertion.
  - Triggers for managing data consistency and enforcing business rules.

- **Users.sql**: Contains user setup scripts for the database. This script sets up users with predefined roles.

- **Queries.sql**: Demonstrates various SQL queries, including:
  - Data retrieval (basic and ordered).
  - Nested and joined queries.
  - Updates and deletions with triggers.

- **application.py**: A Python script for user account management. It allows role-based access control within the database, creating and managing user accounts and permissions for various roles.

- **Details (Including usernames & Passwords).txt**: Credentials for test accounts with role-based permissions, including:
  - **Admin Account**:
    - Username: `test_admin`
    - Password: `Qwerty2003`
  - **Employee Account**:
    - Username: `test_employee`
    - Password: `Qwerty2003`

## 🚀 Getting Started

1. **Setup the Database**:
   - Import `art_museum.sql` into your MySQL database to create tables and insert initial data.
   
2. **Set Up Users and Roles**:
   - Run `Users.sql` to establish user accounts and role-based permissions.

3. **Execute Queries**:
   - Use `Queries.sql` to explore the database with sample queries.

4. **Run the Python Application**:
   - Run `application.py` to manage users and roles, enabling role-specific access to the database.

## ✨ Features

- **Role-Based Access Control**: Ensures users have access based on their roles, limiting operations accordingly.
- **Comprehensive Database Schema**: Includes tables and constraints tailored for museum operations.
- **Data Consistency with Triggers**: Automatically enforces business rules and maintains data integrity.

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

Feel free to explore, modify, and enhance the program to suit your needs. Contributions are welcome!
