# JAVASCRIPT-3 :)
_____
# JavaScript Functions
* A JavaScript function is a block of code designed to perform a particular task.

* A JavaScript function is executed when "something" invokes it (calls it).
________


## JavaScript Function Syntax
```js
function name(parameter1, parameter2, parameter3) {
  // code to be executed
}
```
>Function parameters are listed inside the >parentheses () in the function definition.

>Function arguments are the values received by >the function when it is invoked.

>Inside the function, the arguments (the parameters) behave as local variables.

## Example :
![function](https://dhananjay25.files.wordpress.com/2017/09/image4.png)

________________

## Why Functions?
You can reuse code: Define the code once, and use it many times.

You can use the same code many times with different arguments, to produce different results.

>### note : The () Operator Invokes the Function

_____
## Functions Used as Variable Values
Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.

Example
Instead of using a variable to store the return value of a function:
```js
<script>
document.getElementById("demo").innerHTML =
"The temperature is " + toCelsius(77) + " Celsius";

function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
} 
</script>
```
____________

## Local Variables
Variables declared within a JavaScript function, become LOCAL to the function.

Local variables can only be accessed from within the function.
``` js
// code here can NOT use carName

function myFunction() {
  var carName = "Volvo";
  // code here CAN use carName
}

// code here can NOT use carName
```

__________

## Naming Conventions
Always use the same naming convention for all your code. For example:

•	Variable and function names written as camelCase

•	Global variables written in UPPERCASE (We don't, but it's quite common)

•	Constants (like PI) written in UPPERCASE
