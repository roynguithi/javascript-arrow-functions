# javascript-arrow-functions
Arrow Functions Demo

This project demonstrates the use of arrow functions in JavaScript through simple examples, including mathematical calculations, array filtering, and string manipulation.
Features

    Calculate the Square of a Number
    A concise arrow function to compute the square of a given number.
    Example:

const square = (num) => num * num;
console.log(square(5)); // Output: 25

Add Two Numbers
An arrow function to add two numbers and return the result.
Example:

const add = (a, b) => a + b;
console.log(add(3, 7)); // Output: 10

Filter Even Numbers from an Array
Using arrow functions with Array.filter to extract even numbers from a list.
Example:

const filterEvenNumbers = (numbers) => numbers.filter((num) => num % 2 === 0);
const numbers = [1, 2, 3, 4, 5, 6];
console.log(filterEvenNumbers(numbers)); // Output: [2, 4, 6]

Greet a User
A simple arrow function to return a personalized greeting.
Example:

    const greet = (name) => `Hello, ${name}!`;
    console.log(greet("Alice")); // Output: Hello, Alice!

How to Run

    Ensure you have Node.js installed. You can download it from Node.js Official Website.

    Save the JavaScript code into a file named arrow_functions_demo.js.

    Open a terminal or command prompt, navigate to the file's location, and execute the script using:

    node arrow_functions_demo.js

    Observe the outputs directly in your terminal.

Project Purpose

This program is designed to:

    Showcase the power and simplicity of arrow functions.
    Serve as a learning resource for beginners exploring modern JavaScript features.

Technologies Used

    JavaScript (ES6): Leveraging modern features such as arrow functions and array methods.
    Node.js: For running the JavaScript code in a non-browser environment.

License

This project is open-source and available under the MIT License.
