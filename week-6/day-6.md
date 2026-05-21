# 🧪 Week 9 — Weekly Task Project

# 🎯 Project Title

## Student Information & Result Checker

---

# 📘 Project Objective

Create a JavaScript program that uses:

- Variables
- Data Types
- Operators
- Conditional Statements
- Loops

to build a simple student result checking system.

---

# 🧠 Concepts Used

✅ Variables  
✅ `let`, `const`  
✅ Data Types  
✅ Arithmetic Operators  
✅ Comparison Operators  
✅ Logical Operators  
✅ `if else` Conditions  
✅ Loops

---

# 📋 Project Requirements

Your program should:

1. Store student information
2. Store marks of 3 subjects
3. Calculate total marks
4. Calculate average
5. Check pass or fail
6. Print grade
7. Use loop to print subject numbers

---

# 💻 Project Code

```javascript
// Student Information

let studentName = "Sameer";
const rollNumber = 101;

let math = 80;
let english = 75;
let science = 90;

// Total Marks

let total = math + english + science;

// Average

let average = total / 3;

// Print Information

console.log("Student Name:", studentName);
console.log("Roll Number:", rollNumber);

console.log("Math:", math);
console.log("English:", english);
console.log("Science:", science);

console.log("Total Marks:", total);
console.log("Average:", average);

// Grade System

if (average >= 80) {
  console.log("Grade: A");
} else if (average >= 60) {
  console.log("Grade: B");
} else if (average >= 40) {
  console.log("Grade: C");
} else {
  console.log("Fail");
}

// Loop Example

for (let i = 1; i <= 5; i++) {
  console.log("Subject Number:", i);
}
```

---

# 📝 Expected Output

```javascript
Student Name: Sameer
Roll Number: 101

Math: 80
English: 75
Science: 90

Total Marks: 245
Average: 81.6

Grade: A

Subject Number: 1
Subject Number: 2
Subject Number: 3
Subject Number: 4
Subject Number: 5
```

---

# 🚀 Bonus Challenges

1. Add more subjects
2. Create percentage calculator
3. Check even or odd numbers
4. Create login system
5. Print multiplication table using loops

---

# 📚 Learning Outcomes

After completing this project, students will be able to:

✅ Store data using variables  
✅ Use different data types  
✅ Perform calculations using operators  
✅ Apply conditions using `if else`  
✅ Use loops for repetition  
✅ Build beginner JavaScript programs
