# Helio Math Reviewer ⭐

A friendly, big-button web page for Avery's summer "tester job" reviewing the
**Helio Math** tutor app. Built for a 6-year-old with basic reading: one big
question at a time, tap-to-answer, and a 🔊 "Read it to me" button that speaks
each question aloud so reading is never a blocker.

## How to use it

Just open [`index.html`](index.html) in any web browser (double-click the file).
No install, no build step, no internet needed — it's a single self-contained file.

## What Avery does each day

Each question shows a big emoji mascot and two kinds of feedback:

1. 🐞 Did you find any bugs today? — 👍 Yes / 👎 No
2. 🛠️ Did you find something that could be better? — 👍 Yes / 👎 No
3. 😵 Did you get stuck on anything today? — 👍 Yes / 👎 No
4. 🧠 Did you learn anything new today? — 👍 Yes / 👎 No
5. 😀 How did the app make you feel? — 😞 🙁 😐 🙂 😍
6. 🧗 Was the math too easy or too hard? — ☁️ easy → 🏔️ hard
7. 🌟 How many stars for the app today? — ⭐ 1–5

After each answer she can type **one or two words** to help her remember what she
saw, in case her boss has questions. She can also **Skip** that step.

At the end she gets a 🏆 report screen with all her answers and notes, plus:
- **🖨️ Show Boss my report** — print or save as PDF
- **🔁 Do it again tomorrow** — start fresh

## Notes for grown-ups

- All answers live only in the browser tab while it's open; nothing is uploaded
  or saved anywhere. Use "Show Boss my report" to print/save a copy.
- Everything (questions, emoji, labels) lives in the `QUESTIONS` array near the
  top of the `<script>` in `index.html` — easy to edit.
