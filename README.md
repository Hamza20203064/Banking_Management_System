
# Banking_Managent_System
Practical implementation of OOPs

This system is developed to illustrate key OOP concepts like encapsulation, abstraction, inheritance, and polymorphism.

## **1. Account Class:**

Represents a bank account with attributes such as account number, first name, last name, and balance.
Provides methods for depositing and withdrawing money.
Implements encapsulation by using private member variables and public methods to access them.

## **2.SavingsAccount and CheckingAccount Classes:**

Inherit from the Account class, demonstrating inheritance.
Extend the Account class with specialized methods.
SavingsAccount has an applyInterest method to calculate and add interest to the account balance.
CheckingAccount has a deductFees method to deduct monthly fees.

## **3. Transaction and Derived Classes:**

The Transaction class is an abstract base class for transactions.
DepositTransaction and WithdrawTransaction are derived classes that execute deposit and withdrawal transactions.
Demonstrates polymorphism by using virtual functions in the base class.

## **4. Bank Class:**

Manages a collection of accounts using a std::map.
Provides methods for opening accounts, checking balances, depositing, and withdrawing.
Uses file handling to persist account data between program runs.
Implements encapsulation by keeping the account data within the class.

## **5. Menu-Driven User Interface:**

The main function serves as a user interface, allowing users to interact with the banking system through a menu.
Users can open accounts, check balances, deposit, withdraw, close accounts, and view all accounts.
Demonstrates abstraction by providing a user-friendly interface for interacting with the system.

## **6. File Handling:**

The program uses file handling to store account data in a file named "Bank.data."
The data is read from this file when the program starts and written back when the program exits.
This provides a form of data persistence and demonstrates file I/O.

## **7. Encapsulation, Abstraction, Inheritance, and Polymorphism:**

Encapsulation: Member variables are private, and access is controlled through public methods.
Abstraction: The program abstracts the complexity of banking operations into a user-friendly menu.
Inheritance: Derived classes extend the functionality of the base Account class.
Polymorphism: Virtual functions in the Transaction class allow for different types of transactions to be executed.

## **Running the Banking Management System**

To run this Banking Management System project, follow these steps:

### **1. Clone the Repository**

First, clone this GitHub repository to your local machine. You can do this by running the following command in your terminal:
git clone https://github.com/adhassanza/Banking_Managent_System.git

### **2. Compile the Code**

Navigate to the project directory using the terminal:
cd YourRepository
Compile the C++ code using a C++ compiler (e.g., g++):
`g++ -o mybankingapp code.cpp`

### **3. Run the Program**

Once the compilation is successful (ensure there are no compilation errors), you can run the program using the following command:
`./mybankingapp`

### **4. Use the Menu-Driven Interface**

Your program will start running, and you should see the menu-driven interface for the banking management system. Follow the prompts and choose the desired options to interact with the system.

### **5. Exiting the Program**

Typically, you can exit the program by selecting an option like "Quit" from the menu. If you implemented a different way to exit, follow that procedure.
