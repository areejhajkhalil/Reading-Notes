# Exception Handling:


*The Exception Handling in Java is one of the powerful mechanism to handle the runtime errors so that normal flow of the application can be maintained.*

*-Types of Java Exceptions:*

*There are mainly two types of exceptions: checked and unchecked. Here, an error is considered as the unchecked exception. According to Oracle, there are three types of exceptions:*

-*Checked Exception.*
-*Unchecked Exception.*
-*Error.*

**Difference between Checked and Unchecked Exceptions:**
1) *Checked Exception:*

*The classes which directly inherit Throwable class except RuntimeException and Error are known as checked exceptions e.g. IOException, SQLException etc. Checked exceptions are checked at compile-time.*

2) *Unchecked Exception:*
The classes which inherit RuntimeException are known as unchecked exceptions e.g. ArithmeticException, NullPointerException, ArrayIndexOutOfBoundsException etc. Unchecked exceptions are not checked at compile-time, but they are checked at runtime.

3) *Error:*
*Error is irrecoverable e.g. OutOfMemoryError, VirtualMachineError, AssertionError etc.*


**There are 5 keywords which are used in handling exceptions in Java:**

**_try**: *The "try" keyword is used to specify a block where we should place exception code. The try block must be followed by either catch or finally. It means, we can't use try block alone.*

**catch:** *The "catch" block is used to handle the exception. It must be preceded by try block which means we can't use catch block alone. It can be followed by finally block later.*

**finally:** *The "finally" block is used to execute the important code of the program. It is executed whether an exception is handled or not.*

**throw:** *The "throw" keyword is used to throw an exception.*

**throws:**	*The "throws" keyword is used to declare exceptions. It doesn't throw an exception. It specifies that there may occur an exception in the method. It is always used with method signature.*



**Now that you know what an error is and how the browser treats them, there are two things you can do with the errors.**

1: DEBUG THE SCRIPT TO FIX ERRORS If you come across an error while writing a script (or when someone reports a bug), you will need to
debug the code, track down the source of the error, and fix it.

2: HANDLE ERRORS GRACEFULLY You can handle errors gracefully using try, catch, throw, and f i na 1 ly statement s.

**A DEBUGGING WORKFLOW:**
*Debugging is about deduction: eliminating potential causes of an error. Here is a workflow for techniques you will meet over the next 20 pages. Try to narrow down where the problem might be, then look for clues.*

*WHERE IS THE PROBLEM?*
*First, should try to can narrow down the area where the problem seems to be. In a long script, this is especially important.*

1.*Look at the error message, it tells you:*
• *The relevant script that caused the problem.*
• *The line number where it became a problem for the interpreter. (As you will see, the cause of point at which the script could not continue.)*
•* The type of error (although the underlying cause of the error may be different).*


2. **Check how far the script is running. Use tools to write messages to the console to tell how far your script has executed.*


**WHAT EXACTLY IS THE PROBLEM?**
*Once you think that you might know the rough area in which your problem is located, you can then try to find the actual line of code that is causing the error.*

1.* When you have set breakpoints, you can see if the variables around them have the values you would expect them to. If not, look earlier in the script.*

2. *Break down I break out parts of the code to test smaller pieces of the functionality.*

• *Write values of variables into the console.*

• *Calrfunctions from the console to check if they are returning what you would expect them to.*

• *Check if objects exist and have the methods I properties that you think they do.*

3. *Check the number of parameters for a function, or the number of items in an array.*




