# Week 3: CSS Layout Mastery | [NextGen Arts](https://nextgenarts.pk)

---
## 📋 Prerequisites

- Completed Week 2 CSS fundamentals
- Portfolio Website built in HTML & CSS

---

## 🎯 Week 2 Goals

-  Understand the Flexbox layout model
-  Learn Advanced Flexbox Properties
-  Learn Grid Container & Grid Items
-  Learn Advanced CSS Grid Properties

---

# 📅 Day 1 — CSS Flexbox Basics

## 🎯 Today's Goals

* Understand CSS Flexbox
* Learn Flex Container & Flex Items
* Use `display: flex`
* Align items horizontally & vertically
* Build flexible layouts

---

## 📖 Lesson Content

## 📦 1. What is Flexbox in CSS?

**Flexbox** is a CSS layout system used to arrange items easily.

It helps you:

* Align elements
* Create responsive layouts
* Control spacing
* Arrange items in rows or columns

---

## 🧱 2. Flex Container

To use Flexbox, first make a parent element a **flex container**.

```css id="fx1"
.container {
    display: flex;
}
```

👉 Now child elements become **flex items**

---

## 📐 3. Flex Direction

Controls item direction.

### Row (Default)

```css id="fx2"
.container {
    display: flex;
    flex-direction: row;
}
```

👉 Items appear side by side

### Column

```css id="fx3"
.container {
    display: flex;
    flex-direction: column;
}
```

👉 Items appear top to bottom

---

## 🎯 4. Justify Content

Aligns items **horizontally**

```css id="fx4"
.container {
    display: flex;
    justify-content: center;
}
```

### Common Values:

* `center`
* `space-between`
* `space-around`
* `space-evenly`
* `flex-start`
* `flex-end`

---

## 📍 5. Align Items

Aligns items **vertically**

```css id="fx5"
.container {
    display: flex;
    align-items: center;
}
```

### Common Values:

* `center`
* `flex-start`
* `flex-end`
* `stretch`

---

## 🔥 6. Gap Property

Adds spacing between flex items.

```css id="fx6"
.container {
    display: flex;
    gap: 20px;
}
```

---

## 📦 7. Full Flexbox Example

```css id="fx7"
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 15px;
}
```

---

## 🧠 Easy Understanding Table

| Property        | Purpose              |
| --------------- | -------------------- |
| display: flex   | Enable Flexbox       |
| flex-direction  | Row or column        |
| justify-content | Horizontal alignment |
| align-items     | Vertical alignment   |
| gap             | Space between items  |

---

## ✍️ Hands-On Exercise

Create a webpage and:

* Make a flex container
* Add 3 boxes
* Align items center
* Add spacing using gap
* Change direction row → column

---

## 📝 Homework

Design a **Flexbox Card Layout**:

✔ Create 3 cards
✔ Use `display: flex`
✔ Align cards side by side
✔ Add spacing using `gap`
✔ Center the layout

---

[← Back to Week 3](README.md) | [Day 2 →](day-2.md)
