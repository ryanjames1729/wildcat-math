# Wildcat Math

A single-page math practice game for students. Pick a level, play 10 rounds, earn points and streak bonuses, and collect Wildcat cards.

- **Level 1: Prime or composite** – sort numbers from 2 to 100 and prove composites with a factor pair.
- **Level 2: Fraction fix-up** – add and subtract fractions and write answers in simplest terms.

Best scores and collected cards are saved in the player's browser (`localStorage`); nothing is sent to a server.

## Running it

It's one static file, `index.html`. Open it in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Hosting on GitHub Pages

1. Go to the repository's **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Choose the `main` branch and the `/ (root)` folder, then **Save**.

The site will be published at `https://ryanjames1729.github.io/wildcat-math/`.
