![1](https://techstacker.com/static/5e267e2ee412a23e797106ee564145a0/4148e/js.png)
# Object Literal in JavaScript?
_____

* ### What is an Object Literal?
An **Object** is a special type of value in JavaScript that can have connections with other values.


An **Object Literal** is an object value that you literally write in your program/app.

An Object Literal usually consists of a list of comma-separated name-value pairs (property:value), wrapped inside curly braces {}.

* Example:
![](https://xomino.files.wordpress.com/2013/04/j4.png?w=700)

### * Object Literal Syntax
Object literals are defined using the following syntax rules:

. A colon separates property name[1] from value.
. A comma separates each name-value pair from the next.

. A comma after the last name-value pair is optional.
___________________________

### * Why and How We Use Object Literals
Several JavaScripts from dyn-web use object literals for setup purposes. Object literals enable us to write code that supports lots of features yet still provide a relatively straightforward process for implementers of our code. No need to invoke constructors directly or maintain the correct order of arguments passed to functions. Object literals are also useful for unobtrusive event handling; they can hold the data that would otherwise be passed in function calls from HTML event handler attributes.

There is one drawback: if you are unfamiliar with the syntax, it can be very easy to introduce errors which cause the code to stop working.
________________
# Document Object Model
![3](https://simplesnippets.tech/wp-content/uploads/2018/10/what-is-document-object-model-in-JS-featured-image.jpg)

The document object represents the whole html document.

When html document is loaded in the browser, it becomes a document object. It is the root element that represents the html document. It has properties and methods. By the help of document object, we can add dynamic content to our web page.

* ### What is the HTML DOM?
The HTML DOM is a standard object model and programming interface for HTML. It defines:

- The HTML elements as objects
- The properties of all HTML elements
- The methods to access all HTML elements
- The events for all HTML elements

_____
* ### Methods of Document Object:

1-write(“string”): writes the given string on the document.

2- getElementById(): returns the element having the given id value.

3- getElementsByName(): returns all the elements having the given name value.

4- getElementsByTagName(): returns all the elements having the given tag name.

5- getElementsByClassName(): returns all the elements having the given class name.
__________
 * DOM querySelector() Method

 The querySelector() method returns the first element that matches a specified CSS selector(s) in the document.


Note: The querySelector() method only returns the first element that matches the specified selectors. To return all the matches, use the querySelectorAll() method instead.


If the selector matches an ID in document that is used several times (Note that an "id" should be unique within a page and should not be used more than once), it returns the first matching element.
______

* getElementsByClassName() Method

The getElementsByClassName() method returns a collection of all elements in the document with the specified class name, as an HTMLCollection object.

The HTMLCollection object represents a collection of nodes. The nodes can be accessed by index numbers. The index starts at 0.
________

* Looping through NodeLists with ES6

The traditional way of looping through NodeLists is the same as looping through arrays: with a for loop.

var elems = document.querySelectorAll('.some-selector');
```js
for (var i = 0; i < elems.length; i++) {
    console.log(i); // index
    console.log(elems[i]); // value
}
```
The ES6 Way #

Fortunately, just like with arrays, there’s a forEach() method for NodeLists.
```js
var elems = document.querySelectorAll('.some-selector');

elems.forEach(function (elem, index) {
    console.log(index); // index
    console.log(elem); // value
});
```
## *Accessing Attributes
You can access attributes by creating an object of the class, and by using the dot syntax (.):

____________
 ## * removeAttribute() Method

Example
Remove the class attribute from an < h1> element:
```js
document.getElementsByTagName("H1")[0].removeAttribute("class");
 ```
 _______
 ## Summary :
 The browser represents the page using a DOM tree.

* DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes.

* You can select element nodes by their id or cl ass
attributes, by tag name, or using CSS selector syntax.

* Whenever a DOM query can return more than one
node, it will always return a Nadel i st.

* From an element node, you can access and update its
content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques.

* An element node can contain multiple text nodes and
child elements that are siblings of each other.

* In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).

* Browsers offer tools for viewing the DOM tree