# Inventory Management System
### Overview
This Python-based Inventory Management System is designed to facilitate the management of products, sales, and customer transactions for a fictional retail business. The system provides a simple command-line interface for users to interact with the inventory, make purchases, and generate sales bills. It also maintains a record of transactions in a CSV file for easy tracking.

### Features
Menu Display:

The system displays a menu of available products with details such as Product ID, Type, Name, Price, and Quantity.
Purchase Process:

Users can enter their name, email, and phone number to initiate a purchase.
They select a product by entering its Product ID and specify the quantity they want to purchase.
Billing:

The system generates a bill displaying relevant details, including Product ID, Type, Name, Rate, Quantity, Billing Amount, etc.
Inventory Update:

After a successful purchase, the system updates the inventory by reducing the quantity of the purchased product.
Transaction Logging:

Each transaction is logged in a CSV file (Sales.csv) for future reference.
The log includes Transaction ID, Name, Email, Phone, Product details, Quantity, Amount, Date, and Time.
Error Handling:

The system includes error handling to manage scenarios such as entering an incorrect Product ID, insufficient product quantity, or out-of-stock products.
Transaction ID Management:

A transaction ID is used for uniquely identifying each transaction and is incremented after each purchase.
Date and Time Stamping:

Transactions are stamped with the date and time to keep track of when the purchases were made.
Inventory Storage:

Product details, such as type, name, price, and quantity, are stored in a JSON file (Records.json).

### File Structure
inventory_management.py: The main Python script for the inventory management system.
Records.json: JSON file containing product details and inventory information.
Sales.csv: CSV file logging all sales transactions.
id.txt: Text file storing the current transaction ID.
Usage
Ensure Python is installed on your system.
Run the inventory_management.py script.
Follow the on-screen prompts to make purchases and manage the inventory.
Future Enhancements


### Future aspects
This project can be extended with the following features:

Graphical User Interface (GUI) for a more user-friendly experience.
Integration with a database for improved data management and scalability.
Multi-user support with authentication mechanisms.
Enhanced error handling and input validation.
Feel free to explore, modify, and contribute to this project to suit your specific needs. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

Thank you for using this Inventory Management System!







