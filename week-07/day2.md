# Day 2 — Tuesday

# 🔗 Logical Operators & Ternary Operator

## 📖 Introduction

In the previous lesson, you learned how to make decisions using `if`, `else if`, and `else`.

Today, you will learn how to:

- Combine multiple conditions using **Logical Operators**
- Write short one-line conditions using the **Ternary Operator**

These concepts are commonly used in login systems, form validation, grading systems, and many real-world applications.

---

# 🎯 Learning Objectives

By the end of this lesson, you will understand:

- `&&` (AND)
- `||` (OR)
- `!` (NOT)
- Ternary Operator (`? :`)
- Combining multiple conditions
- Writing cleaner and shorter code

---

# 🧠 What are Logical Operators?

Logical operators allow us to combine two or more conditions.

JavaScript provides three main logical operators:

| Operator | Name |
|-----------|---------|
| `&&` | AND |
| `||` | OR |
| `!` | NOT |

---

# 1️⃣ AND Operator (`&&`)

The AND operator returns `true` only when **both conditions are true**.

### Syntax

```javascript
condition1 && condition2
```

### Example

```javascript
const age = 20;
const hasId = true;

if (age >= 18 && hasId === true) {
  console.log("Entry allowed");
}
```

### Output

```javascript
Entry allowed
```

### Explanation

Both conditions are true:

```javascript
age >= 18       → true
hasId === true  → true
```

Since both are true, the code runs.

---

# 2️⃣ OR Operator (`||`)

The OR operator returns `true` when **at least one condition is true**.

### Syntax

```javascript
condition1 || condition2
```

### Example

```javascript
const marks = 85;
const attendance = 90;

if (marks >= 80 || attendance >= 90) {
  console.log("Eligible for award");
}
```

### Output

```javascript
Eligible for award
```

### Explanation

Only one condition needs to be true for OR to work.

---

# 3️⃣ NOT Operator (`!`)

The NOT operator reverses a Boolean value.

### Syntax

```javascript
!condition
```

### Example

```javascript
const isRaining = false;

if (!isRaining) {
  console.log("Go outside and play!");
}
```

### Output

```javascript
Go outside and play!
```

### Explanation

```javascript
isRaining = false

!false = true
```

Since the condition becomes true, the code executes.

---

# Combining Logical Operators

You can combine multiple conditions together.

### Example

```javascript
const marks = 85;
const attendance = 90;

if (marks >= 80 && attendance >= 75) {
  console.log("Result: Distinction");
}
```

### Output

```javascript
Result: Distinction
```

### Explanation

Both conditions are true:

```javascript
marks >= 80        → true
attendance >= 75   → true
```

Therefore, the result is displayed.

---

# ⚡ Ternary Operator

The Ternary Operator is a shorter way to write simple `if/else` statements.

### Syntax

```javascript
condition ? valueIfTrue : valueIfFalse
```

---

# Traditional if/else

```javascript
let result;

if (marks >= 50) {
  result = "Pass";
} else {
  result = "Fail";
}
```

---

# Same Code Using Ternary Operator

```javascript
const result = marks >= 50 ? "Pass" : "Fail";

console.log(result);
```

### Output

```javascript
Pass
```

### Explanation

If the condition is true:

```javascript
marks >= 50
```

JavaScript returns:

```javascript
"Pass"
```

Otherwise it returns:

```javascript
"Fail"
```

---

# More Examples

### Example 1

```javascript
const age = 20;

const status = age >= 18 ? "Adult" : "Minor";

console.log(status);
```

### Output

```javascript
Adult
```

---

### Example 2

```javascript
const marks = 95;

const label = marks > 90 ? "Excellent" : "Good";

console.log(label);
```

### Output

```javascript
Excellent
```

---

### Example 3

```javascript
const age = 20;
const marks = 95;

const status = age >= 18 ? "Adult" : "Minor";
const label = marks > 90 ? "Excellent" : "Good";

console.log(`Status: ${status}, Performance: ${label}`);
```

### Output

```javascript
Status: Adult, Performance: Excellent
```

---

# 📊 Operator Summary

| Operator | Name | Example | Result |
|-----------|---------|---------|---------|
| `&&` | AND | `true && false` | `false` |
| `||` | OR | `true || false` | `true` |
| `!` | NOT | `!true` | `false` |
| `? :` | Ternary | `age >= 18 ? "A" : "B"` | `"A"` |

---

# 🎯 Practice Exercise

A student passes only if:

- Marks are at least 50
- Attendance is at least 75

### Solution Using AND (`&&`)

```javascript
const marks = 70;
const attendance = 80;

if (marks >= 50 && attendance >= 75) {
  console.log("Pass");
} else {
  console.log("Fail");
}
```

### Output

```javascript
Pass
```

---

# 🚀 Rewrite Using Ternary Operator

```javascript
const marks = 70;
const attendance = 80;

const result =
  marks >= 50 && attendance >= 75
    ? "Pass"
    : "Fail";

console.log(result);
```

### Output

```javascript
Pass
```

---

# 🎯 Complete Practice Code

```javascript
const age = 20;
const hasId = true;
const marks = 85;
const attendance = 90;

if (age >= 18 && hasId === true) {
  console.log("Entry allowed");
}

if (marks >= 80 || attendance >= 90) {
  console.log("Eligible for award");
}

const isRaining = false;

if (!isRaining) {
  console.log("Go outside and play!");
}

if (marks >= 80 && attendance >= 75) {
  console.log("Result: Distinction");
}

const result = marks >= 50 ? "Pass" : "Fail";

console.log(result);
```

---

# ✅ What You Learned Today

- AND Operator (`&&`)
- OR Operator (`||`)
- NOT Operator (`!`)
- Combining multiple conditions
- Ternary Operator (`? :`)
- Writing shorter if/else statements
- Building pass/fail logic using conditions

---

# 🚀 Next Step

In the next lesson, you will learn the **Switch Statement**, which provides another way to handle multiple conditions more cleanly and efficiently.