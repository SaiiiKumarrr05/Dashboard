# 🚀 CSE Elite Dashboard

A sleek, single-file personal productivity dashboard built for CSE students targeting placements and consistent study discipline.

🔗 **Live Demo → [saikumar-dashboard.vercel.app](https://saikumar-dashboard.vercel.app/)**

---

## ✨ Features

- **📊 Overall Progress Tracker** — Visualizes total task completion across all sections with an animated gradient progress bar
- **🔥 Study Streak** — Tracks your daily study streak with a one-click "+1 Today" button and last-update timestamp
- **⏱ Pomodoro Timer** — Configurable timer with 1-hour, Short (10 min), and Break (15 min) modes; includes animated SVG ring and Start / Pause / Reset controls
- **🏆 Rank Goal Selector** — Choose your target discipline level (Tasks Daily, Daily Aptitude, Good Rank) with persistent selection
- **✅ Checklist Sections** — Multiple categorized task lists with custom checkboxes, per-section progress bars, add/delete tasks, and completion counts
- **📅 Weekly Planner** — 7-day grid with today highlighted, showing scheduled focus areas for each day
- **🎯 Subject Progress Circles** — Animated SVG donut charts displaying progress per subject/domain
- **📝 Notes Pad** — Freeform textarea with save confirmation toast
- **💬 Motivational Banner** — Rotating daily quotes with shimmer animation
- **🕐 Live Clock** — Real-time date and time display in the header

---

## 🛠 Tech Stack

| Layer | Tech |
|---|---|
| Structure | HTML5 |
| Styling | Vanilla CSS (glassmorphism, CSS variables, animations) |
| Logic | Vanilla JavaScript |
| Fonts | Google Fonts — Syne + DM Sans |
| Persistence | `localStorage` |
| Deployment | Vercel |

Zero dependencies. Zero build steps. Single file.

---

## 📁 Project Structure

```
Dashboard/
└── index.html   # Entire app — markup, styles, and scripts in one file
```

---

## 🚀 Getting Started

```bash
git clone https://github.com/SaiiiKumarrr05/Dashboard.git
cd Dashboard
# Open index.html in any browser — no server needed
open index.html
```

Or just visit the live deploy: **[saikumar-dashboard.vercel.app](https://saikumar-dashboard.vercel.app/)**

---

## 💾 Data Persistence

All data (tasks, streak, notes, rank goal, timer state) is saved automatically to `localStorage` — no backend, no login, works fully offline.

---

## 📱 Responsive Design

Adapts across breakpoints:
- **≥ 1100px** — 4-column stat grid
- **800–1100px** — 2-column grid
- **< 600px** — single column, stacked layout

---

## 🎨 Design Highlights

- Dark theme with `#070a12` base and layered glassmorphism cards
- Purple → Cyan gradient system throughout
- Animated particle canvas background
- Smooth hover glows, entry animations, and progress transitions

---

## 👤 Author

**Saikumar** — B.Tech AI & ML, Woxsen University  
GitHub: [@SaiiiKumarrr05](https://github.com/SaiiiKumarrr05)
