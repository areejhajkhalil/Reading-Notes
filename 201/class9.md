# HTML Book:

**Forms:**
*There are several types of form controls that you can use to collect information from visitors to your site.*
*An HTML form is used to collect user input. The user input is most often sent to a server for processing.*

*The <form> Element:*
The HTML <form> element is used to create an HTML form for user input:

<form>
.
form elements
.
</form>
The <form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.

All the different form elements are covered in this chapter: HTML Form Elements.



*The <input> Element:*
*The HTML <input> element is the most used form element.*

*An <input> element can be displayed in many ways, depending on the type attribute.*

*Here are some examples:*
<input type="text">



*Text Fields:*
*The <input type="text"> defines a single-line input field for text input.*

*Example:*
*A form with input fields for text:*

<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>


*The Submit Button:*
*The <input type="submit"> defines a button for submitting the form data to a form-handler.*

*The form-handler is typically a file on the server with a script for processing input data.*

*The form-handler is specified in the form's action attribute.*

*Example:*
*A form with a submit button:*

<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form>




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


**Lists:**

***Unordered Lists***
An unordered list created using the <ul> element, and each list item starts with the <li> element.
The list items in unordered lists are marked with bullets. Here's an example:
 <ul>
    <li>Chocolate Cake</li>
    <li>Black Forest Cake</li>
    <li>Pineapple Cake</li>
</ul>


 ***Ordered Lists***
An ordered list created using the <ol> element, and each list item starts with the <li> element. Ordered lists are used when the order of the list's items is important.

The list items in an ordered list are marked with numbers. Here's an example:
<ol start="10">
    <li>Mix ingredients</li>
    <li>Bake in oven for an hour</li>
    <li>Allow to stand for ten minutes</li>
</ol>



***Description Lists***
A description list is a list of items with a description or definition of each item.
The description list is created using <dl> element. The <dl> element is used in conjunction with the <dt> element which specify a term, and the <dd> element which specify the term's definition.

Browsers usually render the definition lists by placing the terms and definitions in separate lines, where the term's definitions are slightly indented. Here's an example:
 <dl>
    <dt>Bread</dt>
    <dd>A baked food made of flour.</dd>
    <dt>Coffee</dt>
    <dd>A drink made from roasted coffee beans.</dd>
</dl>



# js Book:

**EVENT:**
*HTML Events:*
*An HTML event can be something the browser does, or something a user does.*

*Here are some examples of HTML events:*

*An HTML web page has finished loading*
*An HTML input field was changed*
*An HTML button was clicked*
*Often, when events happen, you may want to do something.*

*JavaScript lets you execute code when events are detected.*

*HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.*

*With single quotes:*

<element event='some JavaScript'>
With double quotes:

<element event="some JavaScript">
In the following example, an onclick attribute (with code), is added to a <button> element:

*Example:*
<button onclick="document.getElementById('demo').innerHTML = Date()">The time is?</button>

*Event handlers can be used to handle and verify user input, user actions, and browser actions:*

*Things that should be done every time a page loads*
*Things that should be done when the page is closed*
*Action that should be performed when a user clicks a button*
*Content that should be verified when a user inputs data*
*And more ...*
*Many different methods can be used to let JavaScript work with events:*

*HTML event attributes can execute JavaScript code directly*
*HTML event attributes can call JavaScript functions*
*You can assign your own event handler functions to HTML elements*
*You can prevent events from being sent or being handled*
*And more ...*