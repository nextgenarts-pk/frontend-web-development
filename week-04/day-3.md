# 📅 Day 3 — CSS Pseudo Classes & Pseudo Elements

## 🎯 Today's Goals

* Understand Pseudo Classes
* Understand Pseudo Elements
* Learn `:hover`, `:focus`, `:first-child`
* Learn `::before`, `::after`
* Create interactive and styled UI elements

---

## 📖 Lesson Content

## 🧩 1. What are Pseudo Classes?

**Pseudo Classes** style an element in a **special state**.

Examples:

* Mouse hover
* Input focus
* First child element

Syntax:

```css id="pc1"
selector:pseudo-class {
    property: value;
}
```

---

## 🎯 2. Hover (`:hover`)

Styles element when mouse moves over it.

```css id="pc2"
button:hover {
    background-color: blue;
    color: white;
}
```

👉 Changes style on hover

---

## ✍️ 3. Focus (`:focus`)

Used with inputs or form fields.

```css id="pc3"
input:focus {
    border: 2px solid blue;
}
```

👉 Style changes when input is selected

---

## 📍 4. First Child (`:first-child`)

Styles the first child element.

```css id="pc4"
li:first-child {
    color: red;
}
```

👉 First list item becomes red

---

## 🔥 5. What are Pseudo Elements?

**Pseudo Elements** style a **specific part** of an element.

Syntax:

```css id="pc5"
selector::pseudo-element {
    property: value;
}
```

---

## ✨ 6. Before (`::before`)

Adds content before an element.

```css id="pc6"
h1::before {
    content: "🔥 ";
}
```

👉 Adds emoji before heading

---

## 🚀 7. After (`::after`)

Adds content after an element.

```css id="pc7"
h1::after {
    content: " 🚀";
}
```

👉 Adds emoji after heading

---

## 🎨 8. First Letter (`::first-letter`)

Styles first letter of text.

```css id="pc8"
p::first-letter {
    font-size: 30px;
    color: red;
}
```

---

## 📄 9. First Line (`::first-line`)

Styles first line of text.

```css id="pc9"
p::first-line {
    font-weight: bold;
}
```

---

## 🧠 Easy Understanding Table

| Property         | Purpose              |
| ---------------- | -------------------- |
| `:hover`         | Mouse hover state    |
| `:focus`         | Selected input state |
| `:first-child`   | First child styling  |
| `::before`       | Add content before   |
| `::after`        | Add content after    |
| `::first-letter` | Style first letter   |
| `::first-line`   | Style first line     |

---

## ✍️ Hands-On Exercise

Create a webpage and:

* Add button hover effect
* Style input focus state
* Change first list item color
* Use `::before` & `::after`
* Style paragraph first letter

---

## 📝 Homework

Design an **Interactive Article Page**:

✔ Create styled button hover
✔ Add input focus effect
✔ Use `::before` or `::after` on heading
✔ Style first paragraph letter
✔ Use pseudo selectors creatively

---

[← Previous Day](day-2.md) | [Back to Week 2](README.md) | [Next Day →](day-4.md)
