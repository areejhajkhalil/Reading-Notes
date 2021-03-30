# HTML Book:

 **Links:**
-*Links are created using the <a> element. Users can click on anything between the opening <a> tag and the closing </a> tag. You specify
  which page you want to link to using the href attribute.*

-***links between pages:***
-*Link contact us, about, home or any other external website page using the page links, which gets added inside an HTML document. To   make page links in an HTML page, use the <a> and </a> tags, which are the tags used to define the links.*

<a href="" class="items">Home</a></li>

-***Linking to other sites:***
-*Linking in HTML code is done with the anchor tag, the <A> tag. The letter "A" in the tag is then followed by an attribute. For a link to another web page, the "A" is followed by "HREF". To set a bookmark in the same page, the "A" is followed by "NAME", which you'll see how to do later.*

 <A HREF = "http://www.google.com/">Google Search Engine</A>

-***Email links:***
-*HTML <a> tag provides you option to specify an email address to send an email. While using <a> tag as an email tag, you will use mailto: email address along with href attribute. Following is the syntax of using mailto instead of using http.*

<a href = "mailto: abc@example.com">Send Email</a>



**Loyout:**
-*There are five types:*

**static:**
*HTML elements are positioned static by default and the element is positioned according to the normal flow of the document; static positioned elements are not affected by the top, bottom, left, and right properties.*


**relative:**
*The element is positioned according to the normal flow of the document is positioned relative to its normal position, and then offset relative to itself based on the values of top, right, bottom, and left.*

**absolute:**:
*The element is removed from the normal document flow, and, in the page layout, no space is created for the element. The element is positioned relative to the closest positioned ancestor, if there is any; otherwise, it is placed relative to the initial containing block and its final position is determined by the values of top, right, bottom, and left.*

**fixed:**
*The element it is removed from the normal document flow, and, in the page layout, there is no space created for the element. The element is positioned relative to its initial containing block established by the viewport and its final position is determined by the values top, right, bottom, and left.*

**sticky:**
*The element is positioned corresponding to the normal flow of the document, and then offset relative to its closest ascending block-level, including table-related elements, according to the values of top, right, bottom, and left. The offset does not affect the position of any other elements.*





# JavaScript book:

-***Function Definition:***

*Before we use a function, we need to define it. The most common way to define a function in JavaScript is by using the function keyword, followed by a unique function name, a list of parameters (that might be empty), and a statement block surrounded by curly braces.*

-Syntax:

<script type = "text/javascript">
   <!--
      function functionname(parameter-list) {
         statements
      }
   //-->
</script>


-Example:

<script type = "text/javascript">
   <!--
      function sayHello() {
         alert("Hello there");
      }
   //-->
</script>


-***Calling a Function:***

-*To invoke a function somewhere later in the script, you would simply need to write the name of that function as shown in the following code.*

<html>
   <head>   
      <script type = "text/javascript">
         function sayHello() {
            document.write ("Hello there!");
         }
      </script>
      
   </head>
   
   <body>
      <p>Click the following button to call the function</p>      
      <form>
         <input type = "button" onclick = "sayHello()" value = "Say Hello">
      </form>  …