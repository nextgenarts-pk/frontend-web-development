# 📅 Day 2 — Variables — storing data

## 🧠 Topics Covered

- Variables
- `var`, `let`, `const`
- Rules for naming variables

## 📘 Explanation

# 📘 Variables

Variables are containers used to store data values in JavaScript.  
They help programmers save information and use it later in the program.

## ✅ Why Variables Are Important

- Store user information
- Save numbers and text
- Reuse data multiple times
- Make programs dynamic

## 💻 Example

```javascript
let name = "Sameer";
let age = 17;

console.log(name);
console.log(age);
```

### 📝 Output

```javascript
Sameer;
17;
```

---

### var vs let vs const

```js
// var — old way (avoid in modern JS)
var score = 10;

// let — use when value will CHANGE
let points = 0;
points = 50; // ✅ allowed

// const — use when value will NOT change
const PI = 3.14;
PI = 5; // ❌ ERROR — cannot reassign const
```

| Keyword | Can reassign? | Scope    | Use when          |
| ------- | ------------- | -------- | ----------------- |
| `var`   | ✅ Yes        | Function | Avoid (old style) |
| `let`   | ✅ Yes        | Block    | Value will change |
| `const` | ❌ No         | Block    | Value stays same  |

### Naming rules

```js
// ✅ Valid names
let firstName = "Sara";       // camelCase (recommended)
let student_age = 18;         // underscores allowed
let _count = 0;               // underscore at start ok
let $price = 99;              // dollar sign ok

// ❌ Invalid names
let 1name = "Ali";            // cannot start with number
let my-name = "Ali";          // no hyphens
let let = 5;                  // cannot use reserved words
```

> 💡 **Tip:** Always use `const` by default. Switch to `let` only when you know the value will change. Never use `var`.

---

### ✏️ Exercise

Declare variables for a student profile:

- Name (const)
- Age (let)
- City (const)
- Is enrolled — true or false (const)

Print all of them using `console.log()`.

---
