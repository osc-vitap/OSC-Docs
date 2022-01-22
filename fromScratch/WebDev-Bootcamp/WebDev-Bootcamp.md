# Web development documentation

## Day - 1
## HTML- Hyper Text Markup Language

**HTML** stands for _Hyper Text Markup Language_, it's a language used to structure a web page. It's simple yet a really effective language to start designing web pages. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. To start designing web pages with HTML we need to start the file with `<html>` tag, with this we are done with the first i.e creation of a HTML document.  
Next come the two basic yet most immportant tags of HTML, `<head></head>` and `<body></body>`.

1. `<head>` This tag allows the developer define the head portion of the webpage, such as title(`<title>Title of the webpage</title>`).
2. `<body>` This tag is used to define the documnet's body, majority of the tags that you'll learn will fall in this blocks

If you are wondering what tags are, HTML tags are basically keywords that govern how the content of a web page is formatted and displayed. For example, take a look at these following tags:

-   `<h1>` tag is used to define the headings. Bigger the number after 'h', smaller the size.
    -   Syntax: `<h1>heading</h1>`
    -   <h1>h1 heading looks like this</h1>
    -   <h6>the size of the headings can go as small as this</h6>
-   `<b>` tag is used to bold a text, `<i>` tag is used to italise text, `<u>` is used to underline text
    -   Syntax: `<b>text</b>` `<i>text</i>` `<u>text</u>`
    -   <b><i><u>BOLD. Yes, you can use multiple tags at once</b></i></u>
-   `<a href=https.bamboozle.com>` tag is used to link both internal and external web pages
    -   Syntax: `<a href=hhtp.website.com>Hello world.com</a>`.
    -   <a href=https://www.oscvitap.org>Click here for a very cool website.</a>
-   `<p>` tag is used to enclose paragraphs
    -   Syntax: `<p>paragraph here</p>`
    -   <p>hello, text for paragraph is used here as a placeholder</p>
          <p>second paragraph</p>
-   `<br>` tag is used to break a line and move the pointer to the next line. It's important to note that the `<br>` doesn't have an enclosing tag like the tags above
    -   Syntax: `To break line use<br>`

While the above tags may help in strcuturing the basic contents of your webpage, more often than not you'll find yourself wanting to include tables to organise data, or even include a form that takes input from the end user and store it in database. Well, with the help of HTML tags like `<table></table>` `<form></fomr>` you can design your very own tables and forms. Let's learn a little more about these tags!

**Table tag**  
An HTML structure for creating rows and columns on a Web page. The Table tag defines the overall table and the Table Row `<tr>` tag is used to build each row. The Table Data `<td>` tag defines the actual data. Prior to HTML5, tables were often used for virtually every element on the page. Let's look at an example

```
<table>
    <thead>
        <tr>
            <th colspan="2">The table header</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>The table body</td>
            <td>with two columns</td>
        </tr>
    </tbody>
</table>
```

A few notewrothy attributes of `<table>` are:

-   align: This enumerated attribute indicates how the table must be aligned inside the containing document. It may have the following values
    -   left: the table is displayed on the left side of the document;
    -   center: the table is displayed in the center of the document;
    -   right: the table is displayed on the right side of the document.
-   bgcolor: The background color of the table. It is a 6-digit hexadecimal RGB code, prefixed by a '#'. One of the predefined color kewords can also be used.
-   border: This integer attribute defines, in pixels, the size of the frame surrounding the table. If set to 0, the frame attribute is set to void.
-   cellpadding: This attribute defines the space between the content of a cell and its border, displayed or not.
-   cellspacing: This attribute defines the size of the space between two cells in a percentage value or pixels.
<p>Try and write a HTML code to get the following table as an output:</p>
<table align=center>
  <tr style="background-color: #0f0">
    <th>This</th>
    <th>row is</th>
    <th>Green</th>
  </tr>
  <tr style="background-color: #055">
    <td>This</td>
    <td>row is</td>
    <td>#055</td>
  </tr>
</table>

**Form tag**
The `<form>` tag defines an HTML form that contains interactive controls which enable a user to submit information to a web server. An HTML form is used to capture user information such as username, password, address details, credit card information, and so on.

Information can be captured in the form using many different form controls, such as `<input>`, `<textarea>`, `<select>`, `<option>`, `<button>`.

```
<form action="" method="get" class="form-example">
  <div class="form-example">
    <label for="name">Enter your name: </label>
    <input type="text" name="name" id="name" required>
  </div>
  <div class="form-example">
    <label for="email">Enter your email: </label>
    <input type="email" name="email" id="email" required>
  </div>
  <div class="form-example">
    <input type="submit" value="Submit">
  </div>
</form>
```

<form action="" method="get" class="form-example">
  <div class="form-example">
    <label for="name">Enter your name: </label>
    <input type="text" name="name" id="name" required>
  </div>
  <div class="form-example">
    <label for="email">Enter your email: </label>
    <input type="email" name="email" id="email" required>
  </div>
  <div class="form-example">
    <input type="submit" value="Submit">
  </div>
</form>
<br>
There are numerous html tags to use, [Explore this link to find out more intresting HTML tags](https://devdocs.io/html-elements/).  
<br><br>

## CSS- Cascading Style Sheets

Cascading Style Sheets, defines how the elements of html tags should be displayed on screen. It can control the layput of multiple web pages and provides a lot more versitality in attributing HTML tags.

**Why do we hav to use CSS?**  
When tags like `<font>`, and color attributes were added to the HTML 3.2 specification, it started a nightmare for web developers. Development of large websites, where fonts and color information were added to every single page, became a long and expensive process.

To solve this problem, the World Wide Web Consortium (W3C) created CSS.

CSS removed the style formatting from the HTML page!

**CSS Syntax**
A CSS rule consists of a selector and a declaration block. Let's take a look at the following example and learn more about the syntax of CSS

```
body {
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: verdana;
  font-size: 20px;
}
```

In the above example, we are looking to add attributes to `<body>`, `<h1>`, `<p>` tags of HTML. In CSS, selectors are used to "find" (or select) the HTML elements you want to style. Attributes under each selector(background-color is an attribute of body) are called properties and each attribute is given a specifc value to work with
<img src = https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics/css-declaration-small.png>

There are different types of selectors in CSS, selectors used in the above example are specific selectors. Below are some of the types of selectors

<table border=1>
    <tr>
        <td>Selector name</td>
        <td>Definition</td>
    </tr>
    <tr>
        <td>ID selector </td>
        <td>The element on the page with the specified ID. On a given HTML page, each id value should be unique.</td>
    </tr>
    <tr>
        <td>Class selector</td>
        <td>The element(s) on the page with the specified class. Multiple instances of the same class can appear on a page.</td>
    <tr>
        <td>Attribute selector</td>
        <td>The element(s) on the page with the specified attribute.</td>
    </tr>
    <tr>
        <td>Pseudo-class selector</td>
        <td>The specified element(s), but only when in the specified state. (For example, when a cursor hovers over a link.)</td>
    </tr>
</table>

[If you want to learn about more types selectors click here](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors)

Now that we've explored the syntax/rulesets of CSS, let's get strated with basic CSS rules that'll help you in adding more pizazz to your web page

-   **Fonts and texts:** These rules allow usto add appearnce to texts by changing the fonts and adding other attributes.

```
p {
  font-size: 10px; // Changing the size of the font
  font-family: "Open Sans", sans-serif; // Specifying the font of the text
  color: green; // Color of the text can be changed using this property
  /*This ruleset applies all the properties mentioned to paragraph tags in the HTML document*/
}
```

-   **Changing the page color:** This rule sets a background color for the entire page

```
html {
  background-color: #00539F;
}
```

-   **Styling the body:**

```
body {
  width: 600px;
  margin: 0 auto;
  background-color: #FF9500;
  padding: 0 20px 20px 20px;
  border: 5px solid black;
}
```

## Day - 2

## CSS - Flexible Box, Position, Grid, Media query

## Flexible Box
The Flexible Box Module, usually referred to as flexbox, was designed as a one-dimensional layout model, and as a method that could offer space distribution between items in an interface and powerful alignment capabilities.

The main idea behind the flex layout is to give the container the ability to alter its items’ width/height (and order) to best fill the available space (mostly to accommodate to all kind of display devices and screen sizes). A flex container expands items to fill available free space or shrinks them to prevent overflow.

<details>
<summary>Basics and terminology</summary>

    + Since flexbox is a whole module and not a single property, it involves a lot of things including its whole set of properties. Some of them are meant to be set on the container (parent element, known as “flex container”) whereas the others are meant to be set on the children (said “flex items”). When working with flexbox you need to think in terms of two axes — the main axis and the cross axis. The main axis is defined by the flex-direction property, and the cross axis runs perpendicular to it. Everything we do with flexbox refers back to these axes, so it is worth understanding how they work from the outset.

    + The main axis is defined by flex-direction, which has four possible values: "row, row-reverse,column,column-reverse" should you choose row or row-reverse, your main axis will run along the row in the inline direction.

    +main-start | main-end – The flex items are placed within the container starting from main-start and going to main-end.

    + main size – A flex item’s width or height, whichever is in the main dimension, is the item’s main size. The flex item’s main size property is either the ‘width’ or ‘height’ property, whichever is in the main dimension.

    + cross axis – The axis perpendicular to the main axis is called the cross axis. Its direction depends on the main axis direction.

    + cross-start | cross-end – Flex lines are filled with items and placed into the container starting on the cross-start side of the flex container and going toward the cross-end side.

    +cross size – The width or height of a flex item, whichever is in the cross dimension, is the item’s cross size. The cross size property is whichever of ‘width’ or ‘height’ that is in the cross dimension.
</details>

<details>
<summary>Properties applied to flex items</summary>

    + To have more control over flex items we can target them directly. We do this by way of three properties:
        flex-grow
        flex-shrink
        flex-basis
    
</details>

<details>
<summary>Alignment, justification and distribution of free space between items</summary>

    + A key feature of flexbox is the ability to align and justify items on the main- and cross-axes, and to distribute space between flex items. Note that these properties are to be set on the flex container, not on the items themselves

    + The align-items property will align the items on the cross axis

    + The justify-content property is used to align the items on the main axis, the direction in which flex-direction has set the flow. The initial value is flex-start which will line the items up at the start edge of the container, but you could also set the value to flex-end to line them up at the end, or center to line them up in the centre.

    + 
</details>
<br>
<br>  

[In depth alignments guide](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Aligning_Items_in_a_Flex_Container)

[In depth Flex box properties](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#flexbox-properties)  

[Please follow this link to learn more about Controlling Ratios of Flex Items on the Main Axis](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Controlling_Ratios_of_Flex_Items_Along_the_Main_Ax)  

