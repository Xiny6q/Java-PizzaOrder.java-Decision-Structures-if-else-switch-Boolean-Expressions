Download link :https://programming.engineering/product/java-pizzaorder-java-decision-structures-if-else-switch-boolean-expressions/

# Java-PizzaOrder.java-Decision-Structures-if-else-switch-Boolean-Expressions
Java – PizzaOrder.java – Decision Structures: if/else, switch, Boolean Expressions
Up to this point, all the programs you have written had a sequence structure. This means that all statements are executed in sequence, one after another. Sometimes we need to let the computer make decisions, based on the data. A decision structure allows the computer to decide which statement to execute.

In order to have the computer make a decision, it needs to do a comparison. So we will work with writing boolean expressions. boolean expressions use relational operators and logical operators to create a condition that can be evaluated as true or false.

Once we have a condition, we can conditionally execute statements. This means that there are statements in the program that may or may not be executed, depending on the condition.

We can also chain conditional statements together to allow the computer to choose from several courses of action. We will explore this using nested if-else statements as well as a switch statement.

In this lab, we will be editing a pizza ordering program. It creates a pizza ordered to the specifications that the user desires. ItUp to this point, all the programs you have written had a sequence structure. This means that all statements are executed in sequence, one after another. Sometimes we need to let the computer make decisions, based on the data. A decision structure allows the computer to decide which statement to execute.

In order to have the computer make a decision, it needs to do a comparison. So we will work with writing boolean expressions. boolean expressions use relational operators and logical operators to create a condition that can be evaluated as true or false.

Once we have a condition, we can conditionally execute statements. This means that there are statements in the program that may or may not be executed, depending on the condition.

We can also chain conditional statements together to allow the computer to choose from several courses of action. We will explore this using nested if-else statements as well as a switch statement.

In this lab, we will be editing a pizza ordering program. It creates a pizza ordered to the specifications that the user desires. It walks the user through ordering, giving the user choices, which the program then uses to decide how to make the pizza and how much the cost of the pizza will be. The user will also receive a $2.00 discount if his or her name is Mike or Diane.

Task #1 The if Statement, Comparing Strings, and Flags

Copy the file PizzaOrder.java (see Code Listi walks the user through ordering, giving the user choices, which the program then uses to decide how to make the pizza and how much the cost of the pizza will be. The user will also receive a $2.00 discount if his or her name is Mike or Diane.

Task #1 The if Statement, Comparing Strings, and Flags

Copy the file PizzaOrder.java (see Code Listing 3.1) from the Student CD or as directed by your instructor.

Compile and run PizzaOrder.java. You will be able to make selections, but at this point, you will always get a Hand-tossed pizza at a base cost of $12.99 no matter what you select, but you will be able to choose toppings, and they should

add into the price correctly. You will also notice that the output does not look like money. So we need to edit PizzaOrder.java to complete the program so that it works correctly.

Construct a simple if statement. The condition will compare the String input by the user as his or her first name with the first names of the owners, Mike and Diane. Be sure that the comparison is not case sensitive.

If the user has either first name, set the discount flag to true. This will not affect the price at this point yet.

Task #2 The if-else-if Statement

Write an if-else-if statement that lets the computer choose which statements to execute by the user input size (10, 12, 14, or 16). For each option, the cost needs to be set to the appropriate amount.

The default else of the above if-else-if statement should print a statement that the user input was not one of the choices, so a 12 inch pizza will be made. It should also set the pizza size to 12 and the cost to 12.99.

Compile, debug, and run. You should now be able to get correct output for the pizza size and price (it will still have Hand-tossed crust, the output won’t look like money, and no discount will be applied yet). Run your program multiple times ordering a 10, 12, 14, 16, and 17 inch pizza.

Task #3 The switch Statement

Write a switch statement that compares the user’s choice with the appropriate characters (make sure that both capital letters and small letters will work).

Each case will assign the appropriate string indicating crust type to the crust variable.

The default case will print a statement that the user input was not one of the choices, so a Hand-tossed crust will be made.

Compile, debug, and run. You should now be able to get crust types other than Hand-tossed. Run your program multiple times to make sure all cases of the switch statement operate correctly.

Task #4 Using a Flag as a Condition

Write an if statement that uses the flag as the condition. Remember that the flag is a boolean variable, therefore is true or false. It does not have to be compared to anything.

The body of the if statement should contain two statements:

A statement that prints a message indicating that the user is eligible for a $2.00 discount.

A statement that reduces the variable cost by 2.

Compile, debug, and run. Test your program using the owners’ names (both capitalized and not) as well as a different name. The discount should be displayed correctly at this time.

Task #5 Formatting Output

Edit the appropriate lines in the main method so that any monetary output has 2 decimal places.

Compile, debug, and run. Your output should be completely correct at this time, and numeric output should look like money.

Code Listing 3.1 (PizzaOrder.java)

