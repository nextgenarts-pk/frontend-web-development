## 📅 Day 4 —  Strings & Template Literals

 # Template Literals in JavaScript
 
## 🧠 What are Template Literals?

Template Literals are a modern way to create strings in JavaScript.

Instead of using the `+` operator repeatedly, we can use:

- Backticks `` ` ``
- `${}` placeholders

This makes code cleaner, easier to read, and easier to maintain.

---

# 📘 Traditional String Concatenation

Before Template Literals, strings were combined using the `+` operator.

## 💻 Example

```javascript
const name = "Ali";
const age = 17;

let message = "Mera naam " + name + " hai, umar " + age + " saal";

console.log(message);
```

### 📝 Output

```javascript
Mera naam Ali hai, umar 17 saal
```

### ❌ Problems

- Hard to read
- Too many `+` signs
- Becomes messy with large strings

---

# 📘 Template Literals

Template Literals use backticks instead of quotes.

## 💻 Syntax

```javascript
`Text ${variable}`;
```

---

## 💻 Example

```javascript
const name = "Ali";
const age = 17;
const city = "Skardu";

let message = `Mera naam ${name} hai, umar ${age} saal, ${city} se hoon`;

console.log(message);
```

### 📝 Output

```javascript
Mera naam Ali hai, umar 17 saal, Skardu se hoon
```

---

# 📘 Understanding `${}`

`${}` is called an expression placeholder.

It allows us to insert:

- Variables
- Calculations
- Expressions
- Function calls

directly inside a string.

---

## 💻 Example

```javascript
const name = "Ali";

console.log(`Hello ${name}`);
```

### 📝 Output

```javascript
Hello Ali
```

---

# 📘 Using Calculations Inside Template Literals

One of the biggest advantages of Template Literals is that calculations can be performed directly inside `${}`.

---

## 💻 Example

```javascript
const age = 17;

let message = `Aglay saal ${age + 1} saal ka hounga`;

console.log(message);
```

### 📝 Output

```javascript
Aglay saal 18 saal ka hounga
```

---

# 📘 Line-by-Line Explanation

## 💻 Code

```javascript
const name = "Ali";
const age = 17;
const city = "Skardu";
```

### Explanation

Three variables are created:

- `name` stores `"Ali"`
- `age` stores `17`
- `city` stores `"Skardu"`

---

## 💻 Code

```javascript
let msg1 = "Mera naam " + name + " hai, umar " + age + " saal";
```

### Explanation

This uses the old string concatenation method.

JavaScript joins multiple strings together using the `+` operator.

### Output

```javascript
Mera naam Ali hai, umar 17 saal
```

---

## 💻 Code

```javascript
let msg2 = `Mera naam ${name} hai, umar ${age} saal, ${city} se hoon`;
```

### Explanation

This uses a Template Literal.

Values stored in variables are inserted directly into the string using `${}`.

### Output

```javascript
Mera naam Ali hai, umar 17 saal, Skardu se hoon
```

---

## 💻 Code

```javascript
console.log(msg2);
```

### Explanation

Prints the message stored in `msg2`.

### Output

```javascript
Mera naam Ali hai, umar 17 saal, Skardu se hoon
```

---

## 💻 Code

```javascript
let msg3 = `Aglay saal ${age + 1} saal ka hounga`;
```

### Explanation

JavaScript first calculates:

```javascript
17 + 1;
```

Result:

```javascript
18;
```

Then inserts the value into the string.

### Output

```javascript
Aglay saal 18 saal ka hounga
```

---

# 📘 Why Use Template Literals?

## ✅ Advantages

- Cleaner code
- Easy to read
- Less typing
- Supports calculations
- Supports multiline strings
- Preferred modern JavaScript method

---

# 💻 Full Example

```javascript
const name = "Ali";
const age = 17;
const city = "Skardu";

let msg1 = "Mera naam " + name + " hai, umar " + age + " saal";

let msg2 = `Mera naam ${name} hai, umar ${age} saal, ${city} se hoon`;

let msg3 = `Aglay saal ${age + 1} saal ka hounga`;

console.log(msg1);
console.log(msg2);
console.log(msg3);
```

### 📝 Output

```javascript
Mera naam Ali hai, umar 17 saal
Mera naam Ali hai, umar 17 saal, Skardu se hoon
Aglay saal 18 saal ka hounga
```

---

# 📚 Summary

After completing this lesson, students will understand:

✅ What Template Literals are  
✅ Difference between concatenation and Template Literals  
✅ How to use backticks `` ` ``
✅ How `${}` works  
✅ How to insert variables into strings  
✅ How to perform calculations inside strings
