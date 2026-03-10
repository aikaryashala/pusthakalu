# Think Python — Local Study Edition

A curated, offline-friendly HTML version of *Think Python (3rd Edition)* by **Allen B. Downey**, trimmed to the first three chapters for focused study.

---

## Special Thanks

All content belongs to **Allen B. Downey**.
This project is a personal study edition built from the [official GitHub Pages release](https://github.com/AllenDowney/ThinkPython/tree/gh-pages#).

---

## Project Structure

```
ThinkPython/
├── index.html          # Landing page — Special Thanks + GitHub & Book buttons
├── course_page.html    # Course overview with book cover, description, chapter list
├── chap00.html         # Preface
├── chap01.html         # Chapter 1 — Programming as a way of thinking
├── chap02.html         # Chapter 2 — Variables and Statements
├── chap03.html         # Chapter 3 — Functions
├── _static/            # CSS, JS, fonts (Sphinx / PyData theme assets)
├── _images/            # Images used in chapters
└── _sources/           # Original notebook source files
```

---

## Navigation Flow

```
index.html  →  course_page.html  →  chap00.html  →  chap01.html  →  chap02.html  →  chap03.html
```

Each chapter page has **Previous / Next** buttons at the bottom.
`chap03.html` has no Next button — it is the final chapter in this edition.

---

## Changes Made to the Original

| File | Changes |
|---|---|
| `index.html` | Replaced with a minimal landing page (Special Thanks, GitHub button, Read the Book button) |
| `course_page.html` | New course overview page with book cover image and chapter links |
| `chap00–03.html` | Removed external purchase links (Bookshop.org / Amazon), removed article toolbar (download/fullscreen), trimmed sidebar nav to chapters 1–3 only |

---

## How to Open

Open `index.html` in any modern browser — no server required.

```
ThinkPython/index.html
```

---

## License

*Think Python* is licensed under the
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
© 2023 Allen B. Downey
