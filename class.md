# HTML Forms
___
![forms](https://www.kooba.ie/images/uploads/blog/article/Social_Post_-_Forms.jpg)

### An HTML form is used to collect user input. The user input is most often sent to a server for processing.
- - 

## * The < form> Element
The HTML < form> element is used to create an HTML form for user input:
 ```html
<form>
.
form elements
.
</form>

 ```

* ### note : 
The < form> element is a container for different types of input elements, such as: text fields, checkboxes, radio buttons, submit buttons, etc.
____


 ## HTML Form Elements.

* The **< input>** Element :

The HTML < input> element is the most used form element.

* An < input> element can be displayed in many ways, depending on the type attribute.

Here are some examples:

Type |	Description
------|-------------
< input type="text"> |	Displays a single-line text input field
< input type="radio">	| Displays a radio button (for selecting one of many choices)
< input type="checkbox"> |	Displays a checkbox (for selecting zero or more of many choices)
< input type="submit"> |	Displays a submit button (for submitting the form)
< input type="button"> |	Displays a clickable button
_______

## How Forms Work 

![img](https://th.bing.com/th/id/OIP.r24LFj9R3LlITunueSKUAQHaFj?pid=ImgDet&w=400&h=300&rs=1)

____

## HTML Form Attributes

* The Action Attribute

The action attribute defines the action to be performed when the form is submitted.

Example
```html
<form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="Aseel"><br>
  <label for="lname">Last name:</label><br>
  <br>
  <input type="submit" value="Submit">
</form>
```

___
* The Method Attribute

The method attribute specifies the HTTP method to be used when submitting the form data.

Example

```html 
<form action="/action_page.php" method="get">
```
_______
## HTML Tables

* The < table> tag defines an HTML table.

* Each table row is defined with a < tr> tag. 
* Each table header is defined with a < th> tag. * Each table data/cell is defined with a < td> tag.

--- By default, the text in  < th> elements are bold and centered.

1- HTML Table - Add a Border
To add a border to a table, use the CSS border property

Example

```css
table, th, td {
  border: 1px solid black;
}
```

______
### Summary
1- Use the HTML < table> element to define a table

2- Use the HTML < tr> element to define a table row

3- Use the HTML < td> element to define a table data

4- Use the HTML < th> element to define a table heading

5- Use the HTML < caption> element to define a table caption

* Use the CSS border property to define a border
* Use the CSS border-collapse property to collapse cell borders
* Use the CSS padding property to add padding to cells
* Use the CSS text-align property to align cell text
* Use the CSS border-spacing property to set the spacing between cells
* Use the colspan attribute to make a cell span many columns
* Use the rowspan attribute to make a cell span many rows
* Use the id attribute to uniquely define one table


___________

## HTML List Tags
Tag	| Description
-------|----------
< ul>|	Defines an unordered list
< ol>|	Defines an ordered list
< li>|	Defines a list item
< dl>|	Defines a description list
< dt>|	Defines a term in a description list
< dd>|	Describes the term in a description list
_____
 
 *< ol>
 Type |	Description
 ------|-----------
type="1" |	The list items will be numbered with numbers (default)
type="A" |	The list items will be numbered with uppercase letters
type="a" |	The list items will be numbered with lowercase letters
type="I" |	The list items will be numbered with uppercase roman numbers
type="i" |	The list items will be numbered with lowercase roman numbers

__________

## JavaScript Events

HTML events are "things" that happen to HTML elements.

When JavaScript is used in HTML pages, JavaScript can "react" on these events.

HTML allows event handler attributes, with JavaScript code, to be added to HTML elements.

With single quotes:

< element event='some JavaScript'>
With double quotes:

< element event="some JavaScript">
In the following example, an onclick attribute (with code), is added to a < button> element:
Example

```js
<button onclick="document.getElementById('demo').innerHTML = Date()">The time is?</button>
```

____
### Common HTML Events

Event	| Description
--------|------------
onchange	|An HTML element has been changed
onclick	|The user clicks an HTML element
onmouseover	The user moves the mouse over an HTML element
onmouseout|	The user moves the mouse away from an HTML element
onkeydown	|The user pushes a keyboard key
onload	|The browser has finished loading the page

_______
## JavaScript HTML DOM EventListener
* The addEventListener() method attaches an event handler to the specified element.

* The addEventListener() method attaches an event handler to an element without overwriting existing event handlers.

* Syntax

>element.addEventListener(event, function, useCapture);

### Example

```js
element.addEventListener("click", myFunction);

function myFunction() {
  alert ("Hello World!");
}
```