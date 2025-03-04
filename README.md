﻿# Inventory Management System
## Description
Inventory management system is a web application for inventory tracking that provides support for CRUD operations such as,
* Create inventory items
* Edit Them
* Delete Them
* View a list of them

Apart from the CRUD operation the application also contains a feature to download the inventory items data as a CSV file.

## Tech Stack
This application has been developed using Django web framework which is a Python based framework for web applications. Django uses SQLite Database to perform database operations. The frontend of the application is developed using HTML, JavaScript and jQuery which enables the user to add/view/edit/delete the inventory item and to download the inventory data as CSV from any web browser. 

## Steps to run this application
1. Download and install Python version 3.6+
2. Install Django using the command `pip install django`
3. Clone the repository
4. Unzip the folder and open it in a terminal
5. Go inside the directory `inventory_management` using `cd backend-challenge\inventory_management`
6. Start the server using `python manage.py runserver`
7. Open `http://127.0.0.1:8000/inventory/` in any web browser
