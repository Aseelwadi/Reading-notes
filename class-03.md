# Class 03
________________
# Lists
![img](https://cloud.netlifyusercontent.com/assets/344dbf88-fdf9-42bb-adb4-46f01eedd629/7db7b396-48da-4e19-9df5-ed21d9de5d39/list-markers.jpg)


## HTML List Tags
Tag	| Description
-------|----------
< ul>|	Defines an unordered list
< ol>|	Defines an ordered list
< li>|	Defines a list item
< dl>|	Defines a description list
< dt>|	Defines a term in a description list
< dd>|	Describes the term in a description list

______


* Ordered HTML List
An ordered list starts with the < ol> tag. Each list item starts with the < li> tag.



The list items will be marked with numbers by default:

Example
 ```html
 <ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
 ```
 Type |	Description
 ------|-----------
type="1" |	The list items will be numbered with numbers (default)
type="A" |	The list items will be numbered with uppercase letters
type="a" |	The list items will be numbered with lowercase letters
type="I" |	The list items will be numbered with uppercase roman numbers
type="i" |	The list items will be numbered with lowercase roman numbers

___

* Unordered HTML List
An unordered list starts with the < ul> tag. Each list item starts with the < li> tag.

The list items will be marked with bullets (small black circles) by default:

Example
 ```html
 <ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
 ```
 _______

 # Boxes
 * CSS box-sizing Property
 ![](https://cdncontribute.geeksforgeeks.org/wp-content/uploads/box-model-1.png)
 
 
 _______
 
 Box-decoration-break: slice|clone|initial|inherit|unset;
* Property Values

Value	| Description
---------|----------
slice	| Default. Box decorations are applied to the element as a whole and break at the edges of the element fragments
clone	|Box decorations apply to each fragment of the element as if the fragments were individual elements. Borders wrap the four edges of each fragment of the element, and backgrounds are redrawn in full for each fragment
initial	|Sets this property to its default value. Read about initial
inherit	|Inherits this property from its parent element. Read about inherit


_______
 * Property Values

Value	|Description
----------|---------
content-box |	Default. The width and height properties (and min/max properties) includes only the content. Border and padding are not included
border-box	|The width and height properties (and min/max properties) includes content, padding and border
initial |	Sets this property to its default value. Read about initial
inherit |	Inherits this property from its parent element. Read about inherit

_______
* CSS Border Style
The border-style property specifies what kind of border to display.


1- dotted - Defines a dotted border

2- dashed - Defines a dashed border

3- solid - Defines a solid border

4- double - Defines a double border

5- groove - Defines a 3D grooved border. The effect depends on the border-color value

6-ridge - Defines a 3D ridged border. The effect depends on the border-color value

7-inset - Defines a 3D inset border. The effect depends on the border-color value

8- outset - Defines a 3D outset border. The effect depends on the border-color value

9- none - Defines no border

10- hidden - Defines a hidden border

____________

## JavaScript Booleans

![](https://i.ytimg.com/vi/xvxAtpEoeYU/maxresdefault.jpg)

* Boolean Values

Very often, in programming, you will need a data type that can only have one of two values, like

YES / NO

ON / OFF

TRUE / FALSE

For this, JavaScript has a Boolean data type. It can only take the values true or false.

___________
## Conditional Statements
Very often when you write code, you want to perform different actions for different decisions.

You can use conditional statements in your code to do this.

In JavaScript we have the following conditional statements:

* Use if to specify a block of code to be executed, if a specified condition is true
* Use else to specify a block of code to be executed, if the same condition is false
* Use else if to specify a new condition to test, if the first condition is false
* Use switch to specify many alternative blocks of code to be executed

Example

```js
if (time < 10) {
  greeting = "Good morning";
} else if (time < 20) {
  greeting = "Good day";
} else {
  greeting = "Good evening";
}
```
_________

## JavaScript Switch Statement

The JavaScript Switch Statement
Use the switch statement to select one of many code blocks to be executed.

Syntax
```js
switch(expression) {

  case x:

    // code block

    break;

  case y:

    // code block

    break;

  default:

    // code block
}

```
______
## JavaScript For Loop

* The For Loop

The for loop has the following syntax:

```js
for (statement 1; statement 2; statement 3) {
  // code block to be executed
} 
```
- Statement 1 is executed (one time) before the execution of the code block.

- Statement 2 defines the condition for executing the code block.

- Statement 3 is executed (every time) after the code block has been executed.
```js
Example
for (i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}
```