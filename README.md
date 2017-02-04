# Individual-Assignment-1
This is repository to store starter project for Individual Assignment 1
Due date for Assignment is Feb 18 2017 9:30AM (Before our Class starts)


## Objective
### Demonstrate the following:

1. Usage of Eclipse
2. Variable Assignment
3. Variable Manipulation
4. Object oriented design, Implement class
5. Constructor 
6. Accessor and Mutator
7. User Interaction with multiple options
8. Implementing Methods in classes
9. Use Github for Individual Assignment

### Instructions
* You will create a basic java program to implement cashRegister with two tax category food and non-food item and it's tax
* The program should prompt store-manager various actions he can perform on cashRegister like record food purchase, record non food purchase, user can add multiple item in register (user input part in userInputSimulator method)
* Implement various methods shown in CashRegisterTester.java and CashRegister.java file, initialize constructor with proper values
* Add your own test cases (at least 2) to test functionality try entering multiple items and show expected and actual change given.
* The CashRegister class has an unfortunate limitation: It is closely tied to the coin system in the United States and Canada. Research the system used in most of Europe. Your goal is to produce a cash register that works with euros and cents. Rather than designing another limited CashRegister implementation for the European market, you should design a separate Coin class and a cashRegister that can work with coins of all types.

 
## Total Possible Points: 100
 
1. Program runs as submitted - 5 points
2. Program implements all constructors - 10 points
3. Program adds new Food and Non-Food Items costs - 10 points
4. Program calculates proper tax for each Item category and return total cost - 10 points
5. Program implement payment and giveChange methods - 10 points
6. Program implements proper testing methods - 10 points
7. Program implements userSimulator method properly using scanner - 10 points
8. Program implements Coin class and replace quarter, dollar etc with coin types to make it work for euro zone - 30 points (total)
	* Implement new class called coin and add constructor to set coin value - 5 points
	* Add getValue() method on class to get the value for that coin type - 5 points
	* Change cashRegister's constants like Dollar, quarter etc with coin class and use it in CashRegister class also add internal variable to store currency type (dollar or euro) and add new constructor in CashRegister to initialize currency type. (keep dollar as default value for other constructors) - 10 points
	* Add testing method to show euro type coins - 5 points
	* Create another method to enterEuroPayment() to receive different coin values - 5 points 
9. Code is well documented using proper header provided in class 1 - 5 points
10. Program meets submission criteria as below: (Bonus points)
	* Project is submitted on Github - 5 points
	* At-least 3 commits are done - 5 points
