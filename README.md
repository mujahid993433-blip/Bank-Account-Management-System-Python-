# Bank-Account-Management-System-Python-
This project is a console-based Bank Account Management System developed using Python and file handling. It allows both users and an admin to manage bank accounts securely, with all data stored persistently in a text file (accounts.txt).
Key Features:

User Login System: Users can log in using an account number and PIN. After multiple wrong PIN attempts, the account is automatically blocked for security.

Account Operations: Logged-in users can deposit money, withdraw funds, transfer money to other accounts, check their balance, and view transaction history.

Transaction History: Every transaction is recorded and saved, allowing users to track their account activity.

Admin Panel: The admin can create new accounts, view all accounts, block or unblock accounts, reset user PINs, delete accounts, and view the total bank balance.

Security Control: Accounts can be manually blocked by the admin or automatically blocked after failed login attempts.

File Handling: All account details (balance, PIN, history, and status) are saved in a file, ensuring data is not lost when the program closes.
