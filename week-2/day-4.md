# 📅 Day 4 — Box Model and Padding , Typography Properties

# 🎯 Today's Goals

* Learn CSS Box Model
* Learn Margin and Padding
* Learn Typography Properties
* Apply spacing and text styling

---

# 📖 Lesson Content

## 1. CSS Box Model

The CSS Box Model is used to understand spacing and layout in web design.

It contains:

* Content
* Padding
* Border
* Margin
```
┌─────────────── Margin ───────────────┐
│  ┌─────────── Border ─────────────┐  │
│  │  ┌─────── Padding ──────────┐  │  │
│  │  │  ┌──── Content ───────┐  │  │  │
│  │  │  │   Your text/image  │  │  │  │
│  │  │  └────────────────────┘  │  │  │
│  │  └──────────────────────────┘  │  │
│  └────────────────────────────────┘  │
└──────────────────────────────────────┘
```
---

## 2. Width & Height

### Width Property

```css id="w3k8n1"
width: 300px;
```

Sets element width.

---

### Height Property

```css id="q7m2x5"
height: 150px;
```

Sets element height.

---

## 3. Padding

Padding adds space inside the element.

```css id="p9v4r6"
padding: 20px;
```

---

## 4. Margin

Margin adds space outside the element.

```css id="m5t8y2"
margin: 30px;
```

---

## 5. Border

Border creates a line around the element.

```css id="b2x7k4"
border: 2px solid black;
```

---

## 6. Box Model Example

```html id="z8n1c5"
<div class="box">
   Hello World
</div>
```

```css id="d4v9m7"
.box{
   width: 300px;
   height: 150px;
   padding: 20px;
   margin: 30px;
   border: 3px solid blue;
}
```

---

# 📖 Typography Properties

Typography is used to style text.

---

## 7. Font Size

```css id="f7k3p1"
font-size: 25px;
```

Changes text size.

---

## 8. Font Family

```css id="t5x9m2"
font-family: Arial;
```

Changes text style/font.

---

## 9. Font Weight

```css id="g1v8n4"
font-weight: bold;
```

Makes text bold.

---

## 10. Font Style

```css id="s6m2q9"
font-style: italic;
```

Makes text italic.

---

## 11. Text Align

```css id="a4p7k3"
text-align: center;
```

Aligns text position.

---

## 12. Text Transform

```css id="u8n5x1"
text-transform: uppercase;
```

Changes text case.

---

## 13. Letter Spacing

```css id="l2v6m8"
letter-spacing: 3px;
```

Adds space between letters.

---

## 14. Line Height

```css id="h9k4p2"
line-height: 30px;
```

Controls spacing between lines.

---

## 15. Text Decoration

```css id="e5x7n1"
text-decoration: underline;
```

Adds underline or decoration.

---

# 📖 Complete Example

```html id="r3m8v2"
<!DOCTYPE html>
<html>
<head>
<style>

.box{
   width: 300px;
   padding: 20px;
   margin: 30px;
   border: 2px solid black;
}

h1{
   font-size: 35px;
   font-family: Arial;
   text-align: center;
   text-transform: uppercase;
}

p{
   font-size: 18px;
   line-height: 30px;
   letter-spacing: 2px;
}

</style>
</head>

<body>

<div class="box">
   <h1>CSS Typography</h1>
   <p>This is typography example.</p>
</div>

</body>
</html>
```

---

## ✍️ Hands-On Exercise

Create:

* One box using margin and padding
* One heading with typography styling
* One paragraph with line-height
* One bordered container

---

# 📝 Homework

Apply these properties to your assignment.

* Box Model
* Margin
* Padding
* Border
* Typography Properties

---
[← Previous Day](day-3.md) | [Back to Week 2](README.md) | [Next Day →](day-5.md)