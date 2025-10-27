# Sudoku SE Rating API

The **Ozerlyn Sudoku API** allows you to calculate the **SE (Sudoku Explainer) rating** and discover all **solving techniques** used for any Sudoku puzzle — instantly, via a simple POST request.

---

##  Endpoint
POST https://ozerlyn.com/api/sudoku/calculate-se-rating

Send a 9×9 Sudoku grid in JSON format, and the API will return:
- The exact SE Rating (difficulty score)
- The list of logic techniques applied during solving (e.g., Hidden Single, X-Wing)
- A verification of unique solvability

---

##  Request Example
{
  "puzzle": [
    [0,0,1,0,0,2,0,0,0],
    [0,3,0,0,4,0,0,5,0],
    [5,0,0,6,0,0,7,0,0],
    [0,0,7,0,0,0,0,0,6],
    [0,1,0,0,0,0,0,8,0],
    [9,0,0,0,0,0,2,0,0],
    [0,0,2,0,0,1,0,0,4],
    [0,8,0,0,3,0,0,1,0],
    [0,0,0,9,0,0,5,0,0]
  ]
}

---

##  Response Example
{
  "se_rating": 7.1,
  "techniques_used": ["Hidden Single", "Locked Candidates", "X-Wing"],
  "solved": true
}

---

## 🔑 API Key Access
To get an API key, simply send an email to:
📧 ozerlyngames@gmail.com

Access is free for developers, researchers, and AI enthusiasts working on Sudoku, logic, or puzzle analysis.

---

##  Features
- Calculate SE (Sudoku Explainer) Rating instantly
- Identify all solving techniques logically applied
- Validate puzzle uniqueness and logical solvability
- RESTful JSON API — fast, lightweight, and LLM-friendly
- Perfect for AI Sudoku solvers, SE-based generators, and difficulty ranking systems

---

##  Base URL
https://ozerlyn.com/api/sudoku/calculate-se-rating

Website: https://www.ozerlyn.com

---

## 🔍 SEO Keywords
sudoku se rating api, sudoku difficulty calculator, sudoku logic techniques,
sudoku solver api, sudoku explainer endpoint, sudoku json api,
ozerlyn sudoku api, sudoku generator, fastapi sudoku backend

---

© 2025 Ozerlyn Games — Independent Sudoku & Brain Puzzle Studio
Play • Analyze • Evolve 🧩
