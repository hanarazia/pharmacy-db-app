# Pharmacy Database Application with Python & PostgreSQL

This project implements a backend application for a pharmacy database using **Python**, **PostgreSQL**, and the **psycopg2** library. It focuses on connecting Python to a relational database, executing SQL queries, updating records, and integrating stored functions into a working application layer.

---

## 🚀 Project Highlights

The goal of this project is to build a practical database application interface that interacts with a pharmacy management system. It connects to a PostgreSQL database, performs key operations such as counting customers, updating order statuses, and deleting orders based on specific business logic — all directly from Python code.

This project demonstrates core skills in:
- Database connectivity and query execution with Python.
- Writing and invoking PostgreSQL stored functions.
- Combining SQL logic with application-level operations.
- Performing real-world data manipulation (SELECT, UPDATE, DELETE) through Python.

---

## 📊 Key Features

- **Customer Analytics:**  
  Count the number of unique customers for any given pharmacy using SQL queries executed through Python.

- **Order Status Updates:**  
  Dynamically update order statuses with year-based tagging and conditional logic based on provided parameters.

- **Order Deletion with Business Logic:**  
  Invoke a PostgreSQL stored function to delete future orders based on cancellation history and a configurable limit (`maxOrderDeletions`).

- **Stored Function Integration:**  
  Designed and implemented a stored function (`deleteSomeOrdersFunction`) in PostgreSQL to encapsulate complex deletion logic and return the number of deleted records.

---

## 🛠️ Tech Stack

- **Python 3** – Application layer and database interaction.  
- **PostgreSQL** – Relational database management and stored function execution.  
- **psycopg2** – Python-PostgreSQL adapter for executing SQL queries and transactions.  
- **Docker** – Containerized environment for database and Python runtime.

---

