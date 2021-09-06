# IMS-etg-internship
A basic Inventory Management System built with python in which a user can buy/sell products and the program keeps a track of the inventory and sales.  

### Adding_items_to_Inventory.ipynb
An Inventory of 40 items(smartphones and headphones) is created. User can add a new product or modify an existing one with the help of a unique product id. The program then appends the changes to a new 'records.json' file.


### Purchasing_items_from_Inventory.ipynb
This program first imports the inventory from 'records.json' created previously. A user can buy a product with the help of it's unique product id. User has the freedom of choosing their desired product color and product quantity. Order is successful if product id, product quantity, product color exist in the inventory. To confirm the purchase, the user details are recorded and the inventory is updated. The final sales details are stored in the 'sales.json' file and the updated inventory is stored in the 'records.json' file.


### records.json
This is the original inventory created in 'Adding_items_to_Inventory.ipynb'.


### sales.json
This file contains the sales information created in 'Purchasing_items_from_Inventory.ipynb'.

