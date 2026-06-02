# Week 5 — Only builde your profile website | [NextGen Arts](https://nextgenarts.pk)










# 📅 Day 1 — CSS Overflow, Z-Index, Object-Fit & Object-Position

## 🎯 Today's Goals

* Understand `overflow`
* Learn `z-index`
* Learn `object-fit`
* Learn `object-position`
* Control content, layers, and images in CSS

---

## 📖 Lesson Content

## 📦 1. Overflow Property

`overflow` controls what happens when content becomes **too big** for its container.

---

### Visible (Default)

```css id="oz1"
.box {
    overflow: visible;
}
```

👉 Extra content stays visible

---

### Hidden

```css id="oz2"
.box {
    overflow: hidden;
}
```

👉 Extra content gets hidden

---

### Scroll

```css id="oz3"
.box {
    overflow: scroll;
}
```

👉 Adds scrollbars

---

### Auto

```css id="oz4"
.box {
    overflow: auto;
}
```

👉 Scrollbar appears only when needed

---

## 🗂️ 2. Z-Index

`z-index` controls **stacking order** of elements.

Higher value = appears on top.

```css id="oz5"
.box1 {
    position: absolute;
    z-index: 1;
}

.box2 {
    position: absolute;
    z-index: 5;
}
```

👉 `box2` appears above `box1`

**Note:**
`z-index` usually works with:

* `position: relative`
* `position: absolute`
* `position: fixed`
* `position: sticky`

---

## 🖼️ 3. Object Fit

`object-fit` controls how images/videos fit inside containers.

---

### Cover

```css id="oz6"
img {
    width: 300px;
    height: 200px;
    object-fit: cover;
}
```

👉 Image fills box without stretching

---

### Contain

```css id="oz7"
img {
    object-fit: contain;
}
```

👉 Entire image fits inside container

---

### Fill

```css id="oz8"
img {
    object-fit: fill;
}
```

👉 Image stretches to fill box

---

## 📍 4. Object Position

Controls image position inside its container.

```css id="oz9"
img {
    object-fit: cover;
    object-position: center;
}
```

---

### Other Values

```css id="oz10"
img {
    object-position: top;
}
```

```css id="oz11"
img {
    object-position: bottom right;
}
```

---

## 🔥 5. Combined Example

```css id="oz12"
.card img {
    width: 100%;
    height: 250px;
    object-fit: cover;
    object-position: center;
}
```

👉 Creates clean responsive image cards

---

## 🧠 Easy Understanding Table

| Property        | Purpose               |
| --------------- | --------------------- |
| overflow        | Control extra content |
| hidden          | Hide overflow         |
| scroll          | Always show scrollbar |
| auto            | Smart scrollbar       |
| z-index         | Layer order           |
| object-fit      | Image fitting         |
| object-position | Image placement       |

---

## ✍️ Hands-On Exercise

Create a webpage and:

* Create a box with overflow scroll
* Use `z-index` with overlapping boxes
* Add image using `object-fit`
* Change image position using `object-position`

---

## 📝 Homework

Design a **Modern Card Layout**:

✔ Add image card
✔ Use `object-fit: cover`
✔ Position image properly
✔ Create overlapping badge using `z-index`
✔ Use overflow property on content box

---

[← Back to Week 5](README.md) | [Day 2 →](day-2.md)
