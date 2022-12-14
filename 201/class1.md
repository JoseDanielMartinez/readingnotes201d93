# ***Overview***

Before developers get to work designing websites, it's important they have ideal computer set ups, understand the basics, and apply solid programming fundamentals.

# **Class 1 Assignment**

1. Compose a short poem describing how HTTP sends data between computers.

    Roses are red, violets are blue, your computer uses a browser to send an HTTP request message to the server, asking it to send a copy of the website to the client...how about you?

2. Describe how HTML, CSS, and JS files are “parsed” in the browser.

    The browser parses the HTML file first, which leads to the browser recognizing any \<link>-element references to external CSS             stylesheets and any \<script>-element references to scripts. As the browser parses the HTML, it sends requests back to the server         for any CSS files it has found from \<link> elements, and any JavaScript files it has found from \<script> elements, then parses the     CSS and JavaScript.  The browser then generates an in-memory DOM tree from the parsed HTML, and then also generates an in-memory         CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.  As the browser builds the DOM tree and             applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and     the user sees the page content and can begin to interact with it.

3. How can you find images to add to a Website? 

    You can use free websites such as Google images or Unsplash

4. How do you create a String vs a Number in JavaScript?

    let anyNumber = '10’;
    let anyNumber = 10;

5. What is a Variable and why are they important in JavaScript?

    Variables are containers that store value. Variables are necessary to do anything interesting in programming. If values couldn't change, then you couldn't do anything dynamic, like personalize a greeting message or change an image displayed in an image gallery.

 [Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

 1. What is an HTML attribute?

    Attributes contain extra information about the element that won't appear in the content.

2. Describe the Anatomy of an HTMl element.

    The anatomy of our element is:

    The opening tag: Consists of the name of the element, wrapped in opening and closing angle brackets. This opening tag marks where the     element begins or starts to take effect. 
    The content: This is the content of the element. 
    The closing tag: The same as the opening tag, except it includes a forward slash before the element name. This marks where the           element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.

[Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

3. What is the Difference between \<article> and \<section> element tags?

    An \<article> tag encloses a block of related content that makes sense on its own without the rest of the page.  A \<section> tag is similar to \<article> tag, but it is more for grouping together a single part of the page that constitutes one single piece of functionality or a theme.

[Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

4. What Elements does a “typical” website include?

![Typical HTML Website](html_basic_outline.jpg)

[Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

5. How does metadata influence Search Engine Optimization?
    Meta data descriptions includes keywords relating to the content of your page useful as it has the potential to make your page appear higher in relevant searches.

6. How is the <meta> HTML tag used when specifying metadata?

<meta name="singer" content="Luther Vandross" />

[Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

1. What is the first step to designing a Website?

    Project ideation and is the necessary first step to designing a website.  You should answer before anything else: 1) What exactly do I want to accomplish? 2) How will a website help me reach my goals? 3) What needs to be done, and in what order, to reach my goals?

2. What is the most important question to answer when designing a Website?

    What exactly do I want to accomplish?

[Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)

1.	Why should you use an \<h1> element over a <span> element to display a top-level heading?

    Using \<span> will render it to look like a top level heading, but it’ll lack semantic value, and not get any extra benefits

2.	What are the benefits of using semantic tags in our HTML?

    Search engines will consider its contents as important keywords to influence the page's search rankings
    Screen readers can use it as a signpost to help visually impaired users navigate a page
    Finding blocks of meaningful code is significantly easier than searching through endless divs with or without
    semantic or namespaced classes
    Suggests to the developer the type of data that will be populated
    Semantic naming mirrors proper custom element/component naming

[Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)

1.	Describe 2 things that require JavaScript in the Browser?

    Controlling media: the \<video> and \<audio> elements allow us to embed video and audio into web pages.     
    Animating images: done by programming gradual changes in an element's style.

2. How can you add JavaScript to an HTML document?
    Application Programming Interfaces (APIs) provide you with extra superpowers to use in your JavaScript code.  They are ready-made         sets of code building blocks that allow a developer to implement programs that would otherwise be hard or impossible to implement.

[Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)
    
## Things I want to know more about
