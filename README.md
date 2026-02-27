# 🎮 GameHub - Browser Game Arcade

A collection of **21 fully playable browser games** built with vanilla HTML, CSS, and JavaScript. No frameworks, no build tools — just pure web fun!

## 🕹️ Games Included

| # | Game | Category |
|---|------|----------|
| 1 | Snake | Classic, Arcade |
| 2 | Tetris | Classic, Puzzle |
| 3 | Tic Tac Toe | Classic, Board |
| 4 | Minesweeper | Classic, Puzzle |
| 5 | 2048 | Puzzle |
| 6 | Flappy Bird | Arcade |
| 7 | Pong | Classic, Arcade |
| 8 | Breakout | Classic, Arcade |
| 9 | Memory Match | Puzzle |
| 10 | Whack-a-Mole | Arcade |
| 11 | Rock Paper Scissors | Classic |
| 12 | Simon Says | Puzzle |
| 13 | Sudoku | Puzzle |
| 14 | Chess (vs AI) | Board |
| 15 | Checkers | Board |
| 16 | Hangman | Word |
| 17 | Typing Speed Test | Word |
| 18 | Quiz Game | Word, Puzzle |
| 19 | Dino Runner | Arcade |
| 20 | Space Invaders | Classic, Arcade |
| 21 | Connect Four | Board |

## ✨ Features

- **Modern dark theme** with neon/gaming aesthetic
- **Responsive design** — works on desktop and mobile
- **Search and filter** games by category
- **Score tracking** with localStorage persistence
- **No dependencies** — pure HTML, CSS, and JavaScript

## 🚀 Deployment

This is a purely static site. Deploy to any static hosting:

### Netlify
Simply connect your GitHub repo or drag-and-drop the project folder. A `netlify.toml` is included.

### Local Development
```bash
# Serve with any static file server
python3 -m http.server 8080
# Then open http://localhost:8080
```

## 📁 Project Structure

```
GameHub/
├── index.html          # Landing page with game grid
├── css/style.css       # Shared styles
├── netlify.toml        # Netlify deployment config
├── games/
│   ├── snake/          # Each game in its own folder
│   ├── tetris/
│   ├── tic-tac-toe/
│   ├── ... (21 games)
│   └── connect-four/
└── README.md
```