# 📅 Day 5 — Merge & Conflict Handling

## 🎯 Today's Goals

* Merge branches
* Understand merge conflicts
* Resolve conflicts safely

---

## 📖 Lesson Content

### Merge Branch

Switch to main:

```bash
git switch main
```

Merge branch:

```bash
git merge feature-navbar
```

---

### Merge Conflict Example

Git may show:

```bash
CONFLICT (content): Merge conflict in style.css
```

```bash
git add .
git commit -m "Resolved merge conflict"
```

---

## ✍️ Hands-On Exercise

* Create conflict intentionally
* Resolve conflict manually

---

## 📝 Homework

Create 2 branches editing same file and resolve conflict.

[← Day 1](day-4.md) | [Back to Week 5](README.md) | [Day 3 →](day-6.md)
