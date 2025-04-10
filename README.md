# ChessMate Electron

**ChessMate Electron** is a cross-platform chess assistant built with Electron and a Python backend. Play against a Stockfish-powered bot that evaluates and rates your moves in real time, helping you to improve your chess game.

## Features

- **Interactive Chessboard:** Drag and drop chess pieces using Chessboard.js.
- **Bot Play:** Challenge an AI opponent powered by Stockfish.
- **Move Analysis:** Every move is evaluated and rated (Excellent, Good, Inaccuracy, Mistake, or Blunder).
- **Undo/Reset:** Easily undo moves and reset the game.
- **Cross-Platform:** Built with Electron for desktop distribution.

## Installation

### Backend Setup (Python)

1. Clone the repository and navigate to the backend folder.
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use: venv\Scripts\activate
