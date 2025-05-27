# Random English Word Generator - https://wordgen.shop

A simple static web app that displays a random English word from a full dictionary on page load, on a configurable interval (15–60s), or on demand. Click the displayed word to fetch and show its definition, with support for light/dark mode.

## Features

- Displays a random word from a comprehensive English word list.  
- Auto-refresh interval adjustable via slider (15–60 seconds).  
- **Regenerate Word** button for manual refresh.  
- Clickable word to fetch definitions from [DictionaryAPI.dev](https://dictionaryapi.dev).  
- Light and dark themes with system-preference detection and toggle.  
- Responsive, minimal styling using Google Fonts (Playfair Display & Montserrat).

## Installation
```
1. Clone this repo:  
   `git clone https://github.com/your-username/random-word-generator.git`  
   `cd random-word-generator`

2. Add a dictionary file:  
   Download a word list (one word per line) and save as `dictionary.txt` in the project root.
```

## Usage

**Local development:**  
```python3 -m http.server 8000```
Then browse to `http://localhost:8000.

**Deploy:**
Push to GitHub and connect the repo to any static hosting platform.

## Credits

- Definitions: [DictionaryAPI.dev](https://dictionaryapi.dev)  
- Fonts: Google Fonts (Playfair Display, Montserrat)

---

*Lightweight, zero-dependency, and perfect for vocabulary practice or displaying random words on any static site.*
