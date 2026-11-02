# Ni-Idea 🇪🇸

A lightweight, mobile-friendly English → Spanish vocabulary practice app.

## Features
- 144 English-Spanish vocabulary cards in 12 themed categories
- Type your answer before seeing the translation
- Incorrect answers must be corrected before advancing
- Accepts common alternative translations; comparisons ignore case, punctuation and Spanish accents
- Shuffle decks and revisit missed words
- Accuracy, streak and unique-word tracking
- Browser-local progress (no signup or database)

## Run locally
Open `index.html` in your browser. No dependencies, build step or server required.

## Deploy on GitHub Pages
Go to **Settings → Pages → Build and deployment**, select **Deploy from a branch**, choose **main** and **/(root)**, then Save. Once deployment completes, the site will be available at `https://kenway-creative.github.io/Ni-Idea/`.

## Notes
- Progress is stored in `localStorage` on the current browser and device.
- Answers are checked as vocabulary translations rather than complete sentences.
- Version 1 contains predefined vocabulary, and can be extended with new themes in `decks` inside `index.html`.

## Roadmap
- Spaced repetition with due dates
- Difficulty levels and sentence cards
- Spoken pronunciation and listening exercises
- Optional cloud-synced profiles
