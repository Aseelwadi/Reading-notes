# HTML Images

* HTML Images Syntax

The HTML **< img>** tag is used to embed an image in a web page.

The < img> tag is empty, it contains attributes only, and does not have a closing tag.

* The < img> tag has two required attributes:


src - Specifies the path to the image
alt - Specifies an alternate text for the image .

* ### Align Images
Using Text-align: This method must be applied when images are placed inside the container.
* Align Images Horizontally
![](https://www.tutorialmines.net/wp-content/uploads/2018/02/align-image-horizontal.png)

1-Image Align Center Using Margin
2-Image Align with Float
3-Using Position

*  Vertical Align Image
![](https://www.tutorialmines.net/wp-content/uploads/2018/02/align-image-vertical.png)
_
* image-resolution Property
The image-resolution property specifies the intrinsic resolution of all raster images used in or on the element. It affects both content images (e.g. replaced elements and generated content) and decorative images (such as 'background-image'). The intrinsic resolution of an image is used to determine the image's intrinsic dimensions.

Syntax
```css
image-resolution: [from-image || <resolution>] && snap?
```
_______

* Animated Images
HTML allows animated GIFs:

Example
```html
<img src="programming.gif" alt="Computer Man" style="width:48px;height:48px;"> 
```
_______

## Summary Notes  :
* Use the HTML < img> element to define an image

* Use the HTML src attribute to define the URL of the image

* Use the HTML alt attribute to define an alternate text for an image, if it cannot be displayed

* Use the HTML width and height attributes or the CSS width and height properties to define the size of the image

* Use the CSS float property to let the image float to the left or to the right

___
HTML Image Tags|Tag	Description
----------------|-------------
< img> |	Defines an image
< map> |	Defines an image map
< area>	|Defines a clickable area inside an image map
< picture> |	Defines a container for multiple image resources
__________________________________

# Colors
![](https://th.bing.com/th/id/OIP.AWklo0mzR3uqf_swNsmOsAHaD4?pid=ImgDet&rs=1) 

With CSS, colors can be specified in different ways:

* By color names
* As RGB values
* As hexadecimal values
* As HSL values (CSS3)
* As HWB values (CSS4)
With the currentcolor keyword

> An RGB color value is specified with: rgb( RED , GREEN , BLUE ).

> A hexadecimal color is specified with: #RRGGBB.
>HSL color values are specified with: hsl(hue, saturation, lightness).

________
# Text
Setting Font Face
You can set font face using face attribute but be aware that if the user viewing the page doesn't have the font installed, they will not be able to see it. Instead user will see the default font face applicable to the user's computer.

Example
```html
<!DOCTYPE html>
<html>

   <head>
      <title>Font Face</title>
   </head>

   <body>
      <font face = "Times New Roman" size = "5">Times New Roman</font><br />
      <font face = "Verdana" size = "5">Verdana</font><br />
      <font face = "Comic sans MS" size =" 5">Comic Sans MS</font><br />
      <font face = "WildWest" size = "5">WildWest</font><br />
      <font face = "Bedrock" size = "5">Bedrock</font><br />
   </body>

</html>

```
_______
## Font family 
The font-family property can hold several font names as a 
"fallback" system. If the browser does not support the first 
font, it tries the next font.


There are two types of font family names:


* family-name - The name of a font-family, like "times", "courier", "arial", etc.
* generic-family - The name of a generic-family, like "serif", "sans-serif", "cursive", "fantasy", "monospace".
_________

## font-weight

 different font weight for three paragraphs:
```css
p.normal {
  font-weight: normal;
}

p.thick {
  font-weight: bold;
}

p.thicker {
  font-weight: 900;
}
```

______
## text-transform
The text-transform property changes the capitalization of text within an element, or else directs the user agent to leave the capitalization "as is."


--**Possible Values**

* capitalize − The first letter of each word in the element's text should be capitalized.

* uppercase − All of the characters in the element's text should be uppercase (capital letters).

* lowercase − All of the characters in the element's text should be lowercase.

* none - The capitalization of the element's text should not be altered
______
## letter-spacing
The letter-spacing property increases or decreases the space between characters in a text.

## text-indent 
The text-indent property specifies the indentation of the first line in a text-block.

## text-shadow
The text-shadow property adds shadow to text.

* ## :focus , :active , :hover
![](https://groups.drupal.org/files/6.buttons.png)
_______________________

## TL;DR
Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth.

## Compression
Compression can be of two types — lossless and lossy. In lossless compression, it is possible to reconstruct the original image from the compressed image because there is no information loss during compression.

## Transparency 
## Animation
Animation, in this case, refers to any change or movement in the image. It doesn’t necessarily have to have frame rates like an animated video, but essentially a part or the entire image changes with time.