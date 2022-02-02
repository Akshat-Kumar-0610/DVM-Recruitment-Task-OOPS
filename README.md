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
* Card: A card should get authenticated based on PIN entered
### NOTE: Using PINs:
  * You can create a constant PIN value from the beginning and each user must enter the same value (this is the most basic way, and is not preferred)
  * Better Way: You must allow the user to set his own PIN during 1st arrival (check if username is not present in list of already enrolled users),
    thereafter, each user must enter his own set PIN.

## 3. Note:
* You must use object-oriented principles, accept and provide values only through the CLI.
* Use python’s logger to log the major events during each transaction.
* No property/method should be hardcoded to pass the tests.


## 4. Bonus:
* Create unit tests that handle every edge and the regular case of use of the app.
* Learn Git and Github, publish your repo on Github.


## 5. Resources:
You may refer to the following:
* https://docs.python.org/3/library/unittest.html
* https://docs.python.org/3/howto/logging.html
* https://www.geeksforgeeks.org/python-oops-concepts/
* https://www.youtube.com/watch?v=ZDa-Z5JzLYM&list=PL-osiE80TeTsqhIuOqKhwlXsIBIdSeYtc
* https://www.youtube.com/watch?v=HVsySz-h9r4&list=PL-osiE80TeTuRUfjRe54Eea17-YfnOOAx

## 6. Submission:
* Deadline: 5 Feb Saturday, EOD.
* Submit on: https://forms.gle/Z8cDDm37dKHYu32u9 (Github repo link OR Upload code on Gdrive if you did not use git)

