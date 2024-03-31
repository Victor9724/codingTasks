# codingTask.
'''
This Python program, cafe.py, manages inventory in a café by utilizing user-defined functions and handling strings, lists, and dictionaries.
Table of Contents
Installation
Usage
Credits
Installation
Ensure Python is installed (preferably Python 3).
Download or clone the cafe.py file from this repository.
No additional installations are required.
Usage
Open a terminal or command prompt.
Navigate to the directory containing cafe.py.
Run the program using python cafe.py.
View the total stock worth in the café displayed on the console.
Credit
Author: [Victor Opurum]
'''

# Create a list called menu
menu = ["Coffee", "Tea", "Sandwich", "Cake"]

# Create a dictionary called stock with stock values for each item on the menu
stock = {
    "Coffee": 100,
    "Tea": 80,
    "Sandwich": 50,
    "Cake": 20}

# Create a dictionary called price with prices for each item on the menu
price = {
    "Coffee": 2.50,
    "Tea": 2.00,
    "Sandwich": 5.00,
    "Cake": 3.00
}

# Calculate the total stock worth in the cafe
total_stock_worth = 0
for item in menu:
    item_value = stock[item] * price[item]
    total_stock_worth += item_value

# Print out the result of the calculation
print("Total stock worth in the cafe:", total_stock_worth)
