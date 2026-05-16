# 📅 Day 6 — Visual Effect

# 🎯 Today's Goals

* Learn advanced CSS visual effects
* Understand modern UI styling properties
* Create attractive and interactive designs
* Improve user experience with animations and effects

---

# 📖 Lesson Content

## 1. CSS Gradient Background

Gradients are used to create smooth color transitions.

### Linear Gradient

```css id="g1a9k2"
background: linear-gradient(to right, blue, purple);
```

✔ Used for modern backgrounds (buttons, cards, banners)

---

## 2. Radial Gradient

```css id="r4m8p1"
background: radial-gradient(circle, yellow, orange);
```

✔ Creates circular color effects

---

## 3. CSS Blur Effect (Backdrop Filter)

```css id="b7x2k9"
backdrop-filter: blur(10px);
```

✔ Used in glassmorphism UI design

---

## 4. CSS Opacity Hover Effect

```css id="o5t3n6"
.card:hover{
   opacity: 0.8;
}
```

✔ Makes elements fade on hover

---

## 5. CSS Box Shadow Advanced

```css id="s9v1m4"
box-shadow: 0px 10px 25px rgba(0,0,0,0.3);
```

✔ Used for floating card effects

---

## 6. CSS Transform Scale + Rotate

```css id="t2p7x5"
transform: scale(1.1) rotate(3deg);
```

✔ Makes elements interactive and dynamic

---

## 7. CSS Animation

### Simple Fade Animation

```css id="a6k9v2"
@keyframes fadeIn {
   from {
      opacity: 0;
   }
   to {
      opacity: 1;
   }
}
```

```css id="a6k9v3"
.box{
   animation: fadeIn 2s ease-in-out;
}
```

✔ Used for smooth loading effects

---

## 8. CSS Hover Glow Effect

```css id="h8m3c7"
button:hover{
   box-shadow: 0px 0px 15px cyan;
}
```

✔ Gives glowing modern UI effect

---

## 9. CSS Border Gradient (Advanced UI)

```css id="b3v8n1"
border: 2px solid;
border-image: linear-gradient(to right, red, blue) 1;
```

✔ Used in modern cards and dashboards

---

## 10. CSS Glassmorphism Effect

```css id="g7p2x9"
background: rgba(255,255,255,0.1);
backdrop-filter: blur(10px);
border-radius: 15px;
```

✔ Used in modern app UI design

---

# 📦 Modern UI Example (Advanced Card)

```html id="m9k2v8"
<!DOCTYPE html>
<html>
<head>
<style>

body{
   background: linear-gradient(to right, #4facfe, #00f2fe);
   display: flex;
   justify-content: center;
   align-items: center;
   height: 100vh;
}

.card{
   width: 300px;
   padding: 25px;
   background: rgba(255,255,255,0.2);
   backdrop-filter: blur(10px);
   border-radius: 15px;
   box-shadow: 0px 10px 25px rgba(0,0,0,0.3);
   text-align: center;
   transition: 0.3s ease;
}

.card:hover{
   transform: scale(1.05) rotate(2deg);
   box-shadow: 0px 15px 35px rgba(0,0,0,0.4);
}

button{
   padding: 10px 15px;
   border: none;
   border-radius: 8px;
   background: linear-gradient(to right, blue, purple);
   color: white;
   cursor: pointer;
   transition: 0.3s ease;
}

button:hover{
   box-shadow: 0px 0px 15px cyan;
}

</style>
</head>

<body>

<div class="card">
   <h2>Modern UI Card</h2>
   <p>This card uses advanced CSS visual effects.</p>
   <button>Click Me</button>
</div>

</body>
</html>
```

---

## ✍️ Hands-On Exercise

Create:

* One gradient background page
* One glassmorphism card
* One glowing button
* One hover animation effect

---

# 📝 Homework

Apply these properties to your assignment.
Design a modern UI landing page using:

* Gradients
* Box shadow
* Hover effects
* Glassmorphism
* Animations

---
[← Previous Day](day-5.md) | [Back to Week 2](README.md) | [Next Week →](../week-3/README.md)