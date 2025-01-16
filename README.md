# Inventory-management-System-With---JSON
Inventory Management System
This is an Inventory Management System built in Python to manage product sales and update inventory. The system provides features such as listing products, updating inventory, handling sales, and calculating Goods and Services Tax (GST) on each sale.

Features
View Product Details: Displays a list of all products with their name, price, and available quantity.
User Input: Collects customer details and purchase information.
Inventory Update: Automatically updates the inventory after each purchase.
GST Calculation: Adds an 18% GST to the product price and calculates the final billing amount.
Sales Logging: Records each sale along with customer details and the date/time of the transaction.
Error Handling: If there is insufficient inventory, the system asks if the customer would like to purchase the available quantity.
Installation
To get started with the Inventory Management System, follow these steps:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/inventory-management.git
Navigate into the project directory:

bash
Copy
Edit
cd inventory-management
Ensure you have Python 3.x installed on your system.

Install required libraries (if any). You can create a requirements.txt file if you use additional libraries.

Usage
Product Listing: The system first displays a list of products, including their name, price, and available quantity.

Customer Details: The user is prompted to enter their name, email, phone number, product ID, and quantity.

Billing: The system calculates the total amount, including GST, and prints a detailed bill.

Inventory Update: The inventory is updated automatically after each sale. If the user attempts to purchase more than the available stock, the system prompts them to buy the available quantity.

Sample Output
mathematica
Copy
Edit
-----------------------MENU---------------------
P001 : Product 1   | 100 | 50
P002 : Product 2   | 200 | 30
P003 : Product 3   | 150 | 10
--------------------------------------------------

Enter your Name        : John Doe
Enter your Email id    : johndoe@example.com
Enter your Phone No.   : 1234567890
Enter a Product id : P001
Enter a product Qn : 5

--------------------Billing Amount ------------------------
Name of the Product  :  Product 1
Price of Product     :  Rs 100
Your Quantity        :  5
--------------------------------------------------
GST (18%)             :  Rs 90.0
Billing Amount       :  Rs 590.0

--------------------Inventory Updated--------------------
Thank you for your response 😊
File Structure
bash
Copy
Edit
├── Records.json           # Inventory file with product details (Name, Price, Quantity)
├── Sales.txt              # Log of all sales with customer and transaction details
├── main.py                # Python script containing the main logic
└── README.md              # This readme file
Contributing
Fork the repository.
Create a new branch (git checkout -b feature-xyz).
Make your changes.
Commit your changes (git commit -am 'Add feature xyz').
Push to the branch (git push origin feature-xyz).
Create a new Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
Author: Your Name
Email: your-email@example.com
GitHub: Your GitHub Profile
