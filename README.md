# ATM System

This is a simple ATM system implemented in Python that allows users to perform basic banking operations such as withdrawals, deposits, PIN generation, mini statements, and PIN changes.

## Features

- **Withdrawal**: Allows users to withdraw money from their account.
- **Deposit**: Enables users to deposit money into their account.
- **PIN Generation**: Users can generate a new PIN if they haven't set one.
- **Mini Statement**: Displays account details, including balance and personal information.
- **Change PIN**: Users can update their PIN for security.

## How to Use

1. **Run the script** using Python:
   ```sh
   python atm.py
   ```
2. Choose an option from the menu:
   - Press `1` for Withdrawal
   - Press `2` for Deposit
   - Press `3` for PIN Generation
   - Press `4` for Mini Statement
   - Press `5` for Changing PIN
   - Press `6` to Exit

3. Follow the on-screen instructions to complete transactions.

## Account Details (Sample Data)

The system starts with predefined accounts:

| Account Number | Name   | Date of Birth  | Balance | PIN  |
|---------------|--------|---------------|---------|------|
| 1001          | Ayush  | 17-03-2002    | 50000   | 4321 |
| 1002          | Ninad  | 05-03-2002    | 40000   | 1234 |
| 1003          | Bhavik | 22-07-2002    | 45000   | None |

> **Note**: If an account does not have a PIN set, the user must generate one before performing transactions.

## Requirements

- Python 3.x installed on your system.

## Future Improvements

- Add support for multiple transactions in a session.
- Implement a database for persistent storage.
- Improve security measures like hashing PINs.

