# JAVASCRIPT
___

## Why we use java script :?
JavaScript  a  light weight and very fast  programming language can be used in browsers to make websites more interactive, interesting, and user-friendly.

1- ACCESS CONTENT We can use JavaScript to select any element, attribute, or text from an Html page 

2- MODIFY CONTENT You can use JavaScript to add elements, attributes, 
and text to the page, or remove them.

3- PROGRAM RULES You can specify a set of steps for the browser to follow (like a recipe), which allows it to access or change the content of a page.

4-REACT TO EVENTS You can specify that a script should run when a specific event has occurred.

_______

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
## OPERATORS :
 1- Arithmetic Operators :

Operator        | Description
------------ | -------------
  <+>	| Addition
  <->    | Subtraction
  <*>	| Multiplication
** |	Exponentiation (ES2016)
/	| Division
%	| Modulus (Division Remainder)
++| 	Increment
-- | 	Decrement

/////////

2- Assignment Operators

Assignment operators assign values to JavaScript variables.

Operator        | Example   | Same As
------------ | ------------- |-------
=	| x = y	| x = y
+=| 	x += y| 	x = x + y
-=	1| x -= y| 	x = x - y
*=|	x *= y|	x = x * y
/=	x | /= y	| x = x / y
%= |	x %= y |	x = x % y
**= | 	x **= y	|x = x ** y


///////

3- Logical Operators

Operator | Description
---------|------------
&&	| logical and
II	| logical or
!	| logical not

___

## Functions
A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

Example

>function myFunction(p1, p2) {
  return p1 * p2;   // The function returns the product of p1 and p2
}