# HTML Book:

**Tables:**

**Define an HTML Table:**
*The <table> tag defines an HTML table.*

*Each table row is defined with a <tr> tag. Each table header is defined with a <th> tag. Each table data/cell is defined with a <td> tag.*

*By default, the text in <th> elements are bold and centered.*

*By default, the text in <td> elements are regular and left-aligned.*

*Example:*
*A simple HTML table:*

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th> 
    <th>Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td> 
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td> 
    <td>94</td>
  </tr>
</table>

*To add a border to a table, use the CSS border property:*

*Example:*
table, th, td {
  border: 1px solid black;
}


*HTML Table - Collapsed Borders:*

*Example:*
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}


*HTML Table - Add Cell Padding:*

1-*Cell padding specifies the space between the cell content and its borders.

2-*If you do not specify a padding, the table cells will be displayed without padding.



*To set the padding, use the CSS padding property:*

Example
th, td {
  padding: 15px;
}


*HTML Table - Left-align Headings:*
*By default, table headings are bold and centered.*



*To left-align the table headings, use the CSS text-align property:*

Example
th {
  text-align: left;
}

*HTML Table - Add Border Spacing:*
*Border spacing specifies the space between the cells.*


*To set the border spacing for a table, use the CSS border-spacing property:*

Example
table {
  border-spacing: 5px;
}



# js Book:

**Functions:**
*JavaScript Function Syntax:*
*A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().*

*Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).*

*The parentheses may include parameter names separated by commas:*
(parameter1, parameter2, ...)

*The code to be executed, by the function, is placed inside curly brackets: {}*

function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
*Function parameters are listed inside the parentheses () in the function definition.*

*Function arguments are the values received by the function when it is invoked.*

*Inside the function, the arguments (the parameters) behave as local variables.*



*Function Invocation:*
*The code inside the function will execute when "something" invokes (calls) the function:*

*When an event occurs (when a user clicks a button)*
*When it is invoked (called) from JavaScript code*
*Automatically (self invoked)*



*Function Return:*
*When JavaScript reaches a return statement, the function will stop executing.*

*If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.*

*Functions often compute a return value. The return value is "returned" back to the "caller":*

*Example:*

*Calculate the product of two numbers, and return the result:*

var x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;             // Function returns the product of a and b
}
The result in x will be:
12



*Why Functions?*
*You can reuse code: Define the code once, and use it many times.*

*You can use the same code many times with different arguments, to produce different results.*

*Example:*
Convert Fahrenheit to Celsius:*

function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius(77);
Try it Yourself »
The () Operator Invokes the Function
*Using the example above, toCelsius refers to the function object, and toCelsius() refers to the function result.*

*Accessing a function without () will return the function object instead of the function result.*

Example
function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius;



*Local variables:*

*Variables declared within a JavaScript function, become LOCAL to the function.*

*Local variables can only be accessed from within the function.*

*Example:*
// code here can NOT use carName

function myFunction() {
  var carName = "Volvo";
  // code here CAN use carName
}



**Methods:**
*JavaScript methods are actions that can be performed on objects. A JavaScript method is a property containing a function definition. Methods are functions stored as object properties.*

*The (this)) Keyword:*
*In a function definition, this refers to the "owner" of the function.*

*In the example above, this is the person object that "owns" the fullName function.*

*In other words, this.firstName means the firstName property of this object.*


*JavaScript Methods:*
JavaScript methods are actions that can be performed on objects.

A JavaScript method is a property containing a function definition
*This example accesses the fullName() method of a person object:

*Example:**
*name = person.fullName();*

*If you access the fullName property, without (), it will return the function definition:*

*Example:*
*name = person.fullName;*

*Using Built-In Methods:*
This example uses the toUpperCase() method of the String object, to convert a text to uppercase:

var message = "Hello world!";
var x = message.toUpperCase();
The value of x, after execution of the code above will be:
HELLO WORLD!

*Adding a Method to an Object*
*Adding a new method to an object is easy:*

*Example:*
person.name = function () {
  return this.firstName + " " + this.lastName;
};


**Objects:**
*The HTML <object> element represents an external resource, which can be treated as an image, a nested browsing context, or a resource to be handled by a plugin.*

*Example:*
<object data="flashmovie.swf" width="600" height="800" type="application/x-shockwave-flash">
Please install the Shockwave plugin to watch this movie.
</object>

*Note that the type attribute tells the browser which plugin to load to display the content, but you only need to specify either type or data – not necessarily both. Any text that you include between the <object> and </object> tags will be displayed if the plugin is not available.*

