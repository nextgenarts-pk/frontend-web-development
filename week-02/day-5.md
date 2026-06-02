# 📅 Day 5 — CSS Display Property

## 🎯 Today's Goals

* Understand CSS Display Property
* Learn Block vs Inline elements
* Use `inline`, `block`, `inline-block`
* Learn `none` for hiding elements
* Control layout behavior in webpages

---

## 📖 Lesson Content

## 🧩 1. What is Display Property?

The **display property** defines how an HTML element is shown on the webpage.

It controls:

* Layout behavior
* Position flow
* Visibility style

---

## 🧱 2. Block Elements (`display: block`)

Block elements:

* Start on a new line
* Take full width

```css id="db1"
div {
    display: block;
}
```

### Examples:

* `<div>`
* `<h1>`
* `<p>`

---

## 🔡 3. Inline Elements (`display: inline`)

Inline elements:

* Do NOT start on new line
* Take only needed space

```css id="db2"
span {
    display: inline;
}
```

### Examples:

* `<span>`
* `<a>`
* `<strong>`

---

## 📦 4. Inline-Block (`display: inline-block`)

Inline-block:

* Same line like inline
* But allows width & height like block

```css id="db3"
div {
    display: inline-block;
    width: 150px;
    height: 100px;
}
```

---

## 🚫 5. Display None (`display: none`)

This hides the element completely.

```css id="db4"
p {
    display: none;
}
```

👉 Element will not show on page

---

## 🧠 Easy Understanding Table

| Type         | Line Break | Size Control |
| ------------ | ---------- | ------------ |
| block        | Yes        | Yes          |
| inline       | No         | No           |
| inline-block | No         | Yes          |
| none         | Hidden     | N/A          |

---

## ✍️ Hands-On Exercise

Create a webpage and:

* Make a block element (div box)
* Add inline text using span
* Create buttons using inline-block
* Hide one paragraph using display none

---

## 📝 Homework

Design a **navigation menu** using display property:

✔ Use inline or inline-block
✔ Add links side by side
✔ Style hover effect (optional)
✔ Make layout clean and simple

---

[← Previous Day](day-4.md) | [Back to Week 2](README.md) | [Next Day →](day-6.md)