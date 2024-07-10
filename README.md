This Java program provides a user-friendly interface for managing user information and orders. It includes functionalities to add users, search for users, display all user information, and add orders with discounts based on specific criteria.

Getting Started
To run the program, execute the main class. This will open the main menu with the following four buttons:

Add User
Search
Display
Add Order
1. Add User
Clicking the "Add User" button will open a new frame where you can input the following details:

ID: A unique identifier for the user.
Name: The user's first name.
Surname: The user's last name.
Birthday: The user's birth date (for discount purposes).
Country: The user's country of residence.
City: The user's city of residence.
Account Balance: The user's account balance.
Employment Status: A boolean indicating whether the user works here (for discount purposes).
Note: If a user with the entered ID already exists, you will be prompted to enter a different ID. The purpose of the birthday field is to apply a discount if the user's birthday falls between the 10th and 20th of any month. Additionally, if the user works here, they are eligible for a discount.

2. Search
Clicking the "Search" button will open a prompt asking for the user's ID. If the entered ID matches an existing user, the user's information and any associated order details will be displayed.

3. Display
Clicking the "Display" button will display a list of all users along with their information and any associated orders.

4. Add Order
Clicking the "Add Order" button will open a new frame where you can input the following details:

ID: The user's ID.
Food: Select a food item from the combo box.
Drink: Select a drink item from the combo box.
Count: Enter the quantity of the selected items.
The program calculates the total price of the order based on the selected items and their quantities. If the user has sufficient account balance, the order is saved, and the applicable discounts are applied based on the user's birthday and employment status. If the user does not have enough account balance, an error message is displayed.

Discounts
Birthday Discount: Users receive a discount if their birthday is between the 10th and 20th of any month.
Employee Discount: Users who work here are eligible for a discount.
Error Handling
The program includes error handling to ensure:

A unique ID is entered when adding a new user.
Sufficient account balance is available when adding an order.
Conclusion
This Java program provides an efficient way to manage user information and orders, with special features for applying discounts based on user-specific criteria. By following the steps outlined in this manual, users can easily navigate and utilize the program's functionalities.
