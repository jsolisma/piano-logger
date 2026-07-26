# 🎹 Piano Practice Logger

A simple practice session logger for piano. Download, open in your browser, start logging.

## Why?

I practice piano every now and then, but never consistently. I'd write notes in a book—"worked on Leia's theme, 15 min, left hand tight"—but nothing systematic.

I wanted something I could use on my phone. Built this with Claude—just an HTML file. No backend, no login, no complexity. Download it, open it in your browser, and it saves your practice sessions locally.

## What It Does

- Guides you through **warm-up → technical work → repertoire** (based on Berklee methodology)
- Choose which phases to do each day and set your own time
- Timer + metronome for each phase
- Capture feedback after each phase
- See what you did last session so you can build on it
- All data saves locally on your device

## How to Use

1. Download `piano-logger-v2.html`
2. Open it in any browser (desktop, tablet, mobile)
3. Click "Start Today's Session"
4. Practice
5. Fill in summary, save

That's it.

## What Gets Saved

Each session stores:
- Date and time
- Which phases you ran
- Time spent on each phase
- Feedback for each phase
- Energy level (1-10)
- Session quality (low/medium/good/excellent)
- What went well
- What to focus on next

View all sessions on the home screen.

## Technology

- HTML + CSS + Vanilla JavaScript
- Tone.js for metronome
- Browser localStorage for data persistence
- No backend, no database, no server

## Limitations

- Data stays on this device/browser only
- No cloud sync
- Clear browser cache = lost data
- Manual text feedback

## License

Open source. Use it however you want.

---

Built with Claude. First version. Works. 🎵
