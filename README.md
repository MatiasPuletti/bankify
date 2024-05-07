## Bankify App README

### Overview

Bankify is a web app designed to simulate a banking environment. It allows users to manage accounts, including viewing movements (deposits and withdrawals), transferring funds, requesting loans, and closing accounts.

### Features

#### Account Management

- **Multiple User Accounts**: The application supports multiple user accounts, each with unique credentials and banking details.
- **Login System**: Users can log in using a username and PIN, which is checked against account details.
- **Automatic Logout**: A timer automatically logs users out after a set period of inactivity for security purposes.

#### Financial Transactions

- **Display Movements**: Users can view their account movements (deposits and withdrawals) along with dates and formatted currency values.
- **Transfer Funds**: Users can transfer funds between accounts if they have sufficient balance.
- **Loan Requests**: Users can request loans. Loans are granted if a deposit equal to at least 10% of the loan amount was made previously.
- **Account Closure**: Users can close their accounts if the correct username and PIN are provided.

#### User Interface

- **Interactive UI**: The application updates the UI dynamically to reflect account changes, including balances, recent movements, and a summary of transactions.
- **Sorting Feature**: Users can toggle the sorting of their transactions based on amount.
- **Date and Currency Formatting**: The application formats dates and currency according to user locale and currency settings.

### Security Features

- **Input Validation**: Checks user inputs for logging in, transferring funds, and account closure to prevent unauthorized access.
- **Secure Session Management**: Implements a countdown timer to ensure users are automatically logged out after inactivity to protect account information.
