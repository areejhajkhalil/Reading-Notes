# JS book:

**Object Literals:**
-*Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.*

-*If a variable is part of an object, it is called a property. Properties te ll us about the object, such as the name of a hotel or the number of rooms it has. Each individual hotel might have a different name and a different number of rooms*

-*If a function is part of an object, it is called a method. Methods represent tasks that are associated with the object. For example, you can check how many rooms are available by subtracting the number of booked rooms from the total number of rooms*


*There are different ways to create new objects:*

**Define and create a single object, using an object literal.*
*Define and create a single object, with the keyword new.*
*Define an object constructor, and then create objects of the constructed type.*

*Using an Object Literal:*

*Using an object literal, you both define and create an object in one statement.*

*An object literal is a list of name:value pairs (like age:50) inside curly braces {}.*

*The following example creates a new JavaScript object with four properties:*

*Example*
var person = {firstName:"John", lastName:"Doe", age:50, eyeColor:"blue"};




**Document Object Model:**

*The Document Object Model (DOM) is a programming interface for HTML and XML documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects. That way, programming languages can connect to the page.*

*A Web page is a document. This document can be either displayed in the browser window or as the HTML source. But it is the same document in both cases. The Document Object Model (DOM) represents that same document so it can be manipulated. The DOM is an object-oriented representation of the web page, which can be modified with a scripting language such as JavaScript.*


*For example, the standard DOM specifies that the querySelectorAll method in the code below must return a list of all the <p> elements in the document:*

const paragraphs = document.querySelectorAll("p");
// paragraphs[0] is the first <p> element
// paragraphs[1] is the second <p> element, etc.
alert(paragraphs[0].nodeName);


*DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.*

*You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax.*
