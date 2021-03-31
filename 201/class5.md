# HTML Book:

        **image:**

        *The <img> tag is used to embed an image in an HTML page.*

        *Images are not technically inserted into a web page; images are linked to web pages. The <img> tag creates a holding space for the referenced image.*

        *The <img> tag has two required attributes:*

        *-src - Specifies the path to the image.*
        *-alt - Specifies an alternate text for the image, if the image for some reason cannot be displayed.*
        *-Also, always specify the width and height of an image. If width and height are not specified, the page might flicker while the image loads.*

        example:
        <img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">



        **color:**

        *At the element level, everything in HTML can have color applied to it. Instead, let's look at things in terms of the kinds of things that are drawn in the elements, such as text and borders and so forth. For each, we'll see a list of the CSS properties that apply color to them.*

        *At a fundamental level, the color property defines the foreground color of an HTML element's content and the background-color property defines the element's background color. These can be used on just about any element.*


        ***Text:***

        *Whenever an element is rendered, these properties are used to determine the color of the text, its background, and any decorations on the text.*

        *(color):*

        *The color to use when drawing the text and any text decorations (such as the addition of under- or overlines, strike-through lines, and so forth.*


        body {
        color: red;
        }

        h1 {
        color: #00ff00;
        }

        p.ex {
        color: rgb(0,0,255);
        }
        h1 {



        *(background-color):*

        *The text's background color.*

        body {
        background-image: url("img_tree.gif"), url("paper.gif");
        background-color: #cccccc;
        }


        *(text-shadow):*

        *Configures a shadow effect to apply to text. Among the options for the shadow is the shadow's base color (which is then blurred and blended with the background based on the other parameters). See Text drop shadows in Fundamental text and font styling to learn more.*

        h1 {
        text-shadow: 2px 2px;
        }



        *(text-decoration-color):*

        *By default, text decorations (such as underlines, strikethroughs, etc) use the color property as their colors. However, you can override that behavior and use a different color for them with the text-decoration-color property.*

        p {
        text-decoration: underline;
        text-decoration-color: red;
        }


        *(text-emphasis-color:)*

        *The color to use when drawing emphasis symbols adjacent to each character in the text. This is used primarily when drawing text for East Asian languages.*

        p
        {
        text-align:justify;
        text-justify:inter-word;
        }


        *(caret-color:)*

        The color to use when drawing the caret (sometimes referred to as the text input cursor) within the element. This is only useful in elements that are editable, such as <input> and <textarea> or elements whose HTML contenteditable attribute is set.

        <img src="images/quokka.jpg" alt="A family of
        quokka" width="600" height="450" />



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


                                        