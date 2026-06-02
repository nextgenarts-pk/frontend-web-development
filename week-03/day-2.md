# 📅 Day 2 — Advanced Flexbox

## 🎯 Today's Goals

* Learn Advanced Flexbox Properties
* Understand `flex-wrap`
* Learn `flex-grow`, `flex-shrink`, `flex-basis`
* Use `align-self`
* Build responsive layouts with Flexbox

---

## 📖 Lesson Content

## 🚀 1. What is Advanced Flexbox?

Advanced Flexbox gives **more control over layout behavior**.

You can:

* Wrap items to next line
* Control item size
* Grow or shrink elements
* Align single items separately

---

## 📦 2. Flex Wrap

By default, flex items stay on one line.

Use `flex-wrap` to move items to a new line.

```css id="af1"
.container {
    display: flex;
    flex-wrap: wrap;
}
```

### Common Values:

* `nowrap` (default)
* `wrap`
* `wrap-reverse`

👉 Useful for responsive design

---

## 📏 3. Flex Grow

Controls how much an item can **grow**.

```css id="af2"
.box {
    flex-grow: 1;
}
```

Example:

```css id="af3"
.box1 {
    flex-grow: 1;
}

.box2 {
    flex-grow: 2;
}
```

👉 Box2 takes more space

---

## 📉 4. Flex Shrink

Controls how much an item can **shrink**.

```css id="af4"
.box {
    flex-shrink: 1;
}
```

Disable shrinking:

```css id="af5"
.box {
    flex-shrink: 0;
}
```

---

## 📐 5. Flex Basis

Sets the **starting size** of flex items.

```css id="af6"
.box {
    flex-basis: 200px;
}
```

👉 Works like width for flex items

---

## 🎯 6. Align Self

Align one specific item differently.

```css id="af7"
.box {
    align-self: center;
}
```

### Common Values:

* `flex-start`
* `center`
* `flex-end`
* `stretch`

---

## 🔥 7. Shorthand Flex Property

You can combine multiple properties:

```css id="af8"
.box {
    flex: 1 1 200px;
}
```

Meaning:

* `1` → flex-grow
* `1` → flex-shrink
* `200px` → flex-basis

---

## 🧠 Easy Understanding Table

| Property    | Purpose                 |
| ----------- | ----------------------- |
| flex-wrap   | Move items to next line |
| flex-grow   | Grow item size          |
| flex-shrink | Shrink item size        |
| flex-basis  | Starting size           |
| align-self  | Align one item          |
| flex        | Short form              |

---

## ✍️ Hands-On Exercise

Create a webpage and:

* Create a flex container
* Add multiple boxes
* Use `flex-wrap`
* Apply `flex-grow` & `flex-basis`
* Change alignment of one item using `align-self`

---

## 📝 Homework

Design a **Responsive Product Card Layout**:

✔ Create 4 product cards
✔ Use Flexbox layout
✔ Enable `flex-wrap`
✔ Add equal spacing
✔ Use `flex-grow` for responsive sizing
✔ Style one card differently using `align-self`

---

[← Previous Day](day-1.md) | [Back to Week 2](README.md) | [Next Day →](day-3.md)