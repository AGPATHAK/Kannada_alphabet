# Kannada Alphabet Trainer

A browser-based PWA for learning to recognise the Kannada alphabet, with Devanagari as the answer script. Designed for learners working toward reading fluency — newspapers, simple stories — rather than academic study.

## Live app

[https://agpathak.github.io/Kannada_alphabet/](https://agpathak.github.io/Kannada_alphabet/)

## What it covers

The full Kannada script: 15 vowels (ಸ್ವರ), 34 consonants (ವ್ಯಂಜನ) including conjuncts ಕ್ಷ and ಜ್ಞ, plus anusvara (ಅಂ) and visarga (ಅಃ). Each prompt shows a Kannada character; you pick the correct Devanagari equivalent from multiple-choice options.

Devanagari is used as the answer script rather than transliteration — a practical choice for learners who already read Hindi or Marathi and want a fast bridge into Kannada.

## Practice modes

| Mode | What it does |
|---|---|
| **Full Alphabet** | All vowels and consonants |
| **Vowels only** | Isolate the 15 vowels |
| **Consonants only** | Isolate the consonant groups |
| **Practice Weak Letters** | Cards below 99% accuracy (needs ≥ 8 attempts per card) |

Sessions are configurable: choose card count (5 / 10 / 20 / full set) and a countdown timer (off / 2s / 3s / 5s) to increase pressure as fluency builds.

## Features

- Per-letter accuracy tracking persisted in `localStorage`
- Session history with scores and streaks
- Wrong-letter review at end of each session with retry option
- Keyboard shortcuts: `1` `2` `3` `4` to answer
- Installable as a PWA on iOS and Android
- No server, no backend, no build step — one HTML file

## Install on iPhone

Open the live URL in Safari → Share → **Add to Home Screen**. Launches like a native app with its own icon.

## Files

- `index.html` — the entire app; all letter data is embedded
- `manifest.json` — PWA metadata
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png` — app icons

## Tech

Plain HTML, CSS, and JavaScript. Tailwind CSS via CDN for styling, Noto Sans Kannada via Google Fonts for script rendering. Hosted on GitHub Pages.

## Companion app

Once you're comfortable with the alphabet, move on to the [Kannada Matras Trainer](https://github.com/AGPATHAK/Kannada_matra) which covers consonant + vowel matra combinations (kagunita).

## Note on progress sync

Progress is stored in the browser's `localStorage` — it persists across sessions in the same browser but does not sync across devices.
