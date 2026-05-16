# **Week 2: HTML Form , CSS introduction and properties** | [NextGen Arts](https://nextgenarts.pk?utm_source=chatgpt.com)

---
## 📋 Prerequisites

- Completed Week 1 HTML fundamentals
- Personal bio page built in HTML

---

## 🎯 Week 2 Goals

* HTML Form tags and Input Types
* What is GitHub and why is it used?
* What is CSS and what are its types?
* CSS properties

---

# 📅 Day 1 — Introduction to Web Development and Internet

## 🎯 Today's Goals

* HTML Forms
* Semantic and Non-Semantic Tags

## 📖 Lesson Content

* Understand what an HTML form is
* Use the `<form>` tag
* Create different input fields
* Build a simple registration form

---

# Introduction

HTML forms are used to collect user data such as:

* Name
* Email
* Password
* Phone Number

Forms are commonly used in:

* Login pages
* Registration pages
* Contact forms

---

# Main Form Tag

The `<form>` tag is used to create a form in HTML.

```html
<form>
</form>
```

---

# Important Form Tags

| Tag          | Purpose              |
| ------------ | -------------------- |
| `<form>`     | Creates the form     |
| `<input>`    | Creates input fields |
| `<label>`    | Adds labels          |
| `<textarea>` | Multi-line text      |
| `<button>`   | Creates buttons      |
| `<select>`   | Dropdown menu        |
| `<option>`   | Dropdown options     |

---

# Input Types

## Text Input

```html
<input type="text">
```

## Email Input

```html
<input type="email">
```

## Password Input

```html
<input type="password">
```

## Number Input

```html
<input type="number">
```

## Radio Button

```html
<input type="radio">
```

## Checkbox

```html
<input type="checkbox">
```

## Submit Button

```html
<input type="submit">
```

---

## Simple Form Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>Simple Form</title>
</head>
<body>

    <form>
        <label>Name:</label>
        <input type="text"><br><br>

        <label>Email:</label>
        <input type="email"><br><br>

        <label>Password:</label>
        <input type="password"><br><br>

        <button type="submit">Submit</button>
    </form>

</body>
</html>
```

---

## Difference Between Semantic and Non-Semantic Tags

| Semantic Tags                    | Non-Semantic Tags           |
| -------------------------------- | --------------------------- |
| Describe meaning of content      | Do not describe content     |
| Better for SEO                   | Mainly for styling/layout   |
| Easy to understand               | Generic containers          |
| Examples: `<header>`, `<footer>` | Examples: `<div>`, `<span>` |

## What are Semantic and Non-Semantic Tags?

### Semantic Tags

Semantic tags are HTML tags that clearly describe the meaning of the content.

👉 These tags tell both the browser and developer what the content represents.

### Examples of Semantic Tags

```html id="v1k8m3"
<header></header>
<nav></nav>
<section></section>
<article></article>
<footer></footer>
<main></main>
```

### Benefits of Semantic Tags

* Better website structure
* Easy to read and understand
* Improves SEO
* Helps screen readers and accessibility

---

## Non-Semantic Tags

Non-semantic tags do not describe the meaning of the content.

👉 They are mainly used for layout and styling.

### Examples of Non-Semantic Tags

```html id="n7p2x5"
<div></div>
<span></span>
```

### Why They Are Called Non-Semantic?

Because they do not explain what content is inside them.

Example:

```html id="k4m9t1"
<div>This is content</div>
```

Here, `<div>` does not tell whether it is a header, footer, or section.

---

## Difference Between Semantic and Non-Semantic Tags

| Semantic Tags                    | Non-Semantic Tags           |
| -------------------------------- | --------------------------- |
| Describe meaning of content      | Do not describe content     |
| Better for SEO                   | Mainly for styling/layout   |
| Easy to understand               | Generic containers          |
| Examples: `<header>`, `<footer>` | Examples: `<div>`, `<span>` |

---

## Simple Example

```html id="z5x8c2"
<header>
   <h1>My Website</h1>
</header>

<section>
   <p>This is semantic content.</p>
</section>

<div>
   This is non-semantic content.
</div>
```
---

## ✍️ Hands-On Exercise

Students will create:

* A Login Form
* A Registration Form

Using:

* Text input
* Email input
* Password input
* Submit button

---

# Homework

Create a Student Registration Form using:

* Name
* Email
* Phone Number
* Gender
* Submit Button

---

# Conclusion

Today we learned:

* What HTML forms are
* Form tags
* Input types
* How to create a simple form

---
### HTML ends here with this, And add this to the Week 1 assignment.

---
[← Previous Day](../week-1/day-06.md) | [Back to Week 2](README.md) | [Next Day →](day-2.md)

