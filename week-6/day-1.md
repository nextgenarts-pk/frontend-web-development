# Week 6 — JavaScript Fundamentals

## 🎯 Week Goal

By the end of this week, students will understand the core fundamentals of JavaScript including variables, data types, operators, conditions, loops.

---

# 📅 Day 1 — Introduction to JavaScript

## 🧠 Topics Covered

- What is JavaScript?
- Role of JavaScript in Web Development
- How JavaScript works with HTML & CSS
- Internal vs External JavaScript
- Using `<script>` tag
- Writing first JavaScript code
- Console Output

## 📘 Explanation

# 📅 Day 1 — Introduction to JavaScript

## 🧠 Topics Covered

- What is JavaScript?
- Role of JavaScript in Web Development
- How JavaScript works with HTML & CSS
- Internal vs External JavaScript
- Using `<script>` tag
- Writing first JavaScript code
- Console Output

---

# 📘 What is JavaScript?

JavaScript (JS) is a programming language used to make websites interactive and dynamic.

With JavaScript, websites can:

- Respond to user actions
- Validate forms
- Show alerts and notifications
- Create animations
- Update content without refreshing the page
- Build web applications

JavaScript is one of the three core technologies of web development:

- HTML → Structure
- CSS → Styling
- JavaScript → Functionality

---

## 💻 Example

```javascript
console.log("Hello JavaScript");
```

### 📝 Output

```javascript
Hello JavaScript
```

---

# 📘 Role of JavaScript in Web Development

JavaScript adds functionality and interactivity to websites.

Without JavaScript, websites would only display static content.

---

## ✅ What JavaScript Can Do

- Show and hide elements
- Handle button clicks
- Create image sliders
- Validate forms
- Fetch data from APIs
- Build games
- Create single-page applications

---

## 💻 Example

```html
<button onclick="alert('Button Clicked')">Click Me</button>
```

When the button is clicked, JavaScript runs and displays an alert.

---

# 📘 How JavaScript Works with HTML & CSS

HTML, CSS, and JavaScript work together to build modern websites.

---

## 🔹 HTML

Provides structure.

```html
<h1>Welcome</h1>
<button>Click Me</button>
```

---

## 🔹 CSS

Provides styling.

```css
h1 {
  color: blue;
}
```

---

## 🔹 JavaScript

Provides functionality.

```javascript
document.querySelector("h1").innerText = "Hello Sameer";
```

---

## 📊 Relationship

```text
HTML → Structure
CSS → Design
JavaScript → Behavior
```

---

# 📘 Internal vs External JavaScript

JavaScript can be added in two ways:

1. Internal JavaScript
2. External JavaScript

---

# 🔹 Internal JavaScript

Internal JavaScript is written directly inside the HTML file using the `<script>` tag.

---

## 💻 Example

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Internal JS</title>
  </head>
  <body>
    <script>
      console.log("Hello from Internal JavaScript");
    </script>
  </body>
</html>
```

---

# 🔹 External JavaScript

External JavaScript is written in a separate `.js` file.

This is the recommended method for larger projects.

---

## 📄 app.js

```javascript
console.log("Hello from External JavaScript");
```

---

## 📄 index.html

```html
<script src="app.js"></script>
```

---

## ✅ Advantages of External JavaScript

- Cleaner code
- Better organization
- Easier maintenance
- Reusable across multiple pages

---

# 📘 Using `<script>` Tag

The `<script>` tag is used to add JavaScript to a webpage.

---

## 💻 Basic Syntax

```html
<script>
  // JavaScript code
</script>
```

---

## 💻 Example

```html
<script>
  alert("Welcome to JavaScript");
</script>
```

---

## 📍 Best Practice

Place the `<script>` tag before the closing `</body>` tag.

```html
<body>
  <h1>Hello</h1>

  <script src="app.js"></script>
</body>
```

This helps the page load faster.

---

# 📘 Writing First JavaScript Code

The first JavaScript program usually displays a message in the console.

---

## 💻 Example

```javascript
console.log("Hello World");
```

---

## 💻 Another Example

```javascript
console.log("My name is Sameer");
console.log("I am learning JavaScript");
```

### 📝 Output

```javascript
My name is Sameer
I am learning JavaScript
```

---

# 📘 Console Output

The console is a tool provided by browsers for developers.

It helps:

- Test code
- Find errors
- Display information

---

## 💻 Example

```javascript
console.log("Hello");
console.log("JavaScript");
```

### 📝 Output

```javascript
Hello;
JavaScript;
```

---

## 🔹 Opening Console

### Google Chrome

1. Right Click
2. Inspect
3. Click Console Tab

OR

```text
Ctrl + Shift + J
```

---

# 💻 Full Practice Code

```html
<!DOCTYPE html>
<html>
  <head>
    <title>JavaScript Introduction</title>
  </head>
  <body>
    <h1>Welcome to JavaScript</h1>

    <script>
      console.log("Hello World");
      console.log("My name is Sameer");
    </script>
  </body>
</html>
```

---

# 📝 Tasks

1. Create an HTML file.
2. Add JavaScript using the `<script>` tag.
3. Print your name in the console.
4. Print your age in the console.
5. Create an alert message.

---

# 🎯 Homework

1. Research the history of JavaScript.
2. Practice `console.log()` 10 times.
3. Create an HTML page and connect an external JavaScript file.
4. Print 5 different messages in the browser console.

---

# 📚 Summary

After completing this lesson, students will understand:

✅ What JavaScript is  
✅ The role of JavaScript in web development  
✅ How JavaScript works with HTML and CSS  
✅ Internal and External JavaScript  
✅ Using the `<script>` tag  
✅ Writing basic JavaScript code  
✅ Using the browser console

---
