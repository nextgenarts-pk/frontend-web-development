# Week 2: CSS Fundamentals & Styling Basics

---
## 📋 Prerequisites

- Completed Week 1 HTML 
- portfolio Website built in HTML

---

## 🎯 Week 2 Goals

* CSS Introduction & Selectors
* Typography Properties
* Colors & Backgrounds
* Box Model
* Display Properties
* Positioning

---

# 📅 Day 1 — CSS Introduction & Selectors

## 🎯 Today's Goals

* What is CSS?
* Inline, Internal & External CSS
* Basic Selectors
* Class & ID Selectors
* What is Class & ID
* Difference Between Class and ID

---

## 📖 Lesson Content

## 🎨 1. What is CSS?

CSS (Cascading Style Sheets) is used to **style HTML pages**.
It makes websites colorful, attractive, and well-designed.

---

## 🧩 2. Types of CSS

### 🔹 Inline CSS

```html id="o2k9aa"
<p style="color:red;">This is red text</p>
```

### 🔹 Internal CSS

```html id="b1c8dd"
<head>
<style>
p {
  color: blue;
}
</style>
</head>
```

### 🔹 External CSS

```html id="x9k3lm"
<link rel="stylesheet" href="style.css">
```

---

## 🧠 3. Basic CSS Syntax

```css id="c3d7pq"
selector {
    property: value;
}
```

Example:

```css id="t8a2ww"
p {
    color: green;
}
```

---

## 🏷️ 4. Selectors

### 🔹 Element Selector

```css id="e1s2aa"
h1 {
    color: red;
}
```

### 🔹 Class Selector

```css id="e2s3bb"
.myclass {
    color: blue;
}
```

### 🔹 ID Selector

```css id="e3s4cc"
#myid {
    color: green;
}
```
## 5. What is Class & ID?

A **class** is an HTML attribute used to group multiple elements and apply the same styling.

### Example:

```html id="c1a9k3"
<p class="text">Hello</p>
<p class="text">World</p>
```

```css id="s7m2p8"
.text{
   color: blue;
}
```
✔ One class can be used on multiple elements.
---

An **ID** is an HTML attribute used to uniquely identify a single element.

### Example:

```html id="i4x8n2"
<h1 id="heading">Welcome</h1>
```

```css id="d9v3k1"
#heading{
   color: red;
}
```
✔ ID should be used only once on a page.

---

## 6. Difference Between Class and ID

| Class                      | ID                      |
| -------------------------- | ----------------------- |
| Used for multiple elements | Used for single element |
| Reusable                   | Unique                  |
| CSS selector: `.` dot      | CSS selector: `#` hash  |
| Example: `.box`            | Example: `#box`         |

---

## ✍️ Hands-On Exercise

Create a simple HTML page and:

* Change text color using CSS
* Use class selector
* Use ID selector
* Apply internal CSS

---

## 📝 Homework

Design a simple webpage and:

✔ Change background color
✔ Style headings
✔ Style paragraph text
✔ Use class and ID

---
[← Previous Day](../week-1/day-6.md) | [Back to Week 2](README.md) | [Next Day →](day-2.md)                  