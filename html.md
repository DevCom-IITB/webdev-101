# Hypertext Markup Language (HTML)
![Alt Text](assets/html.jpg)

 HTML serves as the standard markup language for crafting web pages. It defines the structure of a web page through a series of elements, each tasked with instructing the browser on how to present content. These elements act as labels, categorizing different pieces of content, such as headings, paragraphs, links, and more. In essence, HTML provides a framework that dictates how information should be organized and displayed within a web page
## HyperText 
Hypertext is text displayed on a computer display or other electronic devices with references to other text that the reader can immediately access. Hypertext documents are interconnected by hyperlinks, which are typically activated by a mouse click, keypress set, or screen touch

## Structure of a HTML code
```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

### Explanation
* The ```<!DOCTYPE html>``` declaration defines that this document is an HTML5 document
* The ```<html>``` element is the root element of an HTML page
* The ```<head>``` element contains meta information about the HTML page
* The ```<title>``` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
* The ```<body>``` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
* The ```<h1>``` element defines a large heading
* The ```<p>``` element defines a paragraph

## Most Used Tags

### Container Tags
Also known as block-level tags, are HTML elements that define sections or blocks of content within a web page. These tags are used to group and structure content, and they often create a distinct block on the page. Here are some common container tags in HTML:

1. **`<div>`:**
   - Defines a generic container or division in an HTML document. It is a versatile tag often used for grouping and styling content.

    ```html
    <div>
        <!-- Content goes here -->
    </div>
    ```

2. **`<span>`:**
   - Defines an inline container, typically used for applying styles or scripting to a small piece of text within a line.

    ```html
    <span>
        <!-- Inline content goes here -->
    </span>
    ```

3. **`<p>`:**
   - Represents a paragraph, creating a block of text with space above and below it.

    ```html
    <p>
        This is a paragraph.
    </p>
    ```

4. **`<header>`:**
   - Defines a header section for the document or a section within the document.

    ```html
    <header>
        <!-- Header content goes here -->
    </header>
    ```

5. **`<footer>`:**
   - Defines a footer section for the document or a section within the document.

    ```html
    <footer>
        <!-- Footer content goes here -->
    </footer>
    ```

6. **`<section>`:**
   - Represents a generic section within a document, often used to group related content together.

    ```html
    <section>
        <!-- Section content goes here -->
    </section>
    ```

7. **`<article>`:**
   - Represents an independent, self-contained piece of content that can exist and be distributed separately from the rest of the document.

    ```html
    <article>
        <!-- Article content goes here -->
    </article>
    ```

8. **`<main>`:**
   - Defines the main content within an HTML document, excluding headers, footers, and sidebars.

    ```html
    <main>
        <!-- Main content goes here -->
    </main>
    ```

These container tags help organize and structure the content of a web page, making it more readable and providing a clear hierarchy for styling and layout purposes.
### Empty Tags
Empty tags, also known as self-closing tags or void elements, are HTML elements that do not have any content between an opening and closing tag. Instead, they self-close with a single tag. These elements are used for various purposes, such as inserting media, line breaks, or creating standalone elements. Here are some common empty tags in HTML:

1. **`<img>`:**
   - Embeds an image in the document.

    ```html
    <img src="image.jpg" alt="Description">
    ```

2. **`<br>`:**
   - Represents a line break.

    ```html
    <p>This is a line of text.<br>This is a new line.</p>
    ```

3. **`<hr>`:**
   - Represents a thematic break or horizontal rule.

    ```html
    <p>Some content above<hr>Some content below</p>
    ```

4. **`<input>`:**
   - Creates an input field within a form.

    ```html
    <input type="text" name="username">
    ```

5. **`<meta>`:**
   - Provides metadata about the HTML document, such as character set, viewport settings, etc.

    ```html
    <meta charset="UTF-8">
    ```

6. **`<link>`:**
   - Defines the relationship between the current document and an external resource, like a stylesheet.

    ```html
    <link rel="stylesheet" href="styles.css">
    ```

7. **`<area>`:**
   - Defines a clickable area within an image map.

    ```html
    <img src="planets.jpg" usemap="#planetmap">
    <map name="planetmap">
      <area shape="rect" coords="34,44,270,350" alt="Sun">
    </map>
    ```

8. **`<col>`:**
   - Specifies column properties for columns within a table.

    ```html
    <table>
      <colgroup>
        <col style="background-color: yellow;">
        <col style="background-color: lightgreen;">
      </colgroup>
      <tr>
        <td>Column 1</td>
        <td>Column 2</td>
      </tr>
    </table>
    ```

These empty tags simplify the structure of HTML documents and are essential for incorporating various types of content and functionality.

### Basic Tags

Basic HTML tags are the fundamental building blocks used to structure and format content within an HTML document. Here are some of the most common basic HTML tags:

6. **`<h1>` to `<h6>`:**
   - Define headings of different levels, `<h1>` being the largest and `<h6>` the smallest.

    ```html
    <h1>This is a Heading 1</h1>
    <h2>This is a Heading 2</h2>
    <!-- ... -->
    <h6>This is a Heading 6</h6>
    ```

7. **`<p>`:**
   - Represents a paragraph of text.

    ```html
    <p>This is a paragraph.</p>
    ```

8. **`<a>`:**
   - Creates a hyperlink, linking to another document or resource.

    ```html
    <a href="https://www.example.com">Visit Example.com</a>
    ```

9. **`<img>`:**
   - Embeds an image in the document.

    ```html
    <img src="image.jpg" alt="Image Description">
    ```

10. **`<ul>` and `<li>`:**
    - Define an unordered list and list items.

    ```html
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>
    ```

11. **`<ol>` and `<li>`:**
    - Define an ordered list and list items.

    ```html
    <ol>
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>
    ```

12. **`<br>`:**
    - Represents a line break within text.

    ```html
    <p>This is a line of text.<br>This is a new line.</p>
    ```
13. **`<pre>`:**
     - Used for preformatted text, preserving white spaces and line breaks.


    ```html
    <pre>
        This is an example
        of preformatted text.
        
        It preserves      white spaces
        and line breaks.
    </pre>
    ```
    The B, I, and U tags in HTML are used for text formatting:

1. **`<b>` Tag:**
   - Represents bold text.
   ```html
    <p>This is <b>bold</b> text.</p>
    ```

2. **`<i>` Tag:**
   - Represents italicized text.
   ```html
    <p>This is <i>italic</i> text.</p>
    ```

3. **`<u>` Tag:**
   - Represents underlined text.
  


    ```html
    <p>This is <u>underlined</u> text.</p>
    ```
3. **`<font>` Tag:**
   -  used for defining font, color, and size of text.
    ```html
    <font face="Arial" color="blue" size="4">Styled text using the font tag.</font>
    ```
3. **`<marquee>` Tag:**
   -  used to create a scrolling or moving text or image within a webpage.
    ```html
    <marquee behavior="scroll" direction="left">Scrolling Text</marquee>

    ```
    <marquee behavior="scroll" direction="left"> DevCom </marquee>
1. **`<div>`:**
   - Defines a generic container or division in an HTML document. It is a versatile tag often used for grouping and styling content.

    ```html
    <div>
        <!-- Content goes here -->
    </div>
    ```

1. **`<table>`:**
   - The `<table>` tag in HTML is used to create tables for organizing and displaying data in rows and columns. Here's a brief definition with an example:

    ```html
    <table border="1">
    <tr>
    <th>Header 1</th>
    <th>Header 2</th>
    </tr>
    <tr>
    <td>Data 1</td>
    <td>Data 2</td>
    </tr>
    </table>
    ```
1. **`<input>`**
   The `<input>` tag along with the `<form>` tag is used to specify various kinds input fields, creating a whole new architecture of web-based-forms.

   ```html
    <form>
        <label for="fname">First name:</label><br>
        <input type="text" id="fname" name="fname"><br>
        <label for="lname">Last name:</label><br>
        <input type="text" id="lname" name="lname">
    </form>
    ```

    |Type|Description|
    |------|----------------|
    |`<input type="text">` |Displays a single-line text input field|
    |`<input type="radio">` |Displays a radio button (for selecting one of many choices)|
    |`<input type="checkbox">`|Displays a checkbox (for selecting zero or more of many choices)|
    |`<input type="submit">`|Displays a submit button (for submitting the form)|
    |`<input type="button">`|Displays a clickable button|


### Attributes
In HTML, attributes are used to specify certain properties of the elements, like img tag has an src attribute.

The `id` and `class` attributes are commonly used to provide additional information about elements :

1. **`id` Attribute:**
   - The `id` attribute is used to uniquely identify an HTML element within a document.
   - The value of the `id` attribute must be unique within the HTML document, meaning no two elements should have the same `id`.
   - It is often used to link to a specific element using fragment identifiers in URLs or to target elements with CSS and JavaScript.
   - Example:

     ```html
     <div id="uniqueElement">This is a unique element.</div>
     ```

2. **`class` Attribute:**
   - The `class` attribute is used to specify one or more class names for an HTML element.
   - Class names can be shared among multiple elements, allowing you to apply the same styling or behavior to multiple elements.
   - You can define styles for a class in CSS and apply JavaScript actions to elements with a particular class.
   - Multiple classes can be applied to an element by separating them with spaces.
   - Example:

     ```html
     <p class="highlighted">This paragraph has a special style.</p>
     ```

     In this example, the `highlighted` class might be defined in a CSS stylesheet with specific styling.

   - Example with multiple classes:

     ```html
     <p class="highlighted important">This paragraph is both highlighted and important.</p>
     ```

     Here, the element has both the `highlighted` and `important` classes.

These attributes are fundamental for styling and scripting in web development, allowing developers to target specific elements and apply styles or functionality. They are widely used in conjunction with CSS for styling and JavaScript for dynamic behavior on the client side.


