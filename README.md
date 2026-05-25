# Daily Expense Tracker

A clean, lightweight expense tracking app that runs entirely in the browser. No installation, no backend, no accounts — just open and start tracking.

![Light Mode](screenshot-light.png) *(Add screenshot)*

## What it does

Track your daily expenses with automatic categorization. Every day starts fresh. Export your data as JSON to keep a record, and import previous days to review past spending.

## Features

- **Smart categorization** — type "almuerzo" and it's automatically tagged as Food; "nafta" goes to Transport; "luz" to Services. If unsure, it defaults to Others.
- **Daily auto-reset** — expenses clear at midnight. No manual cleanup needed.
- **Dark / Light mode** — respects your system preference and remembers your choice.
- **Category breakdown** — see spending per category with visual bars and totals. Click any category to filter the list.
- **Export / Import JSON** — export today's expenses to a JSON file, or import a previous export to review historical data.
- **Zero dependencies** — no frameworks, no libraries, no CDN. Runs offline from a single HTML file.
- **Glassmorphism UI** — modern frosted-glass design with smooth animations.

## Technologies used

- **HTML5** — semantic structure
- **CSS3** — custom properties, gradients, backdrop-filter, grid, responsive design
- **Vanilla JavaScript** — ES6+ features (`crypto.randomUUID()`, `Intl.NumberFormat`, `FileReader`, `localStorage`)

No frameworks, no build tools, no package manager.

## How to use

1. Open `Daily Expense Tracker.html` in any modern browser.
2. Type an expense name (e.g. "almuerzo", "uber", "luz") and the amount.
3. Press Enter or click **Agregar**.
4. View the total and category breakdown in the sidebar.
5. Export to JSON at the end of the day, or import a previous day's data.

## File structure

```
Daily Expense Tracker/
├── Daily Expense Tracker.html        # Single-file app (HTML + CSS + JS)
└── README.md
```

## Data & privacy

Everything is stored in your browser's `localStorage`. No data is sent anywhere, no cookies, no tracking. Clearing your browser data will remove your expenses.

## License

MIT
