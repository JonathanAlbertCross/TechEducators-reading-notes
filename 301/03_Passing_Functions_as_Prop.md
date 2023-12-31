**React Docs - lists and keys:**

1. `.map()` returns a new array by calling a provided function once for each element in the array and building a new array with the results of those function calls.

2. To loop through an array and display each value in JSX in React, you can use the `.map()` method to create a new array of JSX elements, which can then be rendered within the component's return statement.

3. Each list item needs a unique "key." In React, when rendering a list of items, each item should have a unique key prop to help React identify and track individual list items efficiently.

4. The purpose of a key is to help React identify and differentiate between elements in a list, allowing it to efficiently update and re-render components when the list changes. Keys should be unique and stable, typically using an identifier from the data (e.g., an item's ID).

**The Spread Operator:**

1. The spread operator (`...`) is a feature in JavaScript used for manipulating arrays and objects. It allows you to expand or spread the elements of an iterable (like an array or object) into another array, object, or function call.

2. Four things that the spread operator can do:
   a. Create a shallow copy of an array or object.
   b. Merge two or more arrays into a single array.
   c. Merge two or more objects into a single object.
   d. Spread elements in function arguments.

**Example of using the spread operator to combine two arrays:**
```javascript
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];
const combinedArray = [...arr1, ...arr2];
console.log(combinedArray); // [1, 2, 3, 4, 5, 6]
```

**Example of using the spread operator to add a new item to an array:**
```javascript
const originalArray = [1, 2, 3];
const newItem = 4;
const newArray = [...originalArray, newItem];
console.log(newArray); // [1, 2, 3, 4]
```

**Example of using the spread operator to combine two objects into one:**
```javascript
const obj1 = { name: 'Alice', age: 30 };
const obj2 = { city: 'New York', country: 'USA' };
const combinedObject = { ...obj1, ...obj2 };
console.log(combinedObject);
// { name: 'Alice', age: 30, city: 'New York', country: 'USA' }
```

**How to Pass Functions Between Components:**

1. In the video, the first step the developer does to pass functions between components is defining the function in the parent component that they want to pass to a child component.

2. In my own words, the "increment" function likely increases or increments a value, often a counter or a piece of state in the React component, typically used for interactive elements like buttons.

3. To pass a method from a parent component into a child component, you can include the method as a prop when rendering the child component, just like passing any other data.

4. The child component can invoke a method that was passed to it from a parent component by calling the method as a function, using the prop that holds the method. For example, if the method is passed as a prop named "onIncrement," you can call it within the child component as `this.props.onIncrement()` (in a class-based component) or `props.onIncrement()` (in a functional component).
