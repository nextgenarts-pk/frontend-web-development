# 📅 Day 4 — Advanced CSS Grid

## 🎯 Today's Goals

* Learn Advanced CSS Grid Properties
* Understand `grid-area`
* Learn `grid-column` & `grid-row`
* Use `justify-items` & `align-items`
* Build advanced responsive layouts

---

## 📖 Lesson Content

## 🚀 1. What is Advanced CSS Grid?

Advanced Grid gives **more control** over layout design.

You can:

* Control item placement
* Span rows & columns
* Create named areas
* Align grid items
* Build complex layouts easily

---

## 📦 2. Grid Column & Grid Row

Control how many rows or columns an item uses.

### Grid Column

```css id="ag1"
.box1 {
    grid-column: 1 / 3;
}
```

👉 Box1 spans from column 1 to 3

### Grid Row

```css id="ag2"
.box2 {
    grid-row: 1 / 3;
}
```

👉 Box2 spans across rows

---

## 🎯 3. Grid Area

Use `grid-area` to place items.

```css id="ag3"
.box {
    grid-area: 1 / 1 / 3 / 3;
}
```

Meaning:

* Row Start
* Column Start
* Row End
* Column End

---

## 🗺️ 4. Grid Template Areas

Create named layout sections.

```css id="ag4"
.container {
    display: grid;
    grid-template-areas:
        "header header"
        "sidebar content"
        "footer footer";
}
```

Assign areas:

```css id="ag5"
.header {
    grid-area: header;
}
```

---

## 📍 5. Justify Items

Aligns items **horizontally** inside grid cells.

```css id="ag6"
.container {
    justify-items: center;
}
```

---

## 📐 6. Align Items

Aligns items **vertically** inside grid cells.

```css id="ag7"
.container {
    align-items: center;
}
```

---

## 🔥 7. Minmax Function

Create flexible responsive columns.

```css id="ag8"
.container {
    grid-template-columns: repeat(3, minmax(150px, 1fr));
}
```

👉 Minimum **150px**, maximum **1fr**

---

## 🧠 Easy Understanding Table

| Property            | Purpose               |
| ------------------- | --------------------- |
| grid-column         | Span columns          |
| grid-row            | Span rows             |
| grid-area           | Item placement        |
| grid-template-areas | Named layout sections |
| justify-items       | Horizontal alignment  |
| align-items         | Vertical alignment    |
| minmax()            | Flexible sizing       |

---

## ✍️ Hands-On Exercise

Create a webpage and:

* Build a grid layout
* Use `grid-column` & `grid-row`
* Create named sections using `grid-template-areas`
* Center items using alignment properties
* Use `minmax()` for responsive columns

---

## 📝 Homework

Design a **Responsive Admin Dashboard**:

✔ Create Header, Sidebar, Main Content, Footer
✔ Use `grid-template-areas`
✔ Apply `grid-column` / `grid-row`
✔ Add spacing & alignment
✔ Use `minmax()` for responsive layout

---

[← Previous Day](day-3.md) | [Back to Week 2](README.md) | [Next Day →](day-5.md)
