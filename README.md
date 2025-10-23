# ICS-Quadratic-Grader-Nachilyango-Nambela
##  Project Description
A single-page web application built with HTML, CSS, and JavaScript that provides two main functionalities:
1. **Quadratic Equation Solver** - Solves equations of the form ax² + bx + c = 0
2. **Score to Grade Converter** - Converts numeric scores (0-100) to letter grades

This project was created as part of the ICT251 Web Technologies course assignment.

##  How to Run
1. Download or clone this repository
2. Open the `index.html` file in any modern web browser (Chrome, Firefox, Safari, Edge)
3. No installation or setup required - runs completely offline!

Alternatively, you can view it directly on GitHub Pages (if enabled).

##  Features

### Quadratic Solver
- Input three coefficients (a, b, c)
- Validates that 'a' is not zero
- Calculates and displays:
  - Discriminant value
  - Nature of roots (real distinct, repeated, or complex)
  - Root values with 4 decimal places
- Clear error messages for invalid inputs
- Reset button to clear all fields

### Grade Calculator
- Input score from 0 to 100
- Validates input range
- Returns letter grade based on exact criteria:
  - A+: 85-100
  - A: 75-84
  - B+: 65-74
  - B: 60-64
  - C+: 55-59
  - C: 50-54
  - D: 0-49
- Provides encouraging feedback messages

##  Test Cases

###  Quadratic Solver Test Cases:
1. **Two distinct real roots**: a=1, b=-5, c=6
   - Expected: x₁ = 3, x₂ = 2
2. **One repeated root**: a=1, b=-4, c=4
   - Expected: x = 2
3. **Complex roots**: a=1, b=0, c=4
   - Expected: x₁ = 0 + 2i, x₂ = 0 - 2i
4. **Invalid input**: a=0 (should show error)

###  Grade Calculator Test Cases:
- Score 100 → A+
- Score 85 → A+
- Score 84 → A
- Score 75 → A
- Score 74 → B+
- Score 65 → B+
- Score 64 → B
- Score 60 → B
- Score 59 → C+
- Score 55 → C+
- Score 54 → C
- Score 50 → C
- Score 49 → D
- Score 0 → D
- Score -1 or 101 → Error

## Technologies Used
- HTML5
- CSS3 (with gradient backgrounds and modern styling)
- Vanilla JavaScript (ES6+)

## Repository Structure
ICS-Quadratic-Grader-[Nachilyango-Nambela]/ ├── index.html (Complete web application) └── README.md (This file)
##  Author
[Nambela Nachilyango]
ICT251 - Web Technologies

