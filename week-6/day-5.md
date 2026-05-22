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
