# CSS Colors 
_______
![colors](https://techstream.org/images/img/CSS-Color-Names.jpg)

**Colors are specified using predefined color names, or RGB, HEX, HSL, RGBA, HSLA values.**
___________
1.
# CSS Color Names :
* In CSS, a color can be specified by using a predefined color name:
 ## Example
 ``` js
<h1 style="background-color:Orange;">Orange</h1>
<h1 style="background-color:DodgerBlue;">DodgerBlue</h1>
<p style="background-color:Tomato;">Lorem ipsum...</p>
<h1 style="background-color:MediumSeaGreen;">MediumSeaGreen</h1>

```
_______
* # CSS Text Color
You can set the color of text:
 ``` js
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>
 ``` 
 * # CSS Border Color
You can set the color of borders:
 ``` html
<h1 style="border:2px solid Tomato;">Hello World</h1>
<h1 style="border:2px solid DodgerBlue;">Hello World</h1>
<h1 style="border:2px solid Violet;">Hello World</h1>
 ```
 ______

2.
# CSS RGB Colors
In CSS, a color can be specified as an RGB value, using this formula:

**rgb(red, green, blue)**

Each parameter (red, green, and blue) defines the intensity of the color between 0 and 255.

For example, rgb(255, 0, 0) is displayed as red, because red is set to its highest value (255) and the others are set to 0.

To display black, set all color parameters to 0, like this: rgb(0, 0, 0).

To display white, set all color parameters to 255, like this: rgb(255, 255, 255).

## Example

 ```html
<h1 style="background-color:rgb(255, 0, 0);">rgb(255, 0, 0)</h1>
<h1 style="background-color:rgb(0, 0, 255);">rgb(0, 0, 255)</h1>
<h1 style="background-color:rgb(60, 179, 113);">rgb(60, 179, 113)</h1>
 ```

 ___
 * ## RGBA Value
RGBA color values are an extension of RGB color values with an alpha channel - which specifies the opacity for a color.

An RGBA color value is specified with:

rgba(red, green, blue, alpha)

The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all):

Experiment by mixing the RGBA values below:

>rgba(255, 99, 71, 0.5)
___
3.
# CSS HEX Colors
HEX Value
In CSS, a color can be specified using a hexadecimal value in the form:

#rrggbb

Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).

For example, #ff0000 is displayed as red, because red is set to its highest value (ff) and the others are set to the lowest value (00).

Experiment by mixing the HEX values below:

>#ff6347

____
4.
# CSS HSL Colors
HSL Value
In CSS, a color can be specified using hue, saturation, and lightness (HSL) in the form:

hsl(hue, saturation, lightness)

Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.

Saturation is a percentage value, 0% means a shade of gray, and 100% is the full color.

Lightness is also a percentage, 0% is black, 50% is neither light or dark, 100% is white

Experiment by mixing the HSL values below:

>hsl(0, 100%, 50%)
___
* ## HSLA Value
HSLA color values are an extension of HSL color values with an alpha channel - which specifies the opacity for a color.

An HSLA color value is specified with:

hsla(hue, saturation, lightness, alpha)

The alpha parameter is a number between 0.0 (fully transparent) and 1.0 (not transparent at all):

Experiment by mixing the HSLA values below:

hsla(0, 100%, 50%, 0.5)