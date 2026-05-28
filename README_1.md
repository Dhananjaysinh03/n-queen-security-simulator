# 🔒 N-Queen Security Camera Placement Simulator

A visual, interactive simulator that demonstrates the **N-Queens problem** reframed as a **security camera placement challenge** — placing N cameras on an N×N grid such that no camera is in the line-of-sight (row, column, or diagonal) of another.

Built as a college project to visualize **backtracking algorithms** step-by-step.

---

## 🚀 Live Demo

> Open `index.html` in any browser — no server or installation needed.

---

## 📸 Features

- 🎛️ **Board sizes** from 4×4 to 8×8
- ▶️ **Auto-solve** — watch the backtracking algorithm run in real time
- 👣 **Step mode** — advance one step at a time for deeper understanding
- 🖱️ **Manual placement** — click cells to place cameras yourself; conflicts are highlighted
- 📋 **Algorithm log** — every placement, backtrack, and conflict is logged live
- 📐 **Threat zone visualization** — red dots show squares under surveillance
- ✅ **All solutions listed** — click any solution to display it on the board
- ⚡ **Adjustable speed** — from slow (educational) to near-instant

---

## 🧠 Algorithm

The solver uses **backtracking**:

1. Place a camera in the first available safe cell in the current row
2. Move to the next row and repeat
3. If no safe cell exists in the current row → **backtrack** to the previous row and try the next column
4. Continue until all N cameras are placed (a solution) or all possibilities are exhausted

| Metric | Value |
|--------|-------|
| Time Complexity | O(N!) |
| Space Complexity | O(N) |

---

## 📁 Project Structure

```
n-queen-security-simulator/
├── index.html       # Main application (self-contained)
└── README.md        # Project documentation
```

The entire application is a **single HTML file** — HTML, CSS, and JavaScript are all bundled together for maximum portability.

---

## 🎮 How to Use

1. **Clone or download** this repository
2. Open `index.html` in a browser (Chrome, Firefox, Edge, Safari all work)
3. Choose a board size from the dropdown
4. Click **▶ Solve All** to watch the algorithm run automatically
5. Or click **Step →** to advance one step at a time
6. Or click any cell on the board to place cameras manually
7. Found solutions appear in the sidebar — click one to display it

---

## 📚 Concepts Covered

- **N-Queens Problem** (classic constraint satisfaction problem)
- **Backtracking** search strategy
- **Constraint propagation** (threat zone calculation)
- **Combinatorics** — number of solutions grows with board size

| Board | Solutions |
|-------|-----------|
| 4×4   | 2         |
| 5×5   | 10        |
| 6×6   | 4         |
| 7×7   | 40        |
| 8×8   | 92        |

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5      | Structure |
| CSS3       | Styling, animations, CSS variables |
| Vanilla JavaScript | Algorithm, DOM rendering |
| Google Fonts | JetBrains Mono, Sora |

No frameworks. No build tools. No dependencies.

---

## 🏫 College Project Info

- **Subject:** Data Structures & Algorithms (or as applicable)
- **Topic:** Backtracking Algorithms
- **Language:** JavaScript (Vanilla)

---

## 📄 License

This project is open source and free to use for educational purposes.
