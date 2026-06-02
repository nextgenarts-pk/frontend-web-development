# 📅 Day 3 — CSS Grid Basics

## 🎯 Today's Goals

* Understand CSS Grid
* Learn Grid Container & Grid Items
* Use `display: grid`
* Create rows & columns
* Build layouts using CSS Grid

---

## 📖 Lesson Content

## 🧩 1. What is CSS Grid?

**CSS Grid** is a powerful layout system used to create **2D layouts** (Rows + Columns).

It helps you:

* Create webpage layouts
* Control rows & columns
* Align items easily
* Build responsive designs

---

## 📦 2. Grid Container

First make the parent element a **grid container**.

```css id="gr1"
.container {
    display: grid;
}
```

👉 Child elements become **grid items**

---

## 📏 3. Grid Columns

Use `grid-template-columns` to create columns.

```css id="gr2"
.container {
    display: grid;
    grid-template-columns: 200px 200px 200px;
}
```

### Using `repeat()`

```css id="gr3"
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
}
```

👉 Creates **3 equal columns**

---

## 📐 4. Grid Rows

Use `grid-template-rows`.

```css id="gr4"
.container {
    display: grid;
    grid-template-rows: 100px 100px;
}
```

👉 Creates row heights

---

## 🔥 5. Gap Property

Adds spacing between rows & columns.

```css id="gr5"
.container {
    display: grid;
    gap: 20px;
}
```

---

## 🎯 6. Grid Item Placement

Place items in specific columns or rows.

```css id="gr6"
.box1 {
    grid-column: 1 / 3;
}
```

👉 Box1 spans across columns

---

## 🚀 7. Full Grid Example

```css id="gr7"
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
}
```

---

## 🧠 Easy Understanding Table

| Property              | Purpose             |
| --------------------- | ------------------- |
| display: grid         | Enable Grid         |
| grid-template-columns | Create columns      |
| grid-template-rows    | Create rows         |
| gap                   | Space between items |
| grid-column           | Span columns        |

---

## ✍️ Hands-On Exercise

Create a webpage and:

* Make a grid container
* Create 3 columns
* Add multiple boxes
* Add spacing using `gap`
* Make one box span 2 columns

---

## 📝 Homework

Design a **Simple Dashboard Layout**:

✔ Create 6 boxes
✔ Use CSS Grid
✔ Create 3 columns
✔ Add spacing using `gap`
✔ Make one large featured box using `grid-column`

---

[← Previous Day](day-2.md) | [Back to Week 2](README.md) | [Next Day →](day-4.md)
