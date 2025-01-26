# Python-Bank-Account-Management-System
WsCube Bank System

A simple Python-based banking application that allows users to perform basic banking operations like account creation, deposits, withdrawals, transfers, and viewing transaction history.
Features

    Account Management
        Create accounts with encrypted PAN card storage for privacy.
        Assign a unique account number to each account.
        Set passwords for user authentication.

    Transactions
        Deposit, withdraw, and transfer funds between accounts.
        Real-time balance updates.
        Transaction history with date, type, and remaining balance.

    Security
        Password protection for account access.
        PAN card numbers are securely encrypted using base64 encoding.

Prerequisites

Ensure you have Python 3.6 or above installed.
Installation

    Clone this repository to your local machine:

git clone https://github.com/your-username/wsCube-bank-system.git
cd wsCube-bank-system

Run the script:

    python bank_system.py

Usage
1. Main Menu

Once the program starts, you’ll see the following options:

Menu Options: 
1. Open an account  
2. View transaction details  
3. Withdraw/Deposit/Transfer  
4. View transaction history  
5. Exit program  

2. Account Creation

    Enter your PAN card number, name, account type (Savings/Current), initial deposit, and set a password.
    A unique account number will be generated for you.

3. View Account Details

    Enter your PAN card and password to access account details.

4. Transactions

    Choose to withdraw, deposit, or transfer funds.
    For withdrawals and transfers, ensure sufficient balance.

5. View Transaction History

    Enter your PAN card and password to view a detailed log of transactions, including timestamps.

Code Structure

    Encryption Functions:
        encrypt_pan(): Encrypts PAN card numbers using base64.
        decrypt_pan(): Decrypts encrypted PAN card numbers.

    Core Banking Operations:
        Open Account: Adds user details to the system.
        Withdraw: Deducts funds from the account balance.
        Deposit: Adds funds to the account balance.
        Transfer: Transfers funds between accounts.

    Data Storage:
        account_details: Stores account information.
        transactions: Maintains a history of all transactions.

Security Features

    PAN Card Encryption:
        PAN card numbers are encrypted using base64 encoding before being stored, ensuring privacy.

    Password Authentication:
        Passwords are required to access account details or perform any transactions.

Contributing

Contributions are welcome! If you'd like to add new features or improve the code, please fork the repository and submit a pull request.
