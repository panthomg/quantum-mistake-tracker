
# ⚡ Quantum Mistake Tracker

<p align="center">
  <b>Turn your wrong answers into unfair advantages.</b><br>
  A lightweight, zero-backend, AI-powered diagnostic mistake journal for STEM students, competitive programmers, and high-stakes test takers.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active%20%26%20Open%20Source-10b981?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Architecture-Zero--Build%20Single%20File-0ea5e9?style=for-the-badge" alt="Architecture">
  <img src="https://img.shields.io/badge/Intelligence-Gemini%202.5%20%2F%203.7%20Flash-f59e0b?style=for-the-badge" alt="Gemini">
  <img src="https://img.shields.io/badge/License-MIT-6366f1?style=for-the-badge" alt="License">
</p>

---

## 💡 Why Quantum Mistake Tracker?

Top performers in math competitions, coding interviews (LeetCode/Codeforces), and standardized exams (SAT, JEE, GRE, MCAT) share one habit: **they obsess over their errors.**

Traditional flashcard systems only test recall. **Quantum Mistake Tracker** diagnoses *why* you failed:

[ Problem Occurs ] │ ▼ [ Snapshot / Paste ] ──► [ Gemini Vision Analysis ] │
┌────────────────────────┴────────────────────────┐ ▼ ▼ [ Root Cause
Diagnosed ] [ LaTeX Formatted Solution ] (e.g., Calculation Slip, Concept Gap)
(Step-by-step resolution) │ │
└────────────────────────┬────────────────────────┘
│ ▼ [ Spaced Repetition Drill ] (Automated interval mastery)


---

## ✨ Features at a Glance

| Feature | Description |
| :--- | :--- |
| 🗂️ **Diagnostic Spreadsheet** | High-density log separating the question, correct derivation, root mistake trigger, and prevention rule. |
| 👁️ **Multi-Modal AI Vision** | Paste a screenshot (`Ctrl+V`) or snap a photo of handwritten work. Gemini extracts the problem, converts math to $\LaTeX$, and auto-fills the entry. |
| 📐 **Native $\LaTeX$ Engine** | Real-time formula rendering powered by KaTeX ($...$ and $$...$$). |
| 🔁 **Active Recall Drills** | Built-in flashcard drill system with spacebar reveals and spaced repetition status tracking (`Learning` $\to$ `Reviewing` $\to$ `Mastered`). |
| 📊 **Error Analytics** | Root-cause distribution charts to highlight recurring systematic weaknesses. |
| 🔒 **Local-First & Private** | Zero telemetry. Your notes, images, and API keys remain stored inside your browser's `localStorage`. |
| 📦 **Single-File Portability** | Runs straight out of `index.html`. No `npm install`, no Node.js, no compilation step. |

---

## 🚀 Quickstart

You don't need a development environment or server setup to run this.

### Method 1: Instant Local Run
```bash
# 1. Clone the repository
git clone https://github.com/yourusername/quantum-mistake-tracker.git

# 2. Open in your browser
cd quantum-mistake-tracker
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows

Method 2: Standalone Download

1.  Download index.html directly to your machine.
2.  Double-click the file to open it in Chrome, Safari, Firefox, Edge, or Brave.

🔑 Activating AI Diagnostic Features

The app is fully functional as a manual tracker offline. To enable automated
handwriting extraction and error analysis:

1.  Grab a free API key from Google AI Studio.
2.  Click Gemini API in the top navigation bar.
3.  Paste your key and select your preferred model (gemini-2.5-flash
    recommended).
4.  Hit Save Key (saved locally to your browser).

⌨️ Productivity Hotkeys

| Shortcut               | Context       | Action                                            |
| :--------------------- | :------------ | :------------------------------------------------ |
| `Ctrl + K` / `Cmd + K` | Global        | Focus search filter bar                           |
| `Ctrl + V` / `Cmd + V` | Add Modal     | Paste screenshot directly from clipboard          |
| `Spacebar`             | Drill Session | Reveal step-by-step answer and avoidance takeaway |

🏗️ Under the Hood

Designed to be lightweight, auditable, and hackable:

quantum-mistake-tracker/
├── index.html         # Complete application (UI, Tailwind styles, SRS engine, Gemini client)
├── README.md          # Project documentation
└── LICENSE            # MIT License

  - Core Runtime: Vanilla JavaScript (ES6+ Class Architecture).
  - Styling: Modern utility layout via Tailwind CSS.
  - Math Rendering: KaTeX 0.16.8 (via CDN).
  - Icons: Lucide Icons.
  - Storage Layer: LocalStorage API with JSON backup/restore.
  - AI Provider: Google Gemini Flash REST endpoints (Multi-part reasoning safe).

🗺️ Roadmap & Ideas

- [ ] Export directly to Anki deck packages (.apkg)
- [ ] Tagging system for granular sub-topics (#calculus, #graph-theory)
- [ ] Offline local OCR fallback option
- [ ] Custom review interval schedules (SuperMemo / SM-2 algorithm)

🤝 Contributing

Contributions of any kind are welcome! Whether it's adding features, improving
documentation, or styling tweaks:

1.  Fork the project.
2.  Create your branch (git checkout -b feature/cool-enhancement).
3.  Commit your changes (git commit -m 'Add cool enhancement').
4.  Push to the branch (git push origin feature/cool-enhancement).
5.  Open a Pull Request.

📄 License

This project is completely free and open source under the MIT License.

