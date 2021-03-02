# CSS transforms
![](https://media.24ways.org/2010/desandro/transforms01.png)

CSS transforms change the shape and position of the affected content without disrupting the normal document flow. This guide provides an introduction to using transforms.

* CSS transforms properties

1- transform :- property specifies how nested elements are rendered in 3D space.

2- transform-origin :- allows you to change the position of transformed elements.
______

 * Examples : Rotate, skew, and scale

 ```css
 div.a {
  transform: rotate(20deg);
}

div.b {
  transform: skewY(20deg);
}

div.c {
  transform: scaleY(1.5);
}
```
__________
# Transitions
![](https://i.ytimg.com/vi/8kK-cA99SA0/maxresdefault.jpg)

is a shorthand property for:

* transition-property
* transition-duration
* transition-timing-function
* transition-delay

****Syntax

>transition: property duration timing-function delay|initial|inherit;


Value	| Description
-------|-------------
transition-property	|Specifies the name of the CSS property the transition effect is for
transition-duration	|Specifies how many seconds or milliseconds the transition effect takes to complete
transition-timing-function|	Specifies the speed curve of the transition effect
transition-delay	|Defines when the transition effect will start
initial |	Sets this property to its default value. Read about initial
inherit	|Inherits this property from its parent element. Read about inherit

____________
# Animations
![](https://tse1.mm.bing.net/th?id=OIP.5BeLFYoy2BwcCStWlHapBAHaC2&pid=Api&P=0&w=408&h=158)

allows animation of HTML elements without using JavaScript or Flash!

* ### properties:

* @keyframes 

* animation-name 

* animation-duration :     
  * The animation-duration property defines how long time an animation should take to complete. If the animation-duration property is not specified, no animation will occur, because the default value is 0s (0 seconds). 

* animation-delay :
   * pecifies a delay for the start of an animation.

* animation-iteration-count :

  * specifies the number of times an animation should run.

* animation-direction :

      * pecifies whether an animation should be played forwards, backwards or in alternate cycles.


* animation-timing-function :

      * specifies the speed curve of the animation.

* animation-fill-mode :
    * specifies a style for the target element when the animation is not playing (before it starts, after it ends, or both).

* animation