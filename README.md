# ζωή kíkún — Zoe Kikun

**Life, fully.**

A visual countdown that shows you how much time you have left. Each dot is a day (or week). As time passes, dots disappear from the bottom up — what remains sits above you like sand that hasn't fallen yet.

## Features

- **Swipeable pages** — Semester, Year, Life, or any custom countdown
- **Draggable text** — Place your name, mantras, or reminders anywhere on screen
- **Auto-sizing dots** — Grid fills the screen regardless of timespan (49 days or 80 years)
- **Today pulses** — One glowing dot marks where you are right now
- **Pure black** — Designed for OLED. Every pixel that can be off, is off
- **PWA** — Add to home screen on any phone. No app store needed

## Use it

**Live:** [aayoawoyemi.github.io/zoe-kikun](https://aayoawoyemi.github.io/zoe-kikun)

Open on your phone → Chrome menu → "Add to Home Screen" → Full-screen app, no browser chrome.

## Interactions

| Action | What it does |
|--------|-------------|
| Swipe left/right | Switch between countdowns |
| Drag text blocks | Position text anywhere on screen |
| Double-tap text | Edit the text |
| Tap the number | Toggle count visibility |
| Long press grid | Edit countdown (name, dates) |
| + button | Add a new countdown |

## Run locally

```bash
# Any static server works
python -m http.server 8080
# or
npx serve .
```

## License

MIT
