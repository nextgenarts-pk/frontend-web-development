# Week 6 — JavaScript Basics: 4 Projects + Assignment

> Pure JavaScript · No DOM · Only variables, data types, operators, string methods, console.log()

---

## ✅ Project 1 — Console Calculator

```js
// ===== CONSOLE CALCULATOR =====

// Step 1: Store the two numbers
const num1 = 24;
const num2 = 6;

// Step 2: Perform all operations
const add = num1 + num2;
const subtract = num1 - num2;
const multiply = num1 * num2;
const divide = num1 / num2;
const remainder = num1 % num2;
const power = num1 ** 2;

// Step 3: Check if divisible (boolean)
const isDivisible = num1 % num2 === 0;

// Step 4: Display results using template literals
console.log(`====== CALCULATOR ======`);
console.log(`Numbers: ${num1} and ${num2}`);
console.log(`------------------------`);
console.log(`Addition:       ${num1} + ${num2} = ${add}`);
console.log(`Subtraction:    ${num1} - ${num2} = ${subtract}`);
console.log(`Multiplication: ${num1} x ${num2} = ${multiply}`);
console.log(`Division:       ${num1} / ${num2} = ${divide}`);
console.log(`Remainder:      ${num1} % ${num2} = ${remainder}`);
console.log(`Power:          ${num1}² = ${power}`);
console.log(`------------------------`);
console.log(`Divisible: ${isDivisible}`);
console.log(`========================`);
```

**Expected Output:**

```
====== CALCULATOR ======
Numbers: 24 and 6
------------------------
Addition:       24 + 6 = 30
Subtraction:    24 - 6 = 18
Multiplication: 24 x 6 = 144
Division:       24 / 6 = 4
Remainder:      24 % 6 = 0
Power:          24² = 576
------------------------
Divisible: true
========================
```

---

## ✅ Project 2 — Student Report

```js
// ===== STUDENT REPORT =====

// Step 1: Student information
const studentName = "Ali Ahmed";
const rollNumber = 14;
const className = "8-A";
const school = "Skardu Public School";

// Step 2: Subject marks
const math = 88;
const english = 76;
const science = 92;
const urdu = 85;
const islamiat = 95;

// Step 3: Calculations
const totalMarks = math + english + science + urdu + islamiat;
const totalPossible = 500;
const percentage = (totalMarks / totalPossible) * 100;
const average = totalMarks / 5;

// Step 4: Grade using comparison
const isPassed = percentage >= 50;
const isDistinction = percentage >= 80;

// Step 5: String methods on name
const upperName = studentName.toUpperCase();
const nameLength = studentName.length;

// Step 6: Display report
console.log(`========================================`);
console.log(`           STUDENT REPORT CARD          `);
console.log(`========================================`);
console.log(`School:      ${school}`);
console.log(`Name:        ${upperName}`);
console.log(`Roll No:     ${rollNumber}`);
console.log(`Class:       ${className}`);
console.log(`----------------------------------------`);
console.log(`Math:        ${math}/100`);
console.log(`English:     ${english}/100`);
console.log(`Science:     ${science}/100`);
console.log(`Urdu:        ${urdu}/100`);
console.log(`Islamiat:    ${islamiat}/100`);
console.log(`----------------------------------------`);
console.log(`Total:       ${totalMarks}/${totalPossible}`);
console.log(`Percentage:  ${percentage}%`);
console.log(`Average:     ${average}`);
console.log(`Passed:      ${isPassed}`);
console.log(`Distinction: ${isDistinction}`);
console.log(`Name Length: ${nameLength} characters`);
console.log(`========================================`);
```

**Expected Output:**

```
========================================
           STUDENT REPORT CARD
========================================
School:      Skardu Public School
Name:        ALI AHMED
Roll No:     14
Class:       8-A
----------------------------------------
Math:        88/100
English:     76/100
Science:     92/100
Urdu:        85/100
Islamiat:    95/100
----------------------------------------
Total:       436/500
Percentage:  87.2%
Average:     87.2
Passed:      true
Distinction: true
Name Length: 9 characters
========================================
```

---

## ✅ Project 3 — Unit Converter

```js
// ===== UNIT CONVERTER =====

// Step 1: Base value to convert
const kilometers = 10;
const kilograms = 75;
const celsius = 37;
const hours = 3;

// Step 2: Conversion formulas (arithmetic operators)

// Distance
const meters = kilometers * 1000;
const centimeters = kilometers * 100000;
const miles = kilometers * 0.621371;

// Weight
const grams = kilograms * 1000;
const pounds = kilograms * 2.20462;

// Temperature
const fahrenheit = (celsius * 9) / 5 + 32;
const kelvin = celsius + 273.15;

// Time
const minutes = hours * 60;
const seconds = hours * 3600;

// Step 3: Type check (typeof)
const kmType = typeof kilometers;
const mileType = typeof miles;

// Step 4: Display results
console.log(`========================================`);
console.log(`          UNIT CONVERTER                `);
console.log(`========================================`);
console.log(`--- DISTANCE ---`);
console.log(`${kilometers} km = ${meters} meters`);
console.log(`${kilometers} km = ${centimeters} centimeters`);
console.log(`${kilometers} km = ${miles.toFixed(2)} miles`);
console.log(`--- WEIGHT ---`);
console.log(`${kilograms} kg = ${grams} grams`);
console.log(`${kilograms} kg = ${pounds.toFixed(2)} pounds`);
console.log(`--- TEMPERATURE ---`);
console.log(`${celsius}°C = ${fahrenheit}°F`);
console.log(`${celsius}°C = ${kelvin}K`);
console.log(`--- TIME ---`);
console.log(`${hours} hours = ${minutes} minutes`);
console.log(`${hours} hours = ${seconds} seconds`);
console.log(`--- DATA TYPES ---`);
console.log(`typeof kilometers: ${kmType}`);
console.log(`typeof miles: ${mileType}`);
console.log(`========================================`);
```

**Expected Output:**

```
========================================
          UNIT CONVERTER
========================================
--- DISTANCE ---
10 km = 10000 meters
10 km = 1000000 centimeters
10 km = 6.21 miles
--- WEIGHT ---
75 kg = 75000 grams
75 kg = 165.35 pounds
--- TEMPERATURE ---
37°C = 98.6°F
37°C = 310.15K
--- TIME ---
3 hours = 180 minutes
3 hours = 10800 seconds
--- DATA TYPES ---
typeof kilometers: number
typeof miles: number
========================================
```

---

## ✅ Project 4 — Shopping Bill

```js
// ===== SHOPPING BILL =====

// Step 1: Store items (string + number)
const item1 = "Notebook";
const price1 = 150;
const qty1 = 3;

const item2 = "Pen";
const price2 = 20;
const qty2 = 5;

const item3 = "Geometry Box";
const price3 = 350;
const qty3 = 1;

const shopName = "  Ali Stationery  ";
const customerName = "  sara khan  ";

// Step 2: String methods
const cleanShop = shopName.trim().toUpperCase();
const cleanCustomer = customerName.trim().toUpperCase();
const shopLength = shopName.trim().length;

// Step 3: Calculations (arithmetic operators)
const total1 = price1 * qty1;
const total2 = price2 * qty2;
const total3 = price3 * qty3;

const subtotal = total1 + total2 + total3;
const tax = subtotal * 0.1; // 10% tax
const discount = subtotal * 0.05; // 5% discount
const grandTotal = subtotal + tax - discount;

// Step 4: Boolean checks
const isExpensive = grandTotal > 500;
const hasTax = tax > 0;

// Step 5: typeof check
console.log(`Type of price1: ${typeof price1}`);
console.log(`Type of item1:  ${typeof item1}`);

// Step 6: Display the bill
console.log(`========================================`);
console.log(`         ${cleanShop}         `);
console.log(`========================================`);
console.log(`Customer: ${cleanCustomer}`);
console.log(`Shop name length: ${shopLength} characters`);
console.log(`----------------------------------------`);
console.log(`Item           Qty   Price    Total`);
console.log(`----------------------------------------`);
console.log(`${item1}        x${qty1}    Rs.${price1}   Rs.${total1}`);
console.log(`${item2}             x${qty2}    Rs.${price2}    Rs.${total2}`);
console.log(`${item3}  x${qty3}    Rs.${price3}  Rs.${total3}`);
console.log(`----------------------------------------`);
console.log(`Subtotal:              Rs.${subtotal}`);
console.log(`Tax (10%):             Rs.${tax}`);
console.log(`Discount (5%):        -Rs.${discount}`);
console.log(`----------------------------------------`);
console.log(`GRAND TOTAL:           Rs.${grandTotal}`);
console.log(`========================================`);
console.log(`Is expensive (>500): ${isExpensive}`);
console.log(`Has tax applied:     ${hasTax}`);
console.log(`========================================`);
console.log(`        Thank you for shopping!         `);
console.log(`========================================`);
```

**Expected Output:**

```
========================================
         ALI STATIONERY
========================================
Customer: SARA KHAN
Shop name length: 15 characters
----------------------------------------
Item           Qty   Price    Total
----------------------------------------
Notebook        x3    Rs.150   Rs.450
Pen             x5    Rs.20    Rs.100
Geometry Box  x1    Rs.350  Rs.350
----------------------------------------
Subtotal:              Rs.900
Tax (10%):             Rs.90
Discount (5%):        -Rs.45
----------------------------------------
GRAND TOTAL:           Rs.945
========================================
Is expensive (>500): true
Has tax applied:     true
========================================
        Thank you for shopping!
========================================
```

---
