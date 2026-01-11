# Grocery Store Management System

A comprehensive web-based grocery store management application designed for cashiers to efficiently handle daily store operations. This system enables product management, order processing, and automatic billing calculations.

## Features

- **Product Management**: Add, delete, and update grocery items in the inventory
- **Order Processing**: Create and save customer orders efficiently
- **Billing System**: Automatically calculate totals for customer purchases
- **Inventory Tracking**: Keep track of all grocery items in the store
- **User-Friendly Interface**: Clean and intuitive design for cashiers

## Technology Stack

This is a 3-tier application built with:

### Frontend
- HTML
- CSS
- JavaScript
- Bootstrap

### Backend
- Python
- Flask

### Database
- MySQL

## Prerequisites

Before running this application, make sure you have the following installed:

- Python 3.x
- MySQL Server
- pip (Python package manager)

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/siri2975/grocerystore_management.git
cd grocery-store-management
```

### 2. Install MySQL
Download and install MySQL for Windows: [MySQL Installer](https://dev.mysql.com/downloads/installer/)

### 3. Install Required Python Packages
```bash
pip install flask
pip install mysql-connector-python
```

### 4. Database Setup
1. Open MySQL Workbench or MySQL Command Line
2. Create a new database:
```sql
CREATE DATABASE grocery_store;
```
3. Import the database schema (if schema file is provided) or create the necessary tables

### 5. Configure Database Connection
Update the database configuration in your Python files with your MySQL credentials:
- Host: localhost
- User: your_mysql_username
- Password: your_mysql_password
- Database: grocery_store

## Running the Application

1. Navigate to the project directory
2. Run the Flask application:
```bash
python app.py
```
or
```bash
flask run
```
3. Open your web browser and go to:
```
http://localhost:5000
```

## Usage

1. **Adding Products**: Navigate to the products section and use the form to add new grocery items
2. **Managing Inventory**: View, update, or delete existing products from the inventory
3. **Processing Orders**: Create new orders by selecting products and quantities
4. **Billing**: The system automatically calculates the total amount for each order

## Project Structure

```
grocery-store-management/
│
├── templates/          # HTML files
├── static/            # CSS, JavaScript, and image files
├── app.py             # Main Flask application
├── database/          # Database configuration and queries
└── README.md          # Project documentation
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

Siri Vardhini Thadvai
- GitHub: https://github.com/siri2975

## Acknowledgments

- Thanks to all contributors who helped in building this project
- Inspired by real-world grocery store management needs

---

**Note**: This project is designed for educational purposes and small to medium-sized grocery store operations.
