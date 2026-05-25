# Week 7 — JavaScript Fundamentals

## 🎯 Week Goal

By the end of this week, students will understand the core fundamentals of JavaScript including
functions, arrays, and basic DOM interaction.

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

# 📅 Day 3 — Operators in JavaScript

# 📅 Day 4 — Conditional Statements

## 🧠 Topics Covered

- `if` statement
- `else` statement
- `else if`
- Nested conditions
- Switch statement

---

# 📘 Explanation

Conditional statements allow programs to make decisions.

They check conditions and run different code based on whether the condition is:

- `true`
- `false`

Conditional statements are very important in programming because they make programs smart and interactive.

---

# 📘 `if` Statement

The `if` statement runs code only if the condition is true.

---

## 💻 Syntax

```javascript
if (condition) {
  // code
}
```

---

## 💻 Example

```javascript
let age = 18;

if (age >= 18) {
  console.log("You are eligible");
}
```

### 📝 Output

```javascript
You are eligible
```

---

# 📘 `else` Statement

The `else` statement runs when the condition is false.

---

## 💻 Syntax

```javascript
if (condition) {
  // true code
} else {
  // false code
}
```

---

## 💻 Example

```javascript
let age = 16;

if (age >= 18) {
  console.log("You are eligible");
} else {
  console.log("You are not eligible");
}
```

### 📝 Output

```javascript
You are not eligible
```

---

# 📘 `else if` Statement

`else if` is used to check multiple conditions.

---

## 💻 Syntax

```javascript
if (condition1) {
  // code
} else if (condition2) {
  // code
} else {
  // code
}
```

---

## 💻 Example

```javascript
let marks = 75;

if (marks >= 90) {
  console.log("Grade A");
} else if (marks >= 70) {
  console.log("Grade B");
} else {
  console.log("Grade C");
}
```

### 📝 Output

```javascript
Grade B
```

---

# 📘 Nested Conditions

Nested conditions mean using one condition inside another condition.

---

## 💻 Example

```javascript
let age = 20;
let hasID = true;

if (age >= 18) {
  if (hasID) {
    console.log("Entry Allowed");
  } else {
    console.log("ID Required");
  }
} else {
  console.log("Under Age");
}
```

### 📝 Output

```javascript
Entry Allowed
```

---

# 📘 Switch Statement

The `switch` statement is used when checking many possible values.

It is cleaner than using many `else if` statements.

---

## 💻 Syntax

```javascript
switch (value) {
  case option1:
    // code
    break;

  case option2:
    // code
    break;

  default:
  // code
}
```

---

## 💻 Example

```javascript
let day = 3;

switch (day) {
  case 1:
    console.log("Monday");
    break;

  case 2:
    console.log("Tuesday");
    break;

  case 3:
    console.log("Wednesday");
    break;

  default:
    console.log("Invalid Day");
}
```

### 📝 Output

```javascript
Wednesday;
```

---

# 💻 Full Practice Code

```javascript
let age = 18;

if (age >= 18) {
  console.log("You are eligible");
} else {
  console.log("You are not eligible");
}

let marks = 85;

if (marks >= 80) {
  console.log("Excellent");
} else if (marks >= 50) {
  console.log("Pass");
} else {
  console.log("Fail");
}
```

---

# 📝 Tasks

1. Create age checker.
2. Create grading system.
3. Check even and odd numbers.
4. Create login condition.
5. Practice switch statement.

---

# 🎯 Homework

Create a login condition program.

## 💻 Example

```javascript
let username = "admin";
let password = 1234;

if (username === "admin" && password === 1234) {
  console.log("Login Successful");
} else {
  console.log("Invalid Username or Password");
}
```

---

# 📚 Summary

After completing this lesson, students will understand:

✅ `if` statement  
✅ `else` statement  
✅ `else if` statement  
✅ Nested conditions  
✅ Switch statement  
✅ Decision making in JavaScript  
✅ Multiple condition checking
