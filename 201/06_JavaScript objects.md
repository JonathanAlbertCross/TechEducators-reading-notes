# JavaScript objects 

**Why this is important to know**
We have been working with arrays, which helps us malipulate data and this transition to the next topic of objects helps is build on what we've learned so far.

**1. How to Describe an Object to a Non-Technical Friend:**
Okay, imagine you're a magician, and you've got this magical box. But it's not just any box; it's like Mary Poppins' bag – it can hold all sorts of stuff, and each thing inside has its own name tag. So, you can throw in a tiny elephant, a rainbow, and a talking parrot, and the box keeps them all organized. When you want to play with the elephant, you just say, 'Hey, box, give me the tiny elephant!' and voilà, it hands you the elephant. That's basically what an object is in computer magic – a magical box that holds different things, and you can talk to it to get what you want!" 🎩🪄🐘🌈🦜

**2. Advantages of Creating Object Literals:**
Object literals are a simple and convenient way to create objects in JavaScript. Some advantages include:
- They allow you to group related information together.
- You can easily access and manipulate the data within objects.
- Objects can have methods (like functions) that perform actions related to the data.

**3. Objects vs. Arrays:**
Objects and arrays are both used to store and organize data, but they have different purposes:
- Objects are used to store data as key-value pairs, where each property has a unique name (key).
- Arrays are used to store data as ordered lists, and each piece of data is accessed by its position in the list (index).

**4. Bracket Notation vs. Dot Notation:**
You would use bracket notation to access an object's property when the property name contains special characters or spaces. For example:
```javascript
const person = {
  "first name": "John",
  "last name": "Doe"
};

console.log(person["first name"]); // Using bracket notation
```
In this case, the property name contains a space, so dot notation (person.first name) won't work, and you need to use bracket notation.

**5. Evaluating the Code:**
In the provided code, `this` refers to the current object, which is `dog`. The advantage of using `this` inside the `humanAge` method is that it allows you to access properties of the `dog` object within the method. So, when you call `this.name`, it refers to the `name` property of the `dog` object, and when you call `this.age`, it refers to the `age` property of the `dog` object. This makes the code more flexible because it can work with any dog object without hardcoding specific property values. For example:
```javascript
const dog1 = {
  name: 'Buddy',
  age: 3
};

const dog2 = {
  name: 'Rex',
  age: 5
};

dog1.humanAge(); // Outputs: "Buddy is 21 in human years"
dog2.humanAge(); // Outputs: "Rex is 35 in human years"
```
Using `this` allows the method to access the properties of the specific dog it's called on.6

# DOM

**DOM (Document Object Model):** The DOM, or Document Object Model, is a programming interface for web documents. It represents the structure of an HTML or XML document as a tree-like structure where each element (like headings, paragraphs, links, etc.) in the document is represented as an object. This allows programmers to interact with and manipulate the content and structure of a web page using code.

**Relationship Between the DOM and JavaScript:**
JavaScript and the DOM have a close relationship in web development. Here's a brief description of their relationship:

1. **JavaScript as the Language:** JavaScript is a programming language that is often used to make web pages interactive. It can be embedded directly into HTML documents or included in separate JavaScript files. JavaScript provides the ability to add behavior and interactivity to web pages.

2. **DOM as the Interface:** The DOM serves as an interface to the web page's content and structure. When a web page is loaded in a browser, the browser creates a DOM representation of that page. This representation allows JavaScript to access and manipulate the page's elements and attributes.

3. **JavaScript Manipulates the DOM:** JavaScript can be used to modify the DOM. For example, you can use JavaScript to:
   - Change the content of HTML elements.
   - Add or remove elements from the page.
   - Modify CSS styles to change the appearance of elements.
   - Handle user interactions, such as clicks and input events.

4. **Events and Interaction:** JavaScript can listen for and respond to events triggered by user actions (e.g., clicks, keypresses). When an event occurs, JavaScript can use the DOM to make changes to the web page dynamically.

In summary, JavaScript and the DOM work together to make web pages interactive and dynamic. JavaScript provides the scripting capabilities, while the DOM provides the structured representation of the web page's content, allowing JavaScript to interact with and manipulate that content.

## Things I want to know more about
...
