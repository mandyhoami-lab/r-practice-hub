# R Practice Hub

Flashcards, typing drills, quizzes, a real R console (via WebR), and etymology tables for learning R — built for STAT 200 (Intro to Data Science with R).

Live at [amandata.dev/stat200-practice.html](https://amandata.dev/stat200-practice.html). Open `index.html` here for the standalone version.

## What's inside

- **5 units** — R basics, Programming, Wrangling, Visualization, Modeling & inference
- **~72 flashcards** with tap-to-flip cards
- **50 typing drills** — plain-English prompt, you type the R code
- **40 multiple-choice quizzes** — midterm-style, with explanations
- **~37 etymology entries** — where R names come from (`dplyr`, `ggplot2`, `magrittr`…)
- **Code lab** — a real R console in the browser (WebR/WebAssembly)

## Run it

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000

## Files

| File | What it is |
|---|---|
| `index.html` | Standalone hub page |
| `stat200-data.js` | All content: `window.STAT200` |
| `stat200-drills.js` | Typing drill engine (`window.StatDrills`) |
| `stat200-quiz.js` | Quiz engine (`window.StatQuiz`) |
| `stat200-code.js` | WebR code runner (`window.StatCode`) |
| `stat200.css` | Hub styles |
| `flashcards.css` | Card flip styles |
