# Expense Tracker API

Expense Tracker API is a backend application that helps users manage their personal expenses. Users can register, log in, update their username, delete their account, and perform CRUD operations on their expenses. The API also supports filtering expenses by dates and categories.

This project is inspired by the **Expense Tracker API** from [roadmap.sh](https://roadmap.sh).

## Features
- **Account management**: Users can register, login, update their username, and delete their account.
- **JWT Authentication**: The API is protected by JSON Web Tokens (JWT), ensuring that only authenticated users can access their data.
- **Expense management**: Users can create, read, update, and delete their expenses. Expenses can be filtered by dates and categories.
- **Secure & Scalable Database**: Uses PostgreSQL, with sensitive settings managed through an `.env` file for easy database switching.
- **Database Migrations**: Schema updates are managed via Alembic migrations.
- **Automated Testing**: Uses `pytest` for unit testing to ensure everything works correctly.

## How to Use

Once the application is running, access Swagger’s interactive API documentation at:

[http://localhost:8000/docs](http://localhost:8000/docs)

---

## Main Endpoints

### Authentication:
- `POST /signup`: User registration.
- `POST /login`: User login.

### Expenses:
- `GET /expenses`: Get a list of expenses.
- `POST /expenses`: Create a new expense.
- `PUT /expenses/{id}`: Update an expense by ID.
- `DELETE /expenses/{id}`: Delete an expense by ID.

### User Account:
- `PUT /user`: Update the username.
- `DELETE /user`: Delete the user account.

---

## Feedback & Contributions

This is my first API project, and I welcome feedback and contributions. If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.


