# Week 7 — Conditions & Loops

## 📖 Overview

Welcome to **Week 7 of JavaScript**!

This week, you will learn how to make your programs **think and repeat tasks automatically**. Until now, your code has been running line by line from top to bottom. In this week, you'll learn how to control the flow of your program using **conditions** and **loops**.

Conditions help programs make decisions, while loops allow code to run multiple times without repeating the same statements manually.

These concepts are fundamental in every programming language and are used in real-world applications such as login systems, games, calculators, forms, and much more.

---

# Day 1 — Monday

# 🔀 if / else — Making Decisions in JavaScript

## 📖 Introduction

Until now, your JavaScript code has been running from top to bottom in the same order every time. However, real-world programs need to make decisions based on different situations.

The `if`, `else if`, and `else` statements allow your program to execute different code depending on whether a condition is true or false.

---

# 🎯 Learning Objectives

By the end of this lesson, you will understand:

- `if` statement
- `else` statement
- `else if`
- Conditions
- Boolean values (`true` / `false`)
- Code blocks `{ }`

---

# 🧠 What is a Condition?

A condition is an expression that evaluates to either:

```javascript
true;
```

or

```javascript
false;
```

Example:

```javascript
10 > 5;
```

Output:

```javascript
true;
```

Example:

```javascript
5 > 10;
```

Output:

```javascript
false;
```

---

# 1️⃣ The if Statement

The `if` statement runs a block of code only when a condition is true.

### Syntax

```javascript
if (condition) {
  // code to run
}
```

### Example

```javascript
const age = 20;

if (age >= 18) {
  console.log("You are an adult.");
}
```

### Output

```javascript
You are an adult.
```

### Explanation

Since `20 >= 18` is true, the code inside the braces `{}` runs.

---

# 2️⃣ The else Statement

The `else` block runs when the `if` condition is false.

### Syntax

```javascript
if (condition) {
  // runs if true
} else {
  // runs if false
}
```

### Example

```javascript
const age = 15;

if (age >= 18) {
  console.log("You are an adult.");
} else {
  console.log("You are a minor.");
}
```

### Output

```javascript
You are a minor.
```

### Explanation

Since `15 >= 18` is false, JavaScript skips the `if` block and executes the `else` block.

---

# 3️⃣ The else if Statement

Use `else if` when you need to check multiple conditions.

### Syntax

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

# Example: Student Grade System

```javascript
const marks = 75;

if (marks >= 90) {
  console.log("Grade: A+");
} else if (marks >= 80) {
  console.log("Grade: A");
} else if (marks >= 70) {
  console.log("Grade: B");
} else if (marks >= 50) {
  console.log("Grade: C");
} else {
  console.log("Grade: Fail");
}
```

### Output

```javascript
Grade: B;
```

### Explanation

- Is 75 greater than or equal to 90? ❌ No
- Is 75 greater than or equal to 80? ❌ No
- Is 75 greater than or equal to 70? ✅ Yes

Therefore JavaScript prints:

```javascript
Grade: B;
```

Once a condition becomes true, the remaining conditions are skipped.

---

# 🧩 Boolean Values

A Boolean value can only be:

```javascript
true;
```

or

```javascript
false;
```

Example:

```javascript
console.log(10 > 5);
console.log(10 < 5);
```

### Output

```javascript
true;
false;
```

These Boolean values are often used inside `if` conditions.

---

# 📦 Code Blocks

Code blocks are written inside curly braces `{}`.

Example:

```javascript
if (true) {
  console.log("Line 1");
  console.log("Line 2");
  console.log("Line 3");
}
```

Everything inside the braces belongs to that condition.

---

# 🎯 Practice Exercise

Create a variable called `score` and write a grading system.

### Requirements

| Score    | Grade |
| -------- | ----- |
| 90+      | A+    |
| 80+      | A     |
| 70+      | B     |
| 50+      | C     |
| Below 50 | Fail  |

### Solution

```javascript
const score = 85;

if (score >= 90) {
  console.log("A+");
} else if (score >= 80) {
  console.log("A");
} else if (score >= 70) {
  console.log("B");
} else if (score >= 50) {
  console.log("C");
} else {
  console.log("Fail");
}
```

### Output

```javascript
A;
```

---

# 🧪 Try Different Values

Change the score and observe the output.

```javascript
const score = 95; // A+
const score = 82; // A
const score = 74; // B
const score = 55; // C
const score = 30; // Fail
```

---

# 🎯 Complete Practice Code

```javascript
const age = 20;

if (age >= 18) {
  console.log("You are an adult.");
} else {
  console.log("You are a minor.");
}

const marks = 75;

if (marks >= 90) {
  console.log("Grade: A+");
} else if (marks >= 80) {
  console.log("Grade: A");
} else if (marks >= 70) {
  console.log("Grade: B");
} else if (marks >= 50) {
  console.log("Grade: C");
} else {
  console.log("Grade: Fail");
}
```

---

# ✅ What You Learned Today

- What conditions are
- Boolean values (`true` and `false`)
- `if` statements
- `else` statements
- `else if` statements
- Code blocks `{ }`
- Building a grading system using conditions

---

# 🚀 Next Step

In the next lesson, you will learn how to use logical operators (`&&`, `||`, `!`) to create more powerful conditions and decision-making systems.
