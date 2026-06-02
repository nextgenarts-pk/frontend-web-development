# 📅 Day 4 — CSS Box Model

## 🎯 Today's Goals

* Understand CSS Box Model
* Learn Margin, Border, Padding, Content
* Control spacing in layouts
* Build proper webpage structure

---

## 📖 Lesson Content

## 📦 1. What is Box Model in CSS?

In CSS, every HTML element is treated like a **box**.

This box has 4 main parts:

* Content (text/image)
* Padding (inside space)
* Border (line around content)
* Margin (outside space)

---

## 🧱 2. CSS Box Model Structure

```
Margin
  └── Border
        └── Padding
              └── Content
```

---

## ✍️ 3. Content Area

This is the **main content** inside the element.

```css id="c1c1aa"
p {
    width: 200px;
    height: 100px;
}
```

---

## 📏 4. Padding (Inner Space)

Padding creates space **inside the element**

```css id="p2p2bb"
div {
    padding: 20px;
}
```

---

## 🧱 5. Border (Outline)

Border is the line around the element

```css id="b3b3cc"
div {
    border: 2px solid black;
}
```

You can also change style:

```css id="b4b4dd"
div {
    border: 3px dashed red;
}
```

---

## 🚀 6. Margin (Outer Space)

Margin creates space **outside the element**

```css id="m5m5ee"
div {
    margin: 30px;
}
```

👉 It moves the whole box away from other elements

---

## 🎯 7. Full Box Model Example

```css id="boxmodel1"
div {
    width: 200px;
    height: 100px;
    padding: 20px;
    border: 2px solid blue;
    margin: 15px;
}
```

---

## 🧠 Easy Trick to Remember

* 📦 Content = Inside text
* 🧈 Padding = Butter (inside space)
* 🧱 Border = Wall
* 🌍 Margin = Distance between boxes

---

## ✍️ Hands-On Exercise

Create a webpage and:

* Add a box (div)
* Set width & height
* Apply padding
* Add border style
* Add margin spacing

---

## 📝 Homework

Design a **profile card box** using Box Model:

✔ Add image box
✔ Add name and description
✔ Use padding for spacing
✔ Add border styling
✔ Center the card using margin

---

[← Previous Day](day-3.md) | [Back to Week 2](README.md) | [Next Day →](day-5.md)