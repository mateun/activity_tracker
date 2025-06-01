# Calorie Uplink Terminal

A retro-futuristic, terminal-style web tracker for daily calorie intake and exercise, inspired by classic sci-fi UIs like **Marathon**.

## 🧠 Features

- Log food and sport activities via simple prompts
- Automatically calculates:
  - Total food calories ingested
  - Total calories burned through sport
  - Net daily calorie balance
- Data is saved in **localStorage**, scoped per calendar day
- Clean reset every day — no manual cleanup needed
- Styled in vintage phosphor-green on black terminal aesthetics

## 🖱️ Usage

1. Open `index.html` in any modern browser.
2. Click `[ LOG FOOD ]` or `[ LOG SPORT ]`.
3. Enter the item name and calorie amount.
4. View your entries in the **Data Stream** section and your totals in **Summary Stats**.

## 💾 Data Storage

- Data is saved using `localStorage`, with each day stored under its own key (e.g. `2025-06-01`).
- When the date changes, a new daily log starts automatically.
- No data leaves your browser. No backend. No tracking.

## 📂 File

- `index.html` – the entire self-contained app (HTML, CSS, and JS in one file)



