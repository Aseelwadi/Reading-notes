# Images :
![](https://tse2.mm.bing.net/th?id=OIP.d8ufdoj7e2BXYQNffPVzmQHaEK&pid=Api&P=0&w=332&h=188)

The < img> tag is empty, it contains attributes only, and does not have a closing tag.

The < img> tag has two required attributes:

* src - Specifies the path to the image
* alt - Specifies an alternate text for the image

### Image Size - Width and Height

You can use the style attribute to specify the width and height of an image.

Example
```html
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">
```

* mages in Another Folder

If you have your images in a sub-folder, you must include the folder name in the src attribute:

Example
```html
<img src="/images/html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">
```
* Image as a Link
To use an image as a link, put the < img> tag inside the < a> tag

Abbreviation |	File Format	|File Extension
---------|--------------------|---------
APNG |	Animated Portable Network Graphics|	.apng
GIF |	Graphics Interchange Format|	.gif
ICO	| Microsoft Icon	|.ico, .cur
JPEG|	Joint Photographic Expert Group image|	.jpg, .jpeg, .jfif, .pjpeg, .pjp
PNG	|Portable Network Graphics	|.png
SVG	|Scalable Vector Graphics	|.svg

_______
# HTML5 video and audio
The < video> and < audio> elements allow us to embed video and audio into web pages. As we showed in Video and audio content, a typical implementation looks like this:
``` html
<video controls>
  <source src="rabbit320.mp4" type="video/mp4">
  <source src="rabbit320.webm" type="video/webm">
  <p>Your browser doesn't support HTML5 video. Here is a <a href="rabbit320.mp4">link to the video</a> instead.</p>
</video>
```
___________
# The HTMLMediaElement API
Part of the HTML5 spec, the HTMLMediaElement API provides features to allow you to control video and audio players programmatically — for example HTMLMediaElement.play(), HTMLMediaElement.pause(), etc. This interface is available to both < audio> and < video> elements, as the features you'll want to implement are nearly identical. Let's go through an example, adding features as we go.
_______
## Background Image on a HTML element
To add a background image on an HTML element, use the HTML style attribute and the CSS background-image property:

```css
<style>
body {
  background-image: url('img_girl.jpg');
}
</style>
```

* he HTML **< picture>** element allows you to display different pictures for different devices or screen sizes.

The HTML < picture> element gives web developers more flexibility in specifying image resources.

The < picture> element contains one or more < source> elements, each referring to different images through the srcset attribute. This way the browser can choose the image that best fits the current view and/or device.

Each < source> element has a media attribute that defines when the image is the most suitable.

### HTML  Image Tags

Tag	|Description
---------|---------
< img>	| Defines an image
< map>	| Defines an image map
< area>	| Defines a clickable area inside an image map
< picture>| 	Defines a container for multiple image resources
_______________________________
# Practical Information

* What is Search Engine Optimization?

Simply put, search engine optimization is the practice or organizing your website's content and HTML to improve each page's organic rank (organic rank means basically any unpaid result). To that end there are many different factors that go into organizing content and HTML to be more search engine friendly. The most common factors that you should consider when optimizing are the content of the page, the page title, the meta description and the meta keywords. Obviously there are more than just 4 factors to successful search engine optimization but these elements form the basic core.

* What's Important to Search Engines?

As I stated earlier there are many different factors that search engines weigh when compiling rankings. However, there is a set core of elements:

Page Title
The page title is one of the most important elements of search engine optimization as it provides the search engines with the most relevant keywords for the page. There are several good practices and bad practices when coming up with page titles. Do make your titles relevant and use as many of your most important keywords as possible. Don't be overly repetitive or long winded. Being too repetitive can be considered a "cheat" by search engines and result in a lower rank. Being too long winded in your title can also yield the same result or the search engines may simply concatenate your title and ignore everything after a certain number of characters.

A good title should look something like this:
```html
<title>Search Engine Optimization (SEO) : Getting Started - HTML Goodies</title>
```


________________
# How to Learn More About Your Website Visitors
![](https://www.codemade.io/wp-content/uploads/2020/09/how-to-find-unique-visitors-in-google-analytics-seo-learning-center-amp-backlink-strategy-1600952877ngk84.png)

## Google Analytics
Google Analytics (GA) is free, and can be accessed through a free Gmail account. Register for a free GA account, and you will be given a number and some code to insert on your webpages. If you are creating your site in HTML, you will have to add it to every page you wish to track. You could create a template with the code built in for every new page you create.

If you have a WordPress based site, adding the code to the Header area will make all your pages visible to GA.

Google Analytics is a huge program that can take some time to master. Key metrics include:

* The number of site visitors
* The bounce rate (what percentage click in and out again rapidly without ever really looking at your site)
* The average length of session
* Sources of traffic, such as organic search, direct or social media
* The most popular page urls
* The main countries your traffic comes from
Device users (mobile, desktop, tablet)
____
## Domain Names & Hosting
In order to put your site on the web you will
need a domain name and web hosting.
____
* ### Notes:
* Search engine optimization helps visitors find your
sites when using search engines.
*  Analytics tools such as Google Analytics allow you to
see how many people visit your site, how they find it,
and what they do when they get there.
* To put your site on the web, you will need to obtain a
domain name and web hosting.
* FTP programs allow you to transfer files from your
local computer to your web server.
* Many companies provide platforms for blogging, email
newsletters, e-commerce and other popular website
tools (to save you writing them from scratch).
________
## Bookmark/Skim

We store URL of sites by using my favorite or book mark feature. The URL of the site will be added to our favorite or bookmark links. We will use JavaScript function to do this. On clicking the link browser will open the window for conformation and adding the link to the list. Here is the function and below that the link to add the this site to your favorite list.

Replace your site url and title while using this code.
 function bookmark()
```js
{

bookmarkurl="https://www.example.com";// replace your site URL

bookmarktitle="example.com: PHP SQL and Javascript Source"; // replace this line with your site title

if (document.all)

window.external.AddFavorite(bookmarkurl,bookmarktitle)

else if (window.sidebar) // firefox

	window.sidebar.addPanel(bookmarktitle, bookmarkurl, "");

}
```