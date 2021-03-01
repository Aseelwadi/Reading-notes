# local Storage for Web Applications

![](https://techglimpse.com/wp-content/uploads/2013/04/localstorage.jpg)

The read-only **localStorage** property allows you to access a **Storage** object for the Document's origin; the stored data is saved across browser sessions.

 **localStorage** is similar to **sessionStorage**,
  except that while data stored in localStorage has no expiration time,
   data stored in sessionStorage gets cleared when the page session ends — that is,

 when the page is closed. (Data in a localStorage object created in a **"private browsing"** or "incognito" session is cleared when the last "private" tab is closed.)
 ___________
 ## What is localStorage in JavaScript?
localStorage is a property that allows JavaScript sites and apps to save key/value pairs in a web browser with no expiration date. This means the data stored in the browser will persist even after the browser window is closed.
______
## Where is localStorage stored?
In Google Chrome, web storage data is saved in an SQLite file in a subfolder in the user’s profile.
_____
## What is Window.localStorage?
The localStorage mechanism is available via the Window.localStorage property. Window.localStorage is part of the Window interface in JavaScript, which represents a window containing a DOM document.
_____
## How does it work?
To use localStorage in your web applications, there are five methods to choose from:

* setItem(): Add key and value to localStorage
* getItem(): This is how you get items from localStorage
* removeItem(): Remove an item by key from localStorage
* clear(): Clear all localStorage
* key(): Passed a number to retrieve the key of a localStorage
___
Example :
```js
const person = {
    name: "Obaseki Nosa",
    location: "Lagos",
}

window.localStorage.setItem('user', JSON.stringify(person));
```