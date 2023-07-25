# Codsoft-4-ATM-Interface

A Java program that simulates an ATM (Automated Teller Machine), allowing users to perform banking operations like deposit, withdrawal, balance check, transfer, and view transaction history.

## Introduction

The "ATM Interface" is a Java program that emulates the functionality of an ATM. It provides a user-friendly text-based menu for users to interact with their bank account. Users can perform various operations like depositing money, withdrawing cash, checking their balance, transferring funds to another account, and viewing their transaction history.

## Features

- Deposit: Add money to the bank account.
- Withdraw: Take out cash from the bank account if the balance is sufficient.
- Check Balance: View the current balance in the bank account.
- Transfer: Send money from the user's account to another recipient's account.
- Transaction History: View a list of recent transactions made by the user.

## How to Use

1. Clone or download this repository to your local machine.

2. Open a terminal (command prompt) and navigate to the project directory.

3. Compile the Java source code:
   ```
   javac ATMInterface.java
   ```

4. Run the program:
   ```
   java ATMInterface
   ```

5. Follow the on-screen instructions to interact with the ATM.

## Example

Suppose you use the following sequence of actions in the program:
```
Enter client User ID: john_doe
Enter initial balance: $1000

ATM Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Transfer
5. Transaction History
6. Exit

Enter your choice from (1-6): 1
Enter deposit amount: $500
Deposit successful. New balance: $1500

ATM Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Transfer
5. Transaction History
6. Exit

Enter your choice from (1-6): 2
Enter withdrawal amount: $800
Withdrawal successful. New balance: $700

ATM Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Transfer
5. Transaction History
6. Exit

Enter your choice from (1-6): 3
Current balance: $700

ATM Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Transfer
5. Transaction History
6. Exit

Enter your choice from (1-6): 4
Enter transfer amount: $300
Enter recipient's User ID: alice_smith
Transfer successful. New balance: $400

ATM Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Transfer
5. Transaction History
6. Exit

Enter your choice from (1-6): 5
Transaction History for client User ID: john_doe
2023-07-25 15:30:12: Deposit of $500
2023-07-25 15:31:23: Withdrawal of $800
2023-07-25 15:32:15: Transfer to alice_smith of $300

ATM Menu:
1. Deposit
2. Withdraw
3. Check Balance
4. Transfer
5. Transaction History
6. Exit

Enter your choice from (1-6): 6
Thankyou And Visit Again
```

## How it Works

The program consists of two main classes: `Transaction` and `BankAccount`. The `Transaction` class represents a single transaction with attributes like type (e.g., deposit, withdrawal, transfer), amount, and date. The `BankAccount` class represents a bank account with attributes like user ID, balance, and a list of transaction history.

The `ATM` class acts as the interface for users to interact with their bank account. It provides methods to deposit, withdraw, check balance, transfer funds, and view transaction history. The `ATMInterface` class serves as the user interface, allowing users to input their client User ID and initial balance and then navigate through the available ATM options.

![Screenshot 2023-07-25 162004](https://github.com/deepaktallapudi/Codsoft-4-ATM-Interface/assets/103422044/67a8515d-5496-409c-8f70-36568128ca48)

Enjoy using the ATM Interface! 
