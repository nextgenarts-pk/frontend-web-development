# 📅 Day 5 — Visual Effect

# 🎯 Today's Goals

* Learn CSS Visual Effects
* Understand how to make UI more attractive
* Learn shadows, hover effects, and transitions
* Apply modern UI styling effects

---

# 📖 Lesson Content

## 1. What are Visual Effects in CSS?

Visual effects are used to make websites look:

* Modern
* Attractive
* Interactive
* User-friendly

These effects improve UI (User Interface) experience.

---

## 2. Box Shadow

Box shadow is used to add shadow behind elements.

```css id="b1x9k3"
box-shadow: 0px 4px 10px rgba(0,0,0,0.2);
```

✔ Makes elements look like floating cards.

---

## 3. Text Shadow

Text shadow adds shadow to text.

```css id="t7m2p8"
text-shadow: 2px 2px 5px gray;
```

✔ Makes text stand out.

---

## 4. Hover Effect

Hover effect works when mouse is placed on an element.

```css id="h4v8n1"
button:hover{
   background-color: blue;
   color: white;
}
```

✔ Used in buttons, cards, links.

---

## 5. Transition

Transition makes changes smooth.

```css id="c9p3m7"
transition: 0.3s ease;
```

✔ Makes hover effects smooth.

---

## 6. Transform

Transform is used to move or scale elements.

### Scale Effect

```css id="s6k2v9"
transform: scale(1.1);
```

✔ Zooms element on hover.

---

### Move Effect

```css id="m3t8x1"
transform: translateY(-10px);
```

✔ Moves element up or down.

---

## 7. Opacity

Opacity controls transparency.

```css id="o7n5p2"
opacity: 0.5;
```

✔ Makes element light or faded.

---

## 8. Border Radius

Makes corners rounded.

```css id="r2v9k4"
border-radius: 10px;
```

✔ Used in modern UI cards and buttons.

---

# 📦 Modern UI Card Example

```html id="u8m3c6"
<!DOCTYPE html>
<html>
<head>
<style>

.card{
   width: 250px;
   padding: 20px;
   margin: 20px;
   background-color: white;
   border-radius: 15px;
   box-shadow: 0px 4px 10px rgba(0,0,0,0.2);
   transition: 0.3s ease;
}

.card:hover{
   transform: translateY(-10px);
   box-shadow: 0px 8px 20px rgba(0,0,0,0.3);
}

button{
   padding: 10px;
   border: none;
   border-radius: 8px;
   background-color: black;
   color: white;
   transition: 0.3s ease;
}

button:hover{
   background-color: blue;
}

</style>
</head>

<body>

<div class="card">
   <h2>UI Card</h2>
   <p>This is a modern visual effect card.</p>
   <button>Click Me</button>
</div>

</body>
</html>
```

---

## ✍️ Hands-On Exercise

Create:

* One card with shadow
* One button with hover effect
* One text with shadow
* One smooth transition effect

---

# 📝 Homework

Apply these properties to your assignment.
Design a modern UI card using:

* Box shadow
* Hover effect
* Border radius
* Transition
* Transform effect

---
[← Previous Day](day-4.md) | [Back to Week 2](README.md) | [Next Day →](day-6.md)