# 📅 Day 5 — Responsive Design

## 🎯 Today's Goals

* Understand Responsive Design
* Learn Media Queries
* Use Flexible Units
* Make websites mobile-friendly
* Build responsive layouts

---

## 📖 Lesson Content

## 📱 1. What is Responsive Design?

**Responsive Design** means a website adjusts properly on different screen sizes.

Examples:

* 📱 Mobile
* 💻 Laptop
* 🖥️ Desktop
* 📟 Tablet

A responsive website changes layout based on screen size.

---

## 📏 2. Viewport Meta Tag

Add viewport tag in HTML.

```html id="rd1"
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

👉 Helps website fit properly on mobile devices

---

## 📐 3. Flexible Units

Use flexible units instead of fixed values.

### Percentage (%)

```css id="rd2"
.box {
    width: 50%;
}
```

### Viewport Width (`vw`)

```css id="rd3"
h1 {
    font-size: 5vw;
}
```

### REM Unit

```css id="rd4"
p {
    font-size: 1.2rem;
}
```

---

## 🎯 4. Media Queries

Media Queries apply CSS for different screen sizes.

```css id="rd5"
@media (max-width: 768px) {
    body {
        background-color: lightblue;
    }
}
```

👉 CSS changes when screen width becomes **768px or smaller**

---

## 📦 5. Responsive Flexbox Example

```css id="rd6"
.container {
    display: flex;
    gap: 20px;
}

@media (max-width: 768px) {
    .container {
        flex-direction: column;
    }
}
```

👉 Desktop = Row
👉 Mobile = Column

---

## 🧩 6. Responsive Grid Example

```css id="rd7"
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
}

@media (max-width: 768px) {
    .container {
        grid-template-columns: 1fr;
    }
}
```

👉 Desktop = 3 Columns
👉 Mobile = 1 Column

---

## 🧠 Easy Understanding Table

| Property | Purpose               |
| -------- | --------------------- |
| viewport | Mobile screen fitting |
| %        | Flexible width        |
| vw       | Viewport sizing       |
| rem      | Responsive font size  |
| @media   | Screen-based styling  |

---

## ✍️ Hands-On Exercise

Create a webpage and:

* Add viewport meta tag
* Use `%` or `rem` units
* Create a media query
* Make layout change on mobile size

---

## 📝 Homework

Design a **Responsive Landing Page**:

✔ Add responsive typography
✔ Use Flexbox or Grid layout
✔ Add media queries
✔ Make layout mobile-friendly
✔ Test on different screen sizes

---

[← Day 4](day-4.md) | [Back to Week 3](README.md) | [Day 6 →](day-6.md)