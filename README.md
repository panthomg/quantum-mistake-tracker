
# 🔬 Quantum Mistake Tracker

**Every wrong answer is in a superposition — until you review it, you don't actually know why you got it wrong.**

Quantum Mistake Tracker collapses that uncertainty. Log the problem, log the slip, and watch your blind spots go from *unknown unknowns* to *known, and handled.*


---

## Why "Quantum"?

It's quantum because your mistakes exist in two states at once:

- **Unobserved** — the silly slip you'll swear you'll "never make again," right up until you make it again.
- **Observed** — logged, tagged, and scheduled for review, at which point it stops haunting you and starts teaching you.

This app is the observer. Measurement, in this case, is just brutally honest bookkeeping.

---
<p align="center"> 
  <table> 
    <tr> 
      <td><img src="https://github.com/user-attachments/assets/b0180d8c-0caf-48ec-aec0-6c03fd4a51c9" width="270"/></td> 
      <td><img src="https://github.com/user-attachments/assets/98898ca3-1aec-49f4-911b-b27cc98cf11f" width="270"/></td> 
      <td><img src="https://github.com/user-attachments/assets/e8c86f74-c5dc-4a59-bf82-665de41b9ad8" width="270"/></td> 
      <td><img src="https://github.com/user-attachments/assets/04f392e7-ca67-41c5-a7b5-bbee74bce521" width="270"/></td> 
    </tr> 
  </table> 
</p>


## What it actually does

A study companion app for tracking *why* you get things wrong — not just *that* you did.

- **📋 Log mistakes like a lab notebook** — the incorrect attempt, the correct solution, the reason behind the error (conceptual gap, careless slip, misread question, forgotten formula, time pressure), and a one-line fix for next time.
- **🧠 Three ways to look at your errors** — a dense spreadsheet view for scanning, a card view for browsing, and a diagnostics view that charts your most common failure modes.
- **⚡ Spaced-repetition drills** — mistakes resurface on a schedule tuned to how well you know them. Fail one, it comes back tomorrow. Master one, it fades out gracefully.
- **✨ Optional AI eyes** — plug in a Gemini API key and hand it a screenshot of your mistake; it drafts the breakdown for you (you stay the editor, not the typist).
- **📦 Own your data** — everything lives in your browser's localStorage, with one-click JSON export/import for backups or moving between machines.
- **🌗 Light & dark mode**, because debugging your own brain shouldn't strain your eyes doing it.

---

## Quick start

No build step. No install. No server. This is a single HTML file — the lowest-friction study tool you'll open all week.

```bash
git clone https://github.com/panthomg/quantum-mistake-tracker.git
cd quantum-mistake-tracker
open index.html   # or just double-click it
```

That's it. It runs entirely in your browser.

Want the AI auto-analysis feature? Grab a free key from [Google AI Studio](https://aistudio.google.com/), click **Gemini API** in the top bar, and paste it in. Nothing leaves your browser except the request to Gemini itself.

---

## The philosophy, briefly

Most of us don't repeat mistakes because we're careless — we repeat them because we never *categorized* them. "I made a silly error" and "I misunderstood the concept" call for completely different fixes, but they feel identical in the moment.

This tool forces the distinction. Once your mistakes are sorted by *cause* instead of just *occurrence*, patterns you were blind to start showing up in the diagnostics tab — and patterns you can see are patterns you can fix.

---

## Contributing

Found a bug? Have an idea? Blind spots welcome pull requests too.

1. Fork it
2. Branch it (`git checkout -b feature/your-idea`)
3. Commit it
4. Open a PR

---

## License

MIT — do what you want with it, just don't blame the tracker for mistakes it hasn't observed yet.

---

<p align="center"><i>Uncertainty is the default state. Review is how you resolve it.</i></p>
