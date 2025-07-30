# Banking-System
Developed a banking system application using object oriented programming (OOP).
# Description
The project implements a console-based Banking System using Python. The system 
provides basic functionality such as creating accounts, logging in, performing 
transactions, viewing balances, and admin functionalities for monitoring purposes.
# OOP Features
- An abstract class Account is created, and the CheckingAccount, SavingsAccount & Loan 
classes inherit from it. This promotes code reuse and clarity. 
  * Parent class: Account 
  * Child classes: CheckingAccount, SavingsAccount, and Loan 
- Abstract methods: get_account_balance & transaction_history_ 
- Association b/w classes: Customer and Bank. 
- Composition b/w classes:  
  * Account, Customer → Bank. 
  * Administrator, Customer →User 
- FileSaver class also inherits the functions & variables of classes: Customer, 
CheckingAccount, SavingsAccount, and Loan.
