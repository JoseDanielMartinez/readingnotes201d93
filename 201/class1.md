## ***Overview***

> Before developers get to work designing websites, it's important they have ideal computer set ups, understand the basics, and apply solid programming fundamentals.

1.	Compose a short poem describing how HTTP sends data between computers.

Roses are red, violets are blue, your computer uses a browser to send an HTTP request message to the server, asking it to send a copy of the website to the client...how about you?

2.	Describe how HTML, CSS, and JS files are “parsed” in the browser.

The browser parses the HTML file first, which leads to the browser recognizing any \<link>-element references to external CSS stylesheets and any \<script>-element references to scripts. As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from \<link> elements, and any JavaScript files it has found from \<script> elements, then parses the CSS and JavaScript.  The browser then generates an in-memory DOM tree from the parsed HTML, and then also generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.  As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

3.	How can you find images to add to a Website? 

You can use free websites such as Google images or Unsplash
4.	How do you create a String vs a Number in JavaScript?
let anyNumber = '10’;
let anyNumber = 10;
5.	What is a Variable and why are they important in JavaScript?
Variables are containers that store value. Variables are necessary to do anything interesting in programming. If values couldn't change, then you couldn't do anything dynamic, like personalize a greeting message or change an image displayed in an image gallery.
Source: mdn web docs at: https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works 
