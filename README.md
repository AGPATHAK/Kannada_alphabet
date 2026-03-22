# Kannada Alphabet Trainer

A lightweight, browser-based web app to practice Kannada alphabet recognition with spaced repetition and progress tracking.

## Features

- Clean, distraction-free interface
- Randomized letter practice
- Immediate feedback (Reveal → Correct / Incorrect)
- Progress tracking using localStorage
- Works on desktop and mobile (iPhone compatible)
- Installable as a Home Screen app (PWA)

## Live Demo

https://agpathak.github.io/Kannada_alphabet/

## How to Use

1. Open the app in your browser
2. Click **Start Session**
3. Try to recall the letter
4. Click **Reveal**
5. Mark as **Correct** or **Incorrect**
6. Continue

## iPhone Usage

1. Open the app in Safari
2. Tap **Share**
3. Select **Add to Home Screen**
4. Launch like a native app

## Tech Stack

- HTML, CSS, JavaScript (no frameworks)
- Tailwind CSS (via CDN)
- Google Fonts (Noto Sans Kannada)
- GitHub Pages (hosting)

## Data & Storage

- All data is embedded in the app
- Progress is stored locally in the browser using `localStorage`
- No external database or backend

> Note: Progress does not sync across devices

## Project Structure
index.html
manifest.json
icon-192.png
icon-512.png
apple-touch-icon.png

## Future Improvements (Optional)

- Sync progress across devices
- Add matras and word-level practice
- Introduce Leitner-style scheduling
- Offline support via service worker
- Analytics for weak letters

## License

For personal learning and educational use.
