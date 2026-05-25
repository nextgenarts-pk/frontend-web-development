## Day 4 — Thursday: Operators

### Arithmetic operators

```js
let a = 10;
let b = 3;

console.log(a + b); // 13  — addition
console.log(a - b); // 7   — subtraction
console.log(a * b); // 30  — multiplication
console.log(a / b); // 3.33 — division
console.log(a % b); // 1   — modulus (remainder)
console.log(a ** b); // 1000 — exponent (10³)
```

### Increment & decrement

```js
let x = 5;

x++; // x becomes 6  (increment by 1)
x--; // x becomes 5  (decrement by 1)
x += 10; // x becomes 15 (add 10)
x -= 3; // x becomes 12 (subtract 3)
x *= 2; // x becomes 24 (multiply by 2)
x /= 4; // x becomes 6  (divide by 4)
```

### Comparison operators

```js
console.log(5 == "5"); // true  — equal value (loose)
console.log(5 === "5"); // false — equal value AND type (strict)
console.log(5 !== "5"); // true  — not strictly equal
console.log(10 > 5); // true
console.log(10 < 5); // false
console.log(10 >= 10); // true
console.log(10 <= 9); // false
```

> ⚠️ **Always use `===` instead of `==`** — strict equality avoids unexpected bugs.

### Logical operators

```js
// AND — both conditions must be true
console.log(true && true); // true
console.log(true && false); // false

// OR — at least one must be true
console.log(true || false); // true
console.log(false || false); // false

// NOT — flips true/false
console.log(!true); // false
console.log(!false); // true

// Real examples
let age = 20;
let hasID = true;

if (age >= 18 && hasID) {
  console.log("Entry allowed");
}

if (age < 13 || age > 65) {
  console.log("Special discount");
}
```

### String operators

```js
// Concatenation with +
let first = "Ali";
let last = "Ahmed";
let full = first + " " + last; // "Ali Ahmed"

// Template literals (modern way ✅)
let name = "Sara";
let age = 20;
let msg = `My name is ${name} and I am ${age} years old.`;

// String + Number = String (watch out!)
console.log("5" + 3); // "53"  — string concat!
console.log("5" - 3); // 2     — becomes number
```

---

### ✏️ Exercise

1. Calculate the area of a rectangle (width × height) and print the result
2. Check if a number is even using the `%` modulus operator
3. Use `===` to compare two values and print whether they match
4. Write a template literal that says: `My name is [name], I am [age] years old, I live in [city].`

---
## Day 3 — Wednesday: Data Types ⭐ Key Concept

JavaScript has 7 primitive data types.

### The 7 data types

```js
// 1. String — text, always in quotes
let name = "Ali Ahmed";
let greeting = "Hello!";
let message = `Welcome, ${name}`; // template literal

// 2. Number — integers and decimals
let age = 20;
let price = 99.99;
let negative = -5;

// 3. Boolean — only true or false
let isLoggedIn = true;
let isAdmin = false;

// 4. Undefined — declared but no value assigned
let score;
console.log(score); // undefined

// 5. Null — intentionally empty
let user = null;

// 6. BigInt — very large numbers
let bigNum = 9007199254740991n;

// 7. Symbol — unique identifiers (advanced)
let id = Symbol("id");
```

### Check the type of any value

```js
console.log(typeof "Ali"); // string
console.log(typeof 25); // number
console.log(typeof true); // boolean
console.log(typeof undefined); // undefined
console.log(typeof null); // object  ← known JS bug!
console.log(typeof [1, 2, 3]); // object
```

### Type conversion

```js
// String to Number
let str = "42";
let num = Number(str); // 42
let num2 = parseInt("42px"); // 42

// Number to String
let n = 100;
let s = String(n); // "100"
let s2 = n.toString(); // "100"

// String to Boolean
Boolean(""); // false
Boolean("hello"); // true
Boolean(0); // false
Boolean(1); // true
```

### Falsy vs Truthy

```js
// These 6 values are FALSY (treated as false):
(false, 0, "", null, undefined, NaN);

// Everything else is TRUTHY:
(true, 1, "hello", [], {}, -1);
```

> 💡 **Tip:** Use `typeof` to debug when you are not sure what type a variable is. It saves a lot of confusion.

---

### ✏️ Exercise

1. Create variables of all 5 common types (string, number, boolean, undefined, null)
2. Print each one with `typeof` to see its type
3. Convert the string `"25"` to a number and add `5` to it

# 📅 Day 5 — Loops in JavaScript

## 🧠 Topics Covered

- `for` loop
- `while` loop
- `do while` loop
- Loop control

---

# 📘 Explanation

Loops are used to repeat code multiple times automatically.

Instead of writing the same code again and again, loops help programmers run code efficiently.

Loops are useful for:

- Printing numbers
- Repeating tasks
- Working with arrays
- Creating patterns
- Building games and applications

---

# 📘 `for` Loop

The `for` loop is used when we know how many times we want to repeat code.

---

## 💻 Syntax

```javascript
for (initialization; condition; increment) {
  // code
}
```

---

## 🔹 Parts of `for` Loop

### ✅ Initialization

Starts the loop variable.

```javascript
let i = 1;
```

### ✅ Condition

Checks whether the loop should continue.

```javascript
i <= 5;
```

### ✅ Increment

Increases the loop variable after every repetition.

```javascript
i++;
```

---

## 💻 Example

```javascript
for (let i = 1; i <= 5; i++) {
  console.log(i);
}
```

### 📝 Output

```javascript
1;
2;
3;
4;
5;
```

---

# 📘 `while` Loop

The `while` loop repeats code while the condition is true.

It is useful when the number of repetitions is unknown.

---

## 💻 Syntax

```javascript
while (condition) {
  // code
}
```

---

## 💻 Example

```javascript
let i = 1;

while (i <= 5) {
  console.log(i);
  i++;
}
```

### 📝 Output

```javascript
1;
2;
3;
4;
5;
```

---

# 📘 `do while` Loop

The `do while` loop runs code at least one time before checking the condition.

---

## 💻 Syntax

```javascript
do {
  // code
} while (condition);
```

---

## 💻 Example

```javascript
let i = 1;

do {
  console.log(i);
  i++;
} while (i <= 5);
```

### 📝 Output

```javascript
1;
2;
3;
4;
5;
```

---

# 📘 Difference Between Loops

| Loop Type  | Condition Check  | Runs Minimum |
| ---------- | ---------------- | ------------ |
| `for`      | Before execution | 0 times      |
| `while`    | Before execution | 0 times      |
| `do while` | After execution  | 1 time       |

---

# 📘 Loop Control

Loop control statements are used to control loop behavior.

---

# 🔹 `break`

`break` stops the loop immediately.

---

## 💻 Example

```javascript
for (let i = 1; i <= 5; i++) {
  if (i === 3) {
    break;
  }

  console.log(i);
}
```

### 📝 Output

```javascript
1;
2;
```

---

# 🔹 `continue`

`continue` skips the current iteration and moves to the next one.

---

## 💻 Example

```javascript
for (let i = 1; i <= 5; i++) {
  if (i === 3) {
    continue;
  }

  console.log(i);
}
```

### 📝 Output

```javascript
1;
2;
4;
5;
```

---

# 💻 Full Practice Code

```javascript
for (let i = 1; i <= 5; i++) {
  console.log(i);
}

let num = 1;

while (num <= 3) {
  console.log(num);
  num++;
}

let x = 1;

do {
  console.log(x);
  x++;
} while (x <= 3);
```

---

# 📝 Tasks

1. Print numbers 1–100.
2. Print even numbers.
3. Print odd numbers.
4. Print multiplication table.
5. Practice `break` and `continue`.
6. Create star patterns using loops.

---

# 🎯 Homework

Create the following star pattern using loops.

## 💻 Example

```javascript
*****
*****
*****
```

---

# 💻 Bonus Pattern Example

```javascript
for (let i = 1; i <= 3; i++) {
  console.log("*****");
}
```

### 📝 Output

```javascript
*****
*****
*****
```

---

# 📚 Summary

After completing this lesson, students will understand:

✅ `for` loop  
✅ `while` loop  
✅ `do while` loop  
✅ Loop control statements  
✅ `break` and `continue`  
✅ Repeating code efficiently  
✅ Creating patterns using loops


# 🧪 Week 9 — Weekly Task Project

# 🎯 Project Title

## Student Information & Result Checker

---

# 📘 Project Objective

Create a JavaScript program that uses:

- Variables
- Data Types
- Operators
- Conditional Statements
- Loops

to build a simple student result checking system.

---

# 🧠 Concepts Used

✅ Variables  
✅ `let`, `const`  
✅ Data Types  
✅ Arithmetic Operators  
✅ Comparison Operators  
✅ Logical Operators  
✅ `if else` Conditions  
✅ Loops

---

# 📋 Project Requirements

Your program should:

1. Store student information
2. Store marks of 3 subjects
3. Calculate total marks
4. Calculate average
5. Check pass or fail
6. Print grade
7. Use loop to print subject numbers

---

# 💻 Project Code

```javascript
// Student Information

let studentName = "Sameer";
const rollNumber = 101;

let math = 80;
let english = 75;
let science = 90;

// Total Marks

let total = math + english + science;

// Average

let average = total / 3;

// Print Information

console.log("Student Name:", studentName);
console.log("Roll Number:", rollNumber);

console.log("Math:", math);
console.log("English:", english);
console.log("Science:", science);

console.log("Total Marks:", total);
console.log("Average:", average);

// Grade System

if (average >= 80) {
  console.log("Grade: A");
} else if (average >= 60) {
  console.log("Grade: B");
} else if (average >= 40) {
  console.log("Grade: C");
} else {
  console.log("Fail");
}

// Loop Example

for (let i = 1; i <= 5; i++) {
  console.log("Subject Number:", i);
}
```

---

# 📝 Expected Output

```javascript
Student Name: Sameer
Roll Number: 101

Math: 80
English: 75
Science: 90

Total Marks: 245
Average: 81.6

Grade: A

Subject Number: 1
Subject Number: 2
Subject Number: 3
Subject Number: 4
Subject Number: 5
```

---

# 🚀 Bonus Challenges

1. Add more subjects
2. Create percentage calculator
3. Check even or odd numbers
4. Create login system
5. Print multiplication table using loops

---

# 📚 Learning Outcomes

After completing this project, students will be able to:

✅ Store data using variables  
✅ Use different data types  
✅ Perform calculations using operators  
✅ Apply conditions using `if else`  
✅ Use loops for repetition  
✅ Build beginner JavaScript programs

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

