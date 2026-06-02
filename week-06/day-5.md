# Day 5 —  Review + String Methods

## 📖 Introduction

Today, we will review everything we learned during Week 6 and explore some important JavaScript String Methods. These methods are very useful for working with text and will be helpful in future projects.

---

# ⚡ Week 6 Quick Review

## Variables

Variables are used to store data.

```javascript
let age = 17;
const city = "Skardu";
```

- `let` → The value can be changed later.
- `const` → The value cannot be changed.

---

## Data Types

JavaScript supports different types of data.

```javascript
console.log(typeof "Ali");
console.log(typeof 17);
console.log(typeof true);
```

### Output

```javascript
string;
number;
boolean;
```

---

## Operators

Operators are used for calculations and comparisons.

```javascript
console.log(10 + 3);
console.log(10 % 3);
console.log(10 === "10");
```

### Output

```javascript
13;
1;
false;
```

### Explanation

- `+` → Addition
- `%` → Remainder (Modulus)
- `===` → Strict equality comparison

---

## Template Literals

Template literals allow you to insert variables into strings easily.

```javascript
let name = "Ali";

console.log(`Hello ${name}!`);
console.log(`Age: ${age + 1}`);
```

### Output

```javascript
Hello Ali!
Age: 18
```

---

# 📝 String Methods

```javascript
let name = "  Ali Ahmed  ";
```

---

## 1. length

Returns the total number of characters in a string.

```javascript
console.log(name.length);
```

### Output

```javascript
13;
```

---

## 2. trim()

Removes extra spaces from the beginning and end of a string.

```javascript
console.log(name.trim());
```

### Output

```javascript
Ali Ahmed
```

---

## 3. toUpperCase()

Converts all characters to uppercase.

```javascript
console.log(name.toUpperCase());
```

### Output

```javascript
ALI AHMED
```

---

## 4. toLowerCase()

Converts all characters to lowercase.

```javascript
console.log(name.toLowerCase());
```

### Output

```javascript
ali ahmed
```

---

## 5. includes()

Checks whether a specific word or character exists in the string.

```javascript
console.log(name.includes("Ali"));
console.log(name.includes("Sara"));
```

### Output

```javascript
true;
false;
```

---

## 6. replace()

Replaces a specific word with another word.

```javascript
console.log(name.replace("Ali", "Usman"));
```

### Output

```javascript
Usman Ahmed
```

---

## 7. slice()

Extracts a portion of a string.

```javascript
let clean = name.trim();

console.log(clean.slice(0, 3));
console.log(clean.slice(4));
```

### Output

```javascript
Ali;
Ahmed;
```

---

# 🔄 Type Conversion

User input is usually received as a string.

```javascript
let input = "1995";
```

---

## parseInt()

Converts a string into an integer.

```javascript
let year = parseInt(input);

console.log(year + 10);
```

### Output

```javascript
2005;
```

---

## Without Conversion

```javascript
console.log(input + 10);
```

### Output

```javascript
199510;
```

### Explanation

JavaScript treats the value as a string and concatenates it with `10`.

---

## Number()

Another method for converting a string into a number.

```javascript
let num = Number(input);

console.log(typeof num);
```

### Output

```javascript
number;
```

---

# 🎯 Complete Practice Code

```javascript
let age = 17;
const city = "Skardu";

console.log(typeof "Ali");
console.log(typeof 17);
console.log(typeof true);

console.log(10 + 3);
console.log(10 % 3);
console.log(10 === "10");

let name = "  Ali Ahmed  ";

console.log(name.length);
console.log(name.trim());
console.log(name.toUpperCase());
console.log(name.toLowerCase());
console.log(name.includes("Ali"));
console.log(name.includes("Sara"));
console.log(name.replace("Ali", "Usman"));

let clean = name.trim();

console.log(clean.slice(0, 3));
console.log(clean.slice(4));

let input = "1995";

let year = parseInt(input);
console.log(year + 10);

console.log(input + 10);

let num = Number(input);
console.log(typeof num);
```

---

# ✅ What You Learned Today

- Variables
- Data Types
- Operators
- Template Literals
- String Length
- trim()
- toUpperCase()
- toLowerCase()
- includes()
- replace()
- slice()
- parseInt()
- Number()

---
