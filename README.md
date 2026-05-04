# Sushi Flashcards

A personal flashcard app for learning the names, kanji, appearance, and prep notes of Japanese sushi and sashimi ingredients.

## Open it

Just open **`index.html`** in a web browser. No build step, no server, no dependencies — it runs as a static page directly from the file. If hosted on GitHub Pages or any static host, the URL works the same way.

## How it works

- 200+ entries covering tuna, yellowtail, salmon, white fish, oily fish, eels, shellfish, crustaceans, squid & octopus, uni, roe, anatomy terms, and prep techniques.
- Each card shows up to three faces — English name, Japanese (kanji + romaji), and a photo — with two hidden by default. Click a face to reveal it, or hit **Space** to reveal everything.
- A description panel appears with detailed notes, taste profile, and species/prep/origin context.
- Toggle decks on and off (Tuna only, Uni only, etc.) using the chips at the top.
- Browse mode (button or **B** key) shows everything revealed for studying instead of quizzing.

### Keyboard shortcuts

- **Space** — reveal all faces of the current card
- **→ / Enter** — next card
- **S** — reshuffle
- **B** — toggle browse mode
- **Click** — reveal a single hidden face

## Project structure

```
.
├── index.html              # the app (HTML + CSS + JS)
├── data.js                 # all the entries — edit here to update notes/cards
├── images/                 # photos (slug.jpg, slug1.jpg, slug2.jpg, etc.)
└── README.md
```

To add or replace a photo, drop `<slug>.jpg` (and optionally `<slug>1.jpg`, `<slug>2.jpg`, …) into the `images/` folder. The app auto-detects up to 5 images per slug and lays them out in a gallery grid.

## Image credit & disclaimer

This is a personal educational project. Photos are sourced from various places on the web and used for non-commercial reference purposes; original copyright belongs to the respective photographers. If you are a photographer and would like an image removed, please get in touch.

## Personal notes

Built by someone learning sushi, with help from Claude. Notes are accurate to the best of compiled knowledge but may have regional or expert-level inaccuracies — corrections welcome.
