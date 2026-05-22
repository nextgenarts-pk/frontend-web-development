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
