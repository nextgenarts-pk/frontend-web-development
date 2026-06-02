# 📅 Day 5 — CSS Shadows & Effects

## 🎯 Today's Goals

* Understand CSS Shadows
* Learn `box-shadow`
* Learn `text-shadow`
* Use visual effects in UI
* Create modern styled elements

---

## 📖 Lesson Content

## 🌑 1. What are Shadows in CSS?

**Shadows** add visual depth and effects to elements.

You can apply shadows to:

* Boxes / Cards
* Buttons
* Text
* Images

---

## 📦 2. Box Shadow

`box-shadow` adds shadow around elements.

Basic Syntax:

```css id="se1"
box-shadow: horizontal vertical blur color;
```

Example:

```css id="se2"
.card {
    box-shadow: 5px 5px 10px gray;
}
```

👉 Creates a shadow around the card

---

## ✨ 3. Soft Shadow Example

```css id="se3"
.box {
    box-shadow: 0px 4px 12px rgba(0,0,0,0.3);
}
```

👉 Creates a smooth modern shadow

---

## 🎯 4. Multiple Shadows

You can use more than one shadow.

```css id="se4"
.box {
    box-shadow:
        0 2px 5px gray,
        0 6px 15px lightgray;
}
```

---

## 🔤 5. Text Shadow

Add shadow to text.

Basic Example:

```css id="se5"
h1 {
    text-shadow: 2px 2px 5px gray;
}
```

---

## 🌈 6. Glowing Text Effect

```css id="se6"
h1 {
    color: white;
    text-shadow: 0 0 10px blue;
}
```

👉 Creates a glowing effect

---

## 🎨 7. CSS Effects Example

Combine shadows + transition.

```css id="se7"
.button {
    box-shadow: 0 4px 10px gray;
    transition: 0.3s;
}

.button:hover {
    transform: translateY(-5px);
}
```

👉 Creates hover lift effect

---

## 🧠 Easy Understanding Table

| Property    | Purpose                |
| ----------- | ---------------------- |
| box-shadow  | Shadow around elements |
| text-shadow | Shadow on text         |
| blur        | Shadow softness        |
| rgba()      | Transparent colors     |
| transition  | Smooth effect          |

---

## ✍️ Hands-On Exercise

Create a webpage and:

* Add a card box
* Apply `box-shadow`
* Add `text-shadow` to heading
* Create button hover effect
* Test different shadow styles

---

## 📝 Homework

Design a **Modern Profile Card UI**:

✔ Create profile card
✔ Add `box-shadow`
✔ Add heading `text-shadow`
✔ Apply hover effect
✔ Use smooth transition animation

---

[← Previous Day](day-4.md) | [Back to Week 2](README.md) | [Next Day →](day-6.md)
