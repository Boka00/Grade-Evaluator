# Student Grade Evaluator

## Overview

Student Grade Evaluator is a JavaScript project that demonstrates core programming concepts through a complete student grading system. The application validates scores, calculates averages and weighted grades, processes scores using callbacks, tracks statistics with closures, and generates a final student report.

This project was built as a learning exercise focused on fundamental JavaScript concepts including:

* Control structures
* Operators
* Truthy and falsy values
* Ternary operators
* Arrow functions
* Default parameters
* Higher-order functions
* Callbacks
* Function expressions
* Closures
* Scope
* Template literals

---

## Features

### Part 1 – Grade Validator

* Validate exam scores between 0 and 100.
* Correctly handle falsy values such as `null`, `undefined`, and empty strings.
* Treat `0` as a valid score.
* Convert numeric scores into letter grades.
* Demonstrate the difference between `==` and `===`.

### Part 2 – Score Calculators

* Calculate averages for three or four scores.
* Calculate weighted final scores using:

  * Exam: 60%
  * Homework: 40%
  * Bonus points added afterward
* Determine whether a student is eligible for a retake exam.

### Part 3 – Score Processor

* Apply custom callbacks to validated scores.
* Demonstrate higher-order functions.
* Process multiple scores using reusable logic.

### Part 4 – Score Tracker

* Track:

  * Number of scores entered
  * Running average
  * Highest score
  * Lowest score
* Store state privately using closures.
* Create multiple independent trackers for different subjects.

### Bonus – Final Report

Generate a complete student evaluation report containing:

* Student name
* Exam score
* Homework score
* Bonus points
* Final weighted score
* Letter grade
* Attendance percentage
* Retake eligibility

---

## Example Output

```text
====================================
Student:   Petra Novak
------------------------------------
Exam:       74    (weight: 60%)
Homework:   88    (weight: 40%)
Bonus:       3    pts
Final score: 82.60
Grade:       B
Attendance:  82%
Retake:      No
====================================
```

## Project Structure

```text
grades.js
README.md
```

* `grades.js` – Contains all functions and test cases.
* `README.md` – Project documentation.

---

## Concepts Demonstrated

| Concept                | Usage                             |
| ---------------------- | --------------------------------- |
| Functions              | Validation, calculations, reports |
| Arrow Functions        | Calculator functions              |
| Function Expressions   | Score processing                  |
| Higher-Order Functions | Callback-based processing         |
| Closures               | Score tracker state management    |
| Scope                  | Private tracker variables         |
| Default Parameters     | Optional arguments                |
| Template Literals      | Report formatting                 |
| Conditional Logic      | Grade classification              |
| Ternary Operator       | Pass/Fail decisions               |

---

## Running the Project

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Open the project folder:

```bash
cd <repository-name>
```

3. Run the file with Node.js:

```bash
node grades.js
```

---

## Learning Goals

This project was designed to reinforce essential JavaScript fundamentals by building a realistic grading system. It demonstrates how multiple programming concepts can work together to create a maintainable and reusable application.

---

## Author

Created as a JavaScript learning project focused on functions, callbacks, closures, and data processing.
