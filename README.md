<div align="center">

# 🧠 CompTIA A+ Core 2 (220-1202) Simulation Lab

### Interactive, browser-based performance-based-question (PBQ) practice — no installs, no accounts, no tracking.

[![Exam](https://img.shields.io/badge/Exam-220--1202-14b8a6?style=for-the-badge)](#-whats-inside)
[![Domains](https://img.shields.io/badge/Domains-4%2F4-6366f1?style=for-the-badge)](#-whats-inside)
[![Simulations](https://img.shields.io/badge/Simulations-10-f43f5e?style=for-the-badge)](#-whats-inside)
[![Dependencies](https://img.shields.io/badge/Dependencies-Zero-22c55e?style=for-the-badge)](#-tech-philosophy)
[![License](https://img.shields.io/badge/License-Educational%20Use-9ca3af?style=for-the-badge)](#-license--disclaimer)

**[🚀 Launch the Lab](https://shanemckenney.github.io/A-Plus-Core-2-Simulations/)** &nbsp;·&nbsp; **[📄 Resume Bullets](./resume-bullets.html)** &nbsp;·&nbsp; **[🗂️ What's Inside](#-whats-inside)**

</div>

---

## 📖 About

This is a self-contained training lab built to reinforce **CompTIA A+ Core 2 (220-1202)** exam objectives through hands-on, scenario-driven simulations — the same style of decision-making the real exam's performance-based questions require, without the risk of practicing on the actual exam content.

Every simulation is a single, self-contained HTML file. No build step, no npm install, no backend, no database, no external API calls at runtime. Clone it, open `index.html`, or push it straight to GitHub Pages — it just works.

> ⚠️ **Not official CompTIA material.** These are original, independently written simulations designed to reinforce the *published* 220-1202 exam objectives. They are not "brain dumps," do not reproduce actual exam questions, and should be used alongside official CompTIA study guides and practice exams.

---

## 🗂️ What's Inside

| Simulation | Domain | Difficulty | Est. Time |
|---|:---:|:---:|:---:|
| 📇 Acronym & Terminology Engine (170 terms) | All Domains | — | 30–45 min |
| 📧 Email Threat Analysis & Classification | 2.5 | Beginner | 10–15 min |
| ⚙️ Service Management & Network Map | 1.0 | Beginner | 10–15 min |
| 💻 Terminal Analysis: Inventory Audit | 1.5 / 4.1 | Beginner | 10–15 min |
| 💬 Help Desk Chat Simulator | 4.0 | Intermediate | 15–20 min |
| 📡 Tier 1 Router Support Scenario | 4.0 | Beginner | 8–12 min |
| 🧩 Application Launch Troubleshooting | 3.0 | Intermediate | 10–15 min |
| ⌨️ CLI Troubleshooting Trainer (8 scenarios) | 1.0 / 3.0 | Advanced | 25–35 min |
| 📶 Wireless Reliability Decision Lab | 1.0 / 2.0 | Intermediate | 12–18 min |
| 📶 Router & Access Point Configuration | 2.10 | Intermediate | 15–20 min |

**Total practice time:** ~150–190 minutes across all ten simulations.

Simulations are organized into three tiers inside `index.html`:

- **★ Tier 1 — Must Know**: the highest-yield, most frequently tested skills
- **⚡ Tier 2 — Deeper Learning**: hands-on diagnostic and configuration depth
- **🚀 Tier 3 — Specialized**: reserved for future advanced/niche additions

---

## ✨ Features

- **🎲 Randomized every attempt.** Scenarios, datasets, and answer-option order are all shuffled at runtime — nothing in this lab is memorizable after one pass. Tickets, email banks, quiz questions, and network-neighbor data regenerate on every load.
- **🧭 Explains the "why," not just the "wrong."** Every graded simulation shows what you chose vs. the best answer, with a plain-English explanation — so a miss becomes a lesson instead of just a lost point.
- **🎯 PBQ-realistic interaction.** Live command-line terminals, clickable network maps, real device configuration GUIs, and branching customer chats — built to mirror how the actual exam presents performance-based questions, not just multiple choice.
- **♿ Built-in accessibility toolkit** on every page:
  - 🔤 **OpenDyslexic font toggle** — the real [OpenDyslexic](https://opendyslexic.org) typeface (SIL Open Font License), embedded directly in each file — no CDN, works offline.
  - 🔊 **Read Aloud** — uses the browser's native Web Speech API to read the active scenario, context-aware per simulation (never spoils a flipped-away flashcard face or an unrevealed quiz answer).
- **📄 Career toolkit included.** `resume-bullets.html` turns every simulation into ready-to-use resume bullets written in Google's XYZ format (*"Accomplished X, as measured by Y, by doing Z"*).

---

## 🛠️ Tech Philosophy

| Principle | How it's implemented |
|---|---|
| **No build tools** | Plain HTML, CSS, and vanilla JavaScript. No React, no bundler, no transpiler. |
| **No external dependencies at runtime** | Fonts and logic are embedded directly in each file (base64-encoded where needed). Nothing is fetched from a CDN once the page loads. |
| **No recurring cost** | Static files only. Hosts for free on GitHub Pages indefinitely. |
| **No account, no backend** | Progress tracking (where applicable) uses the browser's own `localStorage` — nothing leaves the student's machine. |
| **Works offline** | Once loaded, every simulation runs entirely client-side. |

---

## 📂 Repository Structure

```
.
├── index.html                                  # Landing page — start here
├── resume-bullets.html                         # Career toolkit (XYZ-format resume bullets)
└── simulations/
    ├── Core_2_Acronym_Practice.html
    ├── Email Analysis v2.html
    ├── Service Management & Network Map.html
    ├── Terminal Analysis - Inventory Audit.html
    ├── Help Desk - Email - Multi Scenario.html
    ├── Tier 1 Router Support Scenario.html
    ├── Application Launch Troubleshooting Simulation.html
    ├── Network Troubleshooting CLI Simulation.html
    ├── Wireless Reliability Decision Lab.html
    └── Router Configuration/
        ├── Neighoring Routers.html              # Router/AP config sim (image-dependent — keep folder intact)
        ├── Router.png
        └── Router_houses.png
```

> **Note:** `Router Configuration/Neighoring Routers.html` depends on the two `.png` files sitting alongside it. If you move or copy that simulation, bring the whole folder — not just the HTML file.

---

## 🚀 Running Locally / Deploying

**Locally:**
```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
open index.html   # or just double-click it
```

**On GitHub Pages:**
1. Push this repository structure to GitHub, exactly as laid out above.
2. In your repo settings, enable **Pages** → deploy from the `main` branch, root folder.
3. Your lab will be live at `https://<your-username>.github.io/<your-repo>/`.

No configuration, no `.github/workflows`, no dependencies to install — GitHub Pages serves the static files as-is.

---

## 🎓 Career Toolkit

`resume-bullets.html` maps every simulation above to real, XYZ-format resume language:

> *"Accomplished [X] as measured by [Y], by doing [Z]."*

Swap in a real number from your own experience before using any bullet on an actual resume — these are templates built from practice work, not literal claims of paid employment.

---

## 📜 License & Disclaimer

- **Educational use.** Built for CompTIA A+ Core 2 (220-1202) exam preparation. Not affiliated with or endorsed by CompTIA.
- **Not exam content.** No official CompTIA questions, PBQs, or proprietary material are reproduced anywhere in this repository.
- **OpenDyslexic** typeface © Abbie Gonzalez, licensed under the [SIL Open Font License](https://opendyslexic.org) — embedded per license terms, no attribution removed.

---

<div align="center">

Built for students working toward CompTIA A+ certification.

**Study smart. Practice often. Read the "why," not just the "what."**

</div>
