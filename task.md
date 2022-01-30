# Recruitment Task 1: Design ATM interface

—----------------------------------------------------------------------------------
## 1. Description:
* Users should be able to insert cards and perform transactions. 
* Users should be authenticated based on the entered pin. 
* Once a user is successfully authenticated he should be able to perform a transaction which can be either deposit, withdrawal, or just view the balance. 
* At the end of each transaction, appropriate messages should be displayed like if the transaction was successful or failed. 

## 2. Class Design:
 Here is the list of the basic classes, interfaces, and methods one should implement - 
* ATM: This class should contain the main logic like entering the pin, selecting the transaction, deposit, withdraw, balance display, the error message displayed, exit message displayed, etc.
* User: A user must have an account and a card 
* Account: An account has a balance that should be updated when a transaction occurs 
* Card: A card should get authenticated based on PIN entered 3. Sample input and outputs:

## 3. Note :
* You must use object-oriented principles, accept and provide values only through the CLI.
* Use python’s logger to log the major events during each transaction.
* Bonus: Try to create unit tests that handle every edge and the regular case of use of the app.
* No property/method should be hardcoded to pass the tests.

## 4. Resources:
You may refer to the following:
* https://docs.python.org/3/library/unittest.html
* https://docs.python.org/3/howto/logging.html
* https://www.geeksforgeeks.org/python-oops-concepts/
* https://www.youtube.com/watch?v=ZDa-Z5JzLYM&list=PL-osiE80TeTsqhIuOqKhwlXsIBIdSeYtc
