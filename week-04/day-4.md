# 📅 Day 4 — CSS Transitions & Transform

## 🎯 Today's Goals

* Understand CSS Transitions
* Learn CSS Transform Property
* Add smooth animations
* Use hover effects
* Create interactive UI elements

---

## 📖 Lesson Content

## 🎬 1. What are CSS Transitions?

**Transitions** create **smooth changes** between CSS property values.

Without transition → Instant change
With transition → Smooth animation

---

## ✨ 2. Transition Property

Basic syntax:

```css id="tt1"
button {
    transition: 0.5s;
}
```

---

## 🎯 3. Transition with Hover

```css id="tt2"
button {
    background-color: blue;
    transition: 0.5s;
}

button:hover {
    background-color: red;
}
```

👉 Color changes smoothly

---

## ⏱️ 4. Transition Properties

Control animation behavior.

```css id="tt3"
.box {
    transition-property: all;
    transition-duration: 1s;
    transition-timing-function: ease;
}
```

### Common Timing Functions:

* `ease`
* `linear`
* `ease-in`
* `ease-out`
* `ease-in-out`

---

## 🔄 5. Transform Property

**Transform** changes an element’s shape, size, or position.

You can:

* Rotate
* Scale
* Move
* Skew

---

## 🔁 6. Rotate

Rotate an element.

```css id="tt4"
.box:hover {
    transform: rotate(45deg);
}
```

---

## 📏 7. Scale

Increase or decrease size.

```css id="tt5"
.box:hover {
    transform: scale(1.2);
}
```

👉 1.2 = 120% size

---

## 🚀 8. Translate

Move element position.

```css id="tt6"
.box:hover {
    transform: translate(30px, 20px);
}
```

👉 Moves Right **30px** & Down **20px**

---

## 📐 9. Skew

Tilt the element.

```css id="tt7"
.box:hover {
    transform: skew(20deg);
}
```

---

## 🔥 10. Combined Example

```css id="tt8"
.button {
    transition: 0.4s ease;
}

.button:hover {
    transform: scale(1.1);
    background-color: green;
}
```

👉 Smooth hover + zoom effect

---

## 🧠 Easy Understanding Table

| Property            | Purpose               |
| ------------------- | --------------------- |
| transition          | Smooth animation      |
| transition-duration | Animation speed       |
| transform           | Change shape/position |
| rotate()            | Rotate element        |
| scale()             | Resize element        |
| translate()         | Move element          |
| skew()              | Tilt element          |

---

## ✍️ Hands-On Exercise

Create a webpage and:

* Add a button
* Apply transition effect
* Use hover animation
* Rotate or scale a box
* Test different timing functions

---

## 📝 Homework

Design an **Animated Card UI**:

✔ Create a card box
✔ Add hover effect
✔ Use transition animation
✔ Apply transform (scale / rotate)
✔ Make interaction smooth

---

[← Previous Day](day-3.md) | [Back to Week 2](README.md) | [Next Day →](day-5.md)
