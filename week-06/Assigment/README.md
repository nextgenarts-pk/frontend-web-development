## 📝 Week 6 — Assignment

> Complete all 4 tasks below. Use only: `const`, `let`, operators, string methods, `console.log()`. **No DOM. No HTML.**

---

### Task 1 — Personal Info Card

Create a JS file that stores and displays your personal information.

**Requirements:**

- Store: full name, age, city, school, favourite subject
- Use `typeof` on every variable and print the type
- Use `.toUpperCase()` on your name
- Use `.trim()` on your city (add spaces deliberately)
- Use `.includes()` to check if your name contains your first name
- Use `.length` to count characters in your name
- Display everything using template literals in a neat box using `console.log()`

**Example output:**

```
==============================
       MY INFO CARD
==============================
Name:    ALI AHMED
Age:     17
City:    SKARDU
School:  Skardu Public School
Subject: Math
------------------------------
typeof name:  string
typeof age:   number
Name length:  9 characters
Has "Ali":    true
==============================
```

---

### Task 2 — Circle Calculator

Calculate all properties of a circle using one radius value.

**Requirements:**

- Store `radius` as a `const`
- Store `PI = 3.14159` as a `const`
- Calculate: diameter, circumference, area
- Use `**` (power operator) for area formula: `PI * r²`
- Check: is the area greater than 100? (boolean)
- Display all results with template literals

**Formulas:**

```
diameter      = 2 * radius
circumference = 2 * PI * radius
area          = PI * radius ** 2
```

---

### Task 3 — Temperature Converter

Convert a temperature from Celsius to Fahrenheit and Kelvin.

**Requirements:**

- Store 3 different Celsius values: body temp (37), boiling (100), freezing (0)
- Convert each to Fahrenheit: `(C * 9/5) + 32`
- Convert each to Kelvin: `C + 273.15`
- Use `typeof` on the celsius values
- Display all conversions in a neat table using `console.log()`

---

### Task 4 — String Detective 🔍

Investigate a string using string methods.

**Requirements:**

- Store this exact string: `"   JavaScript is Amazing!   "`
- Apply and print the result of each method:
  - `.trim()`
  - `.toUpperCase()`
  - `.toLowerCase()`
  - `.length` (before and after trim)
  - `.includes("Amazing")`
  - `.includes("Python")`
  - `.replace("Amazing", "Powerful")`
  - `.slice(3, 13)` (on the original)
- Print each result with a label using template literals

---

## 📋 Assignment Submission Checklist

- [ ] Task 1 — Personal Info Card complete
- [ ] Task 2 — Circle Calculator complete
- [ ] Task 3 — Temperature Converter complete
- [ ] Task 4 — String Detective complete
- [ ] All 4 files named correctly: `task1.js`, `task2.js`, `task3.js`, `task4.js`
- [ ] No DOM used — only `console.log()`
- [ ] All outputs displayed in a neat formatted box
- [ ] Pushed to GitHub in a folder called `week6-assignment`

---

## 📁 Folder Structure

```
week6-assignment/
├── task1.js     ← Personal Info Card
├── task2.js     ← Circle Calculator
├── task3.js     ← Temperature Converter
├── task4.js     ← String Detective
└── README.md    ← Your name + week number
```

---

## 🚀 How to Run

```bash
# Open in VS Code
cd week6-assignment

# Run in browser console
# Open index.html → F12 → Console → paste code

# OR run with Node.js
node task1.js
node task2.js
node task3.js
node task4.js
```

---

## 📚 Week 6 Quick Reference

```js
// Variables
const x = 10;       // cannot change
let y = 20;         // can change

// Data Types
typeof "Ali"    // "string"
typeof 17       // "number"
typeof true     // "boolean"
typeof null     // "object" ⚠️
typeof undefined // "undefined"

// Arithmetic Operators
+   // addition
-   // subtraction
*   // multiplication
/   // division
%   // remainder
**  // power

// Comparison Operators
===   // strict equal (value + type)
!==   // not equal
>     // greater than
<     // less than
>=    // greater than or equal
<=    // less than or equal

// String Methods
.length          // count characters
.toUpperCase()   // ALL CAPS
.toLowerCase()   // all small
.trim()          // remove spaces
.includes("x")   // true or false
.replace("a","b")// swap words
.slice(0, 3)     // cut a piece

// Template Literal
`Hello ${name}, you are ${age} years old`
```

---

_Week 6 · JavaScript Basics · Beginners Web Curriculum_
