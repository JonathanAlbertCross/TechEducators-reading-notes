# JavaScript objects 

**1. How to Describe an Object to a Non-Technical Friend:**
An object in JavaScript is like a container that holds information about something. Think of it like a file folder where you can put different pieces of information about a specific thing you want to describe. These pieces of information are called properties, and they are like labels that help you organize and access data about that thing. Each property has a name (like a label on a folder) and a value (the actual information inside the folder). You can think of it as a way to keep related information together, just like you might organize your toys in different boxes - one for action figures, one for stuffed animals, and so on.

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
