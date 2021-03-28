# HTML Book:

**text**
*-HTML elements are used to describe the structure of the page (e.g. headings, subheadings, paragraphs).*
 *-They also provide semantic information (e.g. where emphasis should be placed, the definition of any acronyms used, when given text is a quotation).*

 *-Headings:*
 
-Headings are used to describe the contents below them, it can be a single word or a phrase. In HTML there are six types of headings    that are used for various sizes of text.
<h1> heading one </h1>
<h2> heading two </h2>
<h3> heading three </h3>
<h4> heading four <h4>
<h5> heading five </h5>
<h6> heading six </h6>

 *-Paragraphs:*
 
-A paragraph is used if you want to finish what you are talking about and start a new conversation. 
If you want to explain something on your web you use a paragraph.
-For a paragraph we use a <p> tag.
-Use a <p> followed by what you want for your paragraph followed by a </p>

*-italic,bold,emphasis:*

-The <i> element was for italic text, now it is also for alternate text, such as foreign words, technical terms, or inline  stage      directions.
-The <b> element was for bold text, now it is also used as a stylistic offset such as keywords in a document of product names.
-The <em> was for emphasis, now it is used for words or sentences you would pronounce differently
 Lastly, the <strong> element is for something with strong emphasis, it represents importance.


**What ccs does and how works?**

- CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look.

- Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements s  should look like).

- Different types of selectors allow you to target your rules at different elements.

- Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.

- CSS rules usually appear in a separate document, although they may appear within an HTML page.

- CSS brings style to your web pages by interacting with HTML elements. Elements are the individual HTML components of a web page.

- In order to use an external style sheet, your .html files need to include a header section that links to the external style sheet and looks something like this:
<head>
<link rel=”stylesheet”  type=”text/css”  href=mysitestyle.css”>
</head>

- Internal style sheets are CSS instructions written directly into the header of a specific .html page. (This is especially useful if you have a single page on a site that has a unique look.) An internal style sheet looks something like this. . .
<head>
<style>
Body  {  background-color:thistle;  }
P  {  font-size:20px;  color:mediumblue;  }
</style>
</head>

- inline styles are snippets of CSS written directly into HTML code, and applicable only to a single coding instance. For example:
<h1  style=”font-size:40px;color:violet;”>Check out this headline!</h1>




# JavaScript book:

**Basic JavaScript Instructions:**

- A script is made up of a series of statements. Each statement is like a step in a recipe.

- Scripts contain very precise instructions. For example,you might specify that a value must be remembered
before creating a calculation using that value.

- Variables are used to temporarily store pieces of information used in the script.

- Arrays are special types variables that store more than one piece of related information.

- JavaScript distinguishes between numbers (0-9),strings (text), and Boolean values (true or false)

- Expressions evaluate into a single value.

- Expressions rely on operators to calculate a value. 

**Decisions and Loops:**

 *Decision Making Statements*
 - A programming language uses control statements to control the flow of execution of the program based on certain conditions.

  1) **if statement:**
 - if statement is the most simple decision making statement.
 - It is used to decide whether a certain statement or block of statements will be executed or not.
 - If a certain condition is true then a block of statement is executed otherwise not.
   Syntax:
if ( condition ) 
{
   // block of code to be executed
}


2) **if…else statement:**
- The if-else statement has two parts if block and else block.
- If the condition is true then if block (true block) will get executed and if the condition is false then else block (false block)  will get executed.
Syntax:
if ( condition )  
{
    // block of code to be executed when condition is true
} 
else 
{
    // block of code to be executed when condition is false
}



3) **if…else...if statement:**

- The if…else…if statement statement is an advanced form of if…else that allows JavaScript to make a correct decision out of several conditions.
- All the if conditions will be checked one by one. If any condition is true out of given then that block will get executed and other blocks are skipped.



**loops:**

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