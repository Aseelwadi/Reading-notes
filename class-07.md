
_______
## HTML Tables

![table](https://th.bing.com/th/id/Rd475bd519325841696d79c8dddc5b6e8?rik=srnZrTKO5Q2k3g&riu=http%3a%2f%2fictacademy.com.ng%2fwp-content%2fuploads%2f2017%2f10%2fHTML-Table-Structure.png&ehk=HQ5oD%2bTbXvGIUUjuLj%2b4xM%2fNPV25PgFXtt93ecU0aHk%3d&risl=&pid=ImgRaw)

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
____
2- HTML Table - Add Cell Padding
Cell padding specifies the space between the cell content and its borders.

If you do not specify a padding, the table cells will be displayed without padding.

To set the padding, use the CSS padding property

______
3- HTML Table - Left-align Headings
By default, table headings are bold and centered.

To left-align the table headings, use the CSS ```text-align``` property:
______
4-Cell that Spans Many Columns
To make a cell span more than one column, use the ```colspan ```
attribute
_______
5- Cell that Spans Many Rows
To make a cell span more than one row, use the ```rowspan``` attribute:

______
### Notes
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

# JavaScript Object Constructors
![](https://th.bing.com/th/id/OIP.P5d9ABHvbNUoA6ap6Zv4BQHaEK?pid=ImgDet&rs=1)


* The **this** Keyword

In JavaScript, the thing called this is the object that "owns" the code.

The value of this, when used in an object, is the object itself.

* Adding a Property to an Object

Adding a new property to an existing object is easy:

Example
 ```js
myFather.nationality = "Jordan";
```

* Adding a Method to an Object

Adding a new method to an existing object is easy:

Example
```js 
myFather.name = function () {
  return this.firstName + " " + this.lastName;
};
```

* Built-in JavaScript Constructors

JavaScript has built-in constructors for native objects:

Example
```js
var x1 = new Object();    // A new Object object
var x2 = new String();    // A new String object
var x4 = new Boolean();   // A new Boolean object
var x5 = new Array();     // A new Array object
var x7 = new Function();  // A new Function object
var x8 = new Date();      // A new Date object
```

________
## Notes :
-- Use object literals {} instead of new Object().

-- Use string literals "" instead of new String().

-- Use number literals 12345 instead of new Number().

-- Use boolean literals true / false instead of new Boolean().

-- Use array literals [] instead of new Array().

-- Use pattern literals /()/ instead of new RegExp().

-- Use function expressions () {} instead of new Function().

