# 📅 Day 5 — CSS Positioning

## 🎯 Today's Goals

* Understand CSS Position Property
* Learn different positioning types
* Use `static`, `relative`, `absolute`, `fixed`, `sticky`
* Control element placement on webpage

---

## 📖 Lesson Content

## 📍 1. What is Positioning in CSS?

Positioning is used to **control where an element appears** on the webpage.

With positioning, you can move elements:

* Left / Right
* Top / Bottom
* Fixed screen position
* Overlapping elements

---

## 🧱 2. Position: Static (Default)

Every element is **static by default**.

```css id="ps1"
div {
    position: static;
}
```

👉 Element stays in normal flow (no movement)

---

## 📦 3. Position: Relative

Relative position moves element **from its original position**.

```css id="ps2"
div {
    position: relative;
    top: 20px;
    left: 30px;
}
```

👉 It shifts but keeps its original space

---

## 🎯 4. Position: Absolute

Absolute position moves element **relative to nearest positioned parent**.

```css id="ps3"
div {
    position: absolute;
    top: 50px;
    left: 100px;
}
```

👉 Removes element from normal flow

---

## 🧷 5. Position: Fixed

Fixed position stays in one place even when scrolling.

```css id="ps4"
div {
    position: fixed;
    top: 0;
    right: 0;
}
```

👉 Useful for navbar or buttons

---

## 📌 6. Position: Sticky

Sticky behaves like relative until you scroll.

Then it becomes fixed.

```css id="ps5"
div {
    position: sticky;
    top: 10px;
}
```

---

## 🧠 Easy Understanding Table

| Position | Behavior                   |
| -------- | -------------------------- |
| static   | Default, no movement       |
| relative | Moves from original spot   |
| absolute | Moves freely inside parent |
| fixed    | Stays fixed on screen      |
| sticky   | Mix of relative + fixed    |

---

## ✍️ Hands-On Exercise

Create a webpage and:

* Move a box using relative
* Place a button using absolute
* Create a fixed navbar
* Test sticky header while scrolling

---

## 📝 Homework

Design a **simple webpage layout using positioning**:

✔ Fixed navigation bar
✔ Relative positioned content box
✔ Absolute positioned badge/button
✔ Sticky section heading

" Apply all these properties to portfolio website and improve it."

--- 

[← Previous Day](day-5.md) | [Back to Week 2](README.md) | [Next Week →](../week-3/README.md)