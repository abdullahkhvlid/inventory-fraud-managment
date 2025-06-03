Inventory Management System (Python Console-Based)
This is a simple and efficient Inventory Management System developed in Python using basic data structures such as dictionaries and lists. The application enables users to purchase items, return items, and view a complete transaction summary in a console environment.

Features
Inventory Display: Shows all available items and their quantities.

Purchase Functionality:

Prompts the user to purchase available items.

Updates the inventory in real-time.

Tracks user purchases.

Provides a reminder if the customer exceeds 5 items in their purchase.

Return Functionality:

Allows customers to return purchased items.

Updates the inventory accordingly.

Flags customers returning more than 5 items.

Transaction Summary:

Displays the items purchased and returned.

Shows the remaining inventory at the end of the session.

How It Works
The script maintains four key components:

inventory: A dictionary storing item names and their available quantities.

cart: Tracks items purchased in the current session.

returns: Tracks items returned by the user.

purchase_history and return_history: Lists used to monitor activity volume.

Core Functions
show_inventory() — Lists all available products with quantities.

purchase_item() — Handles user input to purchase items from the inventory.

return_items() — Allows users to return items to the inventory.

show_summary() — Outputs a clear breakdown of purchases, returns, and final inventory.

Usage
Run the script using a Python 3 interpreter.

Follow the console prompts:

Type an item name to purchase it.

Type 0 to stop purchasing.

Type 1 to switch to return mode.

In return mode, type an item name to return it.

Type 3 to exit return mode.

A complete transaction summary will be shown at the end.
