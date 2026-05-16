# 📅 Day 3 — What is CSS and what are its types? , CSS properties

# 🎯 Today's Goals

* Learn what CSS is
* Learn types of CSS
* Learn CSS properties
* Apply styles to HTML elements

---

# 📖 Lesson Content

## 1. What is CSS?

CSS stands for **Cascading Style Sheets**.

CSS is used to:

* Change colors
* Add designs
* Style webpages
* Make websites attractive

---

## 2. Types of CSS

### Inline CSS

```html 
<p style="color: red;">Hello World</p>
```

---

### Internal CSS

```html id="g7m3p9"
<style>
h1{
   color: blue;
}
</style>
```

---

### External CSS

```html id="n5q2w4"
<link rel="stylesheet" href="style.css">
```

---
## # 🎯 Today's Goals

* Learn what Class and ID are in HTML & CSS
* Understand the difference between Class and ID
* Learn how to use Class and ID in styling
* Apply Class and ID in a simple example

---

## 3. What is Class?

A **class** is an HTML attribute used to group multiple elements and apply the same styling.

👉 Simple meaning:
Class is used when we want to style multiple elements in the same way.

### Example:

```html id="c1a9k3"
<p class="text">Hello</p>
<p class="text">World</p>
```

```css id="s7m2p8"
.text{
   color: blue;
}
```

✔ One class can be used on multiple elements.

---

## 4. What is ID?

An **ID** is an HTML attribute used to uniquely identify a single element.

👉 Simple meaning:
ID is used for only one unique element on a webpage.

### Example:

```html id="i4x8n2"
<h1 id="heading">Welcome</h1>
```

```css id="d9v3k1"
#heading{
   color: red;
}
```

✔ ID should be used only once on a page.

---

## 5. Difference Between Class and ID

| Class                      | ID                      |
| -------------------------- | ----------------------- |
| Used for multiple elements | Used for single element |
| Reusable                   | Unique                  |
| CSS selector: `.` dot      | CSS selector: `#` hash  |
| Example: `.box`            | Example: `#box`         |

---

## 6. Simple Example

```html id="e8m3t6"
<div class="box">Box 1</div>
<div class="box">Box 2</div>

<h1 id="title">Main Title</h1>
```

```css id="k5p9v2"
.box{
   background-color: yellow;
}

#title{
   text-align: center;
}
```
---

## 7. CSS Properties

### Color Property

```
color: red;
```

Changes text color.

---

### Background Color

```css 
background-color: yellow;
```

Changes background color.

---

### Font Size

```css 
font-size: 20px;
```

Changes text size.

---

### Text Align

```css 
text-align: center;
```

Aligns text.

---

### Border Property

```css 
border: 2px solid black;
```

Adds border around elements.

---

### Padding Property

```css 
padding: 10px;
```

Adds space inside elements.

---

### Margin Property

```css 
margin: 20px;
```

Adds outside spacing.

---

## 8. Simple CSS Example

```html 
<!DOCTYPE html>
<html>
<head>
<style>
h1{
   color: blue;
   text-align: center;
}

p{
   font-size: 20px;
   background-color: lightgray;
}
</style>
</head>

<body>

<h1>Welcome</h1>
<p>This is CSS Example</p>

</body>
</html>
```

---

## ✍️ Hands-On Exercise

Create:

* One heading with color
* One paragraph with background color
* One bordered box
* One centered text

---

# 📝 Homework

Apply these properties to your assignment.

* Heading
* Paragraph
* Background color
* Border
* Font size

---
[← Previous Day](day-2.md) | [Back to Week 2](README.md) | [Next Day →](day-4.md)