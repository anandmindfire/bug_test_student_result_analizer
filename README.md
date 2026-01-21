# 🧪 Student Result Analyzer – 5 Subjects (Bug Finding Challenge)

## 📌 Overview

This project is a **frontend debugging and logic assessment challenge** built using **HTML, CSS, and Vanilla JavaScript**.

Candidates are provided with a partially functional **Student Result Analyzer** application that contains **15+ intentional bugs**. The goal is to **identify, debug, and fix** all issues within a limited time.

This test evaluates:

* JavaScript logic
* Mathematical accuracy
* DOM manipulation
* Validation handling
* Edge case handling
* State consistency
* Debugging skills

---

## ⏱ Time Limit

**30–40 minutes**

---

## 🧩 Features Implemented (Buggy)

The application allows users to manage and analyze student results with **exactly 5 subjects per student**.

---

### Student Entry Fields

Each student entry contains:

* Student Name
* Subject 1 Marks (0–100)
* Subject 2 Marks (0–100)
* Subject 3 Marks (0–100)
* Subject 4 Marks (0–100)
* Subject 5 Marks (0–100)

---

### Displayed Per Student

Each student row should show:

* Name
* Marks for all 5 subjects
* Total Marks (out of 500)
* Average Marks
* Grade (A / B / C)

---

### Dashboard Statistics

The system displays:

* Total number of students
* Class average
* Highest total marks
* Count of Grade A students
* Count of Grade B students
* Count of Grade C students

---

## 📜 Business Rules (Must Be Enforced)

The following rules must be implemented correctly:

1. Student name must not be empty
2. All 5 subject marks must be provided
3. Marks must be between **0 and 100**
4. Marks must be numeric
5. Total = sum of all 5 subjects
6. Average = Total / 5
7. Percentage = (Total / 500) × 100
8. Grade must be calculated correctly:

   * A: ≥ 80%
   * B: ≥ 60% and < 80%
   * C: < 60%
9. Deleting a student must update all statistics
10. Highest marks must always be correct
11. No NaN or undefined values in UI
12. Table must not crash on edge cases
13. All calculations must be accurate
14. Empty student list must not break the UI
15. Stats must recalculate on every add/delete

---

## 🧠 Candidate Tasks

Candidates must:

1. Identify all bugs
2. Fix incorrect calculations
3. Enforce all validation rules
4. Fix delete logic
5. Fix loop and indexing issues
6. Ensure UI never crashes
7. Handle all edge cases
8. Keep state consistent
9. Make all statistics accurate
10. Prevent invalid data from being added

---

## 🚫 Restrictions

* ❌ No external libraries
* ❌ No frameworks
* ❌ No backend
* ❌ No TypeScript

Use only:
✔ HTML
✔ CSS
✔ Vanilla JavaScript

---

## ✅ Bonus (Optional Enhancements)

If time permits, candidates may add:

* Subject-wise toppers
* Color-coded grades
* Sorting by total
* Filtering by grade
* Edit student entries
* Search functionality
* LocalStorage persistence
* Data export (CSV)

---

## 📂 Project Structure

```
/project-root
│
├── index.html
└── README.md
```

---

## 📢 Important Note

This is a **logic-heavy debugging test**, not a UI design challenge.

Focus on:
✔ Correctness
✔ Edge cases
✔ Mathematical accuracy
