# Class 02
________________
# Text
___________
## 1- HTML Headings
HTML headings are titles or subtitles that you want to display on a webpage.

* HTML headings are defined with the < h1> to < h6> tags.

< h1> defines the most important heading. < h6> defines the least important heading.

## Example 
> < h1>Heading 1< /h1>

> < h2>Heading 2< /h2>

> < h3>Heading 3< /h3>

> < h4>Heading 4< /h4>

> < h5>Heading 5< /h5>

> < h6>Heading 6< /h6>

_______________
# HTML Formatting Elements
Formatting elements were designed to display special types of text:

 ```html
<b> - Bold text
<strong> - Important text
<i> - Italic text
<em> - Emphasized text
<mark> - Marked text
<small> - Smaller text
<del> - Deleted text
<ins> - Inserted text
<sub> - Subscript text
<sup> - Superscript text 
 ```
_______
# HTML < sup> Tag

Example

Superscript text:

```html
<p>This text contains <sup>superscript</sup> text.</p>
```
* Definition and Usage
The < sup> tag defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1].

______
# HTML < sub> Tag

Example
Subscript text:

 ```html 
 <p>This text contains <sub>subscript</sub> text.</p>
  ```
Definition and Usage
The <sub> tag defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H2O.
__________
## Line Breaks & Horizontal Rules
* < br />

As you have already seen, the
browser will automatically show
each new paragraph or heading
on a new line. But if you wanted
to add a line break inside the
middle of a paragraph you can
use the line break tag < br />.
Line Breaks &

* < hr />

To create a break between
themes — such as a change of
topic in a book or a new scene
in a play — you can add a
horizontal rule between sections
using the < hr /> tag.
There are a few elements that
do not have any words between
an opening and closing tag. They
are known as empty elements
and they are written differently.
An empty element usually
has only one tag. Before the
closing angled bracket of an
empty element there will often
be a space and a forward slash
character. Some web page
authors miss this out but it is a
good habit to get into.
______
## Strong & Emphasis
* < strong>

The use of the < strong>
element indicates that its
content has strong importance.
For example, the words
contained in this element might
be said with strong emphasis.
By default, browsers will show
the contents of a < strong>
element in bold.
* < em>

The < em> element indicates
emphasis that subtly changes
the meaning of a sentence.
By default browsers will show
the contents of an < em> element
in italic.
_____
## Quotation
* < blockquote>

The < blockquote> element is
used for longer quotes that take
up an entire paragraph. Note
how the < p> element is still
used inside the < blockquote>
element.
Browsers tend to indent the
contents of the < blockquote>
element, however you should not
use this element just to indent a
piece of text — rather you should
achieve this effect using CSS.
* < q>

The < q> element is used for
shorter quotes that sit within
a paragraph. Browsers are
supposed to put quotes around
the < q> element, however
Internet Explorer does not —
therefore many people avoid
using the < q> element.
Both elements may use the cite
attribute to indicate where the
quote is from. Its value should
be a URL that will have more
information about the source of
the quotation.
_________
## HTML < abbr> Tag

Example
An abbreviation is marked up as follows:

>The <abbr title="World Health Organization">WHO</>abbr> was founded in 1948.
More "Try it Yourself" examples below.

* Definition and Usage
The < abbr> tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".

Tip: Use the global title attribute to show the description for the abbreviation/acronym when you mouse over the element.
_______
 # Introducing CSS
 ## CSS Tags
 Selectors
 
*   "*'  /all elements

*  divall div tags

*  div,pall divs and paragraphs  /div pparagraphs inside divs
* div >  /pall p tags, one level deep in div
* div + pp / tags immediately after div
* div ~ pp/ tags preceded by div
* .class /nameall elements with class
* #id /nameelement with ID

* div.classname/divs with certain classname

* div#idname /div with certain ID

* #idname *all elements inside #idname
________
## Pseudo classes
a:linklink in normal state

a:activelink in clicked state

a:hoverlink with mouse over it

a:visitedvisited link

p::after{content:"yo";}add content after p

p::beforeadd content before p

input:checkedchecked inputs

div:emptyelement with no children

p::first-letterfirst letter in p

## Attribute selectors
a[target]links with a target attribute

a[target="_blank"]links which open in new tab

[title~="chair"]title element containing a word

[class^="chair"]class starts with chair

[class|="chair"]class starts with the chair word

[class*="chair"]class contains chair

[class$="chair"]class ends with chair

input[type="button"]specified input type
____
# JAVASCRIPT
![pic](https://www.tecschool.net/wp-content/uploads/2019/11/funciones-en-javascript-t1.png)
___
## JavaScript Objects
Objects are variables too. But objects can contain many values.

This code assigns many values (Fiat, 500, white) to a variable named car:

>var car = {type:"Fiat", model:"500", color:"white"};

--
* Object Methods
Objects can also have methods.

Methods are actions that can be performed on objects.

Methods are stored in properties as function definitions.

* Example
>var person = {
  firstName: "John",
  lastName : "Doe",
  id       : 5566,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};

* The this Keyword
In a function definition, this refers to the "owner" of the function.

In the example above, this is the person object that "owns" the fullName function.

In other words, this.firstName means the firstName property of this object.

Read more about the this keyword at JS this Keyword.

Accessing Object Methods
You access an object method with the following **syntax:**

>objectName.methodName()

____
## Data types :
Numbers : int , long int, double etc .

Strings : “ some thing”

Char : ‘c’

Boolean : T ,F (1,0)
____
## The variables : 

> Var …name… and then the value .

### Ex . 
String :

<var name= ”Aseel ”>

number:

<var age = 27>

__
## how can I show the value of a variable ?

**Consol.log**  (age) .. consol.log (variable name) 

Boolean :
Var checked = true ;

**Consol.log**( checked)  …. The result will be( true ) 

Ex. The check box 😊 .
___
## How can we start our js .

Using <script>

* **<Console.log>** (‘Class 04’) ;

 **Examples**

     * console.log (‘Class 04’) ;

     * Var fname = ‘Aseel ’ we can use single quotation in Js ;
     Console.log (fname)

     * Var age = 22 ;
     Console.log (age)

     * Console.log(‘first name :’ + fname);
      (the result will be first name : Aseel)

     * Var Female = true ;
    Console.log (Female)

    * Console.log(‘first name :’ + fname + ’ age ’+ age +’is Female’+ Female );

____
## Note :

Console.log (‘5’+5+5)  the result will be 555 . as a String  because the first parameter was a string .. if it was an integer for example the result will integer . 
__________

## Comments :

Single line comments start with //.
Multi-line comments start with /* and end with */.

**Ps** : “WE can do it using CTRL and forward slash on the keyboard ” .
______

## How can we print it directly in html not in th consol ?
''' 
<main>
<script>
document.write(‘First name: ${fname}’);
</script>
</main>
> '''
________
## Another type to show a message to the user is **Alert**

Why  the content will not shown untel we exit the alert ? ,

Bacouse , the execution is sequinntly line by line . 

_____
## Note 

If I have the result in the console and not shown in the html pages the I should know there’s a false in ordering code .
Tf the result didn’t shown in both then I have error in my code . 

So console is very important for developers to fix problems ,bugs 
And to check the outputs .  
___

## Prompt()
Function inside it we can add message 
Prompt(“Whats your name ? ”);


## How can we use it ??
 Var fname = Prompt(“Whats your name ? ”);

Console.log (fname);

3-	Var fname = Prompt(“Whats your name ?  ‘DEfoult’ ”);
_____


## SCRIPT
A script is a series of instructions that a
computer can follow to achieve a goal.  

____
## JavaScript Arrays
JavaScript arrays are used to store multiple

 1- values in a single variable.

Example

> var cars = ["Saab", "Volvo", "BMW"];

2- Using the JavaScript Keyword new
The following example also creates an Array, and assigns values to it:

Example

>var cars = new Array("Saab", "Volvo", "BMW");

3- Access the Elements of an Array

You access an array element by referring to the index number.

This statement accesses the value of the first element in cars:

> var name = cars[0];

___
4- Changing an Array Element

This statement changes the value of the first
 element in cars:

> cars[0] = "Opel";
___
## Expressions :
An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.

1-	ASSIGN A VALUE TO A VARIABLE

2-	USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE
___

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

_____
## JavaScript Loops
Loops are handy, if you want to run the same code over and over again, each time with a different value.
* Different Kinds of Loops
JavaScript supports different kinds of loops:

for - loops through a block of code a number of times

for/in - loops through the properties of an object

for/of - loops through the values of an iterable object

while - loops through a block of code while a specified condition is true

do/while - also loops through a block of code while a specified condition is true

_________
## Comparison Operators


Operator |	Comparisons | Description
----------|-------------|-----------
Equal (==)   | x == y	|Returns true if the operands are equal.
Strict equal (===)|	x === y	|Returns true if the operands are equal and of the same type.
Not equal (!=)	|x != y|	Returns true if the operands are not equal.
Strict not equal (!==)|	x !== y	|Returns true if the operands are not equal and/or not of the same type.
Greater than (>)|	|x>y|	Returns true if the left operand is greater than the right operand.
Greater than or equal (>=)|	x>=y|	Returns true if the left operand is greater than or equal to the right operand.
Less than (<)|	x<y|	Returns true if the left operand is less than the right operand.
Less than or equal (<=)|	x<=y|	Returns true if the left operand is less than or equal to the right operand.








