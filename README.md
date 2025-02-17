# Banking_Project
# Bank Management System

## Overview

The **Bank Management System** is a C++ console application designed to manage bank accounts. It allows users to create accounts, deposit and withdraw money, modify account details, close accounts, and view account details. This system is built using file handling to persist account data between sessions.

## Features

- **Create Account**: Allows the creation of a new bank account with details such as account number, account holder's name, type (checking/savings), and initial deposit.
- **Deposit Amount**: Deposits money into an existing account.
- **Withdraw Amount**: Withdraws money from an existing account, provided there is sufficient balance.
- **Balance Enquiry**: Displays the balance and details of a specific account.
- **List All Accounts**: Displays a list of all accounts with their details.
- **Close Account**: Deletes an account from the system.
- **Modify Account**: Updates the details of an existing account.

## Prerequisites

- **C++ Compiler**: Ensure you have a C++ compiler installed (e.g., g++, clang++).
- **Operating System**: The application is designed to work on Windows due to the use of `system("CLS")`. For Unix-based systems, replace `system("CLS")` with `system("clear")`.

## Installation

1. **Clone the Repository**: 

    ```bash
    git clone https://github.com/yourusername/bank-management-system.git
    ```

2. **Navigate to the Directory**:

    ```bash
    cd bank-management-system
    ```

3. **Compile the Program**:

    Use the following command to compile the program. Adjust the compiler command according to your environment:

    ```bash
    g++ -o bank_management_system bank_management_system.cpp
    ```

4. **Run the Program**:

    ```bash
    ./bank_management_system
    ```

## Usage

Upon running the program, you'll be presented with a menu with the following options:

1. **NEW ACCOUNT**: Create a new bank account.
2. **DEPOSIT AMOUNT**: Deposit money into an existing account.
3. **WITHDRAW AMOUNT**: Withdraw money from an existing account.
4. **BALANCE ENQUIRY**: View details and balance of a specific account.
5. **ALL ACCOUNT HOLDER LIST**: View a list of all accounts and their details.
6. **CLOSE AN ACCOUNT**: Delete an existing account.
7. **MODIFY AN ACCOUNT**: Update details of an existing account.
8. **EXIT**: Exit the application.

Follow the prompts to interact with the system. Input the required details as instructed.

## File Format

- **account.dat**: This binary file stores the account data. Each record in this file represents an account and contains the following fields:
  - Account Number (int)
  - Account Holder's Name (char array of 50)
  - Deposit (int)
  - Account Type (char)

## Contributing

Contributions are welcome! To contribute to this project:

1. **Fork the Repository**: Click the "Fork" button at the top of the page.
2. **Clone Your Fork**: Clone your fork to your local machine.
3. **Create a Branch**: Create a new branch for your changes.
4. **Make Your Changes**: Implement your changes or fixes.
5. **Commit Your Changes**: Commit your changes with a descriptive message.
6. **Push to Your Fork**: Push your changes to your fork on GitHub.
7. **Create a Pull Request**: Open a pull request from your fork to the original repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or issues, please contact:

- **Author**: Harsh Singh
- **Email**: [your.email@example.com]

## Acknowledgements

- This project was developed for educational purposes.
- Special thanks to the C++ community and various resources that helped in implementing file handling and console applications.

