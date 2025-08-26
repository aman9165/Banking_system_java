# Bank Application

A simple Java console-based banking system that allows users to create accounts, check balances, deposit, withdraw, and view a demo account.

## Features

- Create a new bank account
- Check account balance
- Deposit money
- Withdraw money
- View a demo account
- Exit the application

## Project Structure

```
Bank_Application/
├── BankInfo.java      # Model class for account details
├── Main.java          # Entry point of the application
├── Operation.java     # Handles menu and user choices
├── procces.java       # Implements banking operations
├── *.class            # Compiled Java classes
└── src/               # (Optional) Source folder
```

## Requirements

- Java JDK 8 or higher

## How to Compile

Open a terminal in the project root and run:

```sh
javac Bank_Application/*.java
```

## How to Run

Run the application using the fully qualified class name:

```sh
java Bank_Application.Main
```

## Usage

Follow the on-screen menu to interact with the banking system:

1. **Create a new account**: Enter account details to register.
2. **Check Balance**: View your current account balance.
3. **Deposit**: Add money to your account.
4. **Withdraw**: Remove money from your account (if sufficient balance).
5. **Demo Account**: View a sample account.
6. **Exit**: Close the application.

## Notes

- All data is stored in memory and will be lost when the application exits.
- This project is for educational/demo purposes.

## License

This project is provided for learning and
