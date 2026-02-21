# tn-wordsearch

A web app that generates printable Word Search booklets designed for Traveler's Notebook inserts.

---

## 🌐 Web App (no install needed!)

Just open it in your browser — pick your settings and download a print-ready PDF instantly:

**👉 [einarjonsson.github.io/tn-wordsearch](https://einarjonsson.github.io/wordsearch-travelers-notebook)**

---

## What it does

Generates a landscape A4 PDF with Word Search puzzles sized for either **Regular** or **Passport** Traveler's Notebooks. Each puzzle comes with a word list printed below the grid. Once printed and cut (and folded for Regular), you get mini inserts that fit perfectly inside your TN.

---

## Features

- **5 word categories** — Animals, Nature, Travel, Food & Drink, Geography
- **3 difficulty levels** — Easy (horizontal/vertical), Medium (+ diagonals), Hard (+ backwards)
- **3 font styles** — Classic, Serif, Mono
- **Cover page** — optional framed cover, auto-filled with your custom title
- **Custom title** — printed on every page and on the cover
- **Duplex aware** — detects if your printer supports double-sided printing, otherwise walks you through a simple two-step manual process with correctly ordered pages

---

## Sizes supported

| Size | Layout | Per printed sheet |
|------|--------|-------------------|
| **Regular** | 2 columns × 2 rows, fold + cut | 8 puzzles |
| **Passport** | 2 × 2 grid, cut only | 8 puzzles |

---

## How to print and assemble

### Regular TN
1. Print **Side 1**
2. Flip the paper on the **short edge** and print **Side 2**
3. **Fold** at the dashed line — 110mm from the left
4. **Cut** at the dotted line — 220mm from the left
5. Discard the small waste strip on the right

```
|<-- 110mm -->|<-- 110mm -->|<-- ~77mm -->|
|             |             |             |
|  Puzzle 1   |  Puzzle 3   |   (waste)   |
|             |             |             |
|  Puzzle 2   |  Puzzle 4   |             |
|             |             |             |
      ^fold        ^cut
```

### Passport TN
1. Print **Side 1**
2. Flip the paper on the **short edge** and print **Side 2**
3. **Cut** along the vertical dotted line (centre)
4. **Cut** along the horizontal dotted line (centre)

```
|<-- 134mm -->|<-- 134mm -->|
|  Puzzle 1   |  Puzzle 2   |  } 98mm
|-------------|-------------|  <-- cut here
|  Puzzle 3   |  Puzzle 4   |  } 98mm
        ^cut here
```

---

## Part of the TN Puzzle Suite

This is part of a growing collection of Traveler's Notebook puzzle generators:

- 🔢 **[Sudoku Generator](https://einarjonsson.github.io/sudoku-travelers-notebook)** — printable Sudoku booklets
- 🔤 **Word Search Generator** — this repo

A combined hub bringing everything together is coming soon!

---

## License

MIT — free to use, modify, and share.
