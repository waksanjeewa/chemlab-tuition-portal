# ChemLab — Chemistry Tuition Student Portal

A self-contained, single-file student learning portal for a chemistry tuition. No build step, no server, no dependencies — just open `index.html` in any browser.

**[▶ Open the app](index.html)** (or enable GitHub Pages to host it live)

## Features

- **🔐 Sign in** — name, level and class code; progress is saved per device via `localStorage`
- **🏠 Dashboard** — course-progress ring, average quiz score, topics mastered, study streak, "continue learning" and upcoming classes
- **📘 Lessons** — 6 core topics with real teaching content, worked examples, equation blocks and key-point callouts; mark lessons complete
- **✏️ Quizzes** — auto-graded multiple-choice quizzes per topic with colour-coded feedback; best score saved
- **⚛️ Interactive periodic table** — all 118 elements, colour-grouped by family, tap for element data
- **📎 Resources** — past papers, cheat-sheets and reference material
- **📈 Progress tracking** — per-topic mastery bars and quiz history

Topics covered (O/A-Level): Atomic Structure · Chemical Bonding · The Mole Concept · Acids, Bases & Salts · Rates of Reaction · Intro to Organic.

## Run it

```bash
# just open the file
open index.html          # macOS
# or serve locally
python3 -m http.server   # then visit http://localhost:8000
```

## Tech

Plain HTML, CSS and vanilla JavaScript in one file — fully offline, responsive (mobile drawer nav), dark "lab" theme. State persists in the browser only.

## Roadmap ideas

- Real backend login so students authenticate and material is managed centrally
- Replace sample lessons/quizzes with your own notes and past papers
- Target a specific syllabus (Edexcel IGCSE, Cambridge, IB, Sri Lankan A/L, etc.)
