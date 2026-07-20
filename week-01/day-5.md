# 📅 Day 5 — Table tags , HTML From Tag & Semantic and Non-Semantic Tags

## 🎯 Today's Goals

* Learn table Tags
* Understand what an HTML form is
* Use the `<form>` tag
* Create different input fields
* Build a simple registration form
* Semantic and Non-Semantic Tags

---
## 📖 Lesson Content

### 1. Table Tags

```html id="p1t4e6"
<table bord="1">

<caption>Student Data</caption>

<thead>
<tr>
<th>Name</th>
<th>Class</th>
</tr>
</thead>

<tbody>
<tr>
<td>Ali</td>
<td>8</td>
</tr>
</tbody>

<tfoot>
<tr>
<td colspan="2">End</td>
</tr>
</tfoot>

</table>
```
---

## 2. Main Form Tag

The `<form>` tag is used to create a form in HTML.

```html
<form>
</form>
```
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

## 3. Important Form Tags

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

## 4. Input Types

### Text Input

```html
<input type="text">
```

### Email Input

```html
<input type="email">
```

### Password Input

```html
<input type="password">
```

### Number Input

```html
<input type="number">
```

### Radio Button

```html
<input type="radio">
```

### Checkbox

```html
<input type="checkbox">
```

### Submit Button

```html
<input type="submit">
```
---

## 5. What are Semantic and Non-Semantic Tags?

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
---

## Non-Semantic Tags

Non-semantic tags do not describe the meaning of the content.

👉 They are mainly used for layout and styling.

### Examples of Non-Semantic Tags

```html id="n7p2x5"
<div></div>
<span></span>
```
---

## 6. Difference Between Semantic and Non-Semantic Tags

| Semantic Tags                    | Non-Semantic Tags           |
| -------------------------------- | --------------------------- |
| Describe meaning of content      | Do not describe content     |
| Better for SEO                   | Mainly for styling/layout   |
| Easy to understand               | Generic containers          |
| Examples: `<header>`, `<footer>` | Examples: `<div>`, `<span>` |

---

## 7. Void / Empty Tags List

* `<br>` → line break
* `<hr>` → horizontal line
* `<img>` → image
* `<input>` → input field
* `<meta>` → metadata
* `<link>` → CSS file connect
* `<area>` → image map area
* `<col>` → table column settings
---

## 8.  Types of Tags

### 1. Container Tags

* These have both opening and closing tags.

```html id="8ks6pk"
<p>Hello</p>
<div></div>
```
----

### 2. Empty/Void Tags

* These do not have closing tags.

```html id="j5h4fd"
<br>
<img>
<hr>
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

[← Previous Day](day-4.md) | [Back to Week 01](./README.md) | [Next Week →](../week-2/README.md)