# CODSOFT_TASKSNO3

🏦 ATM Interface

📌 Project Overview

The ATM Interface is a menu-driven Java console application developed as part of my CODSOFT Java Development Internship.

The application simulates basic ATM operations, allowing the user to check the account balance, deposit money, and withdraw money. It uses separate classes to manage account information and ATM operations.

The project demonstrates fundamental object-oriented programming concepts, including classes, objects, constructors, encapsulation, and methods.

🎯 Project Objectives

- Understand object-oriented programming in Java.
- Represent a bank account using a Java class.
- Implement deposit, withdrawal, and balance-checking operations.
- Connect multiple classes through objects.
- Validate user input and transaction amounts.
- Handle insufficient balance conditions.
- Create a menu-driven console application.

✨ Features

1. Account Management

The "BankAccount" class stores the account balance and provides methods to perform banking operations.

2. Balance Checking

The user can view the current account balance at any time through the ATM menu.

3. Deposit Operation

The program accepts a positive deposit amount and adds it to the existing account balance.

4. Withdrawal Operation

The program checks whether the withdrawal amount is valid and whether sufficient funds are available before deducting money from the balance.

5. Insufficient Balance Handling

If the requested withdrawal exceeds the available balance, the transaction is rejected and an appropriate message is displayed.

6. Input Validation

The program validates menu choices and transaction amounts. It rejects invalid menu options, non-numeric entries, and non-positive amounts.

7. Menu-driven Interface

The user interacts with the application through a menu containing four options:

1. Check Balance
2. Deposit
3. Withdraw
4. Exit

8. Session-based Balance Updates

Deposits and withdrawals update the account balance during the running session. The updated balance is used in subsequent transactions.

🛠️ Technologies Used

- Programming Language: Java
- Object-Oriented Programming: Organizes account and ATM functionality into classes.
- Encapsulation: Keeps the balance variable private within the BankAccount class.
- Constructors: Initialize objects with the required values.
- Methods: Implement banking operations and input validation.
- Switch Statement: Processes the selected ATM menu option.
- Loops: Keep the menu running until the user exits.
- Scanner: Reads user input.

🧱 Class Structure

1. BankAccount

The "BankAccount" class represents the user's bank account.

Responsibilities:

- Store the account balance.
- Initialize the balance through a constructor.
- Deposit money.
- Withdraw money.
- Return the current balance.

The balance is declared private and is accessed through the class's methods.

2. ATM

The "ATM" class manages user interaction and transaction selection.

Responsibilities:

- Display the ATM menu.
- Validate menu choices.
- Validate transaction amounts.
- Call the appropriate BankAccount methods.
- Continue processing transactions until the user exits.

3. ATMInterface

The "ATMInterface" class contains the "main" method.

Responsibilities:

- Create a BankAccount object with an initial balance of ₹10,000.
- Create an ATM object connected to the bank account.
- Start the ATM application.

⚙️ How the Application Works

1. The program creates a bank account with an initial balance of ₹10,000.
2. The ATM menu is displayed.
3. The user selects an operation.
4. The program validates the menu choice.
5. For deposits and withdrawals, the amount is validated.
6. The relevant method in the BankAccount class performs the operation.
7. The program displays the transaction result.
8. The menu is displayed again.
9. The process continues until the user selects Exit.

💻 Sample Output

===== ATM MENU =====
1. Check Balance
2. Deposit
3. Withdraw
4. Exit

Enter your choice: 1
Current Balance: ₹10000.0

===== ATM MENU =====
1. Check Balance
2. Deposit
3. Withdraw
4. Exit

Enter your choice: 2
Enter amount to deposit: ₹2000
Amount deposited successfully.

===== ATM MENU =====
1. Check Balance
2. Deposit
3. Withdraw
4. Exit

Enter your choice: 3
Enter amount to withdraw: ₹5000
Please collect your cash.

===== ATM MENU =====
1. Check Balance
2. Deposit
3. Withdraw
4. Exit

Enter your choice: 4
Thank you for using the ATM.

🔎 Transaction Validation Example

If the user attempts to withdraw more than the available balance:

Enter your choice: 3
Enter amount to withdraw: ₹20000
Insufficient balance.

The application rejects the transaction and preserves the existing account balance.

▶️ How to Run the Project

Prerequisites

- Java Development Kit (JDK) installed.
- A terminal or Java-supported IDE.

Steps

1. Clone or download this repository.
2. Open the "Task3_ATMInterface" folder.
3. Open a terminal in that folder.
4. Compile the program:

javac ATMInterface.java

5. Run the application:

java ATMInterface

📚 Learning Outcomes

Through this project, I gained practical experience with classes, objects, constructors, methods, encapsulation, and communication between objects. I also practised menu-driven program design, transaction validation, and conditional logic.

🏁 Conclusion

The ATM Interface demonstrates how object-oriented programming can be used to model basic banking operations. Separating the account logic from the ATM interface makes the program easier to understand and maintain.

This project provided practical experience in applying Java OOP concepts to a small banking simulation.

👨‍💻 Internship Details

- Organization: CODSOFT
- Internship: Java Development Internship
- Task: Task 3 — ATM Interface

Developed as part of my Java programming practice during the internship.
