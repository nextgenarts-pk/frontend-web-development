# 📅 Day 6 — CSS Animations

## 🎯 Today's Goals

* Understand CSS Animations
* Learn `@keyframes`
* Use animation properties
* Create moving UI elements
* Build smooth visual animations

---

## 📖 Lesson Content

## 🎬 1. What are CSS Animations?

**CSS Animations** make elements move or change automatically.

Animations can:

* Move elements
* Change colors
* Rotate objects
* Create loading effects
* Add UI interaction

---

## 🧩 2. @keyframes Rule

`@keyframes` defines animation steps.

Basic Syntax:

```css id="an1"
@keyframes example {
    from {
        background-color: blue;
    }

    to {
        background-color: red;
    }
}
```

👉 Changes color from **blue → red**

---

## 🚀 3. Applying Animation

Use the `animation` property.

```css id="an2"
.box {
    animation: example 2s;
}
```

Meaning:

* `example` → Animation name
* `2s` → Duration

---

## 🎯 4. Animation Properties

Control animation behavior.

```css id="an3"
.box {
    animation-name: moveBox;
    animation-duration: 3s;
    animation-timing-function: ease;
}
```

---

### Common Timing Functions:

* `ease`
* `linear`
* `ease-in`
* `ease-out`
* `ease-in-out`

---

## 🔁 5. Animation Iteration Count

Repeat animation.

```css id="an4"
.box {
    animation-iteration-count: infinite;
}
```

👉 Runs forever

---

## 📍 6. Animation Direction

Control movement direction.

```css id="an5"
.box {
    animation-direction: alternate;
}
```

### Common Values:

* `normal`
* `reverse`
* `alternate`
* `alternate-reverse`

---

## 🌈 7. Moving Box Example

```css id="an6"
@keyframes move {
    from {
        transform: translateX(0);
    }

    to {
        transform: translateX(200px);
    }
}

.box {
    animation: move 2s infinite alternate;
}
```

👉 Box moves left ↔ right

---

## 🔥 8. Loading Spinner Example

```css id="an7"
@keyframes spin {
    from {
        transform: rotate(0deg);
    }

    to {
        transform: rotate(360deg);
    }
}

.loader {
    animation: spin 1s linear infinite;
}
```

---

## 🧠 Easy Understanding Table

| Property                  | Purpose           |
| ------------------------- | ----------------- |
| @keyframes                | Define animation  |
| animation-name            | Animation name    |
| animation-duration        | Speed             |
| animation-timing-function | Motion style      |
| animation-iteration-count | Repeat control    |
| animation-direction       | Direction control |

---

## ✍️ Hands-On Exercise

Create a webpage and:

* Create a moving box
* Use `@keyframes`
* Apply animation duration
* Repeat animation infinitely
* Test different directions

---

## 📝 Homework

Design an **Animated Loading UI**:

✔ Create loader/spinner
✔ Use `@keyframes`
✔ Apply infinite animation
✔ Add smooth timing function
✔ Create moving or rotating effect

---

[← Day 5](day-5.md) | [Back to Week 3](README.md) | [Week 5 →](../week-
5/README.md)