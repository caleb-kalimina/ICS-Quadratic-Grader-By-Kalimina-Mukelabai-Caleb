 # Quadratic Solver & Grading System

This project is part of the *ICT251 Web Technologies* assignment.  
It is a single-page web app built using *HTML, CSS, and JavaScript* that:

1. Solves a quadratic equation of the form *ax² + bx + c = 0*.  
2. Converts a numeric score (0–100) to a letter grade using the given scale.

---

## 🧮 Quadratic Solver
- Enter values for *a, **b, and **c*.
- The program displays:
  - The *discriminant (D = b² - 4ac)*
  - The *nature of the roots*
  - The *root values* (real or complex)
- Validation ensures that a ≠ 0 and all inputs are valid numbers.

---

## 🎓 Grading System
- Enter a *score (0–100)*.
- The app displays the corresponding *letter grade* using this scale:

| Score Range | Grade |
|--------------|--------|
| 85–100 | A+ |
| 75–84 | A |
| 65–74 | B+ |
| 60–64 | B |
| 55–59 | C+ |
| 50–54 | C |
| 0–49  | D |

Example:  
- Score *82 → Grade A*  
- Score *49 → Grade D*

---

## ⚙ How to Run
1. Download or clone this repository.
2. Open the file *index.html* in any browser.
3. The app works fully offline — no server needed.

---

## 🧠 Test Cases

| Test | Input (a,b,c) | Expected Output |
|------|----------------|----------------|
| 1 | 1, -3, 2 | D=1 → Two roots: 2, 1 |
| 2 | 1, 2, 1 | D=0 → One root: -1 |
| 3 | 1, 0, 1 | D=-4 → Complex roots: 0 ± 1i |

| Score | Expected Grade |
|--------|----------------|
| 85 | A+ |
| 75 | A |
| 65 | B+ |
| 60 | B |
| 55 | C+ |
| 50 | C |
| 49 | D |

---

## 👨‍💻 Author
*Kalimina Mukelabai Caleb*

ICT251 — Web Technologies
