## AP Computer Science A  
### Making Change App for Cashiers

In this coding assignment, you are required to ask the user to input (1) the amount of a receipt and (2) how much money the customer gives the cashier. (2 points)

Your job? Determine (5 points) and display (1 point) how many $1s, quarters, dimes, nickels and pennies should be given to the customer in order to give them the smallest number of bills/coins for their change. (6 points total)

Finally, COMMENT. Use comments to explain the purpose of your code and add details to the various calculations being performed. (2 points)

## HINTS:
- Remember that modular division is best used with integers... how do we immediately go from an amount in dollars and cents (ex. $2.34) to just cents (234 cents)?
- To avoid floating point errors (Java giving you $2.339999999999999 instead of $2.34), do as many calculations as possible as integer calculations
    - instead of doing 18.00 - 2.34, do 1800 - 234, then divide by 100.0 to move the decimal point back where you need it to be!

## Some final notes (more to be added later?):
- To COMPILE your runner file, use `javac main.java` in the terminal (NOTE: You will need to recompile after every change!)
- To RUN your compiled code, use `java main` in the terminal
- To COMMIT your changes to the repository, use `git commit -a -m '<your comment about the commit here>'` in the terminal
- To PUSH your changes to me, use `git push` in the terminal
