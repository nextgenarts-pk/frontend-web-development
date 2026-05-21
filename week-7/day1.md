# Week 7 — JavaScript Fundamentals

## 🎯 Week Goal

By the end of this week, students will understand the core fundamentals of JavaScript including
functions, arrays, and basic DOM interaction.

# 📅 Day 1 — Functions in JavaScript

## 🧠 Topics Covered

- What are functions?
- Function declaration
- Parameters and arguments
- Return statement
- Arrow functions

## 📘 Explanation

Functions help organize reusable code.

## 💻 Practice Code

```javascript
function greet(name) {
  return "Hello " + name;
}

console.log(greet("Sameer"));
```

## 📝 Tasks

1. Create addition function.
2. Create greeting function.
3. Create multiplication function.

## 🎯 Homework

Build a calculator using functions.

---

# 📅 Day 7 — Arrays and Basic DOM

## 🧠 Topics Covered

- Arrays
- Array methods
- Accessing array items
- Introduction to DOM
- Selecting HTML elements
- Changing text with JavaScript

## 📘 Explanation

Arrays store multiple values in one variable. DOM allows JavaScript to interact with webpage elements.

## 💻 DOM Example

```html
<h1 id="title">Hello</h1>

<script>
  document.getElementById("title").innerText = "Welcome Sameer";
</script>
```

## 💻 Array Example

```javascript
let fruits = ["Apple", "Banana", "Mango"];

console.log(fruits[0]);
console.log(fruits.length);
```

## 📝 Tasks

1. Create an array of names.
2. Print all array values.
3. Change webpage text using JavaScript.

## 🎯 Homework

Create a simple webpage with button and text.

---

# 🧪 Weekly Mini Project

## Project: Simple Student Information App

### Features

- Store student name
- Store age
- Use functions
- Use conditions
- Print results in webpage

## Example Idea

```javascript
let student = "Sameer";
let marks = 85;

if (marks >= 50) {
  console.log(student + " Passed");
} else {
  console.log(student + " Failed");
}
```

---

# 📚 Week 9 Learning Outcomes

After completing this week, students will be able to:

✅ Understand JavaScript basics  
✅ Use variables and data types  
✅ Apply operators and conditions  
✅ Create loops and functions  
✅ Work with arrays  
✅ Manipulate webpage content using DOM  
✅ Build beginner JavaScript projects

---

# 🚀 Extra Practice Challenges

1. Create a number guessing game.
2. Build a simple calculator.
3. Create a temperature converter.
4. Build a student grading system.
5. Make a random quote generator.

---

# 📖 Recommended Resources

- JavaScript MDN Documentation
- W3Schools JavaScript Tutorial
- freeCodeCamp JavaScript Course
- YouTube JavaScript Beginner Tutorials

---

# 🏁 Final Revision Topics

Before moving to next week, revise:

- Variables
- Data Types
- Operators
- Conditions
- Loops
- Functions
- Arrays
- DOM Basics

Practice every topic with small projects for stronger understanding.
