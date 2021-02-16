# HTML Links - Hyperlinks
![link](https://th.bing.com/th/id/R7b1e3b81911a83ed560bcfee1eb03349?rik=Y6q3ia9KG%2fwqBA&riu=http%3a%2f%2fwww.wikihow.com%2fimages%2f6%2f6c%2fAdd-a-Hyperlink-with-HTML-Step-6-Version-2.jpg&ehk=B0FiyL0tCSrBZJvNCOn7cbxAg0ChF9WzlHlogY0%2fJNk%3d&risl=&pid=ImgRaw)
HTML links are hyperlinks.

You can click on a link and jump to another document.

When you move the mouse over a link, the mouse arrow will turn into a little hand.

Note: A link does not have to be text. A link can be an image or any other HTML element!

HTML Links - Syntax

The HTML < a> tag defines a hyperlink. It has the following syntax:

```html
<a href="url">link text</a>
```

## HTML Links - The target Attribute

The target attribute can have one of the following values:

* _self - Default. Opens the document in the same window/tab as it was clicked
* _blank - Opens the document in a new window or tab
* _parent - Opens the document in the parent frame
* _top - Opens the document in the full body of the window

## HTML Link Colors

* An unvisited link is underlined and blue
* A visited link is underlined and purple
* An active link is underlined and red

```css
<style>
a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color: pink;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}

a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
</style>
```


____
## Link to an Email Address
Use mailto: inside the href attribute to create a link that opens the user's email program (to let them send a new email):

Example
```html
<a href="mailto:someone@example.com">Send email</a>
```
_______
## HTML Layout Elements

* < header> - Defines a header for a document or a section
* < nav> - Defines a set of navigation links
* < section> - Defines a section in a document
* < article> - Defines an independent, self-contained content
* < aside> - Defines content aside from the content (like a sidebar)
* < footer> - Defines a footer for a document or a section
* < details> - Defines additional details that the user can open and close on demand
* < summary> - Defines a heading for the <details> element

### CSS Flexbox Layout
Use of flexbox ensures that elements behave predictably when the page layout must accommodate different screen sizes and different display devices.

The position Property
The position property specifies the type of positioning method used for an element.

There are five different position values:

* static
* relative
* fixed
* absolute
* sticky

---
 ## Position

Gives strict, coordinate-based control over layout.
* position: absolute
![abslute](https://learn-the-web.algonquindesign.ca/topics/css-layout-cheat-sheet/absolute.svg)

* position: relative
![rel](https://learn-the-web.algonquindesign.ca/topics/css-layout-cheat-sheet/relative.svg)

* position: fixed
![1](https://learn-the-web.algonquindesign.ca/topics/css-layout-cheat-sheet/fixed.svg)

* z-index

![2](https://learn-the-web.algonquindesign.ca/topics/css-layout-cheat-sheet/z-index.svg)

______
## JavaScript Functions

JavaScript Function Syntax
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}

```js
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
```
JavaScript Function Syntax
A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}

```js
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
```

_____________

## JavaScript Date Objects
JavaScript Date Output

>By default, JavaScript will use the browser's time zone and display a date as a full text string:


>Sun Feb 14 2021 02:39:37 GMT-0800 (Pacific Standard Time)
.

* Creating Date Objects
Date objects are created with the new Date() constructor.

There are 4 ways to create a new date object:

1-new Date()

2- new Date(year, month, day, hours, minutes, seconds, milliseconds)

3- new Date(milliseconds)

4- new Date(date string)

5- new Date()

6- new Date() 
creates a new date object with the current date and time:

* Example
>var d = new Date();
Date objects are static. The computer time is ticking, but date objects are not.

>new Date(year, month, ...)
>new Date(year, month, ...) creates a new date object with a specified date and time.