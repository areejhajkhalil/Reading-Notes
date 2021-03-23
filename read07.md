**For Loop:**
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