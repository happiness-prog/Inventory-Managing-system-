# INVENTORY MANAGEMENT SYSTEM 
A comprehensive CLI application for managing inventory, suppliers, and sales. THis system allows businesses to track stock levels, manage products and suppliers, process customer orders,generate restock alerts,and view reports on slaes and inventory.

## Features
**Product Management**  
- Add/Edit/Delete products with price and stock tracking  
- Automatic restock alerts when stock falls below 10 units  
- View product details with supplier information  

 **Supplier Management**  
- Maintain supplier contact information  
- Associate suppliers with specific products  
- View all suppliers and their product relationships  

**Order Management**  
- Create customer orders that automatically update stock levels  
- View order history with timestamps  
- Validate orders against available inventory  

 **Reporting**  
- Generate sales reports showing total revenue  
- View inventory status reports  
- See supplier performance metrics  


## Installation
1. Clone the repository
2. Ensure you have python and pipenv installed 
3. set up a virtual environment and install dependancies 
```bash
pipenv install
pipenv shell
```
4. Initialize the database 
``` bash 
alembic upgrade head
```
