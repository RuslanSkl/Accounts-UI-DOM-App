# [Accounts App](https://RuslanSkl.github.io/Accounts-UI-DOM-App/)  ⬅️ Click to open
### User and pins for all 2 accounts

- user: bj pin: 1111
- user: jd pin: 2222
## Overview

The **Accounts App** is a simple banking application that simulates the core functionalities of a modern banking system. With Accounts, users can securely log in, view account details, transfer funds, request loans, and close accounts, all through a sleek and interactive user interface.

This application is built based on extensive use of **arrays and their methods** (e.g., `map`, `filter`, `reduce`, `sort`) and **DOM manipulation**, ensuring dynamic and responsive functionality.

![Accounts App Overview](./accounts.png)


## Features

- **User Authentication**: Log in securely using your unique username and PIN.
- **Transaction History**: View a detailed list of deposits and withdrawals, with sorting capabilities.
- **Balance Overview**: Instantly view the current account balance.
- **Fund Transfers**: Transfer money between accounts seamlessly.
- **Loan Requests**: Request loans, subject to specific approval conditions.
- **Account Closure**: Close accounts with ease after verification.
- **Dynamic UI Updates**: The interface updates dynamically to reflect account activities in real-time.

## Account Types

- **Premium**: Offers higher interest rates for deposits.
- **Standard**: Balanced features with moderate interest rates.
- **Basic**: Simplified account for limited needs.

## Usage Instructions

### Login
1. Enter your **username** and **PIN**.
2. Click the "Login" button.
3. Upon successful login, your account dashboard will appear.

### Transfer Money
1. Enter the recipient's username and the transfer amount.
2. Click the "Transfer" button to process the transfer.

### Request a Loan
1. Enter the loan amount.
2. Click the "Request Loan" button.
3. Loans are approved if there’s a deposit of at least 10% of the loan amount.

### Close Account
1. Enter your **username** and **PIN** in the "Close Account" section.
2. Click the "Close Account" button to permanently delete your account.

### Sort Transactions
- Use the "Sort" button to toggle between ascending and descending order of transactions.

## Technical Details

### Data Structure
Accounts are stored as objects, each containing:
- Owner's name
- Transaction history (`movements`)
- Interest rate
- PIN
- Account type

### Core Functions
- **`displayMovements`**: Renders transaction history on the UI.
- **`calcDisplayBalance`**: Calculates and displays the current
