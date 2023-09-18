[Back to Main Page]()

# 201/01 - Setup Developer Toolbelt

## How HTTP sends data between computers

In the quirky realm of the internet, two playful computers named Alice and Bob found themselves in a rather peculiar situation. Alice, a computer with a penchant for funny cat videos, had stumbled upon an absolute gem and wanted to share it with Bob. But how would she do it? Through the whimsical wonderland of HTTP, of course!

With a mischievous grin on her screen, Alice typed out her request, "Hey Bob, you won't believe this cat video! Send it over, please!" It was the digital equivalent of saying, "Bob, drop everything, it's cat video time!"

Bob's computer, always up for a good laugh, replied with a digital thumbs-up emoji, signaling its readiness for the mission. It was like Bob saying, "Challenge accepted!"

Off Bob's computer went on its adventure, embarking on a wild internet scavenger hunt. It journeyed through the data wilderness, encountering digital squirrels and binary birds along the way. Each server it passed was like a quirky pit stop, filled with memes and GIFs that made it giggle.

Finally, Bob's computer arrived at the server where the hilarious cat video was hiding. It gave the secret cat handshake, and the video revealed itself. Bob's computer quickly downloaded it, careful not to laugh too loudly and wake up the neighbors.

With the cat video safely tucked away, Bob's computer began its triumphant return journey, surfing the data waves with style. It finally arrived back at Alice's computer, out of breath from all the laughter.

Alice's computer eagerly tore open the digital envelope, and there it was—the cat video of epic proportions. Cats doing backflips, wearing sunglasses, and dancing the cha-cha! Alice burst into laughter, and Bob's computer chimed in with cheerful beeps.

HTTP had done its job once again, uniting two computers in the name of laughter and feline fun. In the zany world of the internet, even data transfer could be a hilarious adventure, thanks to HTTP's digital antics. And so, the laughter echoed through the cyber-realm, reminding everyone that even in the virtual world, a good cat video is worth its weight in ones and zeros!

## How HTML, CSS, and JS is parsed in the browser

Parsing HTML, CSS, and JavaScript files in a web browser is a fundamental process that enables the browser to render web pages correctly. Each of these files serves a unique purpose in web development, and they are parsed differently by the browser:

1. HTML (HyperText Markup Language):
   - HTML files contain the structure and content of a web page, defining elements like headings, paragraphs, images, links, and more.
   - When the browser receives an HTML file from a web server, it starts the parsing process.
   - The browser's HTML parser reads the HTML document from top to bottom, tokenizing the content into a Document Object Model (DOM) tree.
   - During this process, it identifies HTML tags, attributes, and their relationships to one another, creating a hierarchical representation of the page's structure.
   - As the HTML is parsed, the browser constructs the DOM tree, which is a structured representation of the page's content and its relationships.
   - Once the DOM tree is built, the browser uses it to render the web page on the screen.

2. CSS (Cascading Style Sheets):
   - CSS files contain rules that define the styling and layout of elements within the HTML document.
   - When a browser encounters a CSS file, it initiates the CSS parsing process.
   - The browser's CSS parser reads the CSS code, interprets selectors (rules that target specific HTML elements), and processes the properties and values associated with those selectors.
   - It builds a data structure called the CSS Object Model (CSSOM) that represents the styles defined in the CSS file.
   - The CSSOM is then combined with the DOM to create a Render Tree, which determines how each element will be displayed on the page.
   - The browser applies styles to elements based on the rules in the CSSOM, resulting in the final visual representation of the web page.

3. JavaScript (JS):
   - JavaScript files contain code that adds interactivity and functionality to web pages.
   - When a browser encounters a JavaScript file (either embedded within the HTML or linked externally), it begins the parsing and execution process.
   - The browser's JavaScript engine parses the JS code, checking for syntax errors and building an Abstract Syntax Tree (AST).
   - Once the AST is created, the JavaScript engine executes the code line by line, following the flow of control and interacting with the DOM and CSSOM as necessary.
   - JavaScript can manipulate the DOM, change styles, handle user input, make network requests, and perform a wide range of actions that enhance user interactions with the web page.

In summary, HTML, CSS, and JavaScript files are parsed separately by the browser, with each file serving a unique purpose in web development. The parsed information from these files is used to create a structured DOM, CSSOM, and execute JavaScript code, ultimately resulting in the rendering and functionality of a web page.

## How to find images to add to a Website

There are several ways to find images to add to a website while ensuring you have the necessary rights and permissions to use them. Here are some common methods:

1. **Create Your Own Images:** If you have the skills and equipment, creating your own images is the best way to ensure originality and avoid any copyright issues. You can use a camera or smartphone to capture photos, create custom graphics, or design illustrations using graphic design software.

2. **Stock Photo Websites:** Many websites offer high-quality stock photos and illustrations for free or for a fee. Popular stock photo websites include Shutterstock, Adobe Stock, Getty Images, Unsplash, Pixabay, and Pexels. Be sure to check the licensing terms to understand how you can use the images.

3. **Creative Commons:** Websites like Flickr and Wikimedia Commons offer images with various Creative Commons licenses. These licenses specify how the images can be used, such as for commercial or non-commercial purposes, with or without attribution. Make sure to follow the terms of the specific license.

4. **Public Domain Resources:** There are websites and databases that provide access to public domain images, which means they are free to use without any restrictions. Websites like Public Domain Pictures and Public Domain Archive are good starting points.

5. **Use Free Icon Sets:** If you need icons or small graphics, you can find free icon sets on websites like Iconfinder and Flaticon. Icons are often available in various formats and styles.

6. **Paid Image Services:** If you're willing to invest in high-quality images and have a specific budget, consider purchasing images from premium stock photo websites. This ensures access to a wide range of professional content.

7. **Government and Educational Institutions:** Some government agencies and educational institutions provide free access to images and resources. For example, NASA offers a vast collection of space-related images.

8. **Attribution and Licensing:** Always check the licensing and attribution requirements associated with each image you use. Some images may require you to give credit to the creator or adhere to specific usage restrictions.

9. **Image Editing and Customization:** Once you have acquired images, you may need to resize or edit them to fit your website's design. Image editing software like Adobe Photoshop, GIMP (free and open-source), or online editors like Canva can help you make necessary adjustments.

10. **Consider Accessibility:** When using images on your website, ensure they are accessible to all users, including those with disabilities. Add alt text to describe images for screen readers and provide captions when necessary.

Remember that copyright laws and licensing terms can vary, so it's crucial to respect the rights of image creators and follow usage guidelines. Always attribute and respect the terms of use associated with each image you incorporate into your website to avoid legal issues.


## How to create certain data types in Javascript

In JavaScript, you can create variables to store both strings and numbers. Here's how to create and differentiate between them:

**Creating a String:**
To create a string in JavaScript, you can use single quotes (' '), double quotes (" "), or backticks (``). Here are examples of each:

```javascript
let strSingle = 'This is a string with single quotes.';
let strDouble = "This is a string with double quotes.";
let strBacktick = `This is a string with backticks.`;
```

All three examples above create string variables. You can use any of these methods to create strings in JavaScript. Strings are typically used to store text or a sequence of characters.

**Creating a Number:**
To create a number in JavaScript, you can simply assign a numerical value to a variable. Numbers can be integers or floating-point values (decimals). Here are examples:

```javascript
let numInteger = 42;       // Integer
let numFloat = 3.14;      // Floating-point number
let numNegative = -10;    // Negative integer
```

Numbers in JavaScript can represent both whole numbers (integers) and fractional numbers (floats). They are used for mathematical calculations and numeric operations.

It's important to note that JavaScript is a dynamically typed language, which means that variables can change their types. For example, you can assign a number to a variable that previously held a string, and vice versa. JavaScript will automatically convert between types as needed, but it's essential to be aware of the types your variables hold to avoid unexpected behavior in your code.

Word of advice: Do not use `var` to declare a variable. This is because var is `global`, meaning
that it will work outside of functions. Use `let` instead. 


## Introduction to HTML

1. What is an HTML attribute?

HTML attributes are put within HTML tags to give extra features. For example, 

```html
<!-- Attributes here are class, and onClick.-->
<div class='red' onClick='removeRed()'>This text is red</div>
```

2. The anatomy of an HTML element is as follows:

```html
<!-- 1. A typical HTML element consists of an opening and closing tag, as well as its content inside of those tags. -->
<p>Hello World</p>

<!-- The opening tag declares the creation of an HTML element. There should be a closing tag to declare its boundaries. -->


<!-- 2. However, some elements are self-closing, such as img. -->
<img src="goldfish.png"/>

```

3. The difference between article and section:

Article: If the text makes sense on its own, or is intended to be reused, such a blog post, or weather widget, use `<article>`.

Section: If your page doesn't have a certain HTML tag to describe it, unlike navigation bars (`<nav>`), use `<section>`. For instance,
if you had a set of buttons in Javascript. 

- [More About Articles](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article)
- [More About Sections](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section)

4. A 'typical' website would include the following:

```html
<!DOCTYPE html>

<html>
    <head>
        <meta charset="utf-8" />

    </head>

    <body>
        <header>
            <h1>Header</h1>

            <nav>
                <li>Home</li>
                <li>About</li>
                <li>Projects</li>
                <li>Contacts</li>
            </nav>


        </header>

        <main>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, 
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam
        </main>
    </body>
</html>

```

5. 

and

6. The metadata influences Search engine optimization by giving it a description that will be shown on the search engine page.
For example, with MDN Web Docs, they use the following tags to get it as the first result.

```html

<title>MDN Web Docs</title>

<meta
  name="description"
  content="The MDN Web Docs site
  provides information about Open Web technologies
  including HTML, CSS, and APIs for both websites and
  progressive web apps." />

```

The meta's description, and title is then shown on the front page.

That's pretty interesting, and I hope I can capitalize on this whenever I make websites!

<img src="https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML/mdn-search-result.png" />
