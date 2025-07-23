# DBMS Store Management System (MySQL + Python)

A MySQL-based Store Management System built with Python and a Tkinter GUI. This project is designed for managing essential store operations, including product inventory, customer and dealer records, purchases, and invoice management, all supported by a normalized relational database.

## Features

- **Tkinter Frontend:** Intuitive graphical interface for all store operations.
- **Comprehensive Database Operations:**
  - Add, update, or delete records for Products, Customers, and Dealers.
  - Create and manage Purchases and Invoices, including automatic ID generation.
  - Display stock levels, search invoices and purchase records.
- **Data Validation & Error Handling:** Ensures data consistency and user-friendly error reporting.
- **Database Normalization:** Follows best practices for database normalization and includes an ER diagram and report for schema design.

## Technologies Used

- **Backend:** Python 3
- **Database:** MySQL
- **GUI:** Tkinter (Python standard library)

## Project Structure

- `Main.py`: Main application file containing the GUI logic and database operations.
- `sample_dataset.py`: Script for creating initial tables and populating them with sample data.
- `Report`: Contains documentation of attributes, relationships, normalization process, and ER diagram.

## Getting Started

### Prerequisites

- Python 3.x
- MySQL Server
- Required Python Packages: `mysql-connector-python`, `tkinter`

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/anmolp-03/DBMS-Store-Management-System-MySQL-Python.git
   cd DBMS-Store-Management-System-MySQL-Python
   ```

2. **Install dependencies:**
   ```bash
   pip install mysql-connector-python
   # Tkinter usually comes with Python, but if not:
   # sudo apt-get install python3-tk  # For Debian/Ubuntu
   ```

3. **Configure MySQL Database:**
   - Edit your MySQL connection details (host, user, password, database) in `Main.py` and `sample_dataset.py`.
   - Run `sample_dataset.py` to create tables and populate sample data.

   ```bash
   python sample_dataset.py
   ```

4. **Run the Application:**
   ```bash
   python Main.py
   ```

## Usage

- **Add/Update/Delete**: Products, Customers, Dealers.
- **Create Purchases and Invoices**: Automated ID generation, interactive forms.
- **View Reports**: Display stock, search, and retrieve invoices or purchase records.
- **Database Schema**: Refer to the `Report` for schema, normalization, and ER diagram.
