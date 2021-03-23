# Comparison Operators:
**Evaluatig Conditions**
*1-Comparison operators are used in logical statements to determine equality or difference between variables or values.*

*2-Comparison operators can be used in conditional statements to compare values and take action depending on the result.*

*3-Logical operators are used to determine the logic between variables or values.*

*4-you can evaluate a situation by comparing one value in the script to what you expect it might be. The reslt will be a Bloolean: true or false.
*(Is Ecqual To ==):This operator compares two values (numbers,Strings, or Booleans) to see if are the same.*
*(IS Not Equal To !=):This opertor compares two values (numbers,Strings, or Booleanes) to see if they are not the same.*
*(Strict Equal To ===):This operator compares two values to check that both the data type and value are same.*
*(Strict Not Equal To !==):This operator compares two values to check that both the data type and value are not same.*
*(Greater Than >):This operator checks if the number on the left is greater than the number on the right.*
*(Greater Than Or Equal To >=):This operator checks if the number on the left is greater than or equal to the number on the right.*
*(Less Than <):This operator checks if the number on the left is less than the number on the right.*
*(Less Than Or Equal TO <=):This operator checks if the number on the left is less than or equal to number on the right. *

# Loops:
**Loops are used in JavaScript to perform repeated tasks based on a condition. Conditions typically return true or false when analysed. A loop will continue running until the defined condition returns false.**

1-**For Loop:**
*initialization - Run before the first execution on the loop. This expression is commonly used to create counters. Variables created here are scoped to the loop. Once the loop has finished it’s execution they are destroyed.*
*condition - Expression that is checked prior to the execution of every iteration. If omitted, this expression evaluates to true. If it evaluates to true, the loop’s statement is executed. If it evaluates to false, the loop stops.*
*final-expression - Expression that is run after every iteration. Usually used to increment a counter. But it can be used to decrement a counter too.*
Syntax
for ([initialization]); [condition]; [final-expression]) {
   // statement
}

+
 2-**while loop:**
*The while loop starts by evaluating the condition. If the condition is true, the statement(s) is/are executed. If the condition is false, the statement(s) is/are not executed. After that, while loop ends.*
Syntax:
while (condition)

{

  statement(s);

}