Point of Sale (POS) System for Small Businesses

Title & Description
This project is a transaction-based application designed to manage and record sales in small businesses. The system captures product details such as name, quantity, and price during each purchase. It automatically generates receipts and securely stores transaction records for tracking and review. Additionally, it provides daily, weekly, and monthly sales summaries to help business owners monitor revenue and identify sales trends. The system is built incrementally and can be expanded as business needs grow.

Developers (BSCS-1B)
- Requierme, Shella Mae B.
- Lamoste, Nestle Marie V.
- Lastimado, Dissere S.
- Ronquillo, Felecil Mae O.

Project Description
- Sales Transaction Processing: This is the process of recording and completinga customers purchase by calculating the total amount, updating stock levels,and saving the transaction details int the sysytem.
- Receipt Generation for Customer: This is the process of creating and providing a receipt to the customer as proof of purchase, showing the items bought, prices, total amount, and payment details.
- Sales Summary and Reporting: This refers to generating reports that summarizes sales data, such as total sales, numbers of transactions, and best selling products, to help monitor business performance.


Prerequisites
- Python
- Flask
- Pip
- html
- Basic understanding of Object-Oriented Programming (OOP)
- Terminal or command prompt access

Installation & Setup
- Step 1: Clone or download the project files
- Step 2: Navigate to the project folder
- Step 3: Run the program using: python main.py

Usage Guide
Example workflow:
Create a cart, add items, display selected products, and proceed to checkout where the system calculates the total and generates a receipt.

Module Description - Module 1: Sales Transaction Processing
  
- Select and add items to transaction
- Enter quantity per item
- Automatically compute subtotal and total amount
- Apply discounts(if applicabcle)
- Process payments(cash or digital)
- Automatically deduct stock after succesfully sale
- Record transaction date and time


Module 2: Receipt Generation of Customers

Access
Admin and User | Route: /receipt Generation for Customers

Features

1. Automatic Receipt Generation
The system automatically creates a receipt after each completed sale. This ensures that every transaction is properly recorded without manual input.

2. Display Purchased Items
The receipt shows a detailed list of all purchased items, including product name, quantity, and price for each item.

3. Display Payment Details
The system clearly shows:

Subtotal
Total amount
Payment received
This ensures transparency and accuracy in every transaction.

4. Transaction Date and Time
Each receipt includes the exact date and time when the transaction was completed.

5. Receipt Output and Storage
Receipts can be:

Printed
Sent digitally (e.g., email)
Automatically saved in the system for future reference


 Example Workflow:

1. Customer selects items to purchase in the system
2. System displays selected items with quantity and price
3. System automatically calculates:
Subtotal
Total amount
4. Cashier/Admin reviews the transaction details
5. Customer provides payment
6. Cashier enters the payment into the system
7. System validates payment:
If payment is incomplete → receipt cannot be generated
If payment is complete → proceed
8.. System generates the receipt automatically with:
Unique Sales ID
Date and time of transaction
Detailed list of purchased items
Subtotal and total amount
Payment received
9. Receipt is displayed on screen
10. User selects output option:
Print receipt
Send digitally
11. System saves a copy of the receipt
12. Receipt is finalized and becomes non-editable
