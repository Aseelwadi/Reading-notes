# Forms
HTML form is used to collect user input. The user input is most often sent to a server for processing.

![](https://i.ytimg.com/vi/O7KKh0peqpc/maxresdefault.jpg)


* < form> Element
The HTML <form> element is used to create an HTML form for user input:

```html
<form>
.
form elements
.
</form>
```

* The < input> Element
The HTML < input> element is the most used form element.

Type|	Description
------|----------
< input type="text"> |	Displays a single-line text input field
< input type="radio">|	Displays a radio button (for selecting one of many choices)
< input type="checkbox">	|Displays a checkbox (for selecting zero or more of many choices)
< input type="submit">	|Displays a submit button (for submitting the form)
< input type="button">	|Displays a clickable button

////////////////////////////////////////////

* Text Fields
The <input type="text"> defines a single-line input field for text input.

* The < label> Element

Notice the use of the < label> element in the example above.
The < label> tag defines a label for many form elements.

The < label> element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

 * Radio Buttons
The <input type="radio"> defines a radio button.

Radio buttons let a user select ONE of a limited number of choices.

* Checkboxes
The <input type="checkbox"> defines a checkbox.

Checkboxes let a user select ZERO or MORE options of a limited number of choices.

* The Submit Button
The <input type="submit"> defines a button for submitting the form data to a form-handler.
______
### The HTML < form> Elements

The HTML < form> element can contain one or more of the following form elements:

* < input>
* < label>
* < select>
* < textarea>
* < button>
* < fieldset>
* < legend>
* < datalist>
* < output>
* < option>
* < optgroup>
_____________
# LISTS, TABLES AND FORMS
* List Style Type

![list](https://idg.net.ua/blog/wp-content/uploads/list-style-type-css-screenshot.png)

* List Style Image
* List Style Position
* List Style Shorthand
* Table Properties
* Empty Cells
![img](https://www.pierre-giraud.com/wp-content/uploads/2019/05/resultat-empty-cells-table.png)
* Gaps Between Cells
* Styling Text Inputs
* Styling Submit Buttons
* Styling Fieldsets and Legends
* Aligning Form Controls: Problem
* Aligning Form Controls: Solution
* Cursor
_________
# HTML Event Attributes

![](https://courses.cs.washington.edu/courses/cse461/10au/section/Section9/WebBasics_files/figure_3_event.png)

* ### The addEventListener() method
x- The addEventListener() method attaches an event handler to the specified element.

x- The addEventListener() method attaches an event handler to an element without overwriting existing event handlers.

* Syntax

element.addEventListener(event, function, useCapture);

* ### The removeEventListener() method
The removeEventListener() method removes event handlers that have been attached with the addEventListener() method

## Notes :
* Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).
* Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon. 