# NJ Driver Knowledge Test — Practice App

A single-file, offline-capable web app for practicing the New Jersey driver
knowledge test. 222 real questions with answer explanations, multiple study
modes, and progress tracking.

**Live app:** open [`index.html`](./index.html) in any browser, or enable
GitHub Pages on this repo and visit the served URL on mobile or desktop.

## Features

- **222 questions** with explanations, sourced from 4 NJ practice exams + a
  200-question pro set + 22 questions extracted from real NJ Permit Practice
  screenshots.
- **Exam countdown** — live timer to your test date.
- **Practice modes:**
  - 📖 **Study Mode** — sequential walk-through with instant explanations.
  - 📝 **Mock Exam** — 50 random questions, 20-minute timer, 80% pass mark
    (matches the real NJ test format).
  - 🔁 Review Wrong · 🚩 Flagged · ✅ Mastered Quiz · 🔀 Shuffle All.
  - 📚 Category-based practice (Alcohol, GDL, Trucks, Signs, etc.).
  - 🔍 Full-text search across the question bank.
- **Study Tools:**
  - 🃏 **Flashcards** with 3D flip, deck filters, and quick-rate.
  - 🗺️ **Mind Map** — every category as a clickable node with mastery progress.
  - 🎯 **Mini Quizzes** — 22 quick 10-question quizzes, best-score tracked.
- **Mobile + desktop responsive**, dark/light theme, keyboard shortcuts
  (`1`–`4`, `←/→`, `F` to flag).
- **All progress saved locally** via `localStorage` — no account, no backend.

## Files

| File | Purpose |
|------|---------|
| [`index.html`](./index.html) | The main app (single file, no build step). |
| [`nj-driver-test.html`](./nj-driver-test.html) | Earlier version, kept for reference. |
| `Picture of Sheikh Md Faysal.jpeg` | Developer credit photo shown in the footer. |

## Use it on mobile

1. Open this repo on your phone, tap `index.html`, then "View raw" to open it
   in the browser.
2. Or enable **GitHub Pages** (Settings → Pages → Deploy from `main` branch,
   root folder) and use the served URL.
3. Add to Home Screen for an app-like experience — everything works offline
   after first load.

---

Built by **Sheikh Md Faysal** (AmiSober). Good luck on test day! 🚗
