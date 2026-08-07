<div align="center">

# 🎓 IMSciences Aggregate Calculator

### A lightweight browser tool for estimating admission aggregate

[![HTML](https://img.shields.io/badge/HTML5-Frontend-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-Styling-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-Calculator-F7DF1E?style=flat-square&logo=javascript&logoColor=111827)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

---

## Overview

This is a small client-side utility created to help prospective **IMSciences** students estimate their admission aggregate from test, interview and first-year/FSc marks.

The project runs entirely in the browser and does not require a backend or database.

> **Note:** This is an unofficial estimation tool. Admission formulas can change, so applicants should always confirm the latest criteria with the university's official admissions information.

---

## Current Formula

The calculator applies the weighting implemented in `scripts.js`:

| Component | Input | Weight |
|---|---:|---:|
| Admission Test | 0–100 | 40% |
| Interview | 0–10 | 10% |
| First-year / FSc marks | 0–600 | 50% |

The final estimate is calculated as:

```text
Aggregate = (Test / 100 × 40)
          + Interview
          + (FSc / 600 × 50)
```

---

## Features

- simple browser-based form
- input-range validation
- weighted aggregate calculation
- instant percentage result
- no installation or server required

---

## Project Structure

```text
ims-aggregate-calculator/
├── index.html      # page structure
├── styles.css      # styling
├── scripts.js      # validation and aggregate calculation
└── README.md
```

---

## Run Locally

Clone the repository:

```bash
git clone https://github.com/najeebafridi/ims-aggregate-calculator.git
cd ims-aggregate-calculator
```

Then open `index.html` directly in a browser.

No package installation is required.

---

## Purpose

This was built as a small student-focused utility and early web-development project. It demonstrates basic DOM interaction, form validation and arithmetic logic with vanilla JavaScript.

---

## Disclaimer

This project is **not an official IMSciences admissions service** and should not be treated as authoritative. The implemented formula reflects the criteria used when the tool was created and may need updating if official admission policy changes.

---

## Author

**Najeeb Ullah**  
AI Engineer & Machine Learning Researcher

[GitHub](https://github.com/najeebafridi)
