# HTML book:

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


**Boxes:**
- All HTML elements can be considered as boxes. In CSS, the term "box model" is used when talking about design and layout.
The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content.

- Explanation of the different parts:

- Content - The content of the box, where text and images appear
- Padding - Clears an area around the content. The padding is transparent
- Border - A border that goes around the padding and content
- Margin - Clears an area outside the border. The margin is transparent.

- The box model allows us to add a border around elements, and to define space between elements.
Width and Height of an Element
In order to set the width and height of an element correctly in all browsers, you need to know how the box model works.

- Here is the math:

320px (width)
+ 20px (left + right padding)
+ 10px (left + right border)
+ 0px (left + right margin)
= 350px



# JS book:

**Array:**
-*An array is a special variable, which can hold more than one value at a time.*

*-If you have a list of items (a list of car names, for example), storing the cars in single variables could look like this:*

var car1 = "Saab";
var car2 = "Volvo";
var car3 = "BMW";

-*An array can hold many values under a single name, and you can access the values by referring to an index number.*

-*Arrays are a special type of objects. The typeof operator in JavaScript returns "object" for arrays.*

 But, JavaScript arrays are best described as arrays.*

*-Arrays use numbers to access its "elements". In this example, person[0] returns John:*

*-Array:
var person = ["John", "Doe", 46];




**if else statements:**

-*Conditional statements allow your code to make decisions about what to do next.*

-*Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>) are used to compare two operands.*

-*Logical operators allow you to combine more than one set of comparison operators.*

-*if ... else statements allow you to run one set of code if a condition is true, and another if it is false.*

-*switch statements allow you to compare a value against possible outcomes (and also provides a default
option if none match).*

-*Data types can be coerced from one type to another.*

-*All values evaluate to either truthy or falsy.*

-*There are three types of loop: for, while, and do ... while. Each repeats a set of statements.*



